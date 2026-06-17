---
type: concept
title: "Terminologia e Tipologie di Manutenzione (UNI 13306)"
created: 2026-06-13
updated: 2026-06-13
tags:
  - laboratorio-medico
  - concept
  - manutenzione
  - terminologia
  - attrezzature
status: developing
address: c-000172
complexity: intermediate
domain: laboratorio-medico
aliases:
  - "Terminologia della Manutenzione"
  - "Tipi di Manutenzione"
  - "Manutenzione Ordinaria e Straordinaria"
related:
  - "[[UNI EN 13306-2018 - Manutenzione Terminologia]]"
  - "[[UNI 10147-2013 - Manutenzione Termini Aggiuntivi]]"
  - "[[UNI 11063-2017 - Manutenzione Ordinaria e Straordinaria]]"
  - "[[UNI 10366-2007 - Criteri di Progettazione della Manutenzione]]"
  - "[[UNI 10685-2007 - Criteri per Contratti di Manutenzione Global Service]]"
  - "[[UNI EN 15341-2019 - Indicatori di Prestazione della Manutenzione (KPI)]]"
  - "[[Gestione degli Asset e Apparecchiature di Laboratorio (ISO 55001)]]"
  - "[[Facility Management (ISO 41001)]]"
  - "[[Gestione di Attrezzature, Reagenti e Fornitori Esterni]]"
  - "[[Tracciabilità Metrologica e Taratura]]"
  - "[[ISO 15189]]"
sources:
  - "[[UNI EN 13306-2018 - Manutenzione Terminologia]]"
  - "[[UNI 10147-2013 - Manutenzione Termini Aggiuntivi]]"
  - "[[UNI 11063-2017 - Manutenzione Ordinaria e Straordinaria]]"
  - "[[UNI 10366-2007 - Criteri di Progettazione della Manutenzione]]"
  - "[[UNI 10685-2007 - Criteri per Contratti di Manutenzione Global Service]]"
  - "[[UNI EN 15341-2019 - Indicatori di Prestazione della Manutenzione (KPI)]]"
---

## Definizione

Questo concetto sintetizza il **vocabolario condiviso della manutenzione** definito dalla trilogia **[[UNI EN 13306-2018 - Manutenzione Terminologia|UNI EN 13306]]** (norma europea fondamentale), **[[UNI 10147-2013 - Manutenzione Termini Aggiuntivi|UNI 10147]]** (termini aggiuntivi italiani) e **[[UNI 11063-2017 - Manutenzione Ordinaria e Straordinaria|UNI 11063]]** (classificazione ordinaria/straordinaria a fini di budget e contratti), e lo **completa** con i criteri operativi di:
- **[[UNI 10366-2007 - Criteri di Progettazione della Manutenzione|UNI 10366]]** - come scegliere la politica manutentiva più adeguata per ogni bene;
- **[[UNI 10685-2007 - Criteri per Contratti di Manutenzione Global Service|UNI 10685]]** - come strutturare un contratto di manutenzione "global service" basato sui risultati;
- **[[UNI EN 15341-2019 - Indicatori di Prestazione della Manutenzione (KPI)|UNI EN 15341]]** - come misurare, con KPI, le prestazioni della manutenzione (disponibilità, MTBF/MTTR, costi).

Costituisce la **base lessicale e metodologica comune** per discutere di manutenzione delle apparecchiature di laboratorio, degli impianti e delle infrastrutture, in coerenza con il framework strategico di **[[Gestione degli Asset e Apparecchiature di Laboratorio (ISO 55001)]]** e con i requisiti operativi di ISO 15189 6.4.5 descritti in **[[Gestione di Attrezzature, Reagenti e Fornitori Esterni]]**.

## Manutenzione: definizione e obiettivi

La **manutenzione** (UNI EN 13306, 2.1) è la "combinazione di tutte le azioni tecniche, amministrative e gestionali, durante il ciclo di vita di un'entità, destinate a mantenerla o riportarla in uno stato in cui possa eseguire la funzione richiesta". Non si limita ad azioni tecniche: include pianificazione, gestione documentale, logistica.

Gli **obiettivi della manutenzione** (2.3) tipicamente comprendono disponibilità, riduzione dei costi, qualità del prodotto/servizio, salvaguardia dell'ambiente, sicurezza, durata di vita utile, salvaguardia del valore dei beni - obiettivi che, per il laboratorio clinico, si traducono direttamente in **continuità del servizio diagnostico** e **qualità analitica**.

UNI 11063 ribadisce tre **finalità fondamentali** della manutenzione di un bene fisico (nel rispetto di salute/sicurezza/ambiente): mantenere la disponibilità delle caratteristiche funzionali richieste, mantenere l'integrità fisica, allungare la vita utile del bene.

## Le tre proprietà della "fidatezza": affidabilità, manutenibilità, disponibilità

La **fidatezza** (dependability, 2.7) è il termine collettivo per le caratteristiche qualitative correlate al tempo di un'entità, e comprende:

- **Affidabilità (4.1)**: attitudine di un'entità a svolgere una funzione richiesta in date condizioni durante un intervallo di tempo stabilito. Si distinguono affidabilità intrinseca/inerente (determinata da progettazione e fabbricazione, ipotizzando solo manutenzione ordinaria), affidabilità prevista (con manutenzione preventiva pianificata) e affidabilità del funzionamento (effettiva, considerando condizioni reali d'uso).
- **Manutenibilità (4.5)**: attitudine di un'entità a essere mantenuta o ripristinata in uno stato funzionale, quando la manutenzione è effettuata in date condizioni con procedure e risorse prescritte.
- **Disponibilità (4.7)**: attitudine di un'entità a essere in uno stato atto a funzionare come e quando richiesto, in determinate condizioni, presupponendo le risorse esterne necessarie. Si quantifica come **disponibilità basata sul tempo (4.9)**, calcolabile con diversi rapporti (UT/(UT+DT), OT/(OT+TTR), OT/(OT+DT)) a seconda di cosa si vuole misurare (disponibilità complessiva, esclusione di fermi non dovuti a guasti, ecc.).

Queste tre proprietà, insieme al supporto logistico di manutenzione, determinano la **fidatezza** complessiva di un'entità - per un analizzatore di laboratorio, la combinazione di queste tre dimensioni determina la sua idoneità a garantire continuità del servizio diagnostico, ed è il sostrato concettuale degli **obiettivi di disponibilità e affidabilità degli analizzatori** già menzionati nel SAMP (si veda **[[Gestione degli Asset e Apparecchiature di Laboratorio (ISO 55001)]]**).

## Tipologie di manutenzione (politiche manutentive)

La norma distingue le politiche manutentive in base al momento e al criterio di intervento:

### Manutenzione preventiva e le sue sotto-tipologie
**Manutenzione preventiva (7.1)**: eseguita per valutare e/o mitigare il degrado e ridurre la probabilità di guasto, **prima** che si verifichi.

- **Manutenzione ciclica (predeterminata, 7.2)**: a intervalli di tempo o unità d'uso stabiliti, **senza** indagine preliminare sulle condizioni dell'entità (es. sostituzione programmata di un componente ogni N ore di utilizzo, indipendentemente dal suo stato effettivo).
- **Manutenzione secondo condizione (7.3)**: preventiva basata sulla valutazione delle condizioni fisiche reali (osservazione, ispezione, collaudo, monitoraggio dei parametri), seguita dalle azioni conseguenti.
- **Manutenzione predittiva (7.4)**: un caso specifico di manutenzione secondo condizione, basata su **previsioni** derivate da analisi ripetute o da caratteristiche note del degrado dell'entità (es. analisi di trend dei parametri di un analizzatore per prevedere il guasto di un componente prima che si manifesti).

### Manutenzione correttiva
**Manutenzione correttiva/a guasto (7.9)**: eseguita **dopo** la rilevazione di un'avaria, per ripristinare la funzione richiesta. Si distingue in:
- **Differita (7.10)**: non eseguita immediatamente, posticipata secondo regole definite.
- **D'urgenza/immediata (7.11)**: eseguita senza indugio per evitare conseguenze inaccettabili.

### Altre tipologie operative rilevanti
- **Manutenzione di routine (8.5)**: attività regolari ed elementari (pulizia, serraggio, sostituzione connettori, controllo livelli, lubrificazione) - spesso eseguite dal personale operativo come **automanutenzione (7.17)**.
- **Manutenzione migliorativa (UNI 10147, 7.4)**: azioni di miglioramento o piccola modifica che **non** incrementano il valore patrimoniale del bene - distinta dalla "modifica" (7.7, UNI EN 13306) che cambia funzioni dell'entità, e dalla "modernizzazione" (7.8).
- **Manutenzione opportunistica (7.13)**: preventiva o correttiva differita eseguita senza programmazione, in concomitanza con altre attività, per ridurre costi/indisponibilità.
- **Manutenzione eccezionale (8.13)**: preventiva infrequente con impatto significativo sui costi di ciclo di vita (grandi revisioni, pianificate o impreviste) - contabilizzata come investimento di capitale, talvolta detta "investimento di sostituzione".
- **Esternalizzazione della manutenzione (7.19)**: appalto totale o parziale delle attività di manutenzione per un periodo definito - rilevante per i **contratti di assistenza** con i fornitori di strumentazione (collegamento con **[[Gestione di Attrezzature, Reagenti e Fornitori Esterni]]** e con ISO 41012 trattata in **[[Facility Management (ISO 41001)]]**).

## La distinzione ordinaria/straordinaria (UNI 11063): una classificazione contabile, non una politica manutentiva

UNI 11063 introduce un asse di classificazione **ortogonale** rispetto alle politiche manutentive sopra descritte: la distinzione tra **manutenzione ordinaria** e **straordinaria** non descrive *come* viene eseguita la manutenzione (preventiva, correttiva, ecc.) ma **a quale categoria di spesa/budget** appartiene un intervento - rilevante soprattutto per la contabilità industriale e per la **contrattualistica** (in particolare i contratti "global service").

- **Manutenzione ordinaria (4.1)**: interventi (di qualunque politica - correttiva, preventiva, migliorativa) che mantengono integrità, caratteristiche funzionali e disponibilità del bene, contrastano il normale degrado, assicurano la vita utile, **senza modificare** caratteristiche originarie, struttura essenziale o destinazione d'uso. Costi previsti nel budget annuale e attribuiti a centri di costo/commesse correnti.
- **Manutenzione straordinaria (4.2)**: interventi **non ricorrenti e di elevato costo** (rispetto al valore di rimpiazzo e ai costi ordinari) che producono **futuri benefici economici** misurabili - riduzione tempi di produzione, miglioramento qualità, incremento capacità, maggiore sicurezza/sostenibilità. Possono prolungare la vita utile e migliorare affidabilità/manutenibilità/efficienza, **senza** modificare caratteristiche originarie o destinazione d'uso (salvo eccezioni settoriali/normative). Il costo può essere imputato a conto economico o **capitalizzato** (iscritto nel libro dei cespiti) se incrementa il valore patrimoniale del bene.

Gli interventi dovuti a **obsolescenza tecnico-economico-funzionale** (ammodernamenti, adeguamenti normativi, potenziamenti, ampliamenti) sono considerati di carattere "eccezionale", non perseguono le finalità fondamentali della manutenzione e vanno trattati come **progetti di investimento** (conto capitale).

### Applicazione al laboratorio clinico

Questa distinzione si traduce concretamente nella pianificazione finanziaria del parco strumenti analitici:

- la **manutenzione ordinaria** (preventiva ciclica/secondo condizione, correttiva a guasto, piccoli interventi migliorativi senza incremento patrimoniale) rientra nel **budget operativo annuale** e tipicamente nei contratti di assistenza/service standard - si collega al monitoraggio degli **indicatori di disponibilità** richiamati in **[[Gestione degli Asset e Apparecchiature di Laboratorio (ISO 55001)]]**;
- la **manutenzione straordinaria** (sostituzione di componenti strutturali rilevanti, retrofit tecnologico, adeguamenti normativi significativi) costituisce **investimento di capitale**, da inserire nel **piano strategico dei beni (SAMP)** e nei piani di rinnovo/sostituzione del parco strumenti (capital replacement planning);
- nei **contratti di global service o di facility management esternalizzato**, la definizione contrattuale del confine ordinaria/straordinaria determina il **confine di responsabilità tecnica ed economica** tra laboratorio (demand organization) e fornitore/provider (collegamento con ISO 41012, si veda **[[Facility Management (ISO 41001)]]**).

## Entità, ciclo di vita e parti di ricambio

UNI EN 13306 definisce **entità/elemento/bene (3.1)** in modo generico (parte, componente, dispositivo, sottosistema, unità funzionale, attrezzatura o sistema descrivibile e considerabile individualmente) e **bene fisico/cespite (3.2)** come entità con valore potenziale o effettivo per un'organizzazione (componenti, macchine, impianti, edifici, infrastrutture). Il **ciclo di vita (4.18)** comprende tipicamente acquisizione, funzionamento, manutenzione, modernizzazione, dismissione/smaltimento - lo stesso framework concettuale del ciclo di vita degli asset trattato da ISO 55001/55002.

Le **parti di ricambio (3.5)** e **parti di ricambio di sicurezza (3.6)** - quelle la cui indisponibilità comporterebbe un tempo di indisponibilità inaccettabile - sono ulteriormente classificate da UNI 10147 (ricambi generici/specifici, scorte, punto di riordino, lotto economico) e si collegano alla gestione dei materiali per la manutenzione delle apparecchiature analitiche.

## Documentazione e governo della manutenzione

UNI 10147 introduce termini organizzativi e documentali utili per strutturare il governo della manutenzione:

- **Scheda macchina (12.10)** e **diario di macchina (12.1)**: documentazione tecnica/storica dell'entità - analoghe al **registro per singola apparecchiatura** richiesto da ISO 15189 6.4.7 (identificazione, dati fabbricante, date di collaudo/messa in servizio, evidenze di conformità, programma di manutenzione, certificati di taratura, stato attuale).
- **Ordine di lavoro (OdL, 12.5)** e **richiesta di lavoro (RdL, 12.8)**: documenti operativi base del flusso di manutenzione, gestiti tramite **sistema informativo di manutenzione (SIM, 10.7)**.
- **Programma di manutenzione (8.15 UNI EN 13306; 10.4 UNI 10147)**: piano che dettaglia quando deve essere eseguita una specifica attività - corrisponde al "programma di manutenzione" richiesto da ISO 15189 6.4.5 basato sulle istruzioni del produttore.
- **Sistema di manutenzione (12.12)**: struttura organizzativa, responsabilità, risorse, processi e procedure per attuare la strategia di manutenzione.

## Collegamento con ISO 15189 6.4.5 e con la tracciabilità metrologica

I requisiti di ISO 15189 6.4.5 (programmi di manutenzione preventiva basati sulle istruzioni del produttore, registrazione delle deviazioni, messa fuori servizio delle apparecchiature difettose) trovano nella terminologia di questo cluster il **linguaggio tecnico preciso** per essere formalizzati: "manutenzione preventiva ciclica" per gli interventi a calendario/utilizzo, "manutenzione secondo condizione/predittiva" per gli interventi basati su monitoraggio, "manutenzione correttiva (differita/d'urgenza)" per la gestione dei guasti, con relativa documentazione (scheda macchina, OdL/RdL) e classificazione di budget (ordinaria/straordinaria).

Resta distinta, ma collegata, la **[[Tracciabilità Metrologica e Taratura]]**: la taratura non è di per sé un'attività di manutenzione nel senso di UNI EN 13306 (non mira a "mantenere o riportare l'entità in uno stato in cui possa eseguire la funzione richiesta" per il guasto, ma a verificarne/garantirne la riferibilità metrologica), ma è frequentemente **programmata insieme alla manutenzione preventiva** e ne condivide gli strumenti documentali (registro, programma, scheda macchina).

## Progettazione della manutenzione: scelta delle politiche in base alla criticità (UNI 10366)

**[[UNI 10366-2007 - Criteri di Progettazione della Manutenzione|UNI 10366]]** fornisce il **metodo sistematico** per tradurre le tipologie manutentive sopra descritte in una **politica aziendale di manutenzione** concreta, applicata bene per bene. Il processo si articola in tre fasi:

1. **Selezione dei beni** (5.2): in base a criteri di sicurezza (vincolanti) e a un diagramma **costo di sostituzione (X) / manutenibilità (Y)** a quattro quadranti:
   - basso costo + bassa manutenibilità -> **non conviene manutenere** (sostituire a guasto);
   - basso costo + alta manutenibilità -> scelta tra manutenere/sostituire in base alla convenienza economica;
   - alto costo + alta manutenibilità -> **conviene manutenere**;
   - alto costo + bassa manutenibilità -> occorre **migliorare la manutenibilità** (interventi migliorativi o attrezzature dedicate).
2. **Individuazione dei beni critici** (5.3.2): un **bene critico/entità critica** (3.1) è quello che per vincoli tecnici, economici o legislativi (sicurezza, ambiente, produzione, qualità) richiede piani di manutenzione, cure e interventi adeguati. Gli elementi discriminanti, in ordine di priorità, sono: sicurezza delle persone, effetti ambientali, disposizioni legislative su controlli/collaudi, disponibilità richiesta dai piani di produzione/servizio, ridondanza, flessibilità della struttura, effetti su qualità del prodotto/servizio, effetti sul danneggiamento/indisponibilità del bene. I **beni non critici** vengono assegnati direttamente a una tipologia d'intervento (a guasto, preventiva ciclica, secondo condizione/predittiva, migliorativa); i **beni critici** richiedono un'analisi ulteriore.
3. **Analisi guasti, effetti e criticità sui beni critici** (5.3.3): analisi di tipo FMECA - scomposizione del bene in parti funzionali/componenti, identificazione dei modi di guasto, frequenza e durata, effetti su quantità/qualità, attribuzione di un **indice di criticità del guasto** (basato su frequenza, durata del disservizio, gravità delle conseguenze su produzione/scarti/qualità/sicurezza/ambiente) usato per definire **priorità** di intervento (non valori assoluti). Per i beni critici si privilegiano le politiche **preventive secondo condizione/predittive** rispetto alla manutenzione a guasto.
4. **Valutazione economica** (5.3.4): tramite Analisi Costi-Efficacia (ACE) o Costi-Benefici (ACB), confrontando il **costo globale di manutenzione** (costo proprio + costi indotti dal guasto, incluso il **costo d'indisponibilità**, 3.2) delle diverse politiche, nell'ottica della "manutenzione produttiva" (sinergia manutenzione/produzione, obiettivo "zero guasti, zero difetti").

### Applicazione al laboratorio clinico

Per il parco analitico di un laboratorio, questo metodo si traduce in:
- classificare gli **analizzatori core** (turni 24/7, assenza di ridondanza, alto impatto su TAT e continuità diagnostica) come **beni critici**, sottoponendoli ad analisi dei modi di guasto e privilegiando politiche **secondo condizione/predittive** (collegandosi alla manutenzione predittiva già descritta in questo concetto, sez. "Manutenzione preventiva e le sue sotto-tipologie");
- valutare strumenti **ridondanti o a basso costo di sostituzione** come **non critici**, gestibili anche a guasto o con preventiva ciclica semplice;
- usare il diagramma costo di sostituzione/manutenibilità per supportare le decisioni "manutenere vs. sostituire" nel **piano di rinnovo del parco strumenti** (capital replacement planning), in coerenza con il **SAMP** di **[[Gestione degli Asset e Apparecchiature di Laboratorio (ISO 55001)]]**.

## Contratti di manutenzione "global service" basati sui risultati (UNI 10685)

**[[UNI 10685-2007 - Criteri per Contratti di Manutenzione Global Service|UNI 10685]]** definisce i criteri per un **contratto di manutenzione basato sui risultati**, detto **"global service di manutenzione"** (3.3): un contratto riferito a una pluralità di servizi sostitutivi delle normali attività di manutenzione, in cui l'**assuntore** (fornitore) assume **piena responsabilità sui risultati** - non sulle ore o sugli interventi eseguiti.

Elementi chiave del modello contrattuale:
- il **capitolato tecnico** (3.2) descrive i beni, il **valore di disponibilità richiesto** (a produrre/erogare il servizio) e lo **stato di conservazione richiesto**, con criteri, metodologie, indici di misura e calendario delle verifiche per entrambi;
- il **progetto del global service di manutenzione** (3.5), presentato dall'assuntore, descrive le **politiche** e i **piani di manutenzione** che intende applicare (collegandosi direttamente alle tipologie manutentive e ai criteri di progettazione di UNI 10366) e l'organizzazione che intende darsi;
- il **compenso** è fisso il primo anno e può variare per **forme incentivanti (bonus)** in caso di superamento della disponibilità richiesta, **penali** per il mancato raggiungimento di disponibilità o stato di conservazione, e variazioni quantitative/qualitative dei beni o dei piani;
- l'**oggetto/obiettivo** del contratto (21.1) prevede sempre una combinazione di: ridurre i costi di manutenzione mantenendo disponibilità e stato di conservazione richiesti, oppure migliorarli a parità di costo.

### Collegamento con la classificazione ordinaria/straordinaria e con il facility management

Il **capitolato tecnico** del global service è il luogo in cui si formalizza concretamente la **distinzione ordinaria/straordinaria (UNI 11063)** descritta in questo concetto: definisce quali interventi rientrano nel compenso forfettario (manutenzione ordinaria) e quali sono regolamentati separatamente (manutenzione straordinaria, eventi imprevedibili da difetti occulti, adeguamenti normativi). Questo determina il **confine di responsabilità tecnica ed economica** tra laboratorio (committente) e fornitore (assuntore).

UNI 10685 è l'**analogo manutenzione-specifico** dei contratti di approvvigionamento strategico trattati da **ISO 41012** per il facility management (si veda **[[Facility Management (ISO 41001)]]**): mentre ISO 41012 fornisce il framework generale per SLA e accordi FM, UNI 10685 specifica come strutturare contrattualmente la **manutenzione delle apparecchiature/impianti** quando esternalizzata in modalità "global service" (richiamata anche da UNI EN 13306, 7.19 - "esternalizzazione della manutenzione").

## Indicatori di prestazione della manutenzione - KPI (UNI EN 15341)

**[[UNI EN 15341-2019 - Indicatori di Prestazione della Manutenzione (KPI)|UNI EN 15341]]** fornisce il **sistema di indicatori quantitativi (KPI)** per misurare le prestazioni della manutenzione, organizzati in 8 gruppi (Physical Asset Management, le 6 sotto-funzioni della manutenzione, ICT/Enabling Technologies). Per il laboratorio, i KPI più rilevanti rendono **operativi** i concetti di fidatezza già introdotti in questo documento:

- **Disponibilità (UNI EN 13306, 4.7-4.9)** -> calcolata operativamente da:
  - **M10 - Disponibilità basata sul tempo (%)**: tempo di funzionamento conseguito / tempo richiesto;
  - **M11 - Disponibilità basata sul tempo operativo (%)**: tempo operativo (OT) / tempo operativo richiesto;
  - **M12 - Disponibilità basata sul tempo di ripristino**: OT / (OT + TTR), dove il **TTR (Time To Restoration)** include tempo attivo di riparazione, ritardi e tempi di ripristino - corrispondente al rapporto OT/(OT+TTR) già menzionato in questo concetto;
  - **PHA8 - Disponibilità operativa dovuta alla manutenzione (%)**: tempo operativo totale / (tempo operativo totale + downtime per guasti e manutenzione preventiva);
  - **PHA6 - Total Equipment Effectiveness (T.E.E./O.E.E.)** = R1 (maintenance effectiveness/disponibilità) x R2 (manufacturing effectiveness) x R3 (quality effectiveness).
- **MTBF, MTTR, tasso di guasto**: richiamati esplicitamente da UNI 10366 (cap. 10) come "informazioni di ritorno" tecniche per la verifica e riprogettazione del piano di manutenzione, e operazionalizzati dagli indicatori M10-M12/PHA8 sopra descritti (basati sui medesimi tempi di funzionamento/riparazione che definiscono MTBF e MTTR).
- **Costi di manutenzione**:
  - **PHA13 - Costo medio di manutenzione per ora di disponibilità operativa (Euro/ora)**;
  - **PHA14 - Costo annuo di manutenzione su costo totale del ciclo di vita annuo (%)**;
  - **PHA17 - Impatto del costo di manutenzione sul fatturato annuo (%)**;
  - **M17 - Contributo del costo totale di manutenzione sulla capacità tecnica (Euro/unità di output)** - il "costo totale di manutenzione" (M15) corrisponde concettualmente al **costo globale di manutenzione** di UNI 10366.
- **Esternalizzazione**: **M9 - Grado di esternalizzazione (%)** (ore-uomo esternalizzate / ore-uomo totali) e il **modello di maturità M1** (livello 5 = "Tecnologica/Computerizzata", che include esplicitamente il **global service** come modello organizzativo avanzato) collegano direttamente gli indicatori di prestazione ai contratti di **[[UNI 10685-2007 - Criteri per Contratti di Manutenzione Global Service|UNI 10685]]**: gli stessi KPI di disponibilità e costo che misurano la performance interna sono quelli usati per **misurare contrattualmente** i risultati pattuiti in un global service.

### Applicazione al laboratorio clinico

Questi KPI forniscono al laboratorio gli strumenti per:
- **monitorare la disponibilità degli analizzatori critici** (identificati con il metodo UNI 10366) con M10-M12/PHA8, fornendo evidenza oggettiva per gli **indicatori di disponibilità e affidabilità** già richiamati nel SAMP (**[[Gestione degli Asset e Apparecchiature di Laboratorio (ISO 55001)]]**);
- **valutare le prestazioni di un contratto global service** (UNI 10685) verificando il raggiungimento dei livelli di disponibilità e stato di conservazione pattuiti nel capitolato tecnico, con conseguente attivazione di bonus/penali;
- **confrontare (benchmark)** le prestazioni di manutenzione del parco strumenti tra periodi, sedi o fornitori, supportando le decisioni di rinnovo/sostituzione e di scelta tra manutenzione interna ed esternalizzata.

## Quadro completo del cluster 12 (terminologia, progettazione, contratti, KPI)

Con questo lotto si completa il quadro della manutenzione per il facility/asset management di laboratorio: la **terminologia comune** (UNI EN 13306, UNI 10147, UNI 11063) fornisce il linguaggio; **UNI 10366** fornisce il metodo per **scegliere** le politiche manutentive in base alla criticità; **UNI 10685** fornisce il modello per **esternalizzare** la manutenzione tramite contratti basati sui risultati; **UNI EN 15341** fornisce gli **indicatori** per misurarne le prestazioni, sia in gestione diretta sia in regime di global service. Questo quadro si integra con i framework di governance trattati da **[[Gestione degli Asset e Apparecchiature di Laboratorio (ISO 55001)]]** (ciclo di vita degli asset, SAMP) e da **[[Facility Management (ISO 41001)]]** (gestione dei servizi di supporto e dei relativi contratti, ISO 41012), e con i requisiti operativi di ISO 15189 6.4.5 descritti in **[[Gestione di Attrezzature, Reagenti e Fornitori Esterni]]**.
