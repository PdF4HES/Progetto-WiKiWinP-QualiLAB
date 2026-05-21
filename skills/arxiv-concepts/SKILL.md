---
name: arxiv-concepts
description: >
  Collega i paper ArXiv ai concetti del vault. Analizza titolo, abstract e categorie
  di ogni paper e assegna 2-5 concetti dalla lista concetti del vault.
  Crea pagine concettuali se non esistono. Aggiorna il campo concepts[] del paper.
  Trigger: "/arxiv-concepts", "collega concetti", "tag concetti",
  "arxiv-concepts [arxiv_id]", "arxiv-concepts --batch".
allowed-tools: Read Write Edit Glob Grep
---

# arxiv-concepts: Collegamento Paper ↔ Concetti

Sei un agente di knowledge management. Il tuo compito è analizzare i paper ArXiv
nel vault e collegarli ai concetti corrispondenti.

---

## Modalità operative

### A. Paper singolo
Trigger: `/arxiv-concepts 2605.XXXXX`

1. Leggi `Wiki/papers/{arxiv_id}.md`
2. Analizza titolo, abstract, primary_category, all_categories
3. Assegna 2-5 concetti dalla lista concetti (vedi sotto)
4. Aggiorna il campo `concepts:` nel frontmatter
5. Per ogni concetto, verifica che esista `Wiki/concepts/{concept}.md`; se no, crealo

### B. Batch (tutti i paper senza concetti)
Trigger: `/arxiv-concepts` senza argomenti o `/arxiv-concepts --batch`

1. Usa Grep per trovare tutti i paper con `concepts: []`
2. Processali in gruppi di 10
3. Per ogni paper: assegna concetti via category mapping (vedi tabella)
4. Aggiorna tutti i file
5. Logga un riepilogo

---

## Lista Concetti del Vault

Usa SOLO concetti da questa lista (o creane di nuovi se veramente necessari):

### Fisica
- `Meccanica Statistica`
- `Sistemi Disordinati`
- `Caos e Nonlinearità`
- `Auto-organizzazione e Sistemi Complessi`
- `Solitoni e Onde Nonlineari`
- `Sistemi Integrabili`
- `Automi Cellulari`
- `Fisica Quantistica`
- `Fisica Matematica`
- `Fisica Biologica`
- `Dinamica dei Fluidi`
- `Storia e Filosofia della Fisica`

### Matematica
- `Sistemi Dinamici`
- `Topologia Algebrica`
- `Geometria Algebrica`
- `Geometria Differenziale`
- `Analisi Funzionale`
- `Teoria delle Categorie`
- `Logica e Fondamenti`
- `Teoria dei Gruppi`
- `Algebra`
- `Analisi Numerica`
- `Equazioni alle Derivate Parziali`

### Informatica / CS
- `Intelligenza Artificiale`
- `Machine Learning`
- `Large Language Models`
- `Sistemi Multi-Agente`
- `Teoria dell'Informazione`
- `Teoria dei Giochi Computazionale`
- `Verifica Formale`
- `Automi e Linguaggi Formali`
- `Calcolo Distribuito`
- `Neuroscienze Computazionali`

---

## Tabella Category → Concetti (mapping rapido)

| Categoria ArXiv | Concetti suggeriti |
|-----------------|-------------------|
| cond-mat.stat-mech | Meccanica Statistica |
| cond-mat.dis-nn | Sistemi Disordinati, Machine Learning |
| nlin.CD | Caos e Nonlinearità, Sistemi Dinamici |
| nlin.AO | Auto-organizzazione e Sistemi Complessi |
| nlin.SI | Sistemi Integrabili, Solitoni e Onde Nonlineari |
| nlin.PS | Solitoni e Onde Nonlineari |
| nlin.CG | Automi Cellulari, Meccanica Statistica |
| physics.bio-ph | Fisica Biologica |
| physics.flu-dyn | Dinamica dei Fluidi |
| physics.hist-ph | Storia e Filosofia della Fisica |
| quant-ph | Fisica Quantistica |
| math-ph | Fisica Matematica |
| math.DS | Sistemi Dinamici |
| math.CT | Teoria delle Categorie |
| math.AT | Topologia Algebrica |
| math.AG | Geometria Algebrica |
| math.DG | Geometria Differenziale |
| math.FA | Analisi Funzionale |
| math.LO | Logica e Fondamenti |
| math.GR | Teoria dei Gruppi |
| math.RA | Algebra |
| math.NA | Analisi Numerica |
| math.AP | Equazioni alle Derivate Parziali |
| math.QA | Teoria delle Categorie, Fisica Matematica |
| math.OA | Analisi Funzionale |
| cs.AI | Intelligenza Artificiale |
| cs.CL | Large Language Models, Intelligenza Artificiale |
| cs.MA | Sistemi Multi-Agente |
| cs.GT | Teoria dei Giochi Computazionale |
| cs.IT | Teoria dell'Informazione |
| cs.LO | Verifica Formale, Logica e Fondamenti |
| cs.FL | Automi e Linguaggi Formali |
| cs.DC | Calcolo Distribuito |
| q-bio.NC | Neuroscienze Computazionali |

Per paper con categorie non in tabella, inferisci dai titoli/abstract.

---

## Aggiornamento frontmatter paper

Trova la riga `concepts: []` e sostituiscila con:
```yaml
concepts:
  - "Concetto 1"
  - "Concetto 2"
```

Usa Edit per aggiornare il file.

---

## Creazione pagina concetto (se non esiste)

Se `Wiki/concepts/{NomeConcetto}.md` non esiste, crealo con:

```markdown
---
type: concept
title: "{NomeConcetto}"
tags:
  - concept
  - {Physics|Math|CS}
created: {today}
related_categories: ["{cat1}", "{cat2}"]
related: []
---

# {NomeConcetto}

<!-- Aggiungi qui la descrizione del concetto -->

---

## Paper Correlati

\```dataview
TABLE title AS "Titolo", authors[0] AS "Autore", primary_category AS "Categoria", submitted AS "Data"
FROM "Wiki/papers"
WHERE contains(concepts, "{NomeConcetto}")
SORT submitted DESC
LIMIT 30
\```

---

## Note e Approfondimenti

<!-- Note personali sul concetto -->

## Connessioni con Altri Concetti

<!-- Wikilink ai concetti correlati -->
```

---

## Report finale

```
arxiv-concepts completato

Paper processati: N
Concetti assegnati: N paper
Pagine concetto create: N (lista)
Pagine concetto aggiornate: N

Distribuzione concetti:
  Meccanica Statistica: N paper
  Sistemi Dinamici: N paper
  ...
```
