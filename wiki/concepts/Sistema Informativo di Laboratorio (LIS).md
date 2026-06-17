---
type: concept
title: "Sistema Informativo di Laboratorio (LIS)"
created: 2026-06-12
updated: 2026-06-12
tags:
  - laboratorio-medico
  - concept
  - sistema-informativo
  - informatica
status: developing
address: c-000035
complexity: intermediate
domain: laboratorio-medico
aliases:
  - "LIS"
  - "Laboratory Information System"
  - "Sistema Informativo di Laboratorio"
related:
  - "[[ISO 15189]]"
  - "[[SIPMeL]]"
  - "[[Sistema di Gestione per la Qualità]]"
  - "[[SIPMeL Q18R1 - Gestione Dati e Informazioni]]"
  - "[[Point-of-Care Testing (POCT)]]"
  - "[[SIPMeL - Inclusione POCT (ISO 22870) in ISO 15189]]"
sources:
  - "[[SIPMeL Q18R1 - Gestione Dati e Informazioni]]"
  - "[[SIPMeL - Infrastruttura Informatica per i Laboratori Medici (LIS) - Raccomandazioni 2020]]"
---

## Cosa è

Il **Sistema Informativo di Laboratorio (LIS, Laboratory Information System)** è l'insieme dei sistemi informatici (e, in parte, non informatici) attraverso cui un laboratorio medico raccoglie, elabora, registra, archivia e recupera dati e informazioni relativi al ciclo dell'esame: richieste, accettazione campioni, risultati analitici, referti, dati di controllo di qualità, tracciabilità delle attività del personale. In **[[ISO 15189]]**, i sistemi informativi di laboratorio sono trattati sia come **attrezzatura** (clausola 6.4) sia come oggetto della clausola di processo **7.6 "Controllo della gestione dei dati e delle informazioni"**.

## Ruolo nel SGQ e requisiti ISO 15189 7.6

Per ISO 15189, al laboratorio non serve necessariamente il **possesso** del sistema informativo, ma la **disponibilità di accesso** ai dati e alle informazioni necessarie, anche tramite sistemi informatici esterni. I requisiti principali della clausola 7.6 includono:

- **Autorità e responsabilità** (7.6.2): il laboratorio deve definire chi è responsabile della gestione dei sistemi informativi, restando il responsabile ultimo anche quando il sistema è gestito da terzi.
- **Validazione e verifica** (7.6.3a): i sistemi per raccolta, elaborazione, registrazione, refertazione, archiviazione e recupero dei dati devono essere validati dal fornitore e verificati dal laboratorio prima dell'introduzione; ogni modifica successiva (incluse configurazioni software) deve essere autorizzata, documentata e validata prima dell'attuazione. Software commerciale d'uso generale (elaboratori di testo, fogli di calcolo) può considerarsi sufficientemente validato.
- **Controllo dell'accesso e integrità dei dati** (7.6.3 b-e): documentazione disponibile per gli utenti autorizzati, protezione da accessi non autorizzati (cibersicurezza), ambiente conforme alle specifiche del fornitore, manutenzione che garantisca l'integrità dei dati e registrazione di guasti e azioni correttive, controllo sistematico di calcoli e trasferimenti di dati.
- **Piani di inattività e gestione fuori sede** (7.6.4-7.6.5): processi pianificati per mantenere le operazioni durante guasti/interruzioni (ridondanza, fault tolerance, piani di contingenza anche cartacei) e, quando il LIS è gestito fuori sede o da fornitori esterni, garanzia che questi si conformino a tutti i requisiti applicabili.

Questi requisiti si intrecciano con la **gestione del rischio informatico** (ISO 22367 Appendice A.13: identificazione/tracciamento pazienti, integrità del middleware, cibersicurezza) e con i **controlli di sicurezza delle informazioni** della famiglia ISO/IEC 27001/27002/27799, applicabili in sanità per riservatezza, integrità e disponibilità dei dati (vedi **[[SIPMeL Q18R1 - Gestione Dati e Informazioni]]**).

## Tracciabilità e backup

ISO 15189 richiede che il LIS permetta di individuare gli **autori di ciascun intervento** (prelievo, esecuzione dell'esame, verifica/rilascio dei risultati, anche da parte di sistemi automatici), garantendo audit trail completi. La conservazione dei dati e la disponibilità di copie di backup/disaster recovery sono presupposti dei piani di inattività richiesti dal punto 7.6.4.

## Architettura: LIS, LAS e middleware

Il documento **[[SIPMeL - Infrastruttura Informatica per i Laboratori Medici (LIS) - Raccomandazioni 2020]]**, elaborato dal Gruppo di Studio Informatica SIPMeL (coordinatore Marco Pradella) nel contesto della razionalizzazione regionale dei sistemi informativi di laboratorio (Veneto, DGRV 1785/2016), precisa la terminologia architetturale distinguendo tre componenti:

- **LIS (Laboratory Information System)**: gestisce i dati clinici e amministrativi del ciclo dell'esame (richiesta, accettazione, risultati, referto, dati di controllo qualità, tracciabilità).
- **LAS (Laboratory Automation System)**: gestisce il flusso fisico dei campioni attraverso le linee di automazione e gli strumenti analitici.
- **Middleware**: livello software intermedio che integra LIS, LAS e strumenti, gestendo regole di instradamento dei campioni, ripetizioni automatiche, riflessi analitici e controllo qualità in tempo reale; il riferimento architetturale generale è lo standard **ISO 12967 (HISA - Health Informatics Service Architecture)**.

## Interoperabilità: standard per il flusso dei risultati

Il flusso dei risultati dagli strumenti analitici al LIS, e dal LIS al referto finale, è normato da diversi standard di interoperabilità:

- **HL7**, **ASTM**, **CLSI LIS01-A2/LIS02-A2** per la comunicazione strumento-LIS.
- Il profilo **IHE LAW (Laboratory Analytical Workflow)**, pubblicato a febbraio 2016, basato su **HL7 2.5.1** con terminologie **LOINC** (codifica degli esami), **JLAC10** e unità di misura **UCUM**.
- **ISO 17090** (parti 1-5) e infrastruttura a chiave pubblica (**PKI**)/certificati digitali per la sicurezza del documento referto — da non confondere con la firma digitale (che attiene solo all'autenticità del documento) rispetto al processo di revisione/validazione clinica dei risultati, che resta la responsabilità primaria secondo ISO 15189.

## Sicurezza informatica

Oltre ai requisiti generali ISO/IEC 2700X già citati sopra, le Raccomandazioni SIPMeL 2020 richiamano specificamente:

- **D.Lgs 196/2003**, artt. 33-34 (misure minime di sicurezza per sistemi che trattano dati sanitari).
- **ISO 27799** ("Health informatics — Information security management in health using ISO/IEC 27002"), specifica per il settore sanitario.
- **CLSI AUTO11**, con raccomandazioni dettagliate su gestione delle password, crittografia, audit trail, e comportamento dei sistemi in caso di guasto: modalità **fail-open** (il sistema continua a operare, con possibile perdita di controlli) vs **fail-closed** (il sistema si blocca, privilegiando la sicurezza sulla continuità operativa).

## Rilascio dei risultati: allarmi, rapporti provvisori e revisioni

Coerentemente con ISO 15189 5.9, il LIS deve supportare: notifica immediata e tracciata (data, ora, operatore, destinatario) per i risultati in intervalli di "allarme" o "critici"; rapporti provvisori sempre seguiti da un rapporto finale; selezione e rilascio automatizzato dei risultati secondo criteri documentati, validati e verificabili (**CLSI AUTO10-A**, "Autoverification of Clinical Laboratory Test Results"), con possibilità di rapida sospensione; gestione dei rapporti con risultati modificati, tramite emissione di un nuovo rapporto chiaramente identificato come revisione, con tracciabilità di data, ora e autore della modifica e conservazione dei dati originali (ISO 15189 5.9.3).

## Criteri di selezione/procurement di un LIS

Le Raccomandazioni SIPMeL 2020 forniscono liste estese di criteri per la valutazione di offerte commerciali in fase di acquisizione o rinnovo di un LIS (sezione 6.1, per il laboratorio "core" — chimica, ematologia, microbiologia, banca del sangue) e di un sistema per l'Anatomia Patologica (sezione 6.2): installazioni di riferimento, caratteristiche tecniche (linguaggi, sistemi operativi, basi di dati, log delle transazioni), certificazione **ISO 27001/ISO 27799**, moduli funzionali (incluse interfacce FSE per ADT, order placer/filler, risultati in PDF/CDA2), supporto **LOINC** e **SNOMED CT**, trasmissione dati per sorveglianza epidemiologica e registri tumori, accesso web, identificazione positiva del paziente, disponibilità del codice sorgente, costi e tempistiche di implementazione. Questi criteri rappresentano un riferimento pratico per i laboratori in fase di scelta o rinnovo del proprio sistema informativo, complementare ai requisiti normativi ISO 15189 7.6 descritti sopra.

## Connessione con il POCT

La connettività dei dispositivi **[[Point-of-Care Testing (POCT)]]** al LIS — per la tracciabilità dei risultati in cartella clinica e per il controllo remoto della strumentazione decentrata da parte del laboratorio centrale — è un requisito ricorrente nei documenti SIPMeL sul POCT (vedi **[[SIPMeL - Inclusione POCT (ISO 22870) in ISO 15189]]** e **[[SIPMeL - Infrastruttura Informatica per i Laboratori Medici (LIS) - Raccomandazioni 2020]]**), e trova nel profilo IHE LAW e negli standard HL7/LOINC/UCUM descritti sopra il riferimento architetturale per la sua implementazione.
