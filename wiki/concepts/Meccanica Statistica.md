---
type: concept
address: c-000016
status: developing
domain: meccanica-statistica
tags:
  - concept
  - meccanica-statistica
  - entropia
  - ensemble
  - Boltzmann
  - fluttuazioni
created: 2026-05-19
updated: 2026-05-19
related:
  - "[[Termodinamica dei Fenomeni Irreversibili]]"
  - "[[Fenomeni Autocooperativi]]"
  - "[[Teoria dei Sistemi]]"
  - "[[Sintesi del Campo]]"
---

# Meccanica Statistica

Navigation: [[Wiki/concepts/_index]] | [[Sintesi del Campo]] | [[index]]

---

## Definizione

La meccanica statistica è il collegamento tra il livello microscopico (particelle, atomi, molecole obbedienti a leggi della meccanica classica o quantistica) e il livello macroscopico (termodinamica: temperatura, pressione, entropia). Fornisce una *derivazione* delle leggi termodinamiche a partire dalle interazioni microscopiche, usando strumenti probabilistici e statistici.

---

## Fondatori e Contributi Chiave

**Ludwig Boltzmann (1844–1906)**
Formula l'entropia statistica: S = k_B ln Ω (dove Ω è il numero di microstati compatibili con lo stato macroscopico). Dimostra il teorema H (l'entropia cresce). Si scontra con Loschmidt e Zermelo sul paradosso della reversibilità.

**Josiah Willard Gibbs (1839–1903)**
Introduce il formalismo degli *ensemble*: invece di tracciare una singola traiettoria, si considera una distribuzione statistica di sistemi. Definisce l'entropia di Gibbs: S = -k_B Σ p_i ln p_i.

**Max Planck (1858–1947) · Albert Einstein (1879–1955)**
Meccanica statistica quantistica: il corpo nero (Planck, 1900) e l'effetto fotoelettrico spiegano le anomalie del classico. Einstein contribuisce con le statistiche di Bose-Einstein e la fluttuazione dei fotoni.

**Enrico Fermi (1901–1954) · Paul Dirac (1902–1984)**
Statistica di Fermi-Dirac per particelle con spin semi-intero (fermioni): il principio di esclusione di Pauli limita l'occupazione degli stati.

---

## Concetti Fondamentali

**Ensemble microcanonico**: sistema isolato con energia E fissa. La probabilità di ciascun microstato è uniforme su tutti i microstati compatibili. S = k_B ln Ω(E,V,N).

**Ensemble canonico**: sistema in equilibrio termico con un bagno (T fissa). La probabilità del microstato i è proporzionale al fattore di Boltzmann: p_i = exp(-βE_i)/Z. La funzione di partizione Z = Σ exp(-βE_i) contiene tutta la termodinamica.

**Ensemble gran-canonico**: scambio di particelle e calore (T e μ fissi). Usato per gas quantistici, sistemi aperti, adsorbimento.

**Connessione termodinamica**:
```
F = -k_B T ln Z   (energia libera di Helmholtz)
S = -∂F/∂T|_V    (entropia)
p = -∂F/∂V|_T   (pressione)
```

**Teorema di fluttuazione-dissipazione**: le fluttuazioni spontanee all'equilibrio e la risposta a perturbazioni esterne sono collegate dallo stesso coefficiente. Base della risposta lineare.

---

## Il Problema dell'Irreversibilità

Il paradosso fondamentale: le equazioni del moto (Newton, Schrödinger, Hamilton) sono simmetriche nel tempo, ma la termodinamica è irreversibile. Come nasce la freccia del tempo?

**Risposta di Boltzmann** (argomento probabilistico): il coarse-graining dello spazio delle fasi. Gli stati "ordinati" sono astronomicamente rari rispetto agli stati "disordinati". La freccia del tempo è statistica, non assoluta.

**Risposta di Prigogine** (vedi [[Prigogine - From Being to Becoming]]): per sistemi con *mixing forte* (K-systems), l'irreversibilità è intrinseca alla dinamica. Non è solo statistica ma una proprietà della classe di sistemi fisici rilevanti.

---

## Domande Aperte

- Il principio ergodico è sempre valido? In quali sistemi fallisce?
- Come si raccordano la freccia del tempo termodinamica e quella cosmologica (espansione dell'universo)?
- L'irreversibilità della misurazione quantistica è della stessa natura di quella termica?

---

## Fonti Disponibili nel Wiki

- [[Tolman - Principles Statistical Mechanics]] — il classico (1938); fondamenti rigorosi; il punto di partenza critico di Prigogine
- [[Reichl - Modern Course Statistical Physics]] — la versione moderna con FDT, Fokker-Planck, caos quantistico
- [[Prigogine - From Being to Becoming]] — il programma di Prigogine: irreversibilità intrinseca alla dinamica
- [[Prigogine Rice - Advances Chemical Physics Vol90]] — la formalizzazione tecnica dell'operatore entropico

## Fonti da Acquisire

- Huang, K. (1987). *Statistical Mechanics*. Wiley. (testo standard moderno)
- Pathria, R.K. & Beale, P.D. (2011). *Statistical Mechanics*. Elsevier. (referenza avanzata)
