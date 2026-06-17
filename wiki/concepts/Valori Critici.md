---
type: concept
title: "Valori Critici"
created: 2026-06-12
updated: 2026-06-12
tags:
  - laboratorio-medico
  - concept
  - valori-critici
  - sicurezza-paziente
status: developing
address: c-000020
complexity: intermediate
domain: laboratorio-medico
aliases:
  - "Valori di Panico"
  - "Critical Values"
  - "Panic Values"
related:
  - "[[ISO 15189]]"
  - "[[Sistema di Gestione per la Qualità]]"
  - "[[Valutazione Esterna di Qualità (VEQ)]]"
  - "[[Audit Interno e Visita Ispettiva]]"
sources:
  - "[[SOP Controllo Valori Critici]]"
  - "[[SOP Tabella Valori Critici (Esempio)]]"
  - "[[Procedura Operativa Standard ISO 15189 (SOP Master)]]"
---

## Definizione

I **valori critici** (o "di panico", *critical/panic values*) sono risultati di esami di laboratorio che indicano una condizione clinica con **rischio immediato per la vita del paziente** e che richiedono una **comunicazione urgente e tracciata** al medico curante o al reparto di degenza, indipendentemente dal normale flusso di refertazione. Esempi tipici: potassio fortemente alterato, glicemia gravemente bassa o alta, emoglobina molto bassa, INR molto elevato, positività di un'emocoltura.

## Perché contano

Un valore critico non comunicato in tempo può tradursi in un evento avverso grave (es. arresto cardiaco da iperkaliemia, coma ipoglicemico). La gestione dei valori critici è quindi uno dei punti in cui il laboratorio ha un impatto **diretto e immediato** sulla sicurezza del paziente, a differenza della maggior parte dei risultati che seguono il referto ordinario.

## Requisito ISO 15189

**[[ISO 15189]]** (§7.4.2, "Segnalazione dei risultati") richiede che il laboratorio abbia una procedura documentata per identificare, segnalare e tracciare i valori critici, con tempi di comunicazione definiti. Questo è uno dei pochi requisiti di processo con un'esplicita componente di **urgenza temporale**, ed è verificato sia in fase di audit interno sia durante la visita ispettiva ACCREDIA (vedi **[[Audit Interno e Visita Ispettiva]]**).

## Il processo del laboratorio

Secondo la **[[SOP Controllo Valori Critici]]** (SOP-GEN-008), il flusso prevede:
1. **Allarme automatico sul LIS** quando un risultato supera le soglie definite nell'Allegato A (vedi **[[SOP Tabella Valori Critici (Esempio)]]** per soglie indicative per analita: es. K+ < 2.8 o > 6.2 mmol/L, Hb < 6.5 g/dL, INR > 5.0, qualsiasi emocoltura positiva).
2. **Verifica tecnica** da parte del TSLB (esclusione di interferenze pre-analitiche, controllo CQI, eventuale ripetizione).
3. **Validazione clinica** del biologo/medico (Delta Check rispetto allo storico del paziente).
4. **Comunicazione d'urgenza entro 15 minuti**, con tecnica del **Read-Back** per evitare errori di trascrizione.
5. **Registrazione** su modulo digitale (MOD-QUAL-012) come evidenza per gli audit.

## Collegamento con la VEQ

La capacità del laboratorio di generare risultati corretti vicino alle soglie critiche dipende dalla qualità analitica monitorata tramite la **[[Valutazione Esterna di Qualità (VEQ)]]**: un controllo VEQ fuori target su un analita con soglie critiche (es. potassio, glucosio) può segnalare un rischio di falsi allarmi o, peggio, di mancate segnalazioni — chiudendo il ciclo tra qualità analitica e sicurezza clinica.
