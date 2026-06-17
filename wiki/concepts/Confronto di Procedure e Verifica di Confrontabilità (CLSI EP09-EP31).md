---
type: concept
title: "Confronto di Procedure e Verifica di Confrontabilità (CLSI EP09/EP31)"
created: 2026-06-13
updated: 2026-06-13
tags:
  - laboratorio-medico
  - concept
  - validazione-metodi
  - statistica
  - clsi
status: developing
address: c-000126
complexity: advanced
domain: laboratorio-medico
aliases:
  - "CLSI EP09-A3"
  - "CLSI EP31-A-IR"
  - "Method Comparison"
  - "Bland-Altman in Medicina di Laboratorio"
related:
  - "[[Validazione e Verifica dei Metodi Analitici]]"
  - "[[Incertezza di Misura]]"
  - "[[ISO 15189]]"
  - "[[Point-of-Care Testing (POCT)]]"
  - "[[SIPMeL - Inclusione POCT (ISO 22870) in ISO 15189]]"
  - "[[Gruppo di Studio Evidence Based Laboratory Medicine (GdS EBLM) SIPMeL]]"
sources:
  - "[[SIPMeL - Linee Guida per il Confronto di Procedure di Esami di Laboratorio (CLSI EP09-A3 ed EP31-A-IR)]]"
---

## Cosa è

Il **confronto di procedure di esame** (method comparison) è l'attività con cui un laboratorio medico o un produttore di sistemi diagnostici accerta la **comparabilità dei risultati** prodotti da due o più procedure di misura (metodi, strumenti, sedi, lotti di reagente). È un requisito esplicito di **[[ISO 15189]]** (punto 5.6.4, comparabilità dei risultati degli esami) e di ISO 22870 (punto 5.6.8, per il **[[Point-of-Care Testing (POCT)]]**). Le linee guida CLSI di riferimento sono:

- **EP09-A3**: confronto tra una procedura "candidata" (nuova) e una "comparativa" (esistente o di riferimento), per stimare lo **scarto sistematico (bias)**.
- **EP31-A-IR**: verifica della comparabilità tra fino a 10 strumenti/sedi all'interno della stessa struttura sanitaria (es. POCT vs laboratorio centrale).
- **EP30-A**: caratterizzazione della **commutabilità** dei materiali di riferimento.

## Validazione (produttore) vs Verifica (laboratorio)

Il documento SIPMeL distingue nettamente due ruoli, con requisiti molto diversi:

| Aspetto | Produttore (validazione) | Laboratorio (verifica) |
|---|---|---|
| Obiettivo | Caratterizzare l'esattezza/bias del metodo candidato | Verificare le dichiarazioni del produttore |
| Numerosità minima | ≥100 campioni | ≥40 campioni |
| Regressione | Obbligatoria (Deming, anche ponderata) | Facoltativa ma raccomandata |
| Analisi minima | Statistica della regressione | Diagramma delle differenze |
| Distribuzione | Diversi siti, 3-5 giorni ciascuno | Singolo sito |

Questa distinzione si collega direttamente a quella già discussa in **[[Validazione e Verifica dei Metodi Analitici]]**.

## Strumenti grafici

- **Scatter plot** (diagramma di dispersione): risultato candidato (Y) vs comparativo (X). La forma della nuvola di punti (cilindrica se DS costante, conica se CV costante) guida la scelta del modello di regressione.
- **Difference plot / Bland-Altman**: differenza tra metodi sull'asse Y, valore comparativo o media sull'asse X; può essere assoluta o relativa (4 combinazioni). È lo strumento **minimo richiesto per la verifica di laboratorio**.
- **Mountain plot** (Krouwer & Monti, CLSI EP21): percentili delle differenze, utile per evidenziare la parte centrale (95%) dei dati e confrontare distribuzioni.

## Modelli di regressione per il confronto di metodi

Poiché entrambe le variabili (candidata e comparativa) hanno errore di misura, la **regressione lineare ordinaria (ORL)** è teoricamente inadeguata (richiede X "senza errore"). Modelli alternativi:

- **Regressione di Deming**: minimizza la distanza ortogonale dei punti dalla retta (proiezione, non distanza verticale come ORL); è simmetrica rispetto allo scambio degli assi. Versione "weighted" (CV costante) per imprecisione proporzionale.
- **Regressione di Passing-Bablok**: non parametrica, robusta agli outlier, richiede numerosità maggiori (>100 produttore, >40 laboratorio).
- ORL resta ammissibile solo con DS costante, distribuzione omogenea e r² ≥ 0,95 — **r² alto non implica concordanza**, solo ammissibilità del modello.

Intervalli di confidenza: diretti per ORL; **jackknife** per Deming; **bootstrap** per Passing-Bablok.

## Interpretazione del bias: i 5 scenari (A-E)

L'accettabilità del bias si valuta confrontando la stima del bias e il suo IC 95% con limiti di accettabilità **predefiniti prima dello studio**:

- **A** — IC include lo zero: bias non significativo.
- **B** — IC entro i limiti: bias accettabile (confidenza 95%).
- **C** — bias entro i limiti, IC esce: possibile accettabilità, confidenza minore.
- **D** — bias fuori dai limiti, IC li include: possibile accettabilità, confidenza bassa.
- **E** — bias e IC entrambi fuori dai limiti: **non accettabile**.

Un bias rilevante può richiedere l'aggiustamento degli **intervalli di riferimento** (CLSI EP28), ma non dei **limiti decisionali clinici**, che sono fissi.

## Criteri di accettabilità del bias

In ordine di robustezza concettuale (ma anche di praticabilità):

1. **Variabilità biologica (CVI)**: bias accettabile tipicamente < 0,33 × CVI — criterio più "oggettivo" ma con limiti pratici.
2. **Raccomandazioni di esperti/società scientifiche** (es. ≤3% per colesterolo totale).
3. **Obiettivi analitici di enti regolatori/accreditamento** — riflettono lo stato dell'arte più che l'obiettivo clinico ideale.
4. **Programmi VEQ/PT** — soggetti a effetti matrice.

## EP31: il test del range per confronti multipli con piccoli campioni

Per confrontare fino a 10 metodi/strumenti/sedi con piccole numerosità (tipico dei confronti POCT vs laboratorio centrale), EP31 propone il **test del range**: w = X_max − X_min tra le medie dei gruppi confrontati. Le tabelle dell'Appendice B (B1-B9) forniscono, in funzione dei rapporti CD/ST (differenza critica/scarto tipo totale) e SR/ST (scarto entro serie/totale), il numero di replicati e il **limite di rifiuto** (moltiplicatore di CD), con potenza statistica target ≥0,80. SR e ST derivano dai dati di CQI, oppure da CLSI EP05 (20 giornate) se serve stimare l'imprecisione in intervalli non coperti dai controlli.

## Commutabilità (CLSI EP30)

La **commutabilità** è l'equivalenza della relazione matematica tra i risultati di un materiale e quelli di campioni di pazienti, tra metodi diversi. Va verificata per **ogni materiale diverso da campioni freschi di pazienti** (controlli, materiali interlaboratorio); diluizione, impoverimento o "spiking" dei campioni ne compromettono la commutabilità. **Calibratori e materiali di verifica della linearità sono esclusi a priori** dal confronto di metodi. La verifica si basa su regressione (ORL/Deming/Passing-Bablock) con intervalli predittivi al 95% (eventualmente semplificata secondo CLSI EP14).

## Perché conta

Questo concept fornisce gli **strumenti statistici operativi** per soddisfare il requisito ISO 15189 §5.6.4 sulla comparabilità dei risultati, completando il quadro più ampio di **[[Validazione e Verifica dei Metodi Analitici]]**. È particolarmente rilevante per i contesti **[[Point-of-Care Testing (POCT)]]**, dove il confronto periodico tra strumenti decentrati e laboratorio centrale (EP31) è una pratica corrente, e per qualsiasi cambio di metodo, lotto di reagenti o strumento di backup.
