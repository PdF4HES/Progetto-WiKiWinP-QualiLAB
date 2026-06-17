---
type: source
title: "SIPMeL Q19 - Processi di Esame e Validità dei Risultati"
created: 2026-06-12
updated: 2026-06-12
tags:
  - laboratorio-medico
  - source
  - sipmel
  - controllo-qualita
  - validazione-metodi
status: developing
address: c-000034
source_type: guideline
domain: laboratorio-medico
publisher: "SIPMeL - Commissione Nazionale Qualità ed Accreditamento, Gruppo di Studio Informatica e Gruppo di Studio Management Sanitario"
document_code: "Q19"
version: "1.0"
publication_date: "2024-02-27"
related:
  - "[[ISO 15189]]"
  - "[[SIPMeL]]"
  - "[[Incertezza di Misura]]"
  - "[[Validazione e Verifica dei Metodi Analitici]]"
  - "[[Intervalli di Riferimento e Limiti Decisionali]]"
sources:
  - "[[.raw/unlocked_SIPMEL - Q19 Raccomandazioni per Accreditamento ISO 15189 del laboratorio medico. Processi di esame, validità dei risultati degli esami.pdf]]"
---

## Cosa è

**Q19** ("Raccomandazioni per Accreditamento ISO 15189 del laboratorio medico: processi di esame, validità dei risultati degli esami", versione 1.0, approvato dal Consiglio Nazionale SIPMeL il 27/2/2024) è il documento congiunto del **Gruppo di Studio Informatica** (coordinatore Marco Pradella) e del **Gruppo di Studio Management Sanitario** (coordinatore Giovanni Casiraghi) che analizza la clausola **7.3.7 "Garantire la validità dei risultati degli esami"** di **UNI EN ISO 15189:2023** (controllo di qualità interno CQI, valutazione esterna di qualità VEQ, comparabilità dei risultati), aggiorna il precedente documento Q11P1 (basato su ISO 15198) e la collega a **ISO/TS 20914** (incertezza di misura), **ISO 15198**, **CLSI C24** e numerose guide CLSI di settore.

## Key claims

- ISO 15189 7.3.7 richiede una procedura di monitoraggio della validità dei risultati basata su quattro pilastri: **monitoraggio, documentazione, statistica, pianificazione/revisione**. Dopo la pubblicazione di **ISO/TS 20914**, il **controllo di qualità interno (CQI)** assume una terza funzione oltre al monitoraggio: diventa la base per la stima dell'**incertezza di misura**, con la componente di precisione strumentale scorporata da quella dei processi pre- e post-esame (a differenza di ISO 17025).
- Il **controllo di qualità è una responsabilità condivisa** tra fabbricanti di dispositivi IVD e laboratorio (principio ISO 15198): il fabbricante deve fornire informazioni su prestazioni e validare le procedure di CQI quando l'analisi del rischio lo richiede; per i dispositivi IVD esistenti, le procedure statistiche convenzionali (CLSI C24) sono generalmente adeguate.
- I **materiali per il CQI** devono essere selezionati per stabilità, matrice simile ai campioni dei pazienti, comportamento analitico comparabile, concentrazioni vicine ai limiti decisionali clinici e, quando possibile, copertura dell'intervallo di misurazione; la procedura deve evitare il cambio simultaneo di lotto di materiale di controllo e di reagente/calibratore.
- Materiali usati solo in modalità **"passa/non passa"** (prima dell'esame sui campioni dei pazienti) non soddisfano pienamente i requisiti ISO 15189 per il CQI di monitoraggio: si avvicinano più a materiali di taratura/verifica che a veri controlli di qualità, e andrebbero affiancati da altre procedure.
- Per i **risultati qualitativi/nominali**, ISO 15189 (punti 3.8, 3.29, 6.5.1, 6.5.3e) riconosce comunque la necessità di stimare precisione/incertezza tramite concordanza; la **statistica kappa** (CLSI QMS24, Appendice D) è proposta per valutare l'accordo tra metodi/operatori (valori >0,8 = ottimo accordo, 0,6-0,8 = ragionevole).
- La **VEQ (valutazione esterna di qualità)** è obbligatoria per tutti gli esami inclusi i POCT (ISO 15189 7.3.7.3, ISO/IEC 17043), con partecipazione "basata sul rischio" e non passiva; quando un programma VEQ adeguato non è disponibile, ISO 15189 elenca alternative (scambi di campioni, confronti tra laboratori su materiali CQI identici, prove in cieco, materiali di riferimento commutabili, ecc.), tutte da motivare e documentare.
- La **comparabilità dei risultati** (ISO 15189 7.3.7.4) è richiesta quando per un esame si usano metodi/strumenti diversi o sedi diverse; il VIM distingue **comparabilità metrologica** (riconducibilità allo stesso riferimento, taratura tracciabile ISO 17511) da **compatibilità metrologica** (differenza tra risultati entro un multiplo dell'incertezza standard, approcci CLSI EP31/EP09).
- **CLSI EP09** (confronto procedure di misurazione con campioni di pazienti, 40 campioni per il laboratorio vs. 100 per il fabbricante, grafico delle differenze/Bland-Altman) è giudicato dalle precedenti raccomandazioni SIPMeL **meno oneroso** di **CLSI EP31** (verifica comparabilità entro un sistema sanitario), pur mantenendo rigore scientifico.
- Il documento osserva che la terminologia "controlli interni/esterni" è ambigua e propone di sostituirla con "controlli inclusi/non inclusi (aggiunti)"; segnala inoltre la sovrapposizione tra 7.3.7.4 (comparabilità) e 7.3.2 (verifica dei metodi).

## Raccomandazioni operative (sintesi)

Tra le raccomandazioni: applicare il CQI sia ai risultati quantitativi che a quelli qualitativi/nominali derivati da soglie; fare riferimento a ISO 15198 e CLSI C24 (e alle guide CLSI di settore — immunologia I/LA02/23/28, microbiologia M22/27/35/40/58, molecolare MM01/07/09/13/20/22/23, POCT07/08/14) per frequenza e materiali di CQI; estendere VEQ/alternative a tutti gli esami inclusi i POCT, motivando le scelte per consentire la valutazione degli ispettori ACCREDIA; per metodi qualitativi/ordinali, basarsi sulle guide EURACHEM e ISO/TR 27877.
