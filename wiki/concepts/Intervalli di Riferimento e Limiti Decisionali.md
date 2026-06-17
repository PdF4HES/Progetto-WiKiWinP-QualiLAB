---
type: concept
title: "Intervalli di Riferimento e Limiti Decisionali"
created: 2026-06-12
updated: 2026-06-13
tags:
  - corso-15189-2024
  - laboratorio-medico
  - concept
  - intervalli-di-riferimento
  - relazioni-con-pazienti
status: developing
address: c-000028
complexity: intermediate
domain: laboratorio-medico
aliases:
  - "Intervalli Biologici di Riferimento"
  - "Reference Intervals"
  - "Clinical Decision Limits"
  - "Limiti Decisionali Clinici"
related:
  - "[[ISO 15189]]"
  - "[[Valori Critici]]"
  - "[[SIPMeL]]"
  - "[[Monitoraggio di Laboratorio degli Anticoagulanti Orali Diretti (DOAC)]]"
  - "[[Corso UNI EN ISO 15189_2024 edXV - Novità Edizione 2024 e Note Operative ACCREDIA RT-35]]"
sources:
  - "[[SIPMeL M2 - Relazioni con Pazienti e Medici, Intervalli di Riferimento]]"
  - "[[SIPMeL - 99° Percentili hs-cTn Specifici per Etnia ed Età - Parte I]]"
  - "[[SIPMeL - 99° Percentili hs-cTn Specifici per Sesso - Parte II]]"
---

## Definizione

Gli **intervalli biologici di riferimento (IR)** sono gli intervalli di valori tipicamente osservati in una popolazione di soggetti **sani** (o privi della condizione indagata) per un dato esame di laboratorio, utilizzati per dare un contesto descrittivo al risultato di un paziente. I **limiti decisionali clinici (LD)** sono invece **soglie** definite per orientare una decisione diagnostica o terapeutica (es. diagnosticare una patologia, classificare un rischio, decidere una terapia), e sono collegati a prestazioni cliniche misurabili come sensibilità, specificità e valori predittivi.

Una distinzione concettuale importante, sottolineata da **[[SIPMeL]]**: gli IR hanno funzione **descrittiva** (riflettono il comportamento di soggetti sani, non le patologie), mentre i LD hanno funzione **inferenziale/diagnostica**. I limiti di riferimento non sono adatti a valutare le prestazioni cliniche di un esame, compito che spetta ai LD.

## Requisito ISO 15189 (7.3.5)

**[[ISO 15189]]**, al punto 7.3.5, richiede che il laboratorio - quando IR e/o LD sono necessari per interpretare i risultati - li **definisca, li faccia riflettere la popolazione di pazienti effettivamente servita (tenendo conto del rischio per il paziente), li comunichi agli utenti (medici e pazienti) e li riveda periodicamente**. Gli intervalli si applicano anche a esami con risultati qualitativi/nominali (es. genetica, virologia), non solo quantitativi. I valori proposti dai fabbricanti dei dispositivi/reagenti devono essere **verificati** dal laboratorio prima dell'uso, e accettati solo se la popolazione su cui sono stati derivati è nota e ritenuta comparabile. Ogni cambiamento di metodo o di modalità di prelievo che possa impattare su IR/LD va valutato e, se necessario, comunicato agli utenti.

## Approccio SIPMeL (documento M2)

Il documento **[[SIPMeL M2 - Relazioni con Pazienti e Medici, Intervalli di Riferimento]]** fornisce indicazioni operative basate sulle guide aggiornate **CLSI EP44** (costruzione di nuovi IR) ed **EP45** (verifica e trasferimento di IR esistenti, tramite studi su piccola scala n=20, su larga scala n=~60, confronto di metodo, o metodi "indiretti" basati su dati storici di laboratorio). SIPMeL raccomanda un approccio proporzionato alle dimensioni e caratteristiche del laboratorio, privilegiando - dove appropriato - i metodi indiretti per finalità descrittive, e sottolinea che la produzione di LD richiede invece studi orientati alle prestazioni cliniche (sensibilità, specificità, valori predittivi), non semplicemente la statistica descrittiva degli IR.

## Caso di studio: il 99° percentile di hs-cTn

Un caso particolare e molto discusso di LDC è il **99° percentile della troponina ad alta sensibilità (hs-cTn)**, che funge contemporaneamente da intervallo di riferimento e da soglia diagnostica per il danno miocardico (vedi **[[99° Percentile e Valori Decisionali in hs-cTn]]**). Il dibattito su quanto questo valore debba essere specifico per sesso, età o etnia — affrontato dal **[[Gruppo di Studio sui Marcatori Miocardici (GdS MM) SIPMeL]]** in **[[SIPMeL - 99° Percentili hs-cTn Specifici per Etnia ed Età - Parte I]]** e **[[SIPMeL - 99° Percentili hs-cTn Specifici per Sesso - Parte II]]** — illustra concretamente le difficoltà pratiche nel definire "la popolazione di riferimento effettivamente servita" richiesta da ISO 15189 §7.3.5.

## Intervalli di riferimento qualitativi e metodi indiretti

ISO 15189 §7.3.5 lettera d) prevede esplicitamente anche **intervalli di riferimento qualitativi** per test genetici (es. presenza/assenza di varianti patogenetiche BRCA1/BRCA2). Quando il reclutamento diretto di soggetti sani non è praticabile, sono utilizzabili **metodi indiretti** basati su dati storici di laboratorio (Hoffmann/Bhattacharya, Kolmogorov-Smirnov "kosmic", refineR). Il framework **IFCC C-RIDL** distingue formalmente intervalli di riferimento (IR) da limiti decisionali clinici (LDC), e l'**EFLM Biological Variation Database** supporta il calcolo di intervalli di riferimento personalizzati (prRI = HSP ± TVset). Dettagli in **[[Corso UNI EN ISO 15189_2024 edXV - Novità Edizione 2024 e Note Operative ACCREDIA RT-35]]**, §6.

## Collegamento con i Valori Critici

I **[[Valori Critici]]** rappresentano un caso particolare e estremo di limite decisionale clinico: soglie che, se superate, segnalano un rischio immediato per la vita del paziente e attivano un processo di comunicazione urgente. Mentre gli IR/LD "ordinari" servono all'interpretazione clinica generale del referto, le soglie critiche sono LD con priorità massima, gestiti con processi dedicati (allarmi, verifica tecnica, comunicazione tracciata) distinti dal flusso ordinario di refertazione.
