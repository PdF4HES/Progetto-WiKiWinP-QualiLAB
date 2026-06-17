---
type: source
title: "SIPMeL - Linee Guida per il Confronto di Procedure di Esami di Laboratorio (CLSI EP09-A3 ed EP31-A-IR)"
created: 2026-06-13
updated: 2026-06-13
tags:
  - laboratorio-medico
  - source
  - sipmel
  - clsi
  - validazione-metodi
  - statistica
status: complete
address: c-000124
related:
  - "[[Confronto di Procedure e Verifica di Confrontabilità (CLSI EP09/EP31)]]"
  - "[[Validazione e Verifica dei Metodi Analitici]]"
  - "[[ISO 15189]]"
  - "[[Incertezza di Misura]]"
  - "[[SIPMeL]]"
sources:
  - ".raw/unlocked_SIPMEL - Linee guida per il confronto di procedure di esami di laboratorio. Utilizzo delle indicazioni di CLSI EP09-A3 ed EP31-A-IR.pdf"
---

## Riferimento bibliografico

Pradella M, Cesana BM. **Linee guida per il confronto di procedure di esami di laboratorio: utilizzo delle indicazioni di CLSI EP09-A3 e EP31-A-IR** (Guidelines for the comparison of laboratory examination procedures: use of indications of CLSI EP09-A3 and EP31-A-IR). *Riv Ital Med Lab*, Rassegna. Manuscript RIME-D-15-00033.

Nota: documento presentato come Linea Guida Q7 della Commissione Nazionale Qualità ed Accreditamento (COMMQUA) SIPMeL al 1° Congresso Nazionale SIPMeL, Roma 2015.

Autori: Marco Pradella (Laboratorio analisi Ospedali di Castelfranco Veneto e Montebelluna; SIPMeL-COMMQUA; CISMEL) e Bruno Mario Cesana (Unità di Statistica e Biomatematica, Università di Brescia; SISMEC, gruppo MisMed).

## Sintesi

### Contesto normativo

Gli standard di accreditamento **ISO 15189:2012 (punto 5.6.4, comparabilità dei risultati degli esami)** e **ISO 22870:2006 (punto 5.6.8, POCT)** richiedono sia al laboratorio medico sia al produttore di sistemi/reagenti di confrontare le procedure che forniscono risultati per lo stesso esame, per accertare la **comparabilità dei risultati** negli intervalli clinicamente appropriati, informare gli utenti di eventuali differenze e documentare/registrare gli interventi correttivi.

Nota terminologica importante: il documento distingue **"esattezza" (trueness)** da **"accuratezza" (accuracy)** — la seconda comprende anche la componente di errore casuale (precisione), la prima si riferisce solo allo scarto sistematico (bias) dal valore vero.

### Tre linee guida CLSI, due ruoli diversi

| Linea guida | Ambito | Attore tipico | Numerosità minima |
|---|---|---|---|
| **CLSI EP09-A3** (Measurement Procedure Comparison and Bias Estimation Using Patient Samples) | Confronto tra una procedura "candidata" e una "comparativa" (anche verso un metodo di riferimento) | Produttore (validazione) o Laboratorio (verifica) | ≥100 campioni (produttore) / ≥40 campioni (laboratorio) |
| **CLSI EP31-A-IR** (Verification of Comparability of Patient Results Within One Health Care System) | Confronto tra fino a 10 strumenti/sedi all'interno della stessa struttura sanitaria (es. POCT vs laboratorio centrale, lotti, strumenti di backup) | Laboratorio | Tabelle dedicate (Appendice B) per numero di serie/replicati |
| **CLSI EP30-A** (Characterization and Qualification of Commutable Reference Materials) | Verifica della **commutabilità** dei materiali di calibrazione/controllo | Produttore/Laboratorio | Regressione con intervalli predittivi 95% |

I "metodi" da confrontare sono convenzionalmente denominati **procedura di misura candidata** (nuova) e **procedura di misura comparativa** (esistente o di riferimento).

### Rappresentazione grafica: scatter plot e difference plot

Strumento fondamentale è la rappresentazione grafica:

- **Diagramma di dispersione (scatter plot)**: candidata (Y) vs comparativa (X). Forma a "cilindro" se la deviazione standard (DS) è costante nell'intervallo, a "cono" se è costante il coefficiente di variazione (CV).
- **Diagramma delle differenze (difference plot / Bland-Altman)**: 4 combinazioni possibili in base ad asse orizzontale (comparativa o media) e asse verticale (differenza assoluta o relativa) — vedi Tabella 3 del documento.
- **Mountain plot** (Krouwer & Monti, secondo CLSI EP21): rappresentazione dei percentili delle differenze, utile per la parte centrale (95%) dei dati e per confrontare distribuzioni diverse, da non confondere con un istogramma tradizionale.

### Stima e accettabilità del bias

- **Diagramma delle differenze**: per il laboratorio (≥40 campioni) è sufficiente; con DS costante la media delle differenze stima il bias, con CV costante si usa la media delle differenze relative percentuali (o la mediana, se distribuzione asimmetrica).
- **Regressione**: obbligatoria per il produttore, facoltativa (ma raccomandata) per il laboratorio:
  - **Regressione lineare ordinaria (ORL)**: valida solo se DS costante, distribuzione omogenea e r² ≥ 0,95 (nota: r² alto NON implica concordanza, solo che l'ORL è ammissibile).
  - **Regressione di Deming**: per "measurement error models" dove entrambe le variabili hanno errore; versione "weighted" per CV costante.
  - **Regressione di Passing-Bablok**: non parametrica, richiede numerosità maggiori (>100 produttore, >40 laboratorio).
- **Intervallo di confidenza (IC) del bias**: per ORL, calcolo diretto dagli errori standard; per altri modelli, tecniche iterative (jackknife per Deming, bootstrap per Passing-Bablok).
- **Outlier**: identificati con il metodo ESD (extreme Studentized deviate) di CLSI EP09-A3 Appendice B.

### Interpretazione (Figura 1 / 5 scenari A-E)

Confrontando il bias stimato e il suo IC 95% con i limiti di bias accettabile predefiniti:

- **A**: IC 95% include lo zero → bias non statisticamente significativo.
- **B**: IC 95% entro i limiti accettabili → bias accettabile con confidenza 95%.
- **C**: bias stimato entro i limiti ma IC esce → conclusione possibile ma con confidenza inferiore.
- **D**: bias stimato fuori dai limiti ma IC li include → conclusione di accettabilità ancora possibile, ma con confidenza bassa.
- **E**: sia bias che IC fuori dai limiti → procedura candidata **non accettabile**.

Se il confronto rivela un bias rilevante, può essere necessario aggiustare gli **intervalli di riferimento** (CLSI EP28) — ma non i **limiti decisionali**, stabiliti da studi clinici e non modificabili.

### Criteri di accettabilità del bias

Diverse fonti possibili, ciascuna con limiti:
- **Variabilità biologica (CVI)**: criterio "oggettivo" più diffuso — bias accettabile tipicamente < 0,33 × CVI.
- **Raccomandazioni di esperti** (es. National Cholesterol Education Program: bias ≤3% per colesterolo totale tra metodi) — senza basi statistiche/biologiche solide.
- **Obiettivi analitici di enti regolatori/accreditamento**: combinano dati interlaboratorio, indicazioni dei produttori e opinioni di esperti.
- **Programmi di valutazione esterna della qualità (VEQ/PT)**: utili ma soggetti a effetti matrice.

### EP31: confronto multiplo con piccoli campioni — il "test del range"

Per confronti tra fino a 10 metodi/strumenti con piccole numerosità, EP31 propone il **test del range (intervallo di variazione)**: w = X_max - X_min tra le medie dei gruppi. Le tabelle dell'Appendice B (B1 per 2 metodi, fino a B9 per 10 metodi) forniscono, in base ai rapporti CD/ST (differenza critica/scarto tipo totale) e SR/ST (scarto tipo nella serie/totale), il numero di replicati necessari e il limite di rifiuto del range (moltiplicatore di CD), con relative potenze statistiche (target ≥0,80).

SR e ST si ottengono dai dati di CQI; se necessario, l'imprecisione va stimata con CLSI EP05 (20 giornate) — lo schema semplificato EP15 (3 replicati × 5 giorni) non è ritenuto adeguato per questo scopo.

### Commutabilità (CLSI EP30)

La **commutabilità** è l'equivalenza della relazione matematica tra i risultati di un materiale (es. controllo, calibratore) e quelli di campioni reali di pazienti, tra metodi diversi. Va sempre verificata per i materiali diversi dai campioni freschi: materiali di controllo, controlli del produttore e campioni da programmi interlaboratorio comportano rischi e vanno evitati quando possibile; **calibratori e materiali di verifica della linearità sono da escludere categoricamente** dal confronto di metodi. La verifica si basa su regressione (ORL, Deming o Passing-Bablock) con intervalli predittivi al 95%.

### Conclusioni del documento

Il confronto di metodi è uno dei principali impegni gestionali del laboratorio medico, che richiede notevoli **risorse umane e culturali**. Per il produttore è una vera **validazione** (molti campioni, statistica complessa); per il laboratorio è una **verifica** (meno campioni, analisi più semplificate). La rappresentazione grafica resta fondamentale, e l'interpretazione deve sempre basarsi su criteri di performance definiti **in anticipo**.

## Perché conta

Questo documento è il riferimento metodologico-statistico più dettagliato della wiki sul **confronto di procedure analitiche**, requisito esplicito di ISO 15189 §5.6.4 e di ISO 22870 §5.6.8 (POCT). Fornisce gli strumenti operativi concreti (scatter plot, Bland-Altman, mountain plot, regressioni di Deming/Passing-Bablock, test del range EP31, commutabilità EP30) che completano, sul piano statistico, il quadro più generale già presente in **[[Validazione e Verifica dei Metodi Analitici]]** e in **[[Incertezza di Misura]]**.

## Collegamenti

- **[[Confronto di Procedure e Verifica di Confrontabilità (CLSI EP09/EP31)]]** — nuovo concept dedicato che approfondisce gli strumenti statistici descritti in questo documento.
- **[[Validazione e Verifica dei Metodi Analitici]]** — distinzione validazione (produttore) / verifica (laboratorio) ripresa e dettagliata qui sul piano statistico.
- **[[ISO 15189]]** — requisito normativo (§5.6.4) che motiva l'intero documento.
- **[[Incertezza di Misura]]** — concetti di precisione/esattezza e regressioni con intervalli predittivi si collegano alla stima dell'incertezza.
