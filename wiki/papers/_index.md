---
type: meta
title: Papers Index
updated: 2026-05-21
tags:
  - meta
  - papers
  - index
status: active
related:
  - "[[index]]"
  - "[[concepts/_index]]"
  - "[[gaps/_index]]"
---

# Papers — ArXiv Collection

Raccolta paper da ArXiv · Aggiornata da `/arxiv-collect`

Navigation: [[index]] | [[concepts/_index|Concepts]] | [[gaps/_index|Gaps]]

---

## Tutti i Paper

```dataview
TABLE
  title AS "Titolo",
  authors[0] AS "Primo Autore",
  year AS "Anno",
  primary_category AS "Categoria",
  status AS "Stato",
  rating AS "Rating"
FROM "Wiki/papers"
WHERE type = "paper"
SORT ingested DESC
LIMIT 50
```

---

## Da Leggere

```dataview
TABLE
  title AS "Titolo",
  primary_category AS "Categoria",
  submitted AS "Submission"
FROM "Wiki/papers"
WHERE type = "paper" AND status = "unread"
SORT submitted DESC
```

---

## Per Gruppo

### Physics

```dataview
TABLE
  title AS "Titolo",
  authors[0] AS "Autore",
  primary_category AS "Categoria",
  submitted AS "Data"
FROM "Wiki/papers"
WHERE type = "paper" AND arxiv_group = "Physics"
SORT submitted DESC
LIMIT 20
```

### Mathematics

```dataview
TABLE
  title AS "Titolo",
  authors[0] AS "Autore",
  primary_category AS "Categoria",
  submitted AS "Data"
FROM "Wiki/papers"
WHERE type = "paper" AND arxiv_group = "Math"
SORT submitted DESC
LIMIT 20
```

### Computer Science

```dataview
TABLE
  title AS "Titolo",
  authors[0] AS "Autore",
  primary_category AS "Categoria",
  submitted AS "Data"
FROM "Wiki/papers"
WHERE type = "paper" AND arxiv_group = "CS"
SORT submitted DESC
LIMIT 20
```

---

## Statistiche

```dataview
TABLE WITHOUT ID
  key AS "Gruppo",
  length(rows) AS "Totale",
  length(filter(rows, (r) => r.status = "unread")) AS "Non letti",
  length(filter(rows, (r) => r.status = "read")) AS "Letti"
FROM "Wiki/papers"
WHERE type = "paper"
GROUP BY arxiv_group
SORT length(rows) DESC
```

---

<!-- I paper vengono aggiunti automaticamente dall'agente /arxiv-collect -->
