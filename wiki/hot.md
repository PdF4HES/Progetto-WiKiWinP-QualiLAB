---
type: meta
title: "Hot Cache"
updated: 2026-06-13
tags:
  - meta
  - hot-cache
status: evergreen
related:
  - "[[index]]"
  - "[[log]]"
  - "[[overview]]"
---

# Recent Context

Navigation: [[index]] | [[log]] | [[overview]]

## Last Updated

2026-06-13

## Key Recent Facts

- This vault now contains a comprehensive knowledge base on clinical laboratory quality management and accreditation: **ISO 15189:2022/2024**, **ACCREDIA** accreditation processes, **SIPMeL** clinical practice guidance and Choosing Wisely lists across roughly 10 study groups, **EU MDR/IVDR** regulatory framework, and the family of generic **UNI organizational standards** for quality management, risk management, business continuity, occupational health and safety, knowledge management, asset management, facility management, and equipment maintenance.
- Vault totals: **124 source documents** ingested, producing **~196 wiki pages**, spanning address range **c-000001 to c-000177**.
- The **full 12-cluster ingest project is now COMPLETE**.

## Recent Changes

This session completed the final clusters of the ingest project (addresses c-000122–c-000177):

- **Cluster 10** (18 docs): SIPMeL Choosing Wisely lists from multiple study groups (autoimmunology, endocrinology/metabolism, EBLM lists I & II, Laboratorio Green/sustainability) plus miscellaneous appropriateness-related sources, consolidating the **Appropriatezza Diagnostica e Choosing Wisely** hub (c-000081) across SIPMeL study groups, EBLM evidence-based methodology, LIS infrastructure, POCT updates, lipid diagnostics, monoclonal gammopathies, lupus anticoagulant/thrombophilia, and PSA/colorectal cancer markers.
- **Cluster 11** (10 docs): UNI generic management-system standards — ISO 9001, ISO 9004 (durable success/self-assessment), ISO 31000 (risk management), ISO 22301 (business continuity), ISO 45001/45002 (occupational health & safety), ISO 29995 (training vocabulary), ISO 30401 (knowledge management), ISO 55001/55002 (asset management) — all newly cross-linked into the central **Sistema di Gestione per la Qualità** hub (c-000003) as an "integrated management system" layer around ISO 15189.
- **Cluster 12** (9 docs): UNI facility management (ISO 41001/41011/41012) and maintenance terminology/standards (13306, 10147, 11063, 10366, 10685, 15341), extending the asset-management layer to the built environment and equipment lifecycle.
- **Consolidated Corso ISO 15189:2024 summary**: 16 ACCREDIA training decks distilled into 2 pages, including a new **Metodologia di Audit Interno (ISO 19011)** concept (c-000177) covering audit principles, program management (PDCA), and auditor competence — cross-linked with the existing **Audit Interno e Visita Ispettiva** page (c-000014).

A lightweight cross-reference check confirmed the major new hub concepts (ISO 31000, SSL, Facility Management, asset/maintenance terminology) are already correctly linked from the SGQ hub, the Choosing Wisely hub already references all relevant cluster 5/10 sources, and the new ISO 19011 page and ISO 31000 page already cross-link with Audit Interno e Visita Ispettiva. No additional cross-link edits were needed.

## Active Threads

- `wiki/index.md` was just rewritten with a full catalog organized into "Laboratorio Clinico — Quadro Normativo" and "Diagnostica di Laboratorio per Area Clinica" sections.
- Suggested next step: a dedicated **"lint the wiki" pass** — check for orphan pages, broken `[[wikilink]]` references, and inconsistent `related`/`sources` frontmatter across the ~196 pages, given the large volume of content created across 12 clusters.
