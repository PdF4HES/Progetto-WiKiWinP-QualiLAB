---
type: source
title: "UNI EN 13306:2018 - Manutenzione - Terminologia di manutenzione"
created: 2026-06-13
updated: 2026-06-13
tags:
  - laboratorio-medico
  - source
  - manutenzione
  - terminologia
  - norma-uni
status: complete
address: c-000169
related:
  - "[[UNI 10147-2013 - Manutenzione Termini Aggiuntivi]]"
  - "[[UNI 11063-2017 - Manutenzione Ordinaria e Straordinaria]]"
  - "[[Terminologia e Tipologie di Manutenzione (UNI 13306)]]"
  - "[[Gestione degli Asset e Apparecchiature di Laboratorio (ISO 55001)]]"
  - "[[Gestione di Attrezzature, Reagenti e Fornitori Esterni]]"
sources:
  - ".raw/unlocked_UNI EN 13306_2018 - Manutenzione - Terminologia di manutenzione.pdf"
---

## Descrizione

**UNI EN 13306:2018** (versione italiana della norma europea EN 13306:2017, edita dal CEN/TC 319 "Maintenance", segreteria UNI) è la **norma fondamentale di terminologia della manutenzione**. Sostituisce la precedente UNI EN 13306:2010. Specifica i termini generici e le relative definizioni per le aree **tecnica, amministrativa e gestionale** della manutenzione, applicabili indipendentemente dal tipo di entità (macchine, impianti, edifici, infrastrutture, apparecchiature). Esclude la manutenzione esclusiva del software, ma considera la manutenzione di entità/sistemi contenenti software.

L'introduzione chiarisce che l'organizzazione della manutenzione ha la responsabilità di definire la strategia di manutenzione secondo gli obiettivi principali di: assicurare la disponibilità dell'entità al costo ottimale, considerare sicurezza/persone/ambiente, e migliorare la durabilità dell'entità e/o la qualità del prodotto/servizio.

## Struttura della norma

La norma è organizzata in 11 sezioni terminologiche principali più appendici informative:

1. **Premessa e introduzione**
2. **Termini principali** (2.1-2.9): manutenzione, gestione della manutenzione, obiettivi/strategia/piano di manutenzione, funzione richiesta, fidatezza, supporto logistico, funzionamento
3. **Termini relativi all'entità** (3.1-3.7): entità/elemento/bene, bene fisico/cespite, entità riparabile, entità di consumo, parte di ricambio, livello d'intervento
4. **Proprietà delle entità** (4.1-4.23): affidabilità, manutenibilità, disponibilità (e sue varianti: istantanea, basata sul tempo, basata sulla produzione), conformità, durabilità, ridondanza, vita utile, tasso di guasto medio, ciclo di vita, obsolescenza
5. **Guasti ed eventi** (5.1-5.16): guasto, modi/cause di guasto, guasto per usura/invecchiamento/utilizzo improprio, degrado, criticità, criteri di guasto
6. **Avarie e stati** (6.1-6.14): avaria, stato di disponibilità/degrado/indisponibilità, stato d'incapacità, arresto programmato
7. **Tipi di manutenzione** (7.1-7.19): preventiva, ciclica, secondo condizione, predittiva, attiva, correttiva (differita/d'urgenza), programmata, opportunistica, remota, in linea, in situ, automanutenzione, esternalizzazione
8. **Attività di manutenzione** (8.1-8.15): ispezione, monitoraggio delle condizioni, manutenzione di routine, revisione, diagnosi/localizzazione di avaria, ripristino, riparazione, ricostruzione, manutenzione eccezionale, programma di manutenzione
9. **Termini relativi al tempo** (9.1-9.20+): tempo di disponibilità (UT), tempo di indisponibilità (DT), tempo di funzionamento (OT), tempo di manutenzione, tempi di riparazione, ritardi logistici/tecnici/amministrativi, tempo tra guasti (MTBF-correlato), OTBF
10. **Logistica e strumenti della manutenzione**
11. **Fattori economici e tecnici**

Appendici informative: A - Manutenzione, quadro generale (con figure su tipi di manutenzione e tempi); B - Stati di un'entità; C - Produzione basata sulla disponibilità; D - Tempi; E - Matrice delle criticità; F - Modifiche tecniche rispetto all'edizione 2010; indici alfabetici multilingue (IT/EN/FR/DE).

## Definizioni chiave per il laboratorio clinico

- **Manutenzione (2.1)**: "Combinazione di tutte le azioni tecniche, amministrative e gestionali, durante il ciclo di vita di un'entità, destinate a mantenerla o riportarla in uno stato in cui possa eseguire la funzione richiesta."
- **Manutenzione preventiva (7.1)**: manutenzione eseguita per valutare e/o mitigare il degrado e ridurre la probabilità di guasto.
  - **Manutenzione ciclica (7.2)**: preventiva a intervalli di tempo/uso prestabiliti, senza indagine preliminare sulle condizioni.
  - **Manutenzione secondo condizione (7.3)**: preventiva basata su valutazione delle condizioni fisiche (osservazione, ispezione, collaudo, monitoraggio).
  - **Manutenzione predittiva (7.4)**: manutenzione secondo condizione basata su previsioni derivate da analisi ripetute o caratteristiche note del degrado.
- **Manutenzione correttiva/a guasto (7.9)**: eseguita dopo la rilevazione di un'avaria, per ripristinare la funzione richiesta. Si distingue in **differita (7.10)** e **d'urgenza (7.11)**.
- **Affidabilità (4.1)**, **manutenibilità (4.5)**, **disponibilità (4.7)**: le tre proprietà fondamentali della "fidatezza" (dependability, 2.7) di un'entità - centrali per gli indicatori di prestazione delle apparecchiature analitiche.
- **Disponibilità basata sul tempo (4.9)**: percentuale del tempo in cui un'entità è stata in grado di funzionare quando richiesto, calcolabile come rapporto UT/(UT+DT) o varianti basate su OT, TTR, DT - base concettuale per indicatori di disponibilità degli analizzatori.
- **Tempi (sezione 9)**: UT (tempo di disponibilità), DT (tempo di indisponibilità), OT (tempo di funzionamento), tempo tra guasti - elementi costitutivi per il calcolo di indicatori come MTBF (Mean Time Between Failures) e MTTR (Mean Time To Repair), pur non essendo questi acronimi anglosassoni usati direttamente nel testo italiano (la norma usa "tempo di funzionamento tra guasti, OTBF" e termini analoghi).
- **Manutenzione di routine (8.5)**: attività regolari/ripetute di manutenzione preventiva elementare (pulizia, serraggio, sostituzione connettori, controllo livelli liquidi, lubrificazione) - rilevante per le attività quotidiane dell'operatore di laboratorio sugli analizzatori.
- **Esternalizzazione della manutenzione (7.19)**: appalto di tutte o parte delle attività di manutenzione per un periodo definito - base per i contratti di assistenza con i fornitori di strumentazione (si veda **[[Gestione di Attrezzature, Reagenti e Fornitori Esterni]]**).

## Nota sulla qualità dell'estrazione testuale

Il testo del PDF (42 pagine) è stato estratto correttamente tramite `pypdf` senza corruzione significativa dell'encoding; la sintesi sopra riportata si basa sulla lettura diretta dell'indice e delle sezioni 2-9.

## Collegamenti

Questa norma costituisce il **vocabolario di base** richiamato e integrato da **[[UNI 10147-2013 - Manutenzione Termini Aggiuntivi]]** (termini complementari) e utilizzato come riferimento normativo primario da **[[UNI 11063-2017 - Manutenzione Ordinaria e Straordinaria]]** per la classificazione ordinaria/straordinaria. Si veda la sintesi concettuale in **[[Terminologia e Tipologie di Manutenzione (UNI 13306)]]**, collegata a sua volta a **[[Gestione degli Asset e Apparecchiature di Laboratorio (ISO 55001)]]** e ai requisiti di manutenzione/taratura di ISO 15189 6.4.5 (si veda **[[Gestione di Attrezzature, Reagenti e Fornitori Esterni]]**).
