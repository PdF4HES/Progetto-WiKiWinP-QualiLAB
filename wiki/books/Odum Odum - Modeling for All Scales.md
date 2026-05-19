---
type: book
title: "Modeling for All Scales: An Introduction to System Simulation"
authors: ["Howard T. Odum", "Elisabeth C. Odum"]
year: 2000
edition: "1st ed."
publisher: "Academic Press"
domain: [ecodinamica, ecofisica, natural-systems]
tags: [book, modellistica, simulazione, energy-systems, emergy, STELLA, Odum]
status: in-coda
created: 2026-05-18
updated: 2026-05-18
raw_file: ".raw/H. T. Odum, E. C. Odum - Modeling for All Scales - An Introduction to System Simulation.pdf"
related:
  - "[[Ecofisica]]"
  - "[[Ecodinamica]]"
  - "[[Begon Townsend Harper - Ecology]]"
  - "[[Reynolds - Energy]]"
---

# Odum & Odum — Modeling for All Scales

**Autori:** Howard T. Odum (U. Florida) & Elisabeth C. Odum (Santa Fe Community College)
**Anno:** 2000 | **Editore:** Academic Press
**Contesto:** Howard T. Odum (1924–2002) è il fondatore dell'ecologia dei sistemi e del concetto di **emergy**.

> [!key-insight] Punto centrale
> I sistemi a tutte le scale — dall'atomo alla biosfera, dall'economia ai sistemi urbani — condividono la stessa struttura energetica. Il libro insegna a costruire, simulare e calibrare modelli usando l'**Energy Systems Language** (ESL/diagrammi Odum) con strumenti come EXTEND, STELLA e BASIC.

---

## Struttura (2 parti + appendici)

### Parte 1 — Modeling

**Cap. 1: Modeling and Simulation**
- TANK: il modello più semplice (una storage + inflow + outflow)
- Parti e insiemi; scala e gerarchia energetica
- Procedura per costruire un modello conciso

**Cap. 2: Energy Systems Diagramming**
- Tradurre parole in simboli ESL
- Pathways, force e flow (flussi causali)
- Circolazione del materiale; circolazione del denaro
- **Simboli precisi** (6 simboli base Odum): Source, Tank, Producer, Consumer, Hexagon (interaction), Sensor
- **Maximum Power Principle** (Lotka–Odum): i sistemi biologici massimizzano il flusso di energia utile

**Cap. 3: Numbers on Networks**
- Diagrammi con numeri; valori energetici; flussi tra due storage

---

### Parte 2 — Simulation

**Cap. 4–5: EXTEND** (software di simulazione a blocchi)
**Cap. 6: Equations from Diagrams** — equazioni per una singola storage; step simulation; equazioni da diagrammi sistemici; caratteristiche matematiche delle unità
**Cap. 7: Calibrating Models** — procedura di calibrazione; spreadsheet
**Cap. 8: Simulating with Spreadsheet**
**Cap. 9: Programming in BASIC** — modelli TANK, EXPO, DRAIN, PC&CYCLE; crescita esponenziale; dispersione; produzione-consumo-riciclo
**Cap. 10: Simulating with STELLA** — il software di system dynamics per ecologia
**Cap. 11: Simulating Emergy and Transformity** — concetti di emergy; EMFISH; EMGTANK; RENEMGY; emergy internazionale

---

## Concetti Chiave

### Energy Systems Language (ESL)

H.T. Odum sviluppa un linguaggio grafico per rappresentare i flussi di energia in sistemi di qualsiasi scala. I 6 simboli base:

| Simbolo | Nome | Significa |
|---------|------|-----------|
| ○ | Source | Sorgente illimitata di energia/materiale dall'esterno |
| □ | Tank (Storage) | Accumulo di materiale o energia |
| Esagono | Interaction | Interazione tra due flussi (es. produzione = luce × piante) |
| ◯ con linea | Producer | Autotrofo che cattura energia e produce biomassa |
| → | Consumer | Eterotrofo che degrada materiale |
| ⬡ | Sensor/Transaction | Segnale di feedback; transazione monetaria |

### Il Modello TANK (Cap. 1)

Il mattone fondamentale: una storage con un inflow e un outflow:
```
dQ/dt = J_in - k·Q
```
- Q = quantità accumulata
- J_in = input esterno
- k = costante di perdita (decay)
- Stato stazionario: Q* = J_in / k

### Principio della Massima Potenza (Cap. 2)

**Maximum Power Principle** (Lotka 1922; Odum 1955): *i sistemi biologici in competizione evolvono verso la configurazione che massimizza il flusso di energia utile*.

Implicazioni:
- I sistemi in competizione con la massima potenza sopravvivono
- La struttura del sistema si adatta per massimizzare l'uso delle risorse disponibili
- Non è la massimizzazione dell'efficienza, ma della *potenza utile*

### Emergy e Transformity (Cap. 11)

**Emergy** (energia di memoria/solare equivalente, EMergy): tutta l'energia solare equivalente (direttamente o indirettamente) usata per produrre un servizio o materiale.

**Transformity**: emergy per unità di energia = qualità energetica.
```
Transformity = Emergy input / Energy output (sej/J)
```

Gerarchia energetica: luce solare (1 sej/J) → biomassa (1000 sej/J) → combustibili fossili (40,000 sej/J) → informazione (10^8 sej/J)

### Modello PC&CYCLE (Produzione-Consumo-Riciclo)

Un sistema chiuso con produttore, consumatore e riciclo della materia:
```
dP/dt = kL·N·P - k1·P·C     (produttore)
dC/dt = k2·P·C - k3·C        (consumatore)
dN/dt = k3·C - kL·N·P        (nutrienti riciclati)
```
Modello fondamentale degli ecosistemi: energia entra, materia è riciclata.

---

## H.T. Odum: Visione Sistemica

Odum vede *tutta* la realtà — economie, ecosistemi, città — come sistemi energetici soggetti alle stesse leggi termodinamiche. La moneta è un contatore di flussi di emergy. I prezzi riflettono (imperfettamente) i costi energetici reali. Questa visione connette:
- Ecologia → Economia → Termodinamica
- Scala molecolare → planetaria

---

## Connessioni nel Wiki

- [[Ecofisica]] — l'emergy e la gerarchia energetica sono al cuore di questa pagina
- [[Ecodinamica]] — il modello PC&CYCLE modella la dinamica dell'ecosistema
- [[Reynolds - Energy]] — Reynolds copre la termodinamica classica; Odum la applica agli ecosistemi
- [[Begon Townsend Harper - Ecology]] — stessi sistemi (produttori/consumatori) da prospettive diverse
- [[Bertuglia Vaio - Nonlinearity Chaos Complexity]] — i modelli Volterra-Lotka sono simulabili con STELLA/EXTEND

---

## Domande Aperte

- L'emergy è rigorosa termodinamicamente? Critiche (Hau & Bakshi) alla sua misurabilità pratica.
- Il Maximum Power Principle è compatibile con il 2° principio della termodinamica?
- Come si raccorda la gerarchia energetica di Odum con la gerarchia sistemica di Boulding?
