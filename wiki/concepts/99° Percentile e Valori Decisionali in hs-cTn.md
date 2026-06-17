---
type: concept
title: "99° Percentile e Valori Decisionali in hs-cTn"
created: 2026-06-12
updated: 2026-06-12
tags:
  - laboratorio-medico
  - concept
  - troponina
  - cardiologia
  - hs-ctn
  - intervalli-di-riferimento
status: developing
address: c-000065
complexity: advanced
domain: laboratorio-medico
aliases:
  - "99th Percentile URL"
  - "Upper Reference Limit hs-cTn"
  - "99° Percentile hs-cTn"
related:
  - "[[SIPMeL]]"
  - "[[Gruppo di Studio sui Marcatori Miocardici (GdS MM) SIPMeL]]"
  - "[[Troponina Cardiaca ad Alta Sensibilità (hs-cTn)]]"
  - "[[Intervalli di Riferimento e Limiti Decisionali]]"
  - "[[Incertezza di Misura]]"
  - "[[Validazione e Verifica dei Metodi Analitici]]"
  - "[[Controllo di Qualità Interno (CQI)]]"
  - "[[ISO 15189]]"
sources:
  - "[[SIPMeL - 99° Percentili hs-cTn Specifici per Etnia ed Età - Parte I]]"
  - "[[SIPMeL - 99° Percentili hs-cTn Specifici per Sesso - Parte II]]"
---

## Cosa è

Il **99° percentile** della distribuzione di concentrazione della **[[Troponina Cardiaca ad Alta Sensibilità (hs-cTn)]]** in una popolazione di riferimento "sana" rappresenta, nelle convenzioni cliniche internazionali a partire dalla "Ridefinizione dell'infarto del miocardio" del 2000, il **limite superiore di riferimento (URL, upper reference limit)** che funge contemporaneamente da **soglia diagnostica (cutoff)** per il danno miocardico nell'ambito della sindrome coronarica acuta (SCA/IMA/NSTEMI). È una particolarità della troponina rispetto alla maggior parte degli altri analiti di laboratorio, per i quali il limite di riferimento convenzionale è il 97,5° percentile e non ha valenza diagnostica diretta: per la hs-cTn, invece, il 99° percentile è insieme un **intervallo di riferimento (IR)** descrittivo e un **limite decisionale clinico (LDC)** — vedi **[[Intervalli di Riferimento e Limiti Decisionali]]**.

## Criteri analitici (definizione di Apple 2009)

Un metodo è classificato "ad alta sensibilità" se soddisfa due criteri al 99° percentile: un coefficiente di variazione **≤10% (CV10%)**, calcolato separatamente su popolazione maschile e femminile, e la capacità di misurare valori superiori al limite di rilevazione (LoD) in **oltre il 50%** dei soggetti sani di riferimento. Poiché la soglia diagnostica si colloca molto vicino al limite analitico inferiore del metodo, anche piccole variazioni nella popolazione di riferimento o nella metodologia statistica possono spostare significativamente il 99° percentile riportato.

## Il dibattito: cutoff universale o specifico per popolazione?

Il 99° percentile di hs-cTn è **metodo-dipendente** (mancanza di armonizzazione/standardizzazione tra produttori) e, all'interno dello stesso metodo, **dipendente dalla popolazione di riferimento** usata per derivarlo (dimensione campionaria, età, sesso, etnia, criteri di esclusione, gestione degli outlier). Da qui il dibattito, ripreso dalle Raccomandazioni IFCC 2022, su quanto sia necessario o opportuno adottare **99° percentili differenziati per sesso, età ed etnia**:

- **Sesso**: i valori sani sono universalmente 1,2-2,4 volte più alti negli uomini; la Quarta Definizione Universale di IMA (2018) e IFCC (2018) ne suggeriscono l'uso, ESC e AHA/ACC non lo raccomandano. Le revisioni sistematiche SIPMeL (vedi **[[SIPMeL - 99° Percentili hs-cTn Specifici per Sesso - Parte II]]**) trovano l'impatto clinico per lo più incerto o negativo.
- **Età**: i valori aumentano con l'età (raddoppio oltre 70-75 anni); molti studi su popolazioni sane raccomandano cutoff differenziati, ma negli studi su pazienti con sospetta SCA i cutoff età-specifici aumentano specificità a scapito della sensibilità, con rischio di sotto-diagnosi negli anziani.
- **Etnia**: dati limitati e confliggenti; nessuna Linea Guida prevede cutoff etnia-specifici (vedi **[[SIPMeL - 99° Percentili hs-cTn Specifici per Etnia ed Età - Parte I]]**).

Le Raccomandazioni IFCC 2022 (Recommendation 2 e 4) propongono criteri rigorosi per la derivazione dell'URL (coorte 50% maschi/50% femmine, 18-80 anni, tutti i gruppi etnici rilevanti, minimo 400+400 soggetti sani per sesso) — praticamente irrealizzabili per il singolo laboratorio, che nella pratica adotta i valori del produttore verificandone comparabilità con metodi semplificati.

## Implicazioni pratiche per il laboratorio

- **Quale popolazione di riferimento**: il laboratorio deve verificare (non necessariamente derivare ex novo) che il 99° percentile fornito dal produttore sia comparabile con la propria popolazione di pazienti, secondo il requisito **ISO 15189 §7.3.5** trattato in **[[Intervalli di Riferimento e Limiti Decisionali]]**.
- **Come refertare**: in assenza di Raccomandazioni consolidate per cutoff differenziati, l'approccio prevalente resta il **99° percentile unico** fornito dal metodo, con eventuale segnalazione qualitativa di età/sesso del paziente per supportare l'interpretazione clinica, ma senza soglie numeriche distinte in automatico.
- **Comunicazione ai clinici**: è essenziale che i clinici comprendano che il 99° percentile è un cutoff **metodo-specifico**, non trasferibile tra strumenti/produttori diversi, e che la sua interpretazione va sempre integrata con la **variazione seriale (rise & fall)** e con la stima dell'**[[Incertezza di Misura]]**, particolarmente rilevante in prossimità della soglia decisionale.
- **Stato dell'arte SIPMeL**: il GdS-MM SIPMeL, dopo revisione sistematica della letteratura, non ritiene al momento le evidenze sufficienti per raccomandare cutoff specifici per sesso, età o etnia, lasciando aperta la questione in attesa di studi futuri (es. trial CODE-MI).
