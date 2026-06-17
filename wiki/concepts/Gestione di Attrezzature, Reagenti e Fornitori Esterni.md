---
type: concept
title: "Gestione di Attrezzature, Reagenti e Fornitori Esterni"
created: 2026-06-12
updated: 2026-06-13
tags:
  - laboratorio-medico
  - concept
  - attrezzature
  - reagenti
  - fornitori
status: developing
address: c-000040
complexity: intermediate
domain: laboratorio-medico
aliases:
  - "Gestione delle Apparecchiature"
  - "Equipment Lifecycle Management"
  - "Prodotti e Servizi Forniti dall'Esterno"
related:
  - "[[Validazione e Verifica dei Metodi Analitici]]"
  - "[[Dispositivi Medico-Diagnostici In Vitro (IVD)]]"
  - "[[ISO 15189]]"
  - "[[SIPMeL Q20 Parte II - Attrezzature, Reagenti e Servizi Esterni]]"
  - "[[Ambienti e Condizioni di Laboratorio]]"
  - "[[Tracciabilità Metrologica e Taratura]]"
  - "[[SIPMeL Q21 - Taratura, Verifica e Incertezza]]"
  - "[[Gestione degli Asset e Apparecchiature di Laboratorio (ISO 55001)]]"
sources:
  - "[[SIPMeL Q20 Parte II - Attrezzature, Reagenti e Servizi Esterni]]"
  - "[[SIPMeL Q21 - Taratura, Verifica e Incertezza]]"
---

## Definizione

Questo concetto raggruppa i requisiti di **[[ISO 15189]]** (capitolo 6, clausole 6.4, 6.6, 6.7, 6.8) relativi al ciclo di vita delle **attrezzature** (apparecchiature, strumenti, sistemi informativi), alla gestione di **reagenti e materiali di consumo**, e alla gestione di **prodotti e servizi forniti dall'esterno** (fornitori, laboratori di referenza, consulenti). Sono temi sviluppati in dettaglio in **[[SIPMeL Q20 Parte II - Attrezzature, Reagenti e Servizi Esterni]]**.

## Ciclo di vita delle attrezzature (clausola 6.4)

ISO 15189 6.4.1 richiede processi per **selezione, approvvigionamento, installazione, prove di accettazione** (con criteri di accettabilità), uso, manutenzione e infine **smantellamento** delle apparecchiature. Punti chiave:

- **Identificazione e registri (6.4.7)**: ogni apparecchiatura deve essere etichettata univocamente e dotata di un registro che riporti dati del fabbricante/fornitore, date di ricevimento/collaudo/messa in servizio, evidenze di conformità ai criteri di accettabilità, programma di manutenzione, certificati di taratura/verifica e stato attuale (attiva, fuori servizio, in quarantena, ritirata). I registri vanno conservati per tutta la vita dell'apparecchiatura e oltre.
- **Qualificazione**: la verifica che l'apparecchiatura, una volta installata, soddisfi i requisiti dichiarati (qualificazione dell'installazione, operativa, delle prestazioni) costituisce il presupposto per l'uso routinario e si collega direttamente alla **[[Validazione e Verifica dei Metodi Analitici]]**.
- **Manutenzione e calibrazione (6.4.5)**: programmi di manutenzione preventiva basati sulle istruzioni del produttore, con registrazione delle deviazioni; le apparecchiature difettose vanno messe fuori servizio e chiaramente etichettate fino a verifica del corretto funzionamento.
- **Salvaguardie (6.4.4)**: misure per evitare regolazioni involontarie che invaliderebbero i risultati; uso solo da parte di personale addestrato e autorizzato.
- **Segnalazioni (6.4.6)**: obbligo di segnalare a fabbricante/fornitore e autorità competenti incidenti attribuibili a un'apparecchiatura, e di rispondere a richiami.

## Gestione di reagenti e materiali di consumo (clausola 6.6)

I requisiti per reagenti e materiali di consumo sono in larga parte paralleli a quelli per le apparecchiature: processi di selezione, approvvigionamento, ricevimento, conservazione secondo le specifiche del produttore (con monitoraggio delle condizioni ambientali — vedi **[[Ambienti e Condizioni di Laboratorio]]**), test di accettazione e **gestione dell'inventario**, con separazione netta tra materiali accettati per l'uso e materiali non ancora ispezionati. I registri per ogni reagente/lotto devono includere identità, dati del produttore, **numero di lotto/partita**, date di ricevimento, scadenza e primo utilizzo; per i reagenti preparati internamente, anche l'operatore e le date di preparazione/scadenza — elementi che garantiscono la **tracciabilità** dei materiali utilizzati per ogni esame, requisito fondamentale anche per i dispositivi **[[Dispositivi Medico-Diagnostici In Vitro (IVD)]]**.

## Prodotti e servizi forniti dall'esterno (clausole 6.7-6.8)

La clausola 6.7 richiede **accordi di servizio** sia con gli utenti del laboratorio (in Italia formalizzati nella Carta dei Servizi) sia con i reparti che utilizzano servizi POCT. La clausola 6.8 disciplina i **prodotti e servizi forniti dall'esterno** — manutenzione di strutture/apparecchiature, taratura, programmi di valutazione esterna di qualità, laboratori di referenza, consulenti — richiedendo un elenco aggiornato dei fornitori (6.8.2) e procedure di **qualificazione, selezione, valutazione delle prestazioni e rivalutazione periodica** (6.8.3).

## Il framework strategico di asset management (ISO 55001/55002)

Il ciclo di vita delle apparecchiature descritto in questa pagina (clausola 6.4) rappresenta il livello **operativo** della gestione delle apparecchiature. A livello **strategico**, **[[UNI ISO 55001-2015 - Gestione dei Beni (Asset Management) - Sistemi di Gestione - Requisiti|ISO 55001]]** e **[[UNI ISO 55002-2015 - Gestione dei Beni (Asset Management) - Sistemi di Gestione - Linee Guida per l'Applicazione della ISO 55001|ISO 55002]]** forniscono il framework generico di **sistema di gestione dei beni (asset management)**, applicabile al governo dell'intero parco di apparecchiature analitiche: politica e piano strategico dei beni (SAMP), obiettivi di asset management (disponibilità, età del parco strumenti, costi di manutenzione), pianificazione della sostituzione e valutazione dei rischi/opportunità nel ciclo di vita. Si veda **[[Gestione degli Asset e Apparecchiature di Laboratorio (ISO 55001)]]** per l'approfondimento applicato.

## Nota di collegamento

La **manutenzione e taratura delle apparecchiature** (clausola 6.4.5) sarà ulteriormente approfondita nel cluster dedicato alle norme UNI sulla manutenzione (cluster 12 — UNI EN ISO 41001/41011/41012 e UNI 10147/10366/10685/11063/13306/15341), che fornirà il quadro tecnico operativo di dettaglio (definizioni, tipologie di manutenzione, indicatori) collocandosi a valle del framework strategico di ISO 55001/55002.
