---
type: source
title: "SIPMeL Q21 - Taratura, Verifica e Incertezza"
created: 2026-06-12
updated: 2026-06-12
tags:
  - laboratorio-medico
  - source
  - sipmel
  - taratura
  - incertezza-di-misura
  - validazione-metodi
status: developing
address: c-000041
source_type: guideline
domain: laboratorio-medico
publisher: "SIPMeL - Commissione Nazionale Qualità ed Accreditamento, Gruppo di Studio Medicina Molecolare e Diagnosi Predittiva"
document_code: "Q21"
version: "Bozza"
publication_date: "2024-02"
related:
  - "[[ISO 15189]]"
  - "[[SIPMeL]]"
  - "[[Incertezza di Misura]]"
  - "[[Gestione di Attrezzature, Reagenti e Fornitori Esterni]]"
  - "[[Validazione e Verifica dei Metodi Analitici]]"
  - "[[Tracciabilità Metrologica e Taratura]]"
sources:
  - "[[.raw/unlocked_SIPMEL - Q21 Raccomandazioni per Accreditamento ISO 15189 del laboratorio medico. Requisiti per taratura, verifica, valutazione dei metodi e incertezza dei risultati.pdf]]"
---

## Cosa è

**Q21** è la Raccomandazione SIPMeL (versione bozza, febbraio 2024) che traduce in pratica i requisiti di **[[ISO 15189]]** sulla **taratura e tracciabilità metrologica delle apparecchiature (clausola 6.5)** insieme ai requisiti di processo della clausola 7.3: verifica dei metodi d'esame (7.3.2), validazione dei metodi (7.3.3), valutazione dell'incertezza di misura (7.3.4) e comparabilità dei risultati (7.3.7.4). Il documento argomenta che, nonostante ISO 15189 collochi la taratura nel capitolo "risorse" (6) e la comparabilità tra i "controlli" (7.3.7), la natura degli argomenti ne raccomanda la gestione congiunta con verifica/validazione/incertezza nello stesso impianto documentale.

## Key claims

- ISO 15189 6.5.2-6.5.3 richiede procedure di taratura (istruzioni del fabbricante, registrazione della tracciabilità metrologica, verifica dell'accuratezza, gestione delle ritarature e dei fattori di correzione) e una **catena documentata e ininterrotta di tarature** che colleghi i risultati al Sistema Internazionale (SI) o a materiali/procedure di riferimento di ordine superiore.
- Per i metodi **senza tracciabilità metrologica** (es. anticorpi eritrocitari, antibiogramma, esami genetici, VES, citometria a flusso, immunoistochimica HER2), l'alternativa raccomandata è la **riproducibilità (concordanza) dimostrata tramite programmi di VEQ**.
- Per gli **esami di genomica** (NGS, sequenziamento), la tracciabilità si stabilisce verso sequenze di riferimento (es. GRCh37/GRCh38, sequenza mitocondriale di Cambridge), seguendo le guide CLSI MM01, MM09, MM17, MM20.
- La **verifica dei metodi d'esame (7.3.2)** deve dimostrare, prima dell'uso clinico, che le prestazioni dichiarate dal produttore sono raggiungibili; va ripetuta se il metodo viene revisionato e va rivista periodicamente, come molti altri requisiti ISO 15189 (programmi di formazione, intervalli di riferimento, accordi con utenti).
- La **valutazione dell'incertezza di misura (7.3.4)** segue ISO/TS 20914 con approccio pragmatico basato sui dati del controllo di qualità interno (CQI); per i risultati qualitativi nominali/ordinali l'incertezza si stima solo in prossimità della soglia decisionale, secondo ISO/TR 27877, ISO/TS 16393 e la Raccomandazione **[[SIPMeL Q16 - Incertezza di Misura|Q16]]**.
- ACCREDIA richiede che la comunicazione dell'incertezza di misura includa livello di fiducia e fattore di copertura (tipicamente k=2, ~95%).
- Per la **comparabilità dei risultati (7.3.7.4)**, il VIM distingue "comparabilità metrologica" (tracciabilità allo stesso riferimento) da "compatibilità metrologica" (differenza tra risultati entro un multiplo dell'incertezza standard); SIPMeL ritiene la guida CLSI EP09 più praticabile di EP31 per il laboratorio, e raccomanda di mantenere la stabilità tramite il CQI piuttosto che con confronti frequenti e onerosi.
- Tra le 26 raccomandazioni finali: taratura, validazione e verifica dei metodi possono essere documentate insieme; i metodi senza tracciabilità metrologica si appoggiano alla VEQ; la certificazione dei materiali di riferimento spetta a laboratori di riferimento accreditati ISO 15195 (distinti dai laboratori di referenza); per la verifica di precisione e scarto sistematico si applica almeno CLSI EP15, per limiti di rilevazione/bianco/quantificazione CLSI EP17.

## Perché è importante

Q21 è il documento SIPMeL che chiude il ciclo "risorse -> metodi -> risultati": collega la gestione dello strumentario (vedi **[[Gestione di Attrezzature, Reagenti e Fornitori Esterni]]**) alla validazione/verifica dei metodi e alla stima dell'incertezza, fornendo ai laboratori italiani un percorso operativo coerente per superare le ambiguità lasciate da ISO 15189 sulla collocazione di questi temi tra i capitoli 6 e 7.
