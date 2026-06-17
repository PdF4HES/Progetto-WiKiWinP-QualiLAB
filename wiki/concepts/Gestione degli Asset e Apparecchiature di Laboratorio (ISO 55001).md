---
type: concept
title: "Gestione degli Asset e Apparecchiature di Laboratorio (ISO 55001)"
created: 2026-06-13
updated: 2026-06-13
tags:
  - laboratorio-medico
  - concept
  - asset-management
  - attrezzature
  - sistema-di-gestione
status: developing
address: c-000164
complexity: intermediate
domain: laboratorio-medico
aliases:
  - "Asset Management di Laboratorio"
  - "Gestione del Ciclo di Vita degli Asset"
  - "Strategic Asset Management Plan (SAMP)"
related:
  - "[[UNI ISO 55001-2015 - Gestione dei Beni (Asset Management) - Sistemi di Gestione - Requisiti]]"
  - "[[UNI ISO 55002-2015 - Gestione dei Beni (Asset Management) - Sistemi di Gestione - Linee Guida per l'Applicazione della ISO 55001]]"
  - "[[Gestione di Attrezzature, Reagenti e Fornitori Esterni]]"
  - "[[Tracciabilità Metrologica e Taratura]]"
  - "[[Sistema di Gestione per la Qualità]]"
  - "[[Continuità Operativa e Resilienza del Laboratorio]]"
  - "[[Gestione del Rischio (ISO 31000)]]"
  - "[[ISO 15189]]"
  - "[[Facility Management (ISO 41001)]]"
  - "[[Terminologia e Tipologie di Manutenzione (UNI 13306)]]"
  - "[[UNI 10685-2007 - Criteri per Contratti di Manutenzione Global Service]]"
  - "[[UNI EN 15341-2019 - Indicatori di Prestazione della Manutenzione (KPI)]]"
sources:
  - "[[UNI ISO 55001-2015 - Gestione dei Beni (Asset Management) - Sistemi di Gestione - Requisiti]]"
  - "[[UNI ISO 55002-2015 - Gestione dei Beni (Asset Management) - Sistemi di Gestione - Linee Guida per l'Applicazione della ISO 55001]]"
---

## Definizione

Questo concetto descrive come il **framework generico di asset management** definito da **[[UNI ISO 55001-2015 - Gestione dei Beni (Asset Management) - Sistemi di Gestione - Requisiti|ISO 55001]]** e **[[UNI ISO 55002-2015 - Gestione dei Beni (Asset Management) - Sistemi di Gestione - Linee Guida per l'Applicazione della ISO 55001|ISO 55002]]** si applica al **parco di apparecchiature analitiche e strumentazione di laboratorio**, fornendo una struttura strategica di sistema di gestione che si affianca (senza sovrapporsi) ai requisiti operativi di dettaglio già previsti da [[ISO 15189]] al punto 6.4 e descritti in **[[Gestione di Attrezzature, Reagenti e Fornitori Esterni]]**.

> **Misurazione delle prestazioni degli asset**: la misurazione operativa di disponibilità, affidabilità e costi del parco asset - elementi centrali del SAMP - è fornita dagli **indicatori KPI di [[UNI EN 15341-2019 - Indicatori di Prestazione della Manutenzione (KPI)|UNI EN 15341]]** (es. M10-M12 per la disponibilità, PHA13/PHA14/PHA17/M17 per i costi), mentre l'eventuale **esternalizzazione della manutenzione del parco asset** può essere strutturata secondo i criteri "global service" di **[[UNI 10685-2007 - Criteri per Contratti di Manutenzione Global Service|UNI 10685]]**. Si veda **[[Terminologia e Tipologie di Manutenzione (UNI 13306)]]** per il quadro completo (terminologia, criteri di progettazione, contratti, KPI).

## Dal "che cosa" operativo al "come" strategico

I requisiti di ISO 15189 6.4 (identificazione e registri delle apparecchiature, programmi di manutenzione, criteri di accettabilità, qualificazione, salvaguardie, segnalazioni) rispondono alla domanda "*che cosa* il laboratorio deve fare per ogni singola apparecchiatura". ISO 55001/55002 rispondono invece alla domanda "*come* l'organizzazione governa, a livello strategico e nel tempo, l'**intero portafoglio** di beni fisici (apparecchiature, ma anche strutture, sistemi informativi) per realizzarne il valore in linea con gli obiettivi organizzativi". I due livelli sono complementari:

- **Livello operativo (ISO 15189 6.4)**: registro per singola apparecchiatura, programma di manutenzione, taratura, messa fuori servizio di apparecchiature difettose.
- **Livello strategico (ISO 55001/55002)**: politica di asset management, **piano strategico dei beni (SAMP)**, obiettivi di asset management (es. tasso di disponibilità degli analizzatori, età media del parco strumenti, percentuale di apparecchiature in garanzia/manutenzione contrattuale), **piani di asset management** per famiglie di strumenti (es. piano di rinnovo degli analizzatori di chimica clinica su un orizzonte di 7-10 anni), valutazione dei rischi/opportunità nel ciclo di vita (obsolescenza tecnologica, indisponibilità di parti di ricambio, fine vita del fornitore), riesame periodico delle prestazioni dell'asset management nel riesame di direzione.

## Il piano strategico dei beni (SAMP) applicato alla strumentazione analitica

Il **SAMP** (Strategic Asset Management Plan), elemento centrale di ISO 55001 punto 4.4 e 6.2, traduce gli obiettivi organizzativi del laboratorio (es. continuità del servizio diagnostico, qualità analitica, sostenibilità economica) in obiettivi specifici per la gestione del parco strumenti. Per un laboratorio clinico, un SAMP applicato alla strumentazione potrebbe definire:

- **criteri di pianificazione della sostituzione** (capital replacement planning): età, obsolescenza tecnologica, costo di manutenzione crescente, disponibilità di parti di ricambio, fine del supporto del fornitore;
- **criteri di ridondanza**: per gli strumenti critici per la continuità operativa (si veda **[[Continuità Operativa e Resilienza del Laboratorio]]**), valutazione del rischio di indisponibilità prolungata e relative misure di mitigazione (backup, accordi con laboratori limitrofi);
- **obiettivi di disponibilità e affidabilità** degli analizzatori, monitorati come indicatori di prestazione dell'asset management (ISO 55001 punto 9.1) — distinti ma collegati agli **indicatori di qualità** richiesti da ISO 15189 8.8;
- **integrazione con la pianificazione finanziaria** del laboratorio (budget di investimento, ammortamenti, contratti di noleggio/reagent-rental).

## Gestione del rischio nel ciclo di vita degli asset

ISO 55001 punto 6.1 richiede la valutazione dei **rischi e opportunità associati al ciclo di vita dei beni**, applicando il framework generico di **[[Gestione del Rischio (ISO 31000)]]** già condiviso da tutti i sistemi di gestione del [[Sistema di Gestione per la Qualità|SGQ]] integrato del laboratorio. Per le apparecchiature analitiche, ciò significa considerare sistematicamente:

- rischio di **interruzione del servizio diagnostico** per guasto/obsolescenza di uno strumento critico (collegamento con [[Continuità Operativa e Resilienza del Laboratorio]]);
- rischio **economico** di sostituzioni non pianificate (acquisti d'urgenza a condizioni svantaggiose);
- rischio di **non conformità metrologica** durante la transizione tra strumenti (collegamento con **[[Tracciabilità Metrologica e Taratura]]** — qualificazione e verifica di confrontabilità dei nuovi strumenti);
- opportunità di **efficienza** da consolidamento/aggiornamento tecnologico del parco strumenti (es. automazione, riduzione dei punti di prelievo manuali).

## Integrazione nel sistema di gestione del laboratorio

Coerentemente con il principio di **integrazione dei sistemi di gestione** già descritto in **[[Sistema di Gestione per la Qualità]]**, ISO 55001/55002 non richiedono un sistema di gestione separato: gli elementi dell'asset management (politica, obiettivi, piani, valutazione dei rischi, riesame) possono essere **incorporati nel SGQ esistente** del laboratorio, ad esempio:

- la **politica di asset management** può essere una sezione della politica per la qualità;
- gli **obiettivi di asset management** (disponibilità, età del parco strumenti, costi di manutenzione) possono entrare negli **indicatori di qualità** monitorati ai sensi di ISO 15189 8.8;
- il **piano di asset management** per la strumentazione può essere un input/output del **riesame di direzione** (ISO 15189 8.9), affiancando gli altri sistemi già discussi (continuità operativa, SSL).

## Connessione con il cluster sulla manutenzione (cluster 12)

Le norme **UNI EN ISO 41001/41011/41012** (facility management, ora ingerite — si veda **[[Facility Management (ISO 41001)]]**) e le norme sulla **manutenzione** (**UNI 10147, UNI 10366, UNI 10685, UNI 11063, UNI 13306, UNI 15341**), oggetto delle restanti voci del cluster 12, forniscono il **dettaglio operativo** (definizioni dei tipi di manutenzione — preventiva, predittiva, correttiva —, indicatori di manutenzione, gestione dei contratti di servizio e di facility management) che si colloca **a valle** del framework strategico definito da ISO 55001/55002: quest'ultimo stabilisce *perché* e *con quali obiettivi* governare il ciclo di vita degli asset, mentre le norme di manutenzione e facility management stabiliscono *come* eseguire e misurare le attività di manutenzione e di gestione delle infrastrutture che ne derivano. Si veda la nota di collegamento già presente in **[[Gestione di Attrezzature, Reagenti e Fornitori Esterni]]**.

In particolare, mentre ISO 55001/55002 si concentrano sul **portafoglio di beni** (strumentazione analitica), **ISO 41001** (facility management) si concentra sull'**ambiente costruito e i servizi di supporto** (edificio, impianti, spazi) che ospitano tale strumentazione e il core business diagnostico — due framework complementari, entrambi basati sulla struttura Annex SL/HLS e integrabili nello stesso SGQ del laboratorio.
