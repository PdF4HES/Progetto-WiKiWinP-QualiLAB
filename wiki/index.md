---
type: meta
title: Wiki Index
updated: 2026-04-07
tags:
  - meta
  - index
status: evergreen
related:
  - "[[overview]]"
  - "[[log]]"
  - "[[hot]]"
  - "[[dashboard]]"
  - "[[Wiki Map]]"
  - "[[Wiki/concepts/_index]]"
  - "[[Wiki/entities/_index]]"
  - "[[Wiki/sources/_index]]"
  - "[[LLM Wiki Pattern]]"
  - "[[Hot Cache]]"
  - "[[Compounding Knowledge]]"
  - "[[Andrej Karpathy]]"
---

# Wiki Index

Last updated: 2026-05-18 | Total pages: 53 | Sources ingested: 17

Navigation: [[overview]] | [[log]] | [[hot]] | [[dashboard]] | [[Wiki Map]] | [[getting-started]]

---

## Concepts

- [[LLM Wiki Pattern]] — the pattern for building persistent, compounding knowledge bases using LLMs (status: mature)
- [[Hot Cache]] — ~500-word session context file, updated after every ingest and session (status: mature)
- [[Compounding Knowledge]] — why wiki knowledge grows more valuable over time, unlike RAG (status: mature)
- [[cherry-picks]] — prioritized feature backlog from ecosystem research; 13 features to add to claude-obsidian (status: current)
- [[SVG Diagram Style Guide]] — canonical visual style for all diagrams: Space Grotesk, #0A0A0A dark theme, #E07850 accent, full design tokens (status: evergreen)
- [[Pro Hub Challenge]] — community challenge pattern for building claude-seo/claude-blog extensions; first challenge produced 6 submissions, 5 integrated in v1.9.0 (status: evergreen)
- [[Semantic Topic Clustering]] — SERP-based keyword grouping replacing paid tools; hub-spoke architecture with interactive visualization (status: evergreen)
- [[Search Experience Optimization]] — "read SERPs backwards" methodology for page-type mismatch detection and persona scoring (status: evergreen)
- [[SEO Drift Monitoring]] — "git for SEO" baseline/diff/track with 17 comparison rules and SQLite persistence (status: evergreen)
- [[DragonScale Memory]] — memory-layer spec inspired by the Heighway dragon curve; fold operator, deterministic page addresses, semantic tiling, boundary-first autoresearch (status: shipped v0.4, all four mechanisms opt-in)
- [[Persistent Wiki Artifact]]: durable Markdown page as the LLM's memory object, distinct from ephemeral chat turns (status: developing)
- [[Source-First Synthesis]]: provenance discipline; raw sources stay immutable while the wiki layer is synthesized and cited (status: developing)
- [[Query-Time Retrieval]]: wiki query path synthesizes with citations; complementary to Obsidian's in-vault search (status: developing)

---

## Entities

- [[Andrej Karpathy]] — AI researcher, creator of the LLM Wiki pattern, former Tesla AI director (status: developing)
- [[Ar9av-obsidian-wiki]] — multi-agent compatible LLM Wiki plugin; delta tracking manifest (status: current)
- [[Nexus-claudesidian-mcp]] — native Obsidian plugin + MCP bridge; workspace memory, task management (status: current)
- [[ballred-obsidian-claude-pkm]] — goal cascade PKM; auto-commit hooks, /adopt command (status: current)
- [[rvk7895-llm-knowledge-bases]] — 3-depth query system, Marp slides, parallel deep research (status: current)
- [[kepano-obsidian-skills]] — official skills from Obsidian creator; defuddle, obsidian-bases (status: current)
- [[Claudian-YishenTu]] — native Obsidian plugin embedding Claude Code; plan mode, @mention (status: current)
- [[Claude SEO]] — Tier 4 Claude Code skill for SEO analysis; 23 skills, 17 agents, 30 scripts at v1.9.0 (status: evergreen)

---

## Sources

- [[claude-obsidian-ecosystem-research]] — 2026-04-08 | web research across 16+ repos | 8 wiki pages created

---

## Questions

- [[How does the LLM Wiki pattern work]] — how the pattern works and why it outperforms RAG at human scale (status: developing)

---

## Comparisons

- [[Wiki vs RAG]] — when to use a wiki knowledge base versus RAG; verdict: wiki wins at <1000 pages
- [[claude-obsidian-ecosystem]] — feature matrix of 16+ Claude+Obsidian projects; where claude-obsidian wins and gaps

---

## Decisions

- [[2026-04-14-community-cta-rollout]] - Skool community CTA footer added to 6 skill repos with per-tool frequency rules (status: active)
- [[2026-04-15-slides-and-release-session]] - Claude SEO v1.9.0 slides (15-slide HTML deck) + GitHub release v1.9.0 with PDF asset (status: complete)
- [[2026-04-15-release-report-session]] - Claude SEO v1.9.0 Release Report PDF: dark theme, 13 pages, WeasyPrint layout fixes, Challenge v2 added (status: complete)
- [[2026-04-14-claude-seo-v190-session]] - Claude SEO v1.9.0 Pro Hub Challenge integration: 5 submissions, 4 new skills, 4 review rounds, cybersecurity audit (status: complete)

---

## Papers

<!-- Aggiungi paper annotati qui -->

---

## Books

### Teoria dei Sistemi
- [[Skyttner - General Systems Theory]] — Skyttner 2005 | GST completa: Boulding, Beer, Lovelock, auto-organizzazione (status: in-coda)
- [[Gharajedaghi - Systems Thinking]] — Gharajedaghi 2011 | Interactive design, mess, multidimensionalità (status: in-coda)
- [[Bertuglia Vaio - Nonlinearity Chaos Complexity]] — Bertuglia/Vaio 2005 | Volterra-Lotka, Lorenz, mappa logistica, complessità (status: in-coda)
- [[Boardman Sauser - Systems Thinking]] — Boardman/Sauser 2008 | Conceptagon, SoS ABCDE, systemigrams (status: in-coda)
- [[Burgess - Thinking in Promises]] — Burgess 2015 | Promise Theory, agenti autonomi, cooperazione distribuita (status: in-coda)

### Ingegneria dei Sistemi
- [[SEBoK v2.7]] — INCOSE 2022 | Enciclopedia SE: fondamenti, lifecycle, MBSE, SoS, healthcare (status: in-coda)
- [[Holt - Systems Engineering Demystified]] — Holt 2023 | MBSE 5-stage evolution, SysML, ontologie (status: in-coda)
- [[Eisner - Essentials SE Management]] — Eisner 2002 | PM + 30 elementi SE + architecting + earned value (status: in-coda)
- [[Wasson - System Analysis Design Development]] — Wasson 2006 | 57-chapter SADD: CONOPS, use cases, V&V, RAM (status: in-coda)
- [[Satzinger Jackson Burd - System Analysis Design]] — Satzinger et al. 2009 | SDLC, UML, OO, database, IT systems (status: in-coda)
- [[Hollnagel Woods Leveson - Resilience Engineering]] — Hollnagel/Woods/Leveson 2006 | STAMP, drift into failure, WAI/WAD (status: in-coda)

### Sistemi Naturali
- [[Begon Townsend Harper - Ecology]] — Begon et al. 2006 | Ecologia 4th ed.: organismi, interazioni, ecosistemi (status: in-coda)
- [[Odum Odum - Modeling for All Scales]] — H.T. Odum 2000 | Emergy, ESL, STELLA/EXTEND, Maximum Power Principle (status: in-coda)
- [[Weiner Matthews - Environmental Engineering]] — Weiner/Matthews 2003 | Acqua, aria, rifiuti, risk analysis (status: in-coda)

### Fisica / Termodinamica
- [[Reynolds - Energy]] — Reynolds 1974 | Energia dalla natura all'uomo; termodinamica accessibile (status: in-coda)

### Fondamenti Informatici
- [[Toffalori et al - Teoria Computabilità Complessità]] — Toffalori et al. 2005 | MT, P=NP, Cook-Levin, Savitch, computazione quantistica (status: in-coda)

---

## Thesis

- [[Sintesi del Campo]] — stato dell'arte complessivo: sistemi, termodinamica, auto-organizzazione (status: developing)

---

## Gaps

<!-- Aggiungi domande aperte qui -->

---

## Goals

- [[Percorso di Studio]] — roadmap complessiva: libro, lezioni universitarie, wiki (status: active)

---

## Journal

- [[2026-05-17-inizio]] — avvio del wiki: scaffold struttura D+E+F, domini definiti

---

## Lessons

<!-- Aggiungi lezioni qui -->

---

## Domains — Sistemi

- [[Teoria dei Sistemi]] — GST (Bertalanffy), cibernetica (Wiener), system dynamics (Forrester) (status: developing)
- [[Termodinamica dei Fenomeni Irreversibili]] — TIP, Onsager, Prigogine, strutture dissipative (status: developing)
- [[Fenomeni Autocooperativi]] — sinergetica (Haken), iperciclo (Eigen), CAS (Kauffman) (status: developing)
- [[Ingegneria dei Sistemi]] — INCOSE, V-Model, MBSE, SysML (status: developing)

---

## Domains — Sistemi Naturali

- [[Wiki/natural-systems/_index|Natural Systems]] — hub: biologia, biochimica, ecofisica, ecodinamica
- [[Biologia dei Sistemi]] — reti geniche/metaboliche/proteomiche, network motifs (Alon), biologia sintetica (status: developing)
- [[Biochimica]] — metabolismo, bioenergetica, ATP-sintetasi, legge di Mitchell, struttura molecolare della vita (status: developing)
- [[Ecofisica]] — leggi di scala allometriche (West), metabolic theory of ecology, flussi energetici, exergia (status: developing)
- [[Ecodinamica]] — Lotka-Volterra, reti trofiche, resilienza (Holling), ciclo adattativo, tipping points (status: developing)
