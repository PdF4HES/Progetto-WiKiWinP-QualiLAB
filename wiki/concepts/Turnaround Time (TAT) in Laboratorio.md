---
type: concept
title: "Turnaround Time (TAT) in Laboratorio"
created: 2026-06-12
updated: 2026-06-12
tags:
  - laboratorio-medico
  - concept
  - tat
  - qualita
  - troponina
status: developing
address: c-000060
complexity: intermediate
domain: laboratorio-medico
aliases:
  - "TAT"
  - "Turnaround Time"
  - "Tempo di Risposta del Laboratorio"
related:
  - "[[SIPMeL]]"
  - "[[Gruppo di Studio sui Marcatori Miocardici (GdS MM) SIPMeL]]"
  - "[[Troponina Cardiaca ad Alta Sensibilità (hs-cTn)]]"
  - "[[Sistema Informativo di Laboratorio (LIS)]]"
  - "[[ISO 15189]]"
  - "[[Point-of-Care Testing (POCT)]]"
  - "[[Fase Preanalitica]]"
sources:
  - "[[SIPMeL - Tempo di Risposta (TAT) per Troponina]]"
  - "[[SIPMeL - Tempo di Risposta (TAT) per Troponina - Aggiornamento 2024]]"
---

## Cosa è

Il **turnaround time (TAT)**, o tempo di risposta del laboratorio, è l'intervallo di tempo che intercorre tra due momenti del processo di esame di laboratorio — tipicamente dal **prelievo del campione** (o, in alcune definizioni, dalla richiesta dell'esame o dalla ricezione del campione in laboratorio) alla **disponibilità/consegna del risultato** al richiedente. È uno dei parametri più direttamente percepiti dai clinici come misura della qualità del servizio di laboratorio, perché incide sulla rapidità delle decisioni diagnostico-terapeutiche.

La definizione esatta del TAT non è univoca: la letteratura distingue tra *sampling-to-report* (dal prelievo alla risposta, preferita dai laboratoristi), *order-to-report* o *receipt-to-report*, e il concetto clinico più ampio di *therapeutic turnaround time (TTAT)*, dall'accesso del paziente al trattamento. Questa ambiguità è discussa a fondo nelle raccomandazioni SIPMeL sulla troponina (vedi sotto), che propendono per la definizione *sampling-to-report* come la più rilevante clinicamente.

## Perché è critico per i marcatori cardiaci

Il caso prototipico in cui il TAT assume importanza clinica diretta è la **[[Troponina Cardiaca ad Alta Sensibilità (hs-cTn)]]** nella diagnosi delle sindromi coronariche acute (SCA/NSTEMI). Gli algoritmi diagnostici rapidi raccomandati dalle linee guida europee (ESC) — protocolli **0/1h**, **0/2h**, **0/3h** e valutazione del singolo valore a tempo zero (**T0**) — si basano sulla disponibilità **molto rapida** del risultato di hs-cTn per permettere il *rule-in/rule-out* dell'infarto miocardico entro 1-3 ore dall'arrivo del paziente in Pronto Soccorso.

Le Raccomandazioni del **[[Gruppo di Studio sui Marcatori Miocardici (GdS MM) SIPMeL]]** (2018, confermate e rafforzate nel 2024 — vedi **[[SIPMeL - Tempo di Risposta (TAT) per Troponina]]** e **[[SIPMeL - Tempo di Risposta (TAT) per Troponina - Aggiornamento 2024]]**) fissano per la cTn un TAT **massimo di 60 minuti e ottimale di 30 minuti** dal prelievo alla consegna del risultato — un target da concordare comunque con i clinici, oggi sostenuto da un livello di evidenza A. Se il TAT del laboratorio centrale non rispetta questa soglia, le linee guida cliniche suggeriscono il ricorso al **[[Point-of-Care Testing (POCT)]]**, pur con i suoi limiti di sensibilità analitica rispetto ai metodi di laboratorio centrale.

## TAT come indicatore di qualità

Il monitoraggio sistematico del TAT — in particolare per gli esami urgenti/critici come la cTn — rientra tra gli **indicatori di qualità** che un laboratorio medico deve definire, misurare e riesaminare periodicamente nell'ambito del proprio sistema di gestione per la qualità secondo **[[ISO 15189]]**. La misurazione richiede strumenti automatici di tracciamento dei tempi lungo tutto il percorso analitico (dal prelievo alla validazione e refertazione), tipicamente implementati attraverso il **[[Sistema Informativo di Laboratorio (LIS)]]**, che registra i timestamp di ogni fase (accettazione, esecuzione, validazione, refertazione) e permette il calcolo di mediane, percentili (es. 90° percentile) e outlier rispetto agli obiettivi fissati.

## Fattori che influenzano il TAT e strategie di miglioramento

Il TAT totale è la somma di componenti **pre-analitiche** (prelievo, trasporto, accettazione — vedi **[[Fase Preanalitica]]**), **analitiche** (esecuzione strumentale) e **post-analitiche** (validazione, refertazione, comunicazione al clinico). Sebbene la fase pre-analitica sia tradizionalmente considerata la più critica, la letteratura recente ne discute il peso effettivo rispetto alle altre fasi.

Le strategie di miglioramento documentate includono: l'implementazione del **[[Point-of-Care Testing (POCT)]]** in Pronto Soccorso, l'automazione totale di laboratorio (Total Laboratory Automation, TLA), metodologie di qualità totale come **Lean/Six Sigma** e **root cause analysis**, ottimizzazione informatica (LIS, sistemi di order entry, alert automatici ai clinici) e riorganizzazione multidisciplinare dei processi. La scelta tra rafforzamento del laboratorio centrale (TLA) e decentramento (POCT) dipende dai vincoli organizzativi specifici di ciascuna struttura, ma in entrambi i casi richiede un monitoraggio continuo del TAT e audit periodici dell'intera filiera operativa.
