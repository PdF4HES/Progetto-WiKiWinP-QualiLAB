---
type: source
title: "SIPMeL Q16 - Incertezza di Misura"
created: 2026-06-12
updated: 2026-06-12
tags:
  - laboratorio-medico
  - source
  - sipmel
  - incertezza-di-misura
status: developing
address: c-000029
source_type: guideline
domain: laboratorio-medico
publisher: "SIPMeL - Commissione Nazionale Qualità ed Accreditamento"
document_code: "Q16"
version: "1.0"
publication_date: "2021-08"
related:
  - "[[ISO 15189]]"
  - "[[SIPMeL]]"
  - "[[Incertezza di Misura]]"
  - "[[Valutazione Esterna di Qualità (VEQ)]]"
sources:
  - "[[.raw/unlocked_SIPMEL - Q16 - Raccomandazioni per la stima dell'incertezza di misura nei laboratori medici (ISO 15189 e ISO 20914).pdf]]"
---

## Cosa è

**Q16** ("Raccomandazioni per la stima dell'incertezza di misura nei laboratori medici - ISO 15189 e ISO 20914", versione 1.0, agosto 2021) è il documento con cui **[[SIPMeL]]**, attraverso la sua Commissione Nazionale Qualità ed Accreditamento (coordinatore Marco Pradella), traduce in indicazioni operative l'applicazione della norma **ISO/TS 20914:2019** ("Practical guidance for the estimation of measurement uncertainty") nel contesto dei requisiti **[[ISO 15189]]** sull'incertezza di misura (MU, measurement uncertainty). Il documento è stato elaborato con il contributo dei Gruppi di Studio Diagnostica Oncologica, Ematologia, Informatica e Malattie Infettive.

## Key claims

- L'incertezza di misura va stimata per tutti i **risultati quantitativi** secondo le modalità di ISO/TS 20914, va riesaminata periodicamente e mantenuta entro livelli accettabili rispetto agli obiettivi analitici; la stima deve essere disponibile su richiesta agli utilizzatori del laboratorio.
- L'incertezza va stimata anche per le **fasi quantitative rilevanti** di esami che producono risultati finali **qualitativi nominali** (es. positivo/negativo), la cui ripetibilità/riproducibilità si valuta con tecniche dedicate (es. CLSI EP12-A2).
- Sul **fronte della taratura**, il processo di fabbricazione dei materiali di calibrazione incorpora già di norma la correzione degli scostamenti sistematici clinicamente significativi; la sola partecipazione alla **VEQ** non è adeguata per verificare lo scostamento sistematico, che va eventualmente stimato su campioni umani.
- Sul **fronte della precisione**, la componente di incertezza deriva dai dati del **controllo di qualità interno (IQC)** raccolti in un periodo lungo, vicino ai livelli decisionali clinici, con verifica della varianza tramite test F rispetto ai campioni umani; per i risultati qualitativi nominali la precisione è la frequenza di positivi (POD%) a livello C95 o C50+20%.
- L'incertezza standard (u) si ottiene dalla radice della varianza; l'**incertezza estesa (U)** si ottiene moltiplicando u per un fattore di copertura k=2 (intervallo ~95%); per misure combinate (es. gap anionico, eGFR) si applicano regole specifiche di propagazione.
- L'incertezza di misura **non viene comunicata di routine** con i risultati, ma è messa a disposizione su richiesta o comunicata quando clinicamente rilevante; i simboli standard sono "u" (incertezza standard) e "U" (incertezza estesa), distinti dal simbolo del materiale "urine".
- Per gli esami con **amplificazione di acidi nucleici** (conformità a ISO 17822), verifica e validazione coprono esattezza, intervallo di risposta, precisione/incertezza, limite di rilevazione, interferenze, robustezza, sensibilità e specificità clinica, con schemi di replicati definiti (es. 2x15 o 3x5 giorni secondo CLSI MM17).
- La **componente di ripetibilità** dell'incertezza è utilizzata come "prova in doppio" (double testing) durante gli audit di parte terza/visite ispettive ACCREDIA, come stress test rapido della stabilità del metodo, interpretata con le statistiche F di Fisher o t di Student.

## Struttura e ambito

Il documento si articola in 6 raccomandazioni numerate: (1) i fondamenti, (2) il fronte della taratura, (3) il fronte della precisione, (4) l'espressione dell'incertezza, (5) il calcolo dell'incertezza, (6) gli esami con amplificazione di acidi nucleici. Esplicitamente, **non** tratta i fondamenti statistici/stocastici delle stime né il dibattito su limiti accettabili di incertezza vs. errore totale accettabile, per i quali rimanda alla letteratura citata (incl. JCGM 100:2008 - GUM).

## Collegamenti

Il documento si inserisce nel quadro più ampio della revisione di **[[ISO 15189]]**, che integra riferimenti a ISO 22870 (POCT), ISO 15190 (sicurezza), ISO 22367 (gestione del rischio) e ISO/TS 20658 (preesame). La componente di precisione dell'incertezza è strettamente legata al controllo di qualità interno e, indirettamente, alla **[[Valutazione Esterna di Qualità (VEQ)]]** (per la verifica dello scostamento sistematico). Vedi **[[Incertezza di Misura]]** per il concetto generale.
