---
description: Collega i paper ArXiv ai concetti del vault. Analizza titolo, abstract e categoria di ogni paper e popola il campo concepts[] con i concetti corrispondenti da Wiki/concepts/.
---

Leggi `Skills/arxiv-concepts/SKILL.md` per la lista completa dei concetti e il mapping categoria → concetto, poi esegui il collegamento.

Modalità operative in base all'argomento:

**`/arxiv-concepts --batch`** (nessun argomento o --batch)
Processa TUTTI i paper con `concepts: []` vuoto:
1. Usa Grep per trovare tutti i file in `Wiki/papers/` con `concepts: \[\]`
2. Per ogni paper: leggi primary_category e all_categories
3. Applica il mapping dalla tabella in SKILL.md (categoria → concetti)
4. Per concetti che richiedono analisi del testo, leggi titolo e abstract
5. Aggiorna il campo `concepts:` in ogni paper (da `[]` a lista di stringhe)
6. Crea pagine concetto in `Wiki/concepts/` se non esistono (usa il template in SKILL.md)
7. Logga un riepilogo: N paper processati, N concetti assegnati, N pagine create

**`/arxiv-concepts 2605.XXXXX`** (arxiv_id specifico)
Processa solo quel paper:
1. Leggi `Wiki/papers/2605.XXXXX.md`
2. Analizza titolo, abstract, categorie
3. Suggerisci 2-5 concetti all'utente per conferma
4. Aggiorna il campo concepts dopo conferma

**`/arxiv-concepts --stats`**
Mostra statistiche: quanti paper hanno concepts popolato vs vuoto, distribuzione per concetto.

Vault path: C:\Users\paolo\Progetti AI\Progetto Ricerche WiKi
Concetti disponibili: vedere `Wiki/concepts/` e `Skills/arxiv-concepts/SKILL.md`
