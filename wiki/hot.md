---
type: meta
title: "Hot Cache"
updated: 2026-05-17T00:00:00
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

2026-05-18: **Batch ingest completato** — 16 libri + 1 fonte MD ingeriti. PDF decriptati con qpdf, convertiti con pdftotext. Creati 16 pagine in wiki/books/. Domain pages aggiornate con link ai libri. La biblioteca del vault è ora completa e cross-referenziata.

2026-05-17: Scaffold completo del wiki per studio personale su sistemi, termodinamica irreversibile, fenomeni autocooperativi, ingegneria dei sistemi. Modalita D+E+F attivate.

## Key Recent Facts

- **16 libri ingeriti** (2026-05-18): GST, nonlinearità/caos, sistemi di sistemi, SE (SEBoK/Holt/Eisner/Wasson), ecologia (Begon), emergy (Odum), resilienza (Hollnagel), termodinamica (Reynolds), ecologia ambientale, computabilità (Toffalori), Promise Theory (Burgess)
- PDF sorgente erano password-protected: decriptati con `qpdf --decrypt`, convertiti con `pdftotext -layout`
- Cross-referenze chiave identificate: Volterra-Lotka appare in Bertuglia + Begon + Odum; STAMP di Leveson connette resilienza e SE; Promise Theory di Burgess formalizza i SoS di Boardman
- Domain concept pages aggiornate: [[Teoria dei Sistemi]], [[Ingegneria dei Sistemi]], [[Fenomeni Autocooperativi]], [[Ecodinamica]], [[Ecofisica]], [[Termodinamica dei Fenomeni Irreversibili]]
- Wiki riconfigurato da vault plugin-dev a vault di studio personale (modalita D+E+F)
- 4 concept seed pages create: [[Teoria dei Sistemi]], [[Termodinamica dei Fenomeni Irreversibili]], [[Fenomeni Autocooperativi]], [[Ingegneria dei Sistemi]]
- Output attesi: libro originale + lezioni universitarie + knowledge base permanente

## Recent Changes

- **2026-05-18**: Created 16 book pages in wiki/books/: Skyttner, Bertuglia/Vaio, Gharajedaghi, SEBoK, Holt, Eisner, Boardman/Sauser, Wasson, Satzinger, Begon, Odum, Hollnagel, Reynolds, Weiner, Toffalori, Burgess
- **2026-05-18**: Updated domain pages with book links: [[Teoria dei Sistemi]], [[Ingegneria dei Sistemi]], [[Fenomeni Autocooperativi]], [[Ecodinamica]], [[Ecofisica]], [[Termodinamica dei Fenomeni Irreversibili]]
- **2026-05-18**: Updated [[Wiki/books/_index]], [[index]] (total pages 56, sources 17)
- 2026-05-17: Created scaffold, domain concept pages, templates

## Active Threads

- Prossimo passo: leggere i libri; iniziare con Skyttner (cap. 2 per fondamenti GST) e Bertuglia (cap. 14-23 per caos)
- Domanda aperta principale: come si collega formalmente la sinergetica di Haken alla TIP di Prigogine?
- Cross-reference chiave da esplorare: Volterra-Lotka in Bertuglia/Begon/Odum; STAMP in Hollnagel/Leveson vs. V-model SE
- Roadmap studio in [[Percorso di Studio]]

## Plugin State (storico, non attivo)

Il contenuto precedente del vault (sviluppo plugin claude-obsidian v1.6.0, DragonScale) e conservato in wiki/meta/ e wiki/concepts/ originali. Non eliminato: e context storico utile sul pattern LLM Wiki.
