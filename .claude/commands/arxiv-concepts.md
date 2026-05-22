---
description: Collega paper ArXiv ai concetti del vault popolando il campo concepts[] nel frontmatter.
---

Leggi `Skills/arxiv-concepts/SKILL.md` per la lista concetti e il mapping categoria→concetto, poi esegui:

**`/arxiv-concepts --batch`** — processa tutti i paper con `concepts: []` vuoto:
1. Grep per trovare file in `Wiki/papers/` con `concepts: \[\]`
2. Per ogni paper: leggi primary_category, applica mapping da SKILL.md
3. Aggiorna `concepts:` nel frontmatter (da `[]` a lista stringhe)
4. Crea `Wiki/concepts/{Concetto}.md` se non esiste (usa template in SKILL.md)
5. Logga riepilogo finale

**`/arxiv-concepts 2605.XXXXX`** — un paper specifico: analizza e suggerisci concetti.

**`/arxiv-concepts --stats`** — statistiche: paper con/senza concetti.

Vault: C:\Users\paolo\Progetti AI\Progetto Ricerche WiKi
