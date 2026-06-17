---
type: source
title: "SIPMeL Q18R1 - Gestione Dati e Informazioni"
created: 2026-06-12
updated: 2026-06-12
tags:
  - laboratorio-medico
  - source
  - sipmel
  - sistema-informativo
status: developing
address: c-000033
source_type: guideline
domain: laboratorio-medico
publisher: "SIPMeL - Commissione Nazionale Qualità ed Accreditamento, Gruppo di Studio Informatica"
document_code: "Q18R1"
version: "1.0"
publication_date: "2024-02-27"
related:
  - "[[ISO 15189]]"
  - "[[SIPMeL]]"
  - "[[Sistema Informativo di Laboratorio (LIS)]]"
  - "[[Sistema di Gestione per la Qualità]]"
sources:
  - "[[.raw/unlocked_SIPMEL - Q18R1 informazioni_Raccomandazioni per Accreditamento ISO 15189 del laboratorio medico. Processi della gestione dati e informazioni.pdf]]"
---

## Cosa è

**Q18R1** ("Raccomandazioni per Accreditamento ISO 15189 del laboratorio medico: processi della gestione dati e informazioni", versione 1.0, approvato dal Consiglio Nazionale SIPMeL il 27/2/2024) è il documento del **Gruppo di Studio Informatica** (coordinatore Marco Pradella) che analizza la clausola **7.6 "Controllo della gestione dei dati e delle informazioni"** di **UNI EN ISO 15189:2023**, collegandola alle norme sulla sicurezza informatica (ISO/IEC 27001, 27002, 27799, ISO/IEC 27000), alla gestione del rischio informatico (ISO 22367, punto A.13), alla gestione informatica del consenso (ISO/TS 17975, ISO 17090-1) e alla guida tecnica **CLSI AUTO11** sulla sicurezza informatica dei sistemi IVD.

## Key claims

- ISO 15189 7.6 richiede che il laboratorio abbia **accesso** ai dati e alle informazioni necessari per le attività di laboratorio, ma non necessariamente il **possesso** del sistema informativo: il termine "sistemi informativi di laboratorio" comprende anche dati gestiti su supporti non informatici, e può includere sistemi informatici esterni.
- Per i **rischi** associati ai sistemi informativi computerizzati, ISO 15189 rimanda a **ISO 22367:2020** (Appendice A.13), che copre identificazione/tracciamento di pazienti e personale, trasmissione/visualizzazione corretta delle informazioni, tolleranza ai guasti, integrità dei sistemi intermediari (middleware) e cibersicurezza generale.
- Per i **controlli di sicurezza delle informazioni** (riservatezza, integrità, disponibilità), ISO 15189 rimanda all'Allegato A di **ISO/IEC 27001:2022**, che organizza 93 controlli in quattro categorie: organizzativi (37), sulle persone (8), fisici (14), tecnologici (34); la certificazione ISO 27001 (rilasciata secondo ISO/IEC 17021-1 e ISO/IEC 27006) è indicata come riferimento "ideale" per dimostrare conformità al punto 7.6.1.
- **ISO 15189:2023 punto 7.6.2-7.6.3** richiede che il laboratorio definisca autorità e responsabilità per la gestione dei sistemi informativi (di cui resta responsabile ultimo); i sistemi per raccolta/elaborazione/archiviazione/recupero dei dati devono essere **validati dal fornitore e verificati dal laboratorio** prima dell'introduzione, e ogni modifica (incl. configurazione software) deve essere autorizzata, documentata e validata prima dell'attuazione. Il software commerciale d'uso generale (word processor, fogli di calcolo) può considerarsi sufficientemente validato.
- La **gestione del consenso informato** (ISO 15189 7.2.4.3) può essere "dedotta" per le procedure ordinarie (es. prelievo venoso); procedure invasive richiedono consenso più esplicito; il documento segnala il progetto UNINFO sulla gestione informatica del consenso, basato su ISO/TS 17975.
- La **firma digitale** (infrastruttura PKI, ISO 17090) non ha ruolo nella sicurezza informatica in senso stretto: garantisce solo l'autenticazione della firma, non impedisce l'accesso ai dati; ISO 15189 non richiede la firma dei documenti ma l'individuazione degli autori di ciascun intervento (anche tramite sistema automatico).
- **ISO 15189:2023 punto 7.6.4-7.6.5** richiede piani per mantenere le operazioni durante guasti/inattività dei sistemi informativi (ridondanza, fault tolerance, piani di contingenza anche su supporto cartaceo) e, per la gestione fuori sede/in cloud, che il fornitore esterno si conformi a tutti i requisiti applicabili — da inserire nei capitolati/contratti.
- Il documento raccomanda l'uso della guida **CLSI AUTO11** (sicurezza informatica di strumenti IVD e sistemi informatici, distinta per fabbricanti MDM, utenti e direzione informatica HDO) come riferimento operativo mancante in ISO 15189, inclusa la procedura di accesso di emergenza ai sistemi IVD critici durante un disastro.

## Conclusioni e raccomandazioni

Il documento conclude che la clausola 7.6 di ISO 15189, pur coerente con le direttive ISO di riduzione dei requisiti prescrittivi, risulta povera di collegamenti operativi; raccomanda quindi ai laboratori di: certificare formalmente il sistema informativo secondo ISO 27001; estendere la sicurezza informatica a tutto il processo d'esame (compreso il middleware) e non solo ai risultati; garantire continuità di responsabilità anche durante manutenzioni/modifiche, fissando regole nei contratti; adottare CLSI AUTO11 come riferimento operativo; regolamentare strettamente nei contratti la gestione informatica fuori sede e in cloud.
