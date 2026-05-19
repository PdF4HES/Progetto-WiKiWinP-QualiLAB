---
type: book
title: "Environmental Engineering"
authors: ["Ruth F. Weiner", "Robin A. Matthews"]
year: 2003
edition: "4th ed."
publisher: "Butterworth-Heinemann / Elsevier"
domain: [natural-systems]
tags: [book, ingegneria-ambientale, acqua, aria, rifiuti, rischio, ecologia-applicata]
status: in-coda
created: 2026-05-18
updated: 2026-05-18
raw_file: ".raw/R. F. Weiner, R. Matthews - Environmental Engineering.pdf"
related:
  - "[[Ecodinamica]]"
  - "[[Ecofisica]]"
  - "[[Begon Townsend Harper - Ecology]]"
---

# Weiner & Matthews — Environmental Engineering (4th ed.)

**Autori:** Ruth F. Weiner (U. Michigan, Nuclear Engineering) & Robin A. Matthews (Western Washington U., Huxley College)
**Anno:** 2003 | **Editore:** Butterworth-Heinemann | **pp.** ~540
**ISBN:** 0750672943
**Note:** Aggiornamento del classico testo di Peirce & Vesilind.

> [!key-insight] Punto centrale
> L'ingegneria ambientale applica principi ingegneristici alla protezione dell'ambiente umano e naturale. È un campo di confine tra ingegneria civile, chimica, biologia e diritto ambientale. Centrale è il concetto di **risk analysis**: ogni decisione ambientale comporta una valutazione quantitativa del rischio per la salute e l'ecosistema.

---

## Struttura (~20 capitoli)

### Sezione 1 — Fondamenti

- **Cap. 1: Environmental Engineering** — storia (ingegneria civile → sanità pubblica → ecologia → etica); professione; organizzazione del testo
- **Cap. 2: Assessing Environmental Impact** — impatto ambientale; risk analysis; impatto socioeconomico
- **Cap. 3: Risk Analysis** — concetto di rischio; dose-response; probabilità; rischio per la popolazione; percezione del rischio; ecosystem risk assessment

### Sezione 2 — Acqua

- **Cap. 4: Water Pollution** — fonti di inquinamento; elementi di ecologia acquatica; biodegradazione; BOD; DO sag curve; laghi; acque sotterranee; metalli pesanti
- **Cap. 5: Measurement of Water Quality** — DO, BOD, COD, TOC, pH, azoto, fosforo, patogeni
- **Cap. 6: Water Supply** — ciclo idrologico; acque sotterranee (falda freatica, artesiana); acque superficiali; trasmissione
- **Cap. 7: Water Treatment** — coagulazione/flocculazione; sedimentazione; filtrazione; disinfezione (cloro, UV, ozono)
- **Cap. 8: Collection of Wastewater** — stima quantità; layout fogna; idraulica delle fognature
- **Cap. 9: Wastewater Treatment** — trattamento primario, secondario (fanghi attivi, filtri biologici), terziario
- **Cap. 10: Sludge Treatment and Disposal** — caratteristiche; digestione anaerobica; disidratazione; smaltimento
- **Cap. 11: Nonpoint Source Water Pollution** — erosione del suolo; trasporto di inquinanti; prevenzione

### Sezione 3 — Rifiuti Solidi

- **Cap. 12: Solid Waste** — quantità e caratteristiche dei rifiuti municipali; raccolta
- **Cap. 13: Solid Waste Disposal** — landfill; incenerimento; compostaggio

### Sezione 4 — Aria

*(Capitoli sull'inquinamento atmosferico, dispersione degli inquinanti, particolato, NOx, SOx, ozono)*

### Sezione 5 — Rifiuti Pericolosi, Rumore, Legge

*(Hazardous waste, CERCLA/Superfund, legge ambientale, rumore)*

---

## Concetti Chiave

### Risk Analysis (Cap. 3)

**Definizione di rischio:**
```
Risk = Hazard × Exposure
```
Più formalmente: Risk = f(probability, severity)

**Dosi-risposta**: curva dose-risposta (dose-response curve); NOAEL (No Observed Adverse Effect Level); LOAEL; dose letale LD50.

**Tipi di rischio:**
- Rischio cancerogeno (leptokurtosis of dose-response)
- Rischio non-cancerogeno (threshold model)

**Risk per la popolazione:**
```
Annual Risk = P(exposure) × P(harm | exposure)
```

### DO Sag Curve (Cap. 4)

L'ossigeno disciolto (DO) in un fiume inquinato con BOD:
```
DO deficit (D) = D₀·exp(-k_r·t) - (L₀·k_d/(k_r-k_d))·[exp(-k_d·t) - exp(-k_r·t)]
```
- k_d = constante di deoxygenation (consumo di ossigeno)
- k_r = constante di reaeration (riossigenazione)
- Il "sag" è il punto di DO minimo

La curva modella l'autodepurazione dei fiumi: a distanza sufficiente dall'ingresso del pollutant, il DO si recupera.

### BOD — Biochemical Oxygen Demand (Cap. 5)

Il BOD misura la quantità di ossigeno richiesta da batteri per ossidare la materia organica:
```
BOD_t = L₀·(1 - exp(-k_d·t))
```
- BOD₅ (5 giorni) è il valore standard
- BOD₅ tipico: acque reflue domestiche 200–300 mg/L; acque pulite < 2 mg/L

### Trattamento delle Acque Reflue (Cap. 9)

**Trattamento primario** (fisico): sedimentazione; rimozione solidi grossolani; ~30% BOD rimosso
**Trattamento secondario** (biologico): fanghi attivi (activated sludge) o filtri biologici; riduzione BOD ~90%
**Trattamento terziario** (chimica/fisica avanzata): rimozione N, P; filtrazione fine; disinfezione avanzata

---

## Connessioni nel Wiki

- [[Ecodinamica]] — l'autodepurazione dei fiumi e il ciclo dei nutrienti sono processi ecologici
- [[Ecofisica]] — la DO sag curve è un modello fisico-chimico di un processo ecosistemico
- [[Begon Townsend Harper - Ecology]] — il flusso della materia (cap. 18 di Begon) include i cicli biogeochimici che Weiner tratta dal lato ingegneristico
- [[Reynolds - Energy]] — i sistemi di trattamento consumano energia; bilanci energetici sono centrali

---

## Domande Aperte

- Come si integra la gestione del rischio ambientale (Weiner cap. 3) con l'approccio STAMP di Leveson?
- La resilienza degli ecosistemi acquatici (autodepurazione) è misurabile con le stesse metriche della resilienza ingegneristica?
