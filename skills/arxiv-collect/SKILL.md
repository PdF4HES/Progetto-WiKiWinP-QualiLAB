---
name: arxiv-collect
description: >
  Raccoglie paper recenti da ArXiv per tutte le categorie configurate e li archivia
  nel vault come note strutturate con frontmatter Dataview-ready.
  Legge la configurazione da arxiv-agent-config.md, esegue sub-agenti in parallelo
  per gruppo (Physics / Math / CS), deduplica contro note esistenti, aggiorna index e log.
  Trigger: "/arxiv-collect", "raccogli paper", "fetch arxiv", "aggiorna papers",
  "scarica nuovi paper", "arxiv update".
allowed-tools: Read Write Edit Glob Grep WebFetch Bash
---

# arxiv-collect: Raccolta Paper da ArXiv

Sei l'orchestratore della raccolta ArXiv. Leggi la config, dispatchi agenti per gruppo,
poi aggiorni index e log. L'output va in `wiki/papers/` — non in chat.

---

## 1. Carica Configurazione

Leggi `arxiv-agent-config.md` dal root del vault.

Estrai dal frontmatter YAML:
- `settings.max_results_per_category`
- `settings.days_back`
- `settings.papers_path`
- `settings.sort_by` / `sort_order`
- Lista `categories` dove `enabled: true`

Calcola le date:
- `date_to` = oggi (formato YYYYMMDD)
- `date_from` = oggi - `days_back` giorni (formato YYYYMMDD)

Raggruppa le categorie abilitate per `group`: Physics | Math | CS.

Mostra all'utente il piano prima di procedere:
```
Piano raccolta ArXiv
Periodo: {date_from} → {date_to} ({days_back} giorni)
Max per categoria: {max_results}

Physics: {N} categorie abilitate
Math:    {N} categorie abilitate
CS:      {N} categorie abilitate

Totale categorie: {N}
Stima paper max: {N * max_results}

Avvio? [sì per continuare, o modifica le impostazioni]
```

Attendi conferma prima di procedere.

---

## 2. Dispatcha Agenti per Gruppo

Per ciascuno dei tre gruppi (Physics, Math, CS), dispatcha sub-agenti **in parallelo**
usando il profilo `Agents/arxiv-collect.md`.

Passa a ogni agente:
```
category_code:  {code}
category_name:  {name}
group:          {group}
max_results:    {max_results_per_category}
date_from:      {date_from}
date_to:        {date_to}
papers_path:    {papers_path}
```

Esempio dispatch per il gruppo CS (tutti in parallelo):
- Agent cs.AI → Agents/arxiv-collect.md
- Agent cs.CL → Agents/arxiv-collect.md
- Agent cs.MA → Agents/arxiv-collect.md
- ... (tutte le categorie CS abilitate)

Poi Physics in parallelo, poi Math in parallelo.
(Tre ondate di parallelismo, una per gruppo.)

---

## 3. Raccogli i Report

Attendi il completamento di tutti gli agenti.

Compila una tabella aggregata:
```
Categoria              | Nuovi | Saltati | Errori
-----------------------|-------|---------|-------
cs.AI                  |   4   |    1    |   0
cs.MA                  |   3   |    0    |   0
...
```

---

## 4. Aggiorna wiki/papers/_index.md

Leggi il file attuale. Aggiungi i nuovi paper nella sezione per gruppo.
Formato entry:
```markdown
- [[{arxiv_id}]] — {autori brevi}, {anno} · `{primary_category}`
```

---

## 5. Aggiorna wiki/index.md

Aggiorna il contatore nella sezione Papers o aggiungi un riferimento se assente.

---

## 6. Aggiorna wiki/log.md

Prependi in cima al file:
```markdown
## {YYYY-MM-DD} arxiv-collect | {groups} | {date_from}→{date_to}

- Categorie processate: {N}
- Paper nuovi: {total_new}
- Paper saltati (già presenti): {total_skipped}
- Errori: {total_errors}
- Nuovo: {list of new arxiv_ids}
```

---

## 7. Aggiorna wiki/hot.md

Sostituisci il contenuto con:
```markdown
---
type: meta
title: Hot Cache
updated: {today}
---

# Hot Cache

Ultima sessione: arxiv-collect {today}
Periodo coperto: {date_from} → {date_to}
Paper aggiunti: {total_new} in {N} categorie

## Paper più recenti
{lista ultimi 5 paper con titolo e categoria}
```

---

## 8. Aggiorna arxiv-agent-config.md

Aggiorna il campo `last_run` nel frontmatter:
```yaml
last_run: {today}
```

---

## 9. Report Finale all'Utente

```
ArXiv Collect completato — {today}

Periodo: {date_from} → {date_to}
Categorie: {N} ({Physics: N} · {Math: N} · {CS: N})

Paper nuovi:    {total_new}
Già presenti:   {total_skipped}
Errori:         {total_errors}

File creati in wiki/papers/:
  {lista file nuovi}

Prossima raccolta consigliata: {today + days_back}
```

---

## Gestione Errori

- Se WebFetch fallisce per una categoria: logga l'errore, continua con le altre
- Se ArXiv restituisce XML vuoto: logga "0 risultati" e continua
- Se una nota esiste già: salta senza sovrascrivere (deduplicazione per arxiv_id)
- Se `arxiv-agent-config.md` non trovato: interrompi e segnala all'utente

---

## Modalità Prima Esecuzione

Se `last_run` è `null` nel config, suggerisci di aumentare `days_back` a 30
per ottenere un batch iniziale più ricco:

```
Prima esecuzione rilevata. Consiglio: imposta days_back: 30 nel config
per raccogliere un batch iniziale più sostanzioso.
Vuoi procedere con 30 giorni o mantenere i 7 giorni configurati?
```
