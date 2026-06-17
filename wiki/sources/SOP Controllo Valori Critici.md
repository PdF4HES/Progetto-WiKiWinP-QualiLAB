---
type: source
title: "SOP Controllo Valori Critici"
created: 2026-06-12
updated: 2026-06-12
tags:
  - laboratorio-medico
  - source
  - normativa
  - valori-critici
status: developing
address: c-000017
source_type: internal-document
author: ""
date_published: 2026-06-12
url: ""
confidence: high
key_claims:
  - "SOP-GEN-008 'Procedura per la gestione e comunicazione dei valori critici', Rev. 01 del 12/06/2026, ha lo scopo di identificare, validare e comunicare al medico curante i risultati che indicano un rischio immediato per la vita del paziente, garantendo tracciabilità totale."
  - "Si applica a tutti i campioni biologici processati e a tutto il personale tecnico, biologico e medico coinvolto nella validazione."
  - "Identifica due rischi clinici principali: mancata segnalazione del valore critico da parte dell'analizzatore (mitigata da blocco automatico e allarme non bypassabile sul LIS) ed errato destinatario della comunicazione (mitigata dall'obbligo di Read-Back)."
  - "Il flusso operativo prevede: identificazione/verifica tecnica del dato (TSLB), validazione clinica con Delta Check (Validatore biologo/medico), e comunicazione d'urgenza entro 15 minuti dalla validazione."
  - "La comunicazione segue una procedura di Read-Back obbligatoria: il Validatore si identifica, registra le generalità del ricevente e fa ripetere ad alta voce nome paziente e valore comunicato."
  - "Ogni comunicazione viene registrata sul LIS nel modulo digitale MOD-QUAL-012 con data/ora, identità del ricevente, esito del Read-Back e note cliniche."
  - "Cita come riferimenti UNI EN ISO 15189:2024 §7.4.2 (Segnalazione dei risultati), il Regolamento Tecnico ACCREDIA RT-35 e le Linee Guida SIBioC-SIPMeL sull'armonizzazione dei valori critici."
related:
  - "[[Valori Critici]]"
  - "[[ISO 15189]]"
  - "[[Procedura Operativa Standard ISO 15189 (SOP Master)]]"
  - "[[SOP Tabella Valori Critici (Esempio)]]"
  - "[[ACCREDIA]]"
  - "[[SIPMeL]]"
sources:
  - "[[.raw/Procedura Operativa Standard ISO 15189 - Controllo dei Valori Critici.docx]]"
---

## Cosa è

**SOP-GEN-008** è la procedura operativa del laboratorio dedicata alla **gestione e comunicazione dei valori critici** (valori "di panico"), redatta seguendo lo schema dell'header documentale e delle sezioni descritte nel **[[Procedura Operativa Standard ISO 15189 (SOP Master)]]**. È firmata da TSLB (redazione), Responsabile Qualità (verifica) e Direttore di Laboratorio (approvazione), con data di entrata in vigore 12/06/2026.

## Contenuto principale

La procedura assegna ruoli precisi: il **TSLB** identifica l'allarme generato dal LIS e ne verifica la plausibilità tecnica (assenza di emolisi, lipemia, coaguli; controllo dei CQI della seduta; eventuale ripetizione in duplicato). Il **Validatore** (biologo o medico) effettua la valutazione clinica confrontando il dato con la storia del paziente (Delta Check), firma elettronicamente e da quel momento ha **15 minuti** per completare la comunicazione d'urgenza.

La comunicazione distingue **pazienti ricoverati** (contatto con la medicheria di reparto) da **pazienti esterni/territoriali** (Medico di Medicina Generale, oppure invio diretto al Pronto Soccorso se irreperibile). In entrambi i casi è obbligatoria la tecnica del **Read-Back**: il Validatore si identifica, raccoglie le generalità dell'interlocutore, comunica i dati e richiede la ripetizione a voce di nome paziente e valore per escludere errori di trascrizione.

Tutto viene registrato sul LIS tramite il modulo **MOD-QUAL-012** (registro elettronico delle comunicazioni), che include data/ora, identità e qualifica del ricevente, esito del Read-Back (positivo/negativo) e eventuali note cliniche.

## Collegamento con ISO 15189 e l'accreditamento

La procedura cita esplicitamente **UNI EN ISO 15189:2024 §7.4.2** (segnalazione dei risultati), il **Regolamento Tecnico ACCREDIA RT-35** e le linee guida SIBioC-SIPMeL, collegando questo documento operativo sia a **[[ISO 15189]]** sia all'ecosistema **[[ACCREDIA]]** / **[[SIPMeL]]**. Le soglie operative richiamate (Allegato A) sono dettagliate nella **[[SOP Tabella Valori Critici (Esempio)]]**, e il concetto generale è approfondito in **[[Valori Critici]]**.
