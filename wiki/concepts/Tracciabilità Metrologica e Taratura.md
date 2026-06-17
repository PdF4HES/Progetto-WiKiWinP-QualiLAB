---
type: concept
title: "Tracciabilità Metrologica e Taratura"
created: 2026-06-12
updated: 2026-06-12
tags:
  - laboratorio-medico
  - concept
  - tracciabilita-metrologica
  - taratura
  - metrologia
status: developing
address: c-000043
complexity: advanced
domain: laboratorio-medico
aliases:
  - "Metrological Traceability"
  - "Calibration Hierarchy"
  - "Gerarchia di Taratura"
related:
  - "[[Incertezza di Misura]]"
  - "[[Dispositivi Medico-Diagnostici In Vitro (IVD)]]"
  - "[[ISO 15189]]"
  - "[[SIPMeL]]"
  - "[[SIPMeL Q21 - Taratura, Verifica e Incertezza]]"
  - "[[SIPMeL L5Q15 - Glossario ISO Laboratori Medici]]"
  - "[[Gestione di Attrezzature, Reagenti e Fornitori Esterni]]"
sources:
  - "[[SIPMeL Q21 - Taratura, Verifica e Incertezza]]"
  - "[[SIPMeL L5Q15 - Glossario ISO Laboratori Medici]]"
---

## Definizione

La **tracciabilità (riferibilità) metrologica** è la proprietà di un risultato di misura per cui esso è posto in relazione a un riferimento attraverso una **catena documentata e ininterrotta di tarature**, ciascuna delle quali contribuisce all'**[[Incertezza di Misura]]** complessiva (VIM3 2.41, ISO 17511 3.31). È uno dei requisiti chiave di **[[ISO 15189]]** al punto 6.5 (Taratura delle apparecchiature e tracciabilità metrologica).

## Gerarchia di taratura (ISO 17511)

La **gerarchia di taratura** è la sequenza di tarature che parte da un riferimento di ordine superiore (idealmente il Sistema Internazionale di unità di misura, SI) e arriva al sistema di misura usato in laboratorio, dove l'esito di ciascuna taratura dipende da quello precedente. ISO 17511 stabilisce i requisiti per la riferibilità metrologica dei **valori assegnati** a calibratori, materiali di controllo dell'esattezza e campioni umani, includendo il concetto di "gerarchie di taratura" eredità di ISO 18153. Quando i riferimenti di ordine superiore sono tecnicamente irraggiungibili, **ISO 21151** definisce **protocolli di armonizzazione internazionale** (es. per BCR-ABL1, anticorpi anti-rosolia) per stabilire comunque valori assegnati comparabili tra metodi diversi.

## Taratura vs verifica della taratura

La **taratura** (ISO 17511 3.4) è l'operazione che, in due fasi, stabilisce la relazione tra i valori forniti da standard di misura e le indicazioni dello strumento, e poi usa questa relazione per ottenere risultati di misura. Non va confusa con:
- la **regolazione** (adjustment) del sistema di misura, spesso erroneamente chiamata "autotaratura";
- la **verifica dello stato di taratura**, ossia il controllo periodico che la taratura sia ancora valida (mediante materiali di controllo della taratura, "calibration verification controls").

ISO 15189 6.5.2 richiede procedure che includano le istruzioni del fabbricante, la registrazione della tracciabilità, la verifica dell'accuratezza richiesta, la gestione delle ritarature e dei fattori di correzione, e la gestione delle situazioni di "taratura fuori controllo".

## Valore assegnato e materiali di riferimento

Il **valore assegnato** a un calibratore o materiale di controllo deriva, nell'ordine di preferenza, da: una **procedura di misura di riferimento (RMP)** di ordine superiore; un **materiale di riferimento certificato (CRM)** prodotto da un fornitore competente conforme a ISO 17034/15194, con dichiarata riferibilità al SI; oppure, quando questi non sono disponibili, da procedure di misurazione di riferimento "convenzionali", metodi specificati o norme di consenso. La certificazione dei materiali di riferimento spetta a **laboratori di riferimento** accreditati ISO 15195 - da non confondere con i **laboratori di referenza** (ISO 15189 6.8.2), che eseguono esami per conto di altri laboratori.

## Calibrazione fornita dal produttore (IVD)

Per i **[[Dispositivi Medico-Diagnostici In Vitro (IVD)]]**, le informazioni sulla riferibilità a un materiale o procedura di riferimento di ordine superiore possono essere fornite direttamente dal fabbricante, ma sono accettabili **solo se il sistema d'esame e le procedure di taratura del produttore vengono usati senza modifiche**. ISO 21151 introduce anche i "calibration verification controls": materiali forniti dal produttore per confermare che la taratura ottenuta con i calibratori dell'utente finale sia soddisfacente.

## Metodi senza tracciabilità metrologica

Alcuni metodi (anticorpi eritrocitari, antibiogramma, esami genetici, VES, citometria a flusso, immunoistochimica HER2) non consentono tracciabilità metrologica in senso stretto. Per questi, **[[SIPMeL Q21 - Taratura, Verifica e Incertezza|Q21]]** raccomanda di basarsi sulla **riproducibilità (concordanza) tra laboratori** verificata tramite programmi di **Valutazione Esterna di Qualità (VEQ)**. Per gli esami di genomica, la tracciabilità si stabilisce verso sequenze di riferimento pubbliche (es. GRCh38, sequenza mitocondriale di Cambridge).
