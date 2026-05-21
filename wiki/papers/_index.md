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
  title as "Titolo",
  authors[0] as "Primo Autore",
  year as "Anno",
  primary_category as "Categoria",
  status as "Stato",
  rating as "Rating"
FROM "wiki/papers"
WHERE type = "paper"
SORT ingested DESC
LIMIT 50
```

---

## Da Leggere

```dataview
TABLE
  title as "Titolo",
  primary_category as "Categoria",
  submitted as "Submission"
FROM "wiki/papers"
WHERE type = "paper" AND status = "unread"
SORT submitted DESC
```

---

## Per Gruppo

### Physics

```dataview
TABLE
  title as "Titolo",
  authors[0] as "Autore",
  primary_category as "Categoria",
  submitted as "Data"
FROM "wiki/papers"
WHERE type = "paper" AND group = "Physics"
SORT submitted DESC
LIMIT 20
```

### Mathematics

```dataview
TABLE
  title as "Titolo",
  authors[0] as "Autore",
  primary_category as "Categoria",
  submitted as "Data"
FROM "wiki/papers"
WHERE type = "paper" AND group = "Math"
SORT submitted DESC
LIMIT 20
```

### Computer Science

```dataview
TABLE
  title as "Titolo",
  authors[0] as "Autore",
  primary_category as "Categoria",
  submitted as "Data"
FROM "wiki/papers"
WHERE type = "paper" AND group = "CS"
SORT submitted DESC
LIMIT 20
```

---

## Statistiche

```dataview
TABLE WITHOUT ID
  group as "Gruppo",
  length(rows) as "Paper",
  length(filter(rows, (r) => r.status = "unread")) as "Non letti",
  length(filter(rows, (r) => r.status = "read")) as "Letti"
FROM "wiki/papers"
WHERE type = "paper"
GROUP BY group
```

---

<!-- I paper vengono aggiunti automaticamente dall'agente /arxiv-collect -->
