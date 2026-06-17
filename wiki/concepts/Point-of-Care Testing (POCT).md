---
type: concept
title: "Point-of-Care Testing (POCT)"
created: 2026-06-12
updated: 2026-06-12
tags:
  - laboratorio-medico
  - concept
  - poct
  - iso-22870
status: developing
address: c-000049
complexity: intermediate
domain: laboratorio-medico
aliases:
  - "POCT"
  - "near-patient testing"
  - "esami eseguiti vicino al paziente"
related:
  - "[[ISO 15189]]"
  - "[[SIPMeL - Inclusione POCT (ISO 22870) in ISO 15189]]"
  - "[[Controllo di Qualità Interno (CQI)]]"
  - "[[Ambienti e Condizioni di Laboratorio]]"
  - "[[Sistema Informativo di Laboratorio (LIS)]]"
  - "[[Validazione e Verifica dei Metodi Analitici]]"
  - "[[Troponina Cardiaca ad Alta Sensibilità (hs-cTn)]]"
  - "[[Turnaround Time (TAT) in Laboratorio]]"
  - "[[Gruppo di Studio sui Marcatori Miocardici (GdS MM) SIPMeL]]"
sources:
  - "[[SIPMeL - Inclusione POCT (ISO 22870) in ISO 15189]]"
  - "[[SIPMeL - Implementazione POCT Troponina]]"
  - "[[SIPMeL - Implementazione POCT Troponina per Sindromi Coronariche Acute - Aggiornamento 2024]]"
  - "[[SIPMeL - Autocontrollo della Glicemia (SMBG) - Sinossi]]"
  - "[[SIPMeL - PoCT e Diagnostica Decentrata - Posizione del GdS Point of Care Testing - Aggiornamento 2016]]"
---

## Cosa è

Il **Point-of-Care Testing (POCT)**, o "esame eseguito vicino al paziente" (near-patient testing), è l'esecuzione di esami di laboratorio con dispositivi diagnostici in vitro (IVD) compatti e di facile uso, direttamente presso o in prossimità del paziente — reparto di degenza, ambulatorio, pronto soccorso — anziché nel laboratorio centrale. Il risultato è destinato a influenzare in tempi rapidi le decisioni cliniche. La norma di riferimento è **ISO 22870:2016** ("Point-of-care testing — Requirements for quality and competence"), pensata per essere usata **in conjunction with** (in aggiunta a) **[[ISO 15189]]**, non in sua sostituzione: ISO 22870 si applica quando il POCT è eseguito in ospedale, clinica o struttura ambulatoriale, mentre l'autodiagnosi del paziente a domicilio è esclusa dal campo di applicazione.

## Sfide di governance

Il POCT pone sfide organizzative specifiche perché i dispositivi sono spesso fisicamente fuori dal laboratorio, operati da personale clinico (infermieri, medici di reparto) non formato come tecnico di laboratorio. ISO 22870 richiede quindi una governance dedicata: un **Medical Advisory Committee** che definisca l'ambito clinico del POCT e un **POCT management group** multidisciplinare (laboratorio, direzione, reparti clinici) che selezioni i dispositivi, alloghi le responsabilità e designi il personale autorizzato. La **formazione** del personale non di laboratorio deve coprire l'uso del dispositivo, la teoria della misura, gli aspetti preanalitici, il controllo qualità e la gestione dei risultati anomali — ambito per cui **ISO/TS 22583** fornisce una guida dedicata a supervisori e operatori privi di formazione di laboratorio. Altre criticità tipiche includono la **connettività** dei dispositivi al **[[Sistema Informativo di Laboratorio (LIS)]]** per la tracciabilità dei risultati in cartella clinica (distinguendoli da quelli del laboratorio centrale) e il **controllo di qualità** dei dispositivi decentrati, che deve garantire la confrontabilità dei risultati con quelli prodotti dal laboratorio centrale (CLSI EP09/EP31).

## Inquadramento regolatorio

Nell'accreditamento ISO 15189, il POCT non è accreditabile come attività isolata: rientra tra le "sedi secondarie" disciplinate dal regolamento multisito ACCREDIA, sotto l'unico sistema di gestione qualità del laboratorio accreditato. Il documento SIPMeL **[[SIPMeL - Inclusione POCT (ISO 22870) in ISO 15189]]** ha proposto, in occasione della revisione 2022 di ISO 15189, quali requisiti di ISO 22870 dovessero diventare parte integrante della norma generale per i laboratori medici — molti dei quali risultano poi effettivamente assorbiti nelle clausole su sistema di gestione, competenza del personale, **[[Controllo di Qualità Interno (CQI)]]** e ambienti e condizioni operative (vedi **[[Ambienti e Condizioni di Laboratorio]]**), confermando ISO 22870 come norma complementare e non alternativa a ISO 15189.

## La posizione SIPMeL del GdS PoCT (aggiornamento 2016)

Il **Gruppo di Studio Point of Care Testing SIPMeL (GdS PoCT)** ha pubblicato nel 2016 un aggiornamento ("UPDATE 2016") della propria posizione su PoCT e diagnostica decentrata, che sostituisce la precedente posizione SIMeL del 2009: vedi **[[SIPMeL - PoCT e Diagnostica Decentrata - Posizione del GdS Point of Care Testing - Aggiornamento 2016]]**. Il documento identifica le due sfide chiave per l'integrazione del POCT nel laboratorio "hub" — un sistema di assicurazione qualità unificato e la connettività al **[[Sistema Informativo di Laboratorio (LIS)]]** — e propone un modello di governance (Direttore di Laboratorio/Responsabile designato, **GDM** = Gruppo Direzionale Multidisciplinare, **GO** = Gruppo Operativo, coinvolgimento della Direzione Strategica) che precisa e completa lo schema Medical Advisory Committee/POCT management group di ISO 22870 descritto sopra.

L'aggiornamento introduce inoltre il nuovo paradigma del controllo di qualità basato su **IQCP (Individualized Quality Control Plan)** secondo **CLSI EP23-A**: analisi del rischio (**RA**) su 5 macro-aree (campione, ambiente, reagente, sistema di misura, personale), piano di controllo qualità (**QCP**) e monitoraggio continuo (**QA**) — un approccio risk-based che integra e precede concettualmente il riferimento a CLSI EP09/EP31 per la comparabilità POCT/laboratorio centrale citato sopra. Il documento amplia infine il campo applicativo del POCT a scenari **extra-ospedalieri** (assistenza domiciliare, Case della Salute, autocontrollo in farmacia), non coperti dalla posizione SIMeL del 2009.

## Caso applicativo: POCT per troponina nelle sindromi coronariche acute

Il **POCT per troponina cardiaca (cTn)** nei Dipartimenti di Emergenza è uno dei casi applicativi più studiati e normati del POCT in Italia, oggetto di due Raccomandazioni dedicate del **[[Gruppo di Studio sui Marcatori Miocardici (GdS MM) SIPMeL]]**: **[[SIPMeL - Implementazione POCT Troponina]]** (2016, 15 raccomandazioni) e il suo **[[SIPMeL - Implementazione POCT Troponina per Sindromi Coronariche Acute - Aggiornamento 2024|aggiornamento 2024]]**.

- **Razionale d'implementazione**: il POCT cTn va considerato quando il Laboratorio Centrale non è in grado di garantire la tempestività necessaria, dopo una revisione dell'organizzazione complessiva del ciclo richiesta-risposta — il POCT non è una "scorciatoia" per problemi organizzativi del Dipartimento di Emergenza.
- **Target di TAT**: la Raccomandazione 2016 fissava per il POCT cTn lo stesso obiettivo del Laboratorio Centrale (TAT ≤ 60 minuti, ottimale 30 minuti — vedi **[[Turnaround Time (TAT) in Laboratorio]]**). L'aggiornamento 2024, alla luce della diffusione del POCT per **[[Troponina Cardiaca ad Alta Sensibilità (hs-cTn)|hs-cTn]]** (fase analitica di soli 8-17 minuti), abbassa il target del TAT POCT a **< 30 minuti** dalla richiesta alla disponibilità della risposta — più stringente del target di laboratorio centrale.
- **Governance e formazione**: entrambe le Raccomandazioni richiamano la necessità di un Gruppo Direzionale Multidisciplinare (clinici DE/Cardiologia, laboratoristi, Direzione Strategica) e di una formazione del personale non di laboratorio condotta sotto la responsabilità del Laboratorio — in linea con i requisiti generali di governance ISO 22870/ISO 15189 descritti sopra (Medical Advisory Committee, POCT management group) e con la guida **ISO/TS 22583** (aggiornata al 2024) per supervisori e operatori non di laboratorio.
- **Controllo di qualità e comparabilità**: il POCT cTn deve essere allineato, sottoposto a **[[Controllo di Qualità Interno (CQI)]]** (2-3 livelli, frequenza basata sul rischio) e a forme di Valutazione Esterna di Qualità, e deve garantire risultati comparabili con il Laboratorio Centrale (CLSI EP09/EP31; ISO 15189:2022 punto 7.3.7.4) — requisito ora di Livello di evidenza A. Dal 2024 si raccomanda inoltre che, se il metodo del Laboratorio Centrale è hs-cTn, anche il POCT collegato debba essere un metodo hs-cTn con criteri analitici equivalenti (99° percentile, CV ≤ 10%, LoD/LoQ).
- **Connettività al LIS**: il POCT cTn deve essere "connesso" al **[[Sistema Informativo di Laboratorio (LIS)]]** e al sistema informativo aziendale (HIS/EHR), con autenticazione informatica dell'operatore, controllo remoto della strumentazione da parte del Laboratorio Centrale e archiviazione integrata dei risultati nel quadro clinico del paziente — un requisito presente già nella Raccomandazione 2016 e riconfermato nel 2024.
