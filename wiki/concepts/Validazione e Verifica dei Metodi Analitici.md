---
type: concept
title: "Validazione e Verifica dei Metodi Analitici"
created: 2026-06-12
updated: 2026-06-13
tags:
  - corso-15189-2024
  - laboratorio-medico
  - concept
  - validazione-metodi
  - controllo-qualita
status: developing
address: c-000036
complexity: advanced
domain: laboratorio-medico
aliases:
  - "Validazione dei Metodi"
  - "Verifica dei Metodi"
  - "Method Validation and Verification"
related:
  - "[[ISO 15189]]"
  - "[[Incertezza di Misura]]"
  - "[[Controllo di Qualità Interno (CQI)]]"
  - "[[Dispositivi Medico-Diagnostici In Vitro (IVD)]]"
  - "[[SIPMeL]]"
  - "[[SIPMeL Q19 - Processi di Esame e Validità dei Risultati]]"
  - "[[Gestione di Attrezzature, Reagenti e Fornitori Esterni]]"
  - "[[Tracciabilità Metrologica e Taratura]]"
  - "[[SIPMeL Q21 - Taratura, Verifica e Incertezza]]"
  - "[[Point-of-Care Testing (POCT)]]"
  - "[[SIPMeL - Inclusione POCT (ISO 22870) in ISO 15189]]"
  - "[[Troponina Cardiaca ad Alta Sensibilità (hs-cTn)]]"
  - "[[Monitoraggio di Laboratorio degli Anticoagulanti Orali Diretti (DOAC)]]"
  - "[[Confronto di Procedure e Verifica di Confrontabilità (CLSI EP09/EP31)]]"
  - "[[Corso UNI EN ISO 15189_2024 edXV - Novità Edizione 2024 e Note Operative ACCREDIA RT-35]]"
sources:
  - "[[SIPMeL Q19 - Processi di Esame e Validità dei Risultati]]"
  - "[[SIPMeL Q21 - Taratura, Verifica e Incertezza]]"
  - "[[SIPMeL - Inclusione POCT (ISO 22870) in ISO 15189]]"
---

## Definizione e distinzione

Nei laboratori medici, **[[ISO 15189]]** (clausola 7.3 "Processi di esame") distingue concettualmente due attività:

- **Validazione**: confermare, tramite esame ed evidenza oggettiva, che i requisiti per uno specifico uso previsto siano soddisfatti, applicata a metodi **nuovi o non standardizzati** (sviluppati in laboratorio, modificati rispetto a quanto previsto dal fabbricante, o usati al di fuori del campo di applicazione previsto). La validazione richiede la caratterizzazione completa delle prestazioni: precisione, esattezza/bias, intervallo di misura, limiti di rilevazione/quantificazione, interferenze, robustezza.
- **Verifica**: confermare che un metodo **già validato dal fabbricante** (procedura standard, dispositivo medico-diagnostico in vitro con marcatura CE/marchio di conformità) produca, nelle condizioni del laboratorio che lo adotta, le prestazioni dichiarate. La verifica è più limitata della validazione: tipicamente conferma precisione e, dove rilevante, esattezza su un sottoinsieme di prestazioni critiche per l'uso clinico previsto.

## Requisiti ISO 15189 clausola 7.3

La clausola 7.3 collega esplicitamente la verifica/validazione dei metodi alla **garanzia della validità dei risultati** (punto 7.3.7, vedi **[[SIPMeL Q19 - Processi di Esame e Validità dei Risultati]]**): il punto 7.3.1 lettera e) richiede la **rivalutazione periodica** dei metodi, e il punto 7.3.2 ("verifica dei metodi") si collega direttamente alla validità dei risultati prodotti. Le prestazioni stabilite in fase di validazione/verifica (in particolare la **precisione**) costituiscono l'input principale per la stima dell'**[[Incertezza di Misura]]** secondo l'approccio top-down di ISO/TS 20914.

## Controllo di qualità interno (CQI) e revisione dei risultati

Una volta che un metodo è validato/verificato e in uso routinario, ISO 15189 7.3.7.2 richiede una procedura di **controllo di qualità interno (CQI)** per monitorare in modo permanente la validità dei risultati, verificando il raggiungimento della qualità prevista e la pertinenza al processo decisionale clinico. Il CQI:

- utilizza materiali di controllo selezionati per stabilità, matrice simile ai campioni di pazienti e concentrazioni vicine ai limiti decisionali clinici;
- fornisce i dati storici di **precisione** alla base della stima dell'incertezza di misura (ISO/TS 20914);
- deve essere integrato dalla **valutazione esterna di qualità (VEQ)** e, quando richiesto, da verifiche di **comparabilità** tra metodi/strumenti/sedi diverse (ISO 15189 7.3.7.4) — vedi **[[Confronto di Procedure e Verifica di Confrontabilità (CLSI EP09/EP31)]]** per gli strumenti statistici (scatter plot, Bland-Altman, regressione di Deming/Passing-Bablock, test del range CLSI EP31) usati per questa verifica, requisito di ISO 15189 §5.6.4.

Prima del rilascio, i **risultati degli esami** devono essere sottoposti a **revisione**: il CQI fornisce il contesto per giudicare se un risultato è plausibile e affidabile, e l'incertezza di misura permette di valutare se un risultato vicino a un limite decisionale clinico (vedi **[[Intervalli di Riferimento e Limiti Decisionali]]**) o a un valore critico (vedi **[[Valori Critici]]**) richieda approfondimento prima della trasmissione al medico richiedente.

## Scopo di accreditamento fisso vs flessibile

Dal punto di vista ACCREDIA (RT-35 rev.02), la gestione della validazione/verifica dei metodi in-house è legata al tipo di **scopo di accreditamento**: con **scopo fisso**, la mancata presentazione della documentazione di validazione interna per un metodo esclude quell'esame dal campo di accreditamento; con **scopo flessibile**, il laboratorio può introdurre o modificare metodi entro famiglie predefinite mantenendo evidenza interna di validazione, verificabile nelle sorveglianze periodiche. Vedi **[[Corso UNI EN ISO 15189_2024 edXV - Novità Edizione 2024 e Note Operative ACCREDIA RT-35]]** per i dettagli procedurali.

## Collegamento con i dispositivi IVD in-house

La distinzione validazione/verifica ha un risvolto regolatorio diretto: i test **in-house** — dispositivi **[[Dispositivi Medico-Diagnostici In Vitro (IVD)]]** fabbricati e usati esclusivamente all'interno di un'istituzione sanitaria — sono esentati dai requisiti generali dell'**IVDR (Regolamento UE 2017/746)** solo se, ai sensi dell'**art. 5(5)**, il laboratorio è conforme a EN ISO 15189 (o normativa nazionale equivalente in materia di accreditamento). In questi casi la **validazione completa** del metodo secondo i requisiti tecnici di ISO 15189 clausola 7.3 non è solo un requisito di accreditamento, ma il presupposto stesso per l'uso legittimo del dispositivo in-house sotto IVDR.
