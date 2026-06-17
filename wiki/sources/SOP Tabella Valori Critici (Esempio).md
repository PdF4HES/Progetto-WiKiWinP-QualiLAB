---
type: source
title: "SOP Tabella Valori Critici (Esempio)"
created: 2026-06-12
updated: 2026-06-12
tags:
  - laboratorio-medico
  - source
  - valori-critici
status: developing
address: c-000018
source_type: internal-document
author: ""
date_published: 2026-06-12
url: ""
confidence: medium
key_claims:
  - "È l'Allegato A della SOP-GEN-008: la tabella delle soglie analitiche oltre le quali il LIS blocca automaticamente il referto e impone la comunicazione d'urgenza entro 15 minuti."
  - "I valori riportati sono dichiarati 'parametri standard comunemente accettati dalla letteratura scientifica internazionale (SIBioC / CLSI) per pazienti adulti', quindi un esempio/punto di partenza da personalizzare per il laboratorio."
  - "Copre quattro aree analitiche: Biochimica, Ematologia, Coagulazione e Microbiologia, ciascuna con soglie inferiore e/o superiore di panico."
  - "Esempi di soglie: Potassio < 2.8 o > 6.2 mmol/L; Sodio < 120 o > 160 mmol/L; Glucosio < 50 o > 450 mg/dL; Emoglobina < 6.5 o > 20.0 g/dL; Piastrine < 30 o > 1.000 x10^9/L; PT(INR) > 5.0; qualsiasi positività di emocoltura/liquor è considerata critica."
related:
  - "[[Valori Critici]]"
  - "[[SOP Controllo Valori Critici]]"
  - "[[Procedura Operativa Standard ISO 15189 (SOP Master)]]"
sources:
  - "[[.raw/Procedura Operativa Standard ISO 15189 - Esempio di tabella dei Valori Critici.docx]]"
---

## Cosa è

Questo documento è l'**Allegato A** richiamato dalla **[[SOP Controllo Valori Critici]]** (SOP-GEN-008): una tabella di riferimento che definisce, analita per analita, le **soglie di panico** (valore inferiore e/o superiore) oltre le quali il software LIS blocca l'emissione automatica del referto e fa scattare l'obbligo di comunicazione telefonica d'urgenza al medico curante entro 15 minuti.

Il documento è esplicitamente presentato come un **esempio basato su parametri standard di letteratura** (SIBioC / CLSI) per pazienti adulti, da adattare ai range effettivi e alla strumentazione del laboratorio.

## Soglie riportate (esempio)

| Area | Analita | Unità | Soglia inferiore | Soglia superiore |
|---|---|---|---|---|
| Biochimica | Potassio (K+) | mmol/L | ≤ 2.8 | ≥ 6.2 |
| Biochimica | Sodio (Na+) | mmol/L | ≤ 120 | ≥ 160 |
| Biochimica | Calcio totale (Ca++) | mg/dL | ≤ 6.5 | ≥ 13.0 |
| Biochimica | Glucosio | mg/dL | ≤ 50 | ≥ 450 |
| Biochimica | Creatinina (nuovo riscontro) | mg/dL | — | ≥ 5.0 |
| Ematologia | Emoglobina (Hb) | g/dL | ≤ 6.5 | ≥ 20.0 |
| Ematologia | Piastrine (PLT) | x10⁹/L | ≤ 30 | ≥ 1.000 |
| Ematologia | Globuli bianchi (WBC) | x10⁹/L | ≤ 1.5 | ≥ 50.0 |
| Coagulazione | PT (INR) | Ratio | — | ≥ 5.0 |
| Coagulazione | Fibrinogeno | mg/dL | ≤ 100 | — |
| Microbiologia | Emocoltura / Liquor | — | qualsiasi positività | — |

## Rilevanza

La tabella è il dato quantitativo che rende operativa la **[[SOP Controllo Valori Critici]]**: senza soglie definite, l'allarme automatico sul LIS descritto in quella SOP non potrebbe funzionare. Per l'inquadramento generale del concetto di valore critico, vedi **[[Valori Critici]]**.
