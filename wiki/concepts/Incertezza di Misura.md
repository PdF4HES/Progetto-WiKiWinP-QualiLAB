---
type: concept
title: "Incertezza di Misura"
created: 2026-06-12
updated: 2026-06-12
tags:
  - laboratorio-medico
  - concept
  - incertezza-di-misura
  - metrologia
status: developing
address: c-000031
complexity: advanced
domain: laboratorio-medico
aliases:
  - "Measurement Uncertainty"
  - "MU"
  - "Incertezza Estesa"
related:
  - "[[ISO 15189]]"
  - "[[Valutazione Esterna di Qualità (VEQ)]]"
  - "[[Controllo di Qualità Interno (CQI)]]"
  - "[[SIPMeL]]"
  - "[[Sistema di Gestione per la Qualità]]"
  - "[[Tracciabilità Metrologica e Taratura]]"
  - "[[SIPMeL Q21 - Taratura, Verifica e Incertezza]]"
  - "[[Troponina Cardiaca ad Alta Sensibilità (hs-cTn)]]"
sources:
  - "[[SIPMeL Q16 - Incertezza di Misura]]"
  - "[[SIPMeL Q21 - Taratura, Verifica e Incertezza]]"
---

## Definizione

L'**incertezza di misura (MU, measurement uncertainty)** è un parametro, associato al risultato di una misurazione, che caratterizza la dispersione dei valori ragionevolmente attribuibili al misurando (secondo il **VIM**, Vocabolario Internazionale di Metrologia). In pratica, indica entro quale intervallo si colloca il "vero" valore di un'analisi con un determinato livello di confidenza. Si esprime come **incertezza standard (u)**, analoga allo scarto tipo, oppure come **incertezza estesa (U)**, ottenuta moltiplicando u per un fattore di copertura k=2, che corrisponde a un intervallo di confidenza di circa il 95%.

## Perché ISO 15189 la richiede

**[[ISO 15189]]** richiede che i laboratori medici stimino l'incertezza di misura per i risultati quantitativi, la riesaminino periodicamente e la mantengano a livelli coerenti con gli obiettivi analitici. Si tratta di un requisito di **competenza metrologica**: conoscere la variabilità intrinseca di un esame è indispensabile per giudicare l'affidabilità dei risultati, per confrontarli con intervalli di riferimento e limiti decisionali clinici, e per dimostrare agli ispettori ACCREDIA la padronanza del processo analitico. A differenza di ISO/IEC 17025, ISO 15189 **esclude** dal calcolo la componente di campionamento e altre forme di "incertezza definizionale" (es. variabilità biologica), che restano informazioni distinte da fornire ai medici utilizzatori.

## Approccio ISO/TS 20914 (top-down)

La norma **ISO/TS 20914:2019**, recepita operativamente da **[[SIPMeL]]** nel documento **[[SIPMeL Q16 - Incertezza di Misura]]**, propone un approccio prevalentemente "**top-down**", basato su dati già disponibili in laboratorio:
- la componente di **precisione** deriva dai dati storici del **controllo di qualità interno (IQC)**, raccolti per un periodo lungo e valutati vicino ai livelli decisionali clinici;
- la componente di **scostamento sistematico (bias)** è normalmente già corretta dal produttore dei calibratori in fase di taratura (tracciabilità ISO 17511); la sola **[[Valutazione Esterna di Qualità (VEQ)]]** non è considerata sufficiente per verificarla, e in caso di dubbio il laboratorio deve stimarla con campioni umani;
- per risultati qualitativi nominali (positivo/negativo), la precisione è espressa come probabilità di positivi (POD%) vicino alla soglia decisionale.

## Uso nell'interpretazione dei risultati

L'incertezza di misura non viene comunicata di routine nel referto, ma è messa a disposizione su richiesta o in situazioni clinicamente rilevanti. Serve a: distinguere una variazione reale del paziente da una variazione analitica (delta check); valutare se un risultato vicino a un **limite decisionale clinico** (vedi **[[Intervalli di Riferimento e Limiti Decisionali]]**) o a un **valore critico** (vedi **[[Valori Critici]]**) sia affidabile; e fornire evidenza oggettiva durante audit interni e visite ispettive, ad esempio tramite la "prova in doppio" (ripetibilità a breve termine).
