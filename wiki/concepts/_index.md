---
type: meta
title: Concepts Index
updated: 2026-05-21
tags:
  - meta
  - index
  - concepts
status: developing
related:
  - "[[index]]"
---

# Concepts Index

Concetti teorici trasversali — collegati ai paper via campo `concepts:` nel frontmatter.

Per aggiungere concetti ai paper: `/arxiv-concepts`

---

## Fisica

| Concetto | Paper |
|----------|-------|
| [[Meccanica Statistica]] | `cond-mat.stat-mech`, `cond-mat.dis-nn` |
| [[Caos e Nonlinearità]] | `nlin.CD`, `nlin.AO` |
| [[Auto-organizzazione e Sistemi Complessi]] | `nlin.AO`, sistemi emergenti |
| [[Solitoni e Onde Nonlineari]] | `nlin.PS`, `nlin.SI` |
| [[Sistemi Integrabili]] | `nlin.SI` |
| [[Fisica Quantistica]] | `quant-ph` |
| [[Fisica Matematica]] | `math-ph` |
| [[Fisica Biologica]] | `physics.bio-ph` |
| [[Dinamica dei Fluidi]] | `physics.flu-dyn` |
| [[Storia e Filosofia della Fisica]] | `physics.hist-ph` |

## Matematica

| Concetto | Paper |
|----------|-------|
| [[Sistemi Dinamici]] | `math.DS`, `nlin.CD` |
| [[Teoria delle Categorie]] | `math.CT`, `math.AT` |
| [[Topologia Algebrica]] | `math.AT`, `math.GT` |
| [[Geometria Algebrica]] | `math.AG` |
| [[Geometria Differenziale]] | `math.DG` |
| [[Analisi Funzionale]] | `math.FA`, `math.OA` |
| [[Logica e Fondamenti]] | `math.LO`, `cs.LO` |
| [[Teoria dei Gruppi]] | `math.GR` |
| [[Algebra]] | `math.RA` |
| [[Analisi Numerica]] | `math.NA` |
| [[Equazioni alle Derivate Parziali]] | `math.AP` |

## Informatica

| Concetto | Paper |
|----------|-------|
| [[Intelligenza Artificiale]] | `cs.AI`, `cs.LG` |
| [[Large Language Models]] | `cs.CL`, `cs.AI` |
| [[Sistemi Multi-Agente]] | `cs.MA` |
| [[Teoria dei Giochi Computazionale]] | `cs.GT` |
| [[Teoria dell'Informazione]] | `cs.IT` |
| [[Verifica Formale]] | `cs.LO` |
| [[Automi e Linguaggi Formali]] | `cs.FL` |
| [[Calcolo Distribuito]] | `cs.DC` |
| [[Neuroscienze Computazionali]] | `q-bio.NC` |

---

## Tutti i concetti con paper collegati

```dataview
TABLE length(filter(file.inlinks, (l) => l.type = "paper")) AS "Paper collegati"
FROM "Wiki/concepts"
WHERE type = "concept"
SORT file.name ASC
```
