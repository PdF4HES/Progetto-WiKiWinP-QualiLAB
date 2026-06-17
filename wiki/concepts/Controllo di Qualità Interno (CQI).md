---
type: concept
title: "Controllo di Qualità Interno (CQI)"
created: 2026-06-12
updated: 2026-06-13
tags:
  - laboratorio-medico
  - concept
  - cqi
  - controllo-qualita
status: seed
address: c-000046
aliases:
  - "CQI"
  - "Internal Quality Control"
  - "IQC"
  - "Controllo Interno di Qualità"
related:
  - "[[ISO 15189]]"
  - "[[Validazione e Verifica dei Metodi Analitici]]"
  - "[[Incertezza di Misura]]"
  - "[[Valutazione Esterna di Qualità (VEQ)]]"
  - "[[SIPMeL Q19 - Processi di Esame e Validità dei Risultati]]"
  - "[[SIPMeL - Monitoraggio Validità dei Risultati degli Esami]]"
  - "[[Troponina Cardiaca ad Alta Sensibilità (hs-cTn)]]"
  - "[[Corso UNI EN ISO 15189_2024 edXV - Novità Edizione 2024 e Note Operative ACCREDIA RT-35]]"
sources:
  - "[[SIPMeL - Monitoraggio Validità dei Risultati degli Esami]]"
  - "[[SIPMeL Q19 - Processi di Esame e Validità dei Risultati]]"
---

## Cosa è

Il **Controllo di Qualità Interno (CQI)**, in inglese **Internal Quality Control (IQC)**, è l'insieme delle procedure con cui il laboratorio analizza periodicamente **materiali di controllo a valore noto o stabilito** (diversi dai campioni dei pazienti) sui propri sistemi analitici, per verificare che il processo di misura rimanga entro limiti di accettabilità predefiniti. A differenza della **[[Valutazione Esterna di Qualità (VEQ)]]**, che fornisce un confronto periodico e retrospettivo con altri laboratori, il CQI è un'attività **quotidiana e continua**, eseguita internamente, che permette di rilevare tempestivamente derive (drift), perdita di precisione o errori sistematici prima che impattino sui risultati dei pazienti.

## Materiali, frequenza e regole statistiche

Per **ISO 15189**, la frequenza del CQI deve basarsi sulla stabilità e solidità del metodo e sul rischio di danno al paziente; i dati devono essere registrati in modo da permettere l'individuazione di tendenze e variazioni, e rivisti a intervalli regolari con criteri di accettabilità definiti. La norma non scende in dettagli operativi: per questo **CLSI C24** (statistica del CQI per misure quantitative) e **ISO 15198** (compiti del fabbricante IVD nella validazione del CQI) costituiscono i riferimenti principali, come evidenziato dalle Raccomandazioni **[[SIPMeL - Monitoraggio Validità dei Risultati degli Esami|SIPMeL Q19]]**.

Gli strumenti classici per l'interpretazione dei dati di CQI sono le **carte di Levey-Jennings** (rappresentazione grafica dei valori di controllo rispetto a media e deviazione standard) e le **regole di Westgard** (regole multi-livello, es. 1₃s, 2₂s, R₄s, per discriminare tra errori casuali e sistematici e decidere se accettare o respingere una seduta analitica). CLSI C24 introduce inoltre la **metrica Sigma** (rapporto tra variabilità accettabile e imprecisione della misura), utile per dimensionare il numero di regole e la frequenza dei controlli in base alla qualità intrinseca del metodo, e distingue schemi **a lotti** (es. micropiastre o sequenze predefinite) da schemi **continui**.

I materiali di controllo possono provenire dal fabbricante del sistema IVD, da terze parti (preferibili per indipendenza), oppure essere preparati internamente (campioni di pazienti aggregati, calibratori di lotto diverso). Quando il materiale di controllo non è disponibile, ISO 15189 ammette alternative come la **media mobile** sui risultati dei pazienti, il confronto con metodi a stessa taratura (**ISO 17511**) o la ripetizione di esami su campioni conservati.

## Collegamento con incertezza di misura e monitoraggio

Dalla pubblicazione di **ISO/TS 20914**, il CQI ha assunto un ruolo duplice: oltre al monitoraggio quotidiano della validità dei risultati, fornisce la base sperimentale per la stima dell'**[[Incertezza di Misura]]**, separando concettualmente l'incertezza strumentale (derivata dai dati di CQI a lungo termine) da quella introdotta dai processi pre- e post-esame. Questo collegamento rende il CQI un elemento trasversale tra il monitoraggio operativo della clausola 7.3.7 di ISO 15189 e le attività di **[[Validazione e Verifica dei Metodi Analitici]]**, dove i dati storici di CQI sono spesso impiegati anche per le verifiche periodiche di precisione e per la sorveglianza della comparabilità tra strumenti diversi.

## Rilevanza per l'accreditamento

La documentazione del CQI (carte di controllo, regole applicate, gestione delle non conformità a fronte di violazioni delle regole, azioni correttive) è un elemento centrale delle verifiche ispettive **ACCREDIA** secondo **[[ISO 15189]]**, e costituisce evidenza oggettiva — insieme alla **[[Valutazione Esterna di Qualità (VEQ)]]** — del monitoraggio continuo della validità dei risultati richiesto dalla norma.

## Esempi pratici di stima dell'incertezza basata sul CQI (ISO/TS 20914)

La guida **ISO/TS 20914:2019** fornisce esempi numerici svolti che illustrano in pratica il collegamento CQI → incertezza di misura descritto sopra: sodio, anion gap, calcolo dell'osmolalità, rapporto Ca/Crea urinario, HBsAg. Dettagli ed elenco completo dei riferimenti tecnici (VIM 3.19 nota 7, ISO 20397-2 per NGS, ecc.) in **[[Corso UNI EN ISO 15189_2024 edXV - Novità Edizione 2024 e Note Operative ACCREDIA RT-35]]**, §5.
