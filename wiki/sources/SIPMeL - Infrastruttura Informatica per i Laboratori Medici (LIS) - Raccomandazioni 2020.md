---
type: source
title: "SIPMeL - Infrastruttura Informatica per i Laboratori Medici (LIS) - Raccomandazioni 2020"
created: 2026-06-13
updated: 2026-06-13
tags:
  - laboratorio-medico
  - source
  - guideline
  - informatica
  - lis
  - sipmel
status: developing
address: c-000134
source_type: guideline
year: 2020
authors:
  - "Marco Pradella (Coordinatore)"
  - "Giovanni Casiraghi (Vice Coordinatore)"
  - "Gruppo di Studio Informatica SIPMeL (GdS-I)"
publication: "SIPMeL GdS Informatica - \"Raccomandazioni per la razionalizzazione e la convergenza della informatica di laboratorio nei Servizi Sanitari Regionali\" - documento datato 21 gennaio 2017, pubblicato 2020 (Riv Ital Med Lab)"
related:
  - "[[SIPMeL]]"
  - "[[Sistema Informativo di Laboratorio (LIS)]]"
  - "[[SIPMeL Q18R1 - Gestione Dati e Informazioni]]"
  - "[[ISO 15189]]"
  - "[[Point-of-Care Testing (POCT))]]"
  - "[[SIPMeL - Inclusione POCT (ISO 22870) in ISO 15189]]"
key_claims:
  - "Il documento nasce nel contesto della DGRV (Delibera Giunta Regionale Veneto) n.1785 del 07/11/2016, che richiedeva la razionalizzazione e convergenza dei sistemi informatici di laboratorio nei Servizi Sanitari Regionali verso il Fascicolo Sanitario Elettronico (FSE)."
  - "Definisce un glossario di riferimento per LIS (Laboratory Information System) e LAS (Laboratory Automation System): il LIS gestisce dati clinici/amministrativi del ciclo dell'esame, il LAS gestisce il flusso fisico dei campioni attraverso la strumentazione; il middleware è il livello intermedio che integra LIS, LAS e strumenti analitici (riferimento ISO 12967/HISA per l'architettura dei sistemi informativi sanitari)."
  - "Mappa in dettaglio i requisiti ISO 15189 5.10 'Gestione delle informazioni di laboratorio': 5.10.2 autorità e responsabilità del sistema informativo, 5.10.3 caratteristiche del sistema (validazione/verifica secondo CLSI LIS03-A), gestione pre-esame, post-esame, controllo documenti/non conformità, servizi di consulenza, sicurezza informatica."
  - "Sulla sicurezza informatica, richiama il D.Lgs 196/2003 (artt. 33-34, misure minime di sicurezza), la famiglia di norme ISO/IEC 2700X (in particolare ISO 27799 per l'informatica sanitaria) e le raccomandazioni dettagliate CLSI AUTO11 su gestione password, crittografia, audit trail e comportamento fail-open/fail-closed dei sistemi in caso di guasto."
  - "Descrive il flusso dei risultati dagli strumenti analitici (standard HL7, ASTM, CLSI LIS01-A2/LIS02-A2) e il nuovo profilo IHE LAW (Laboratory Analytical Workflow, febbraio 2016), basato su HL7 2.5.1 con terminologie LOINC, JLAC10 e unità UCUM."
  - "Tratta la sicurezza del documento referto (ISO 17090 e infrastruttura a chiave pubblica PKI per certificati digitali), distinguendo firma digitale (autenticità del documento) da revisione/validazione dei risultati (responsabilità clinica)."
  - "Descrive i requisiti ISO 15189 5.9 per il rilascio dei risultati (allarmi/valori critici, rapporti provvisori e finali, comunicazione verbale, selezione/rilascio automatizzato secondo CLSI AUTO10-A, rapporti modificati con tracciabilità delle revisioni)."
  - "Fornisce due liste estese di criteri (sezioni 6.1 Laboratorio/LIS e 6.2 Anatomia Patologica/AP) per la valutazione delle offerte di mercato in fase di acquisizione/rinnovo di sistemi informatici di laboratorio: installazioni di riferimento, moduli funzionali (chimica/ematologia, microbiologia, banca del sangue, istologia/citologia/AP, interfacce FSE per ADT/order/risultati in PDF/CDA2), supporto LOINC/SNOMED CT, certificazione ISO 27001/27799, costi e tempistiche di implementazione."
---

## Cosa è

Questo documento, elaborato dal **Gruppo di Studio Informatica della SIPMeL (GdS-I)** sotto il coordinamento di **Marco Pradella** (vice coordinatore Giovanni Casiraghi), presenta le **"Raccomandazioni per la razionalizzazione e la convergenza della informatica di laboratorio nei Servizi Sanitari Regionali"**. Il documento (datato 21 gennaio 2017, pubblicato su Riv Ital Med Lab nel 2020) nasce dal contesto specifico della **Delibera della Giunta Regionale del Veneto (DGRV) n. 1785 del 07/11/2016**, che richiedeva ai laboratori medici regionali un percorso di razionalizzazione e convergenza dei propri sistemi informatici verso il **Fascicolo Sanitario Elettronico (FSE)**, ma è formulato come riferimento generale applicabile a qualunque Servizio Sanitario Regionale.

Il documento è organizzato in 7 sezioni: 1. Premessa; 2. Riferimenti normativi; 3. Definizioni; 4. Fascicolo Sanitario Elettronico; 5. Requisiti secondo ISO 15189 (5.1 elementi essenziali, 5.2 flusso operativo); 6. Criteri di massima per la valutazione delle offerte sul mercato; 7. Bibliografia essenziale.

## Glossario LIS, LAS e middleware

Il documento fornisce un **glossario di riferimento** per la terminologia dei sistemi informativi di laboratorio, distinguendo:

- **LIS (Laboratory Information System)**: il sistema informatico che gestisce i dati clinici e amministrativi del ciclo dell'esame (richiesta, accettazione, risultati, referto, dati di controllo qualità).
- **LAS (Laboratory Automation System)**: il sistema che gestisce il flusso fisico dei campioni attraverso le linee di automazione e gli strumenti analitici.
- **Middleware**: il livello software intermedio che integra LIS, LAS e strumenti analitici, gestendo regole di instradamento dei campioni, ripetizioni automatiche, riflessi analitici e controllo qualità in tempo reale. Il documento richiama lo standard architetturale **ISO 12967 (HISA - Health Informatics Service Architecture)** come riferimento per l'integrazione dei sistemi informativi sanitari.

Questo glossario costituisce un riferimento terminologico utile a integrare e precisare la trattazione generale del **[[Sistema Informativo di Laboratorio (LIS)]]**.

## Requisiti ISO 15189 5.10 - Gestione delle informazioni di laboratorio

Il documento offre una mappatura dettagliata, articolo per articolo, dei requisiti **ISO 15189 punto 5.10** (nella numerazione dell'edizione allora vigente, corrispondente a 7.6 nell'edizione 2022):

- **5.10.2 Autorità e responsabilità**: il laboratorio deve definire chi ha l'autorità e la responsabilità sui contenuti dei sistemi informativi, in particolare per modifiche, cancellazioni o sovrascritture di dati registrati.
- **5.10.3 Caratteristiche del sistema**: i sistemi devono essere validati dal fornitore e verificati dal laboratorio prima dell'uso, secondo **CLSI LIS03-A** ("Laboratory Information Systems Validation"); ogni successiva modifica deve essere documentata, autorizzata e validata.
- **Gestione pre-esame** (5.2.1): modulo di richiesta, identificazione del paziente, identificazione del campione tramite codici a barre, trasporto e catena di custodia, accettazione/check-in.
- **Gestione dell'esame** (5.2.2): regole di controllo di qualità integrate nel flusso analitico.
- **Controllo documenti e non conformità, servizi di consulenza, sicurezza informatica**: requisiti trasversali di gestione del sistema informativo.

## Sicurezza informatica

Il documento dedica ampio spazio alla **sicurezza informatica sanitaria**, richiamando:

- Il **D.Lgs 196/2003** (Codice in materia di protezione dei dati personali), artt. 33-34, sulle misure minime di sicurezza per i sistemi informatici che trattano dati sanitari.
- La famiglia di norme **ISO/IEC 2700X** (sistemi di gestione della sicurezza delle informazioni), in particolare **ISO 27799** ("Health informatics — Information security management in health using ISO/IEC 27002"), specifica per il settore sanitario.
- Le raccomandazioni dettagliate di **CLSI AUTO11** ("Laboratory Automation: Communications with Automated Clinical Laboratory Systems, Instruments, Devices, and Information Systems") su gestione delle password, crittografia, registrazione degli audit trail, e comportamento dei sistemi in caso di guasto: distinzione tra modalità **fail-open** (il sistema continua a operare, potenzialmente con perdita di controlli) e **fail-closed** (il sistema si blocca, privilegiando la sicurezza a scapito della continuità operativa).

## Flusso dei risultati e interoperabilità (5.2.3)

Il documento descrive in dettaglio il flusso dei risultati dalla strumentazione analitica al referto finale (sezioni 5.2.3.1-5.2.3.8):

- **5.2.3.1 Flusso dei risultati dagli strumenti**: basato sugli standard **HL7**, **ASTM**, **CLSI LIS01-A2/LIS02-A2**, e sul nuovo profilo **IHE LAW (Laboratory Analytical Workflow)**, pubblicato a febbraio 2016, che utilizza **HL7 versione 2.5.1** con terminologie **LOINC** (codifica degli esami), **JLAC10** (codifica giapponese, citata come riferimento alternativo) e unità di misura **UCUM**.
- **5.2.3.2 Comunicazione dei risultati agli utenti**: requisiti di contenuto del referto secondo ISO 15189 5.8.3 (identificazione univoca dell'esame, del laboratorio, del paziente, del richiedente, data/ora di raccolta, tipo di campione, risultati in unità SI, intervalli di riferimento, interpretazione, identificazione del revisore, numerazione delle pagine).
- **5.2.3.3 Sicurezza del documento con i risultati (ISO 17090 e PKI)**: lo standard ISO non richiede una firma dei referti, ma solo la tracciabilità di revisioni e autorizzazioni. La crescente diffusione di internet ha portato all'adozione dell'**infrastruttura a chiave pubblica (PKI)** e dei **certificati digitali** secondo **ISO 17090** (parti 1-5), per applicazioni come posta elettronica clinica, comunicazioni territorio-ospedale, fatturazione, tele-radiologia, prescrizioni elettroniche. Il documento raccomanda di **non confondere la firma digitale** (che attiene solo all'autenticità del documento) con il processo di revisione/validazione dei risultati, e di valutare attentamente i contesti reali di utilità della PKI in laboratorio, anche in relazione al volume di informazioni scambiate.
- **5.2.3.4 Risultati da laboratorio esterno**: responsabilità del laboratorio ricevente (non di quello esterno) nella trasmissione dei risultati al richiedente, con identificazione chiara del laboratorio esterno e degli autori di eventuali commenti aggiuntivi.
- **5.2.3.5 Rilascio dei risultati**: procedure documentate per la gestione di campioni inadeguati, valori "di allarme" o "critici" (con notifica immediata e registrazione di data/ora/operatore/destinatario), rapporti provvisori sempre seguiti da un rapporto finale, comunicazioni telefoniche tracciate.
- **5.2.3.6 Rilascio anticipato di risultati provvisori**: riferimento alle CAP Checklists (College of American Pathologists) per casi tipici di referto preliminare (es. esami colturali, liquido cefalo-rachidiano, emocolture, bacilli alcol-acido resistenti).
- **5.2.3.7 Selezione e rilascio automatizzati**: secondo ISO 15189 5.9.2 e **CLSI AUTO10-A** ("Autoverification of Clinical Laboratory Test Results"), i criteri di autoverifica devono essere documentati, validati prima dell'uso e verificati dopo ogni modifica al sistema; deve esistere un processo per la rapida sospensione della selezione automatica.
- **5.2.3.8 Rapporti con risultati modificati**: secondo ISO 15189 5.9.3, ogni modifica a un risultato già refertato richiede l'emissione di un nuovo rapporto chiaramente identificato come revisione, con tracciabilità di data, ora e autore della modifica, mantenendo i dati originali.

## Criteri per la valutazione delle offerte di mercato (sezione 6)

Il documento fornisce due liste estese di criteri pratici per la valutazione di offerte commerciali in fase di acquisizione o rinnovo di un sistema informativo di laboratorio:

- **6.1 Laboratorio (LIS)**: criteri relativi a installazioni di riferimento (numero, dimensione, distribuzione geografica), caratteristiche tecniche (linguaggi di programmazione, sistemi operativi, basi di dati, log delle transazioni), certificazione di sicurezza **ISO 27001**/**ISO 27799**, e un'ampia lista di moduli funzionali: chimica clinica ed ematologia, microbiologia, banca del sangue, istologia/citologia/patologia molecolare/citogenetica/citofluorimetria, interfacce FSE (ADT, order placer/filler, risultati in PDF e CDA2), filtro di appropriatezza della richiesta, supporto **LOINC** e **SNOMED CT**, trasmissione dati per sorveglianza epidemiologica e registri tumori, accesso web, identificazione positiva del paziente, disponibilità del codice sorgente.
- **6.2 Anatomia Patologica (AP)**: criteri analoghi specifici per i sistemi di Anatomia Patologica — gestione di istologia/citologia/autopsia, etichettatura di vetrini e cassette con codici a barre, digitalizzazione vocale per macroscopia e diagnosi finale, immagini macro/microscopiche nel referto, calcoli automatici (punteggio Gleason, tabelle Partin), rapporti sinottici, CAP checklists elettroniche per neoplasie, trasmissione automatica al registro tumori.

## Bibliografia essenziale

Il documento riporta una bibliografia di riferimenti propri del coordinatore Marco Pradella sui temi della validazione dei risultati di laboratorio in regime ISO 15189, dell'introduzione del LIS nel laboratorio clinico, della firma digitale del referto e della sicurezza informatica del dato di laboratorio (RIMeL-IJLaM, 2004-2015).

## Rilevanza per il quadro qualità/accreditamento

Questo documento amplia in modo sostanziale la trattazione del concetto **[[Sistema Informativo di Laboratorio (LIS)]]**, fornendo il dettaglio architetturale, terminologico e procedurale (glossario LIS/LAS/middleware, profilo IHE LAW, sicurezza PKI/CLSI AUTO11, criteri di procurement) che integra i requisiti generali **[[ISO 15189]]** già descritti in **[[SIPMeL Q18R1 - Gestione Dati e Informazioni]]**. Il tema della connettività dei dispositivi POCT al LIS, centrale per la governance del **[[Point-of-Care Testing (POCT))]]** e trattato anche in **[[SIPMeL - Inclusione POCT (ISO 22870) in ISO 15189]]**, trova qui un riferimento architetturale più approfondito (profilo IHE LAW, standard HL7/LOINC/UCUM per l'interoperabilità degli strumenti).
