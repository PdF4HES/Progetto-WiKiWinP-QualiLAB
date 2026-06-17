---
type: concept
title: "Falsi Positivi e Falsi Negativi in Diagnostica di Laboratorio"
created: 2026-06-12
updated: 2026-06-12
tags:
  - laboratorio-medico
  - concept
  - falsi-positivi
  - falsi-negativi
  - interferenze-analitiche
status: developing
address: c-000055
complexity: intermediate
domain: laboratorio-medico
aliases:
  - "Interferenze Analitiche"
  - "False Positive e False Negative Results"
  - "FP/FN"
related:
  - "[[Troponina Cardiaca ad Alta Sensibilità (hs-cTn)]]"
  - "[[Fase Preanalitica]]"
  - "[[SIPMeL]]"
  - "[[Gruppo di Studio sui Marcatori Miocardici (GdS MM) SIPMeL]]"
  - "[[Controllo di Qualità Interno (CQI)]]"
  - "[[Validazione e Verifica dei Metodi Analitici]]"
  - "[[ISO 15189]]"
sources:
  - "[[SIPMeL - Falsi Positivi e Falsi Negativi di Troponina - Parte I (Revisione Letteratura)]]"
  - "[[SIPMeL - Falsi Positivi e Falsi Negativi di Troponina - Parte II (Indagine GdS MM)]]"
  - "[[SIPMeL - Falsi Positivi e Falsi Negativi di Troponina - Parte III (Ruolo Industria)]]"
  - "[[SIPMeL - Falsi Positivi e Falsi Negativi di Troponina - Parte IV (Raccomandazioni GdS MM)]]"
---

## Cosa sono

Un **falso positivo (FP)** è un risultato di laboratorio anomalo (es. elevato) in assenza della condizione clinica che dovrebbe causarlo; un **falso negativo (FN)** è un risultato normale/non rilevato nonostante la presenza della condizione clinica. Nella diagnostica di laboratorio, questi termini possono riferirsi a tre livelli distinti — un nodo terminologico spesso fonte di confusione: **specificità clinica** (il test distingue correttamente malati e sani?), **specificità tissutale** (il marcatore è specifico per l'organo/tessuto di interesse?) e **specificità analitica** (il metodo di misura è soggetto a interferenze che alterano il risultato indipendentemente dalla condizione del paziente?). Quest'ultimo livello — le **interferenze analitiche** — è il più direttamente sotto il controllo del laboratorio e il principale oggetto della garanzia di qualità.

## Cause principali di interferenza analitica

Le interferenze analitiche si classificano in base alla fase del processo in cui originano:

- **Cause legate al paziente (pre-analitiche)**: sostanze endogene o esogene che alterano il dosaggio, come **biotina** (interferisce con sistemi streptavidina-biotina usati per amplificare il segnale: FP nei metodi competitivi, FN nei sandwich), **iperbilirubinemia**, **iperlipemia**, **fosfatasi alcalina elevata**, oppure condizioni patologiche del paziente (emolisi in vivo da anemie emolitiche o altre cause).
- **Cause legate al prelievo (pre-analitiche)**: **emolisi in vitro** (rilascio di analiti intracellulari o interferenza spettrofotometrica dell'emoglobina), presenza di **fibrina** residua (intrappolamento dell'analita o legami aspecifici con gli anticorpi del metodo), tipo di provetta/matrice non conforme alle indicazioni del produttore.
- **Cause legate al campione/analita (analitiche)**: **anticorpi eterofili (HA)** e **anti-animale (HAMA)**, **fattore reumatoide**, formazione di **macrocomplessi** (es. macrotroponina) che reagiscono in modo aspecifico con gli anticorpi dei metodi sandwich, **autoanticorpi** contro l'analita stesso o contro componenti del reagente (es. anti-streptavidina).
- **Cause legate a strumento e metodo (analitiche)**: outliers/fliers casuali (micro-coaguli, debris, problemi di pipettaggio), effetto gancio (hook effect) ad alte concentrazioni, carry-over, mancanza di standardizzazione/armonizzazione tra metodi diversi dello stesso analita.

## La troponina come caso di studio

La **[[Troponina Cardiaca ad Alta Sensibilità (hs-cTn)]]** è il caso paradigmatico per studiare questi meccanismi: è un analita ad alto impatto clinico (diagnosi di infarto), misurato a concentrazioni molto basse (quindi sensibile a piccole interferenze) e con soglie decisionali (99° percentile) molto vicine ai limiti analitici dei metodi. I lavori del **[[Gruppo di Studio sui Marcatori Miocardici (GdS MM) SIPMeL]]** sui FP/FN di cTn documentano in modo sistematico l'intero spettro di queste interferenze.

## Implicazioni per la qualità di laboratorio

La gestione delle interferenze richiede misure trasversali ai processi di qualità: criteri di accettabilità dei campioni in **[[Fase Preanalitica]]** (es. rilevazione di emolisi/lipemia/icteria tramite indici sierici), **[[Validazione e Verifica dei Metodi Analitici]]** che includa la verifica delle interferenze dichiarate dal produttore, **[[Controllo di Qualità Interno (CQI)]]** per individuare derive sistematiche, e procedure di **revisione dei risultati** (es. prove di diluizione, conferma con metodo alternativo) per i casi sospetti — tutti elementi richiesti, direttamente o indirettamente, da **[[ISO 15189]]**.

## Le raccomandazioni del GdS MM SIPMeL (Parte IV): cosa fare in pratica

La **[[SIPMeL - Falsi Positivi e Falsi Negativi di Troponina - Parte IV (Raccomandazioni GdS MM)|Parte IV]]** della serie SIPMeL sui FP/FN di troponina rappresenta, ad oggi, il riferimento più operativo per tradurre questi concetti in pratiche di laboratorio. Le **10 Raccomandazioni del GdS MM** (metodo Delphi modificato, criteri NACB/AACC, validate dalla Commissione Qualità SIPMeL) si possono riassumere in tre blocchi di azioni concrete:

**1. Prevenzione (Raccomandazioni 1-3, Classe I / Livello B)**
- Conoscere a fondo le caratteristiche del proprio metodo/strumento: robustezza (% attesa di outlier), matrice raccomandata dal produttore, sensibilità analitica.
- Applicare con rigore le regole di **[[Controllo di Qualità Interno (CQI)]]**: calibrazione e ri-calibrazione lotto-lotto, CQI multilivello (incluso un livello vicino al 99° percentile e al LoD), VEQ e manutenzione programmata, per minimizzare variabilità e outlier ("flyers").
- Rispettare i criteri di accettabilità del campione in **[[Fase Preanalitica]]**, in particolare per emolisi e fibrina, seguendo le linee guida nazionali/europee disponibili.

**2. Interpretazione clinico-laboratoristica (Raccomandazioni 4-6, Classe I-IIa / Livello B-C)**
- Interpretare il valore di cTn tenendo conto delle caratteristiche del soggetto (età, sesso, attività fisica, ritmo circadiano) e della variabilità biologica (reference change value, RCV).
- Valutare sempre il risultato nel contesto della richiesta clinica (sospetta SCA, danno miocardico, prognosi) e nella sua serie temporale, escludendo prima le cause cliniche cardio- e non cardio-vascolari di un valore anomalo, **prima** di ipotizzare un FP/FN analitico.
- Gestire la ricerca dell'interferente **in collaborazione con il clinico**: la qualità del rapporto clinica-laboratorio è determinante per la risoluzione.

**3. Risoluzione del sospetto FP/FN (Raccomandazioni 7-10, Classe I-IIb / Livello C)**
- **Primo passo (Racc. 7)**: ripetere il dosaggio su un nuovo campione, verificando la fase preanalitica e lo stato analitico dello strumento; la ri-centrifugazione è un'opzione rapida ma va validata sul proprio metodo (può causare misclassificazioni con metodi non hs-cTn); se possibile, confermare con un metodo alternativo di cTn (non POCT).
- **Sospetto FP (Racc. 8)**: dopo aver escluso cause pre-analitiche, eseguire in sequenza prove di diluizione, bloccanti per anticorpi eterofili (HBR/HBT), mixing con sieri animali (per HA/HAMA), ricerca del fattore reumatoide e precipitazione con PEG/ultracentrifugazione (per macrotroponina).
- **Sospetto FN (Racc. 9)**: dopo aver escluso cause pre-analitiche, eseguire prove di mixing con sieri umani per evidenziare autoanticorpi anti-cTn.
- **Tracciabilità (Racc. 10)**: registrare **tutti** i casi FP/FN, anche di lieve entità, per misurarne la prevalenza locale, documentare le azioni correttive e comunicarli formalmente al produttore e alla comunità scientifica — un anello spesso mancante ma essenziale per il miglioramento continuo.

Queste raccomandazioni completano il quadro aperto dalla **[[SIPMeL - Falsi Positivi e Falsi Negativi di Troponina - Parte I (Revisione Letteratura)|Parte I]]** (cause da letteratura), dalla **[[SIPMeL - Falsi Positivi e Falsi Negativi di Troponina - Parte II (Indagine GdS MM)|Parte II]]** (scarsa consapevolezza nei laboratori italiani) e dalla **[[SIPMeL - Falsi Positivi e Falsi Negativi di Troponina - Parte III (Ruolo Industria)|Parte III]]** (limiti dell'informazione industriale), fornendo la base per protocolli locali integrati nel sistema di gestione qualità secondo **[[ISO 15189]]**.
