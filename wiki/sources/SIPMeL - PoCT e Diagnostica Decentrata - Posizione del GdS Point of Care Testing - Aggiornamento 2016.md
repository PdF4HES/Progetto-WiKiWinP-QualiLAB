---
type: source
title: "SIPMeL - PoCT e Diagnostica Decentrata - Posizione del GdS Point of Care Testing - Aggiornamento 2016"
created: 2026-06-13
updated: 2026-06-13
tags:
  - laboratorio-medico
  - source
  - guideline
  - poct
  - iqcp
  - sipmel
status: developing
address: c-000135
source_type: guideline
year: 2016
authors:
  - "Pasquale Coppolecchia (corresponding author)"
  - "Cettina Drago"
  - "Luca Rossi"
  - "Rossana Colla"
  - "Renato Tozzoli"
  - "Gruppo di Studio Point of Care Testing SIPMeL (GdS PoCT)"
publication: "Riv Ital Med Lab - Rassegna, manoscritto RIME-D-15-00028R2, \"PoCT e diagnostica decentrata. UPDATE 2016. Posizione SIPMeL del GdS Point of Care Testing\""
related:
  - "[[SIPMeL]]"
  - "[[Point-of-Care Testing (POCT)]]"
  - "[[Sistema Informativo di Laboratorio (LIS)]]"
  - "[[SIPMeL - Inclusione POCT (ISO 22870) in ISO 15189]]"
  - "[[Controllo di Qualità Interno (CQI)]]"
  - "[[ISO 15189]]"
key_claims:
  - "Il documento aggiorna (UPDATE 2016) la precedente 'Posizione SIMeL su PoCT e diagnostica decentrata' del 2009, alla luce dell'evoluzione normativa (ISO 22870:2016, CLSI EP23-A su IQCP) e della diffusione del POCT in contesti extra-ospedalieri."
  - "Identifica due sfide principali per l'integrazione del POCT nel sistema qualità del laboratorio centrale (hub lab): (1) un sistema di assicurazione qualità unificato; (2) la connettività dei dispositivi decentrati al sistema informativo."
  - "Definisce il modello di governance del POCT secondo ISO 22870/ISO 15189: Direttore di Laboratorio o Responsabile designato, GDM (Gruppo Direzionale Multidisciplinare), GO (Gruppo Operativo) e coinvolgimento della Direzione Strategica (DS)."
  - "Distingue scenari clinici ospedalieri (Pronto Soccorso/emergenza, reparti specialistici, monitoraggio frequente) da scenari extra-ospedalieri (assistenza domiciliare, Centri di Assistenza Domiciliare CAD, ambulatori pneumologici, Case della Salute, autocontrollo privato in farmacia o su navi da crociera)."
  - "Propone il nuovo paradigma del controllo di qualità per il POCT basato su IQCP (Individualized Quality Control Plan) secondo CLSI EP23-A, articolato in tre componenti: RA (Risk Analysis, analisi del rischio su 5 macro-aree: campione, ambiente, reagente, sistema di misura, personale), QCP (Quality Control Plan) e QA (Quality Assessment, monitoraggio continuo)."
  - "Elenca 17 criteri (a-r) per la selezione dei dispositivi POCT: menu analitico, volume di campione, indici serici, facilità d'uso, costo, archiviazione dati, manutenzione, prestazioni analitiche, calibrazione/auto-QC, blocco operativo (lockout) in caso di fallimento del QC, tracciabilità, rilevamento errori, autodiagnosi, connettività, sicurezza dell'operatore, supporto del fornitore."
  - "Per la formazione, richiede corsi certificati con refresh periodico, con gli intervalli definiti dal GDM."
  - "Sulla refertazione, richiede validazione tecnica e clinica, conformità a ISO 22870/ISO 15189, connettività al LIS per la tracciabilità (in linea con le linee guida 2006 del Ministero della Salute sulla dematerializzazione del referto) e transcodifica dei messaggi di errore dello strumento."
---

## Cosa è

Questo documento è l'**aggiornamento 2016** ("UPDATE 2016") della posizione SIPMeL del **Gruppo di Studio Point of Care Testing (GdS PoCT)** sul tema "PoCT e diagnostica decentrata", pubblicato come rassegna su Riv Ital Med Lab (manoscritto RIME-D-15-00028R2). Autore corrispondente **Pasquale Coppolecchia** (Servizio di Patologia Clinica e Rete PoCT, AUSL Modena), con Cettina Drago, Luca Rossi, Rossana Colla, Renato Tozzoli e i membri del GdS PoCT SIPMeL.

Il documento **aggiorna la precedente "Posizione SIMeL su PoCT e diagnostica decentrata" del 2009** (non precedentemente ingerita in questa wiki), alla luce dell'evoluzione normativa nel periodo 2009-2016: pubblicazione di **ISO 22870:2016**, diffusione del paradigma **IQCP** (Individualized Quality Control Plan) secondo **CLSI EP23-A**, ed espansione del POCT a contesti extra-ospedalieri (assistenza domiciliare, autocontrollo).

Parole chiave: PoCT, IQCP, referto di laboratorio, PoCT extra-ospedaliero, autocontrollo (self testing), risk management.

## Le due sfide dell'integrazione POCT-laboratorio centrale

Il documento identifica **due sfide principali** per l'integrazione dei dispositivi POCT decentrati nel sistema qualità del laboratorio centrale (hub lab):

1. **Un sistema di assicurazione qualità unificato**, che garantisca la comparabilità dei risultati POCT con quelli del laboratorio centrale, indipendentemente da dove e da chi viene eseguito l'esame.
2. **La connettività dei dispositivi al sistema informativo** (LIS), per assicurare la tracciabilità dei risultati POCT in cartella clinica al pari di quelli prodotti dal laboratorio centrale — tema approfondito anche in **[[Sistema Informativo di Laboratorio (LIS)]]** e **[[SIPMeL - Infrastruttura Informatica per i Laboratori Medici (LIS) - Raccomandazioni 2020]]**.

## Modello di governance (ISO 22870/ISO 15189)

Il documento descrive il modello di governance richiesto da ISO 22870 in conjunction con ISO 15189:

- **Direttore di Laboratorio o Responsabile designato**: responsabilità ultima del sistema qualità POCT, anche quando i dispositivi sono fisicamente fuori dal laboratorio.
- **GDM (Gruppo Direzionale Multidisciplinare)**: gruppo che coinvolge clinici delle unità operative interessate, laboratoristi e Direzione Strategica, responsabile della selezione dei dispositivi, definizione di policy, formazione e monitoraggio.
- **GO (Gruppo Operativo)**: gruppo operativo che gestisce gli aspetti tecnici quotidiani (manutenzione, controllo qualità, gestione delle non conformità).
- **DS (Direzione Strategica)**: coinvolgimento della direzione aziendale per le decisioni di investimento e organizzative di più ampio respiro.

Questo modello di governance è coerente e complementare a quello descritto in **[[Point-of-Care Testing (POCT)]]** (Medical Advisory Committee, POCT management group).

## Scenari clinici: ospedalieri ed extra-ospedalieri

Il documento distingue scenari applicativi del POCT:

- **Scenari ospedalieri**: Pronto Soccorso/Dipartimento di Emergenza (urgenza, alto turnover), reparti specialistici (es. terapia intensiva, cardiologia), monitoraggio frequente di parametri (es. emogasanalisi, glicemia).
- **Scenari extra-ospedalieri**: assistenza domiciliare, Centri di Assistenza Domiciliare (CAD), ambulatori pneumologici territoriali, Case della Salute, e contesti di **autocontrollo privato** (self testing) come farmacie e ambiti non sanitari (es. navi da crociera).

L'espansione del POCT verso contesti extra-ospedalieri, non previsti dalla posizione 2009, è uno degli elementi distintivi di questo aggiornamento 2016.

## Il nuovo paradigma del controllo qualità: IQCP (CLSI EP23-A)

Elemento centrale dell'aggiornamento è l'adozione del paradigma **IQCP (Individualized Quality Control Plan)** secondo **CLSI EP23-A**, basato sulla **gestione del rischio** piuttosto che su un controllo qualità "a frequenza fissa". L'IQCP si articola in tre componenti:

1. **RA (Risk Analysis)** — analisi del rischio articolata su **5 macro-aree**: campione, ambiente, reagente, sistema di misura, personale.
2. **QCP (Quality Control Plan)** — il piano di controllo qualità derivato dall'analisi del rischio, che definisce frequenza e modalità dei controlli.
3. **QA (Quality Assessment)** — il monitoraggio continuo dell'efficacia del piano, con eventuale revisione.

Questo paradigma rappresenta un'evoluzione significativa rispetto agli approcci precedenti, spostando l'enfasi dalla frequenza fissa dei controlli alla **gestione personalizzata del rischio** specifico di ciascuna postazione POCT.

## Criteri per la selezione dei dispositivi POCT (17 criteri a-r)

Il documento propone una lista di **17 criteri** per la selezione dei dispositivi POCT:

a) menu analitico disponibile; b) volume di campione richiesto; c) indici serici (emolisi, ittero, lipemia); d) facilità d'uso; e) costo; f) archiviazione dei dati; g) manutenzione; h) prestazioni analitiche; i) calibrazione e auto-QC; j) **blocco operativo (lockout)** in caso di fallimento del controllo qualità; k) tracciabilità; l) rilevamento errori; m) autodiagnosi; n) connettività; o) sicurezza dell'operatore; p) supporto del fornitore; q-r) ulteriori criteri operativi.

## Formazione

Il documento richiede **corsi di formazione certificati** per gli operatori non di laboratorio, con **refresh periodico** la cui frequenza è definita dal GDM — coerente con la guida **ISO/TS 22583** per supervisori e operatori privi di formazione di laboratorio, citata anche in **[[Point-of-Care Testing (POCT)]]**.

## Referto e connettività al LIS

Il documento dedica una sezione al **referto POCT**, richiedendo:

- **Validazione tecnica e clinica** dei risultati, in conformità a ISO 22870/ISO 15189.
- **Connettività al LIS** per garantire la tracciabilità dei risultati POCT in cartella clinica, in linea con le **linee guida del Ministero della Salute del 2006 sulla dematerializzazione del referto**.
- **Transcodifica dei messaggi di errore** dello strumento in un formato comprensibile e gestibile dal sistema informativo.

## Collaborazione con l'industria

Il documento include una sezione sulla collaborazione tra laboratori e produttori di dispositivi POCT, per il miglioramento continuo delle caratteristiche tecniche (connettività, sicurezza, auto-QC) rilevanti per l'integrazione nel sistema qualità.

## Bibliografia

Il documento riporta una bibliografia di 35 riferimenti, tra cui: Kohn LT et al. (Institute of Medicine, "To Err Is Human", 2000), Plebani M (2009), Cappelletti P (2001, 2004), Pradella M (2014, 2015), **CLSI EP23-A** (IQCP), **CLSI POCT09-A/POCT4-A02** (standard specifici per il POCT).

## Rilevanza per il quadro qualità/accreditamento

Questo documento aggiorna e completa il quadro sul **[[Point-of-Care Testing (POCT)]]** descritto in questa wiki, fornendo il dettaglio sul nuovo paradigma di controllo qualità **IQCP/CLSI EP23-A** (non trattato in dettaglio altrove), sul modello di governance GDM/GO/DS, sui criteri di selezione dei dispositivi e sull'espansione del POCT a contesti extra-ospedalieri. È complementare a **[[SIPMeL - Inclusione POCT (ISO 22870) in ISO 15189]]** (che mappa i requisiti ISO 22870 nella revisione di ISO 15189:2022) e rafforza il legame tra POCT e **[[Sistema Informativo di Laboratorio (LIS)]]** già evidenziato nella sezione "Sfide di governance" del concetto POCT.
