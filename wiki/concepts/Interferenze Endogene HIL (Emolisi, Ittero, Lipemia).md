---
type: concept
title: "Interferenze Endogene HIL (Emolisi, Ittero, Lipemia)"
created: 2026-06-13
updated: 2026-06-13
tags:
  - laboratorio-medico
  - concept
  - interferenze-analitiche
  - fase-preanalitica
  - hil
status: developing
address: c-000092
complexity: intermediate
domain: laboratorio-medico
aliases:
  - "HIL"
  - "Indici del Siero"
  - "Serum Indices"
related:
  - "[[Falsi Positivi e Falsi Negativi in Diagnostica di Laboratorio]]"
  - "[[Controllo di Qualità Interno (CQI)]]"
  - "[[Fase Preanalitica]]"
  - "[[SIPMeL]]"
  - "[[Gruppo di Studio Variabilità Extra-Analitica (GdS VEA) SIPMeL]]"
  - "[[ISO 15189]]"
  - "[[Incertezza di Misura]]"
  - "[[Flebotomia e Prelievo Venoso]]"
sources:
  - "[[SIPMeL - Interferenza da Lipemia]]"
  - "[[SIPMeL - Interferenza da Ittero]]"
  - "[[SIBioC-SIMeL - Campioni Emolizzati e Indice di Emolisi]]"
---

## Cosa sono

**HIL** è l'acronimo di *Hemolysis, Icterus, Lipemia*: le tre principali interferenze endogene che alterano l'aspetto e la composizione del siero/plasma e che possono produrre risultati analitici sistematicamente alterati. Sono accomunate dal fatto di derivare da caratteristiche del campione o del paziente (non da un malfunzionamento dello strumento) e dall'essere oggi rilevabili in modo automatizzato, all'inizio del processo analitico, tramite la misura degli **indici del siero** (H-index, I-index, L-index) su un ampio spettro di lunghezze d'onda dopo diluizione del campione.

## Come si misurano gli indici HIL

Storicamente la rilevazione era **visiva** (ispezione di colore/limpidezza del campione), un metodo dimostrato poco riproducibile tra operatori (k = 0.5-0.7) e poco confrontabile con i metodi automatizzati, oltre a essere impraticabile sui volumi dei laboratori moderni. Il metodo oggi standard è la **determinazione automatica degli indici del siero**, eseguita dagli analizzatori biochimici tramite misure spettrofotometriche multiple su campione diluito: per l'emolisi e l'ittero le lunghezze d'onda utili cadono prevalentemente tra 400-540 nm (picchi a 414 nm per l'emoglobina e 456 nm per la bilirubina), per la lipemia tra 300-700 nm (picco 340 nm). Lo standard di riferimento per definizione, misura e refertazione è il documento **CLSI C56-A** (*Hemolysis, Icterus, and Lipemia/Turbidity Indices as Indicators of Interference*). Un problema trasversale, evidenziato per tutti e tre gli indici, è la **mancata armonizzazione tra produttori**: lambda, diluizioni, espressione dei risultati e soglie decisionali differiscono sensibilmente tra sistemi (Roche, Siemens, Abbott, ecc.), e non esiste una definizione universalmente accettata di "interferenza significativa" - molti adottano ancora il criterio empirico del 10% proposto da Glick et al. 30 anni fa, altri preferiscono le Desirable Specifications for Imprecision (DSI) basate sulla variabilità biologica.

## Meccanismi di interferenza

I tre indici interferiscono con meccanismi parzialmente diversi ma sovrapponibili: **interferenza spettrofotometrica** (l'emoglobina, la bilirubina e le lipoproteine assorbono luce nelle stesse bande utilizzate da molti metodi colorimetrici, turbidimetrici e immunoturbidimetrici/nefelometrici, alterando la lettura del segnale); **interferenza chimica** (componenti del campione reagiscono con i reagenti del metodo, es. la bilirubina con l'intermedio H2O2 nella reazione di Trinder, o sostanze rilasciate dall'emolisi che competono nelle reazioni enzimatiche); ed effetti **fisici/strumentali** (spiazzamento di volume per la lipemia con pseudoiponatriemia, interferenza sui sensori di "campione insufficiente", compartimentazione post-centrifugazione di sostanze idrofobiche). L'effetto può essere positivo o negativo a seconda dell'analita e del sistema metodo-strumento, e talvolta è discordante tra produttori per lo stesso analita.

## Refertazione e gestione del risultato

Le pratiche di refertazione in presenza di indici HIL fuori soglia seguono generalmente tre vie: **diluizione** del campione (per analiti con matrice di diluizione validata e LoQ non clinicamente critico), **cancellazione/sospensione del risultato** (quando l'interferenza è probabile e non gestibile altrimenti), oppure **rilascio con commento standardizzato** (quando il produttore attesta assenza di interferenza fino alla concentrazione testata). Survey internazionali (WG-PRE EFLM, indagini nazionali) mostrano però che queste pratiche sono ancora poco armonizzate e che il **[[Controllo di Qualità Interno (CQI)]]** e la verifica esterna di qualità dedicati agli indici HIL sono implementati solo da una minoranza di laboratori.

## L'emolisi (H-index): la più frequente delle interferenze HIL

L'**emolisi** è di gran lunga la più frequente delle tre interferenze HIL: i campioni emolizzati rappresentano il 40-70% di tutte le non conformità dei campioni biologici, con una prevalenza media intorno al 3% di tutti i campioni di routine (fino a oltre il 10% in pronto soccorso e pediatria). L'**H-index** (indice di emolisi) è misurato spettrofotometricamente (picchi utili a 414, 540 e 570 nm per l'emoglobina libera) e quantifica un fenomeno valutabile anche in termini assoluti: emoglobina libera <300 mg/L (lieve), 300-600 mg/L (modesta), >600 mg/L (elevata). A differenza di ittero e lipemia, l'emolisi è quasi sempre **in vitro**, cioè conseguente a errori nella fase di prelievo, trasporto o trattamento del campione (raramente riflette un'emolisi in vivo/anemia emolitica, distinguibile tramite l'aptoglobina plasmatica). Per questo l'emolisi è il punto di congiunzione più diretto tra le interferenze HIL e la qualità della **[[Flebotomia e Prelievo Venoso|flebotomia]]**: la prevenzione a monte (tecnica di prelievo corretta) è più efficace della sola rilevazione a valle tramite H-index. Questi temi sono trattati in **[[SIBioC-SIMeL - Campioni Emolizzati e Indice di Emolisi]]**.

## Rilevanza per la qualità di laboratorio

Le interferenze HIL sono una delle classi più importanti di cause **pre-analitiche** di **[[Falsi Positivi e Falsi Negativi in Diagnostica di Laboratorio|falsi positivi e falsi negativi]]**: criteri di accettabilità del campione basati su HIL fanno parte dei requisiti della **[[Fase Preanalitica]]** secondo **[[ISO 15189]]**, mentre la sorveglianza sistematica degli indici e la loro inclusione nei criteri di validità del risultato concorrono alla stima dell'**[[Incertezza di Misura]]** e alla validità complessiva dei dati riportati. Il quadro HIL completo (emolisi, ittero, lipemia) è stato sviluppato dal **[[Gruppo di Studio Variabilità Extra-Analitica (GdS VEA) SIPMeL]]** e dal gruppo intersocietario SIBioC-SIMeL-CISMEL che lo ha preceduto, le cui rassegne su lipemia, ittero ed emolisi costituiscono le fonti principali di questa pagina, ora completa.
