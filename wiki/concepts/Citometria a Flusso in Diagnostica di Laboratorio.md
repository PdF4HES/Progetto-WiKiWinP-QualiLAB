---
type: concept
title: "Citometria a Flusso in Diagnostica di Laboratorio"
created: 2026-06-12
updated: 2026-06-12
tags:
  - laboratorio-medico
  - concept
  - citometria
  - referto
  - lis
status: developing
address: c-000079
complexity: intermediate
domain: laboratorio-medico
aliases:
  - "Citofluorimetria"
  - "Flow Cytometry"
related:
  - "[[SIPMeL]]"
  - "[[Sistema Informativo di Laboratorio (LIS)]]"
  - "[[ISO 15189]]"
  - "[[SIPMeL Q18R1 - Gestione Dati e Informazioni]]"
sources:
  - "[[SIPMeL - Il Referto Citofluorimetrico]]"
---

## Cosa è

La **citometria a flusso (citofluorimetria)** è una tecnica analitica che misura, su singola cellula, parametri fisici (dimensione, granularità) e di fluorescenza, permettendo l'identificazione e la quantificazione di popolazioni cellulari mediante anticorpi monoclonali coniugati a fluorocromi (immunofenotipizzazione multiparametrica, oggi tipicamente a 6/8/10 colori). È divenuta negli ultimi decenni il **gold standard** per numerose applicazioni di laboratorio in ematologia e immunologia clinica.

## Applicazioni cliniche

Gli ambiti applicativi principali comprendono: la **diagnosi e classificazione delle leucemie acute** (definizione del lineage delle cellule blastiche, complementare alla morfologia); le **sindromi linfoproliferative croniche e i linfomi non-Hodgkin** (definizione della linea B/T/NK e della clonalità nelle linfoproliferazioni B); lo studio della **malattia minima residua** nel follow-up delle leucosi acute, sfruttando il "fenotipo leucemia-associato" identificato alla diagnosi; le **sindromi mielodisplastiche/mieloproliferative**, dove rileva anomalie di espressione antigenica su cellule mieloidi ed eritroidi; la **quantificazione delle sottopopolazioni linfocitarie (T, B, NK)** in percentuale e numero assoluto, fondamentale nella valutazione dei **disordini immunologici** (immunodeficienze primitive e secondarie) e nel monitoraggio delle terapie immunosoppressive; e l'identificazione dei cloni di **emoglobinuria parossistica notturna (EPN)**, per cui rappresenta oggi il metodo di riferimento.

## Standardizzazione del referto

La forte **eterogeneità interpretativa** legata alla soggettività dell'operatore è un problema noto da decenni (Hassett & Parker, 1995) e ancora oggetto di sforzi di armonizzazione a livello internazionale (Consensus Conference di Bethesda 2006, modello Del Vecchio, linee guida ICSH e BCSH). La standardizzazione del referto citofluorimetrico richiede la documentazione esplicita di: tipologia di esame e metodo (es. pannello di anticorpi monoclonali utilizzati), informazioni "operative" sul campione (cellularità, qualità, conta differenziale citometrica), descrizione della **strategia di gating** adottata e un **giudizio interpretativo conclusivo** differenziato per tipologia di indagine — emopatia maligna, immunofenotipo linfocitario nei disordini immunologici, o EPN. È raccomandato non inserire dot plot o immagini strumentali nel referto, conservandoli invece nell'archivio elettronico del laboratorio per eventuale consultazione.

## Integrazione con LIS e requisiti ISO 15189

La progettazione del referto citometrico — pannelli di anticorpi monoclonali, strategie di gating documentate, valori di riferimento per sottopopolazione e per fascia di età, giudizio interpretativo — deve integrarsi nel **[[Sistema Informativo di Laboratorio (LIS)]]**, sia per garantire la **tracciabilità** dei dati grezzi (file FCS, dot plot) sia per la generazione di un referto strutturato, riproducibile e confrontabile tra laboratori. Questo si collega ai requisiti **post-analitici e di refertazione** di **[[ISO 15189]]** (interpretazione dei risultati, comunicazione efficace al clinico) e alla gestione informatica dei dati e della loro conservazione trattata in **[[SIPMeL Q18R1 - Gestione Dati e Informazioni]]**, in particolare per quanto riguarda l'archiviazione a lungo termine dei dati strumentali non riportati nel referto e la conformità alle norme italiane su tracciabilità documentale e firma digitale.
