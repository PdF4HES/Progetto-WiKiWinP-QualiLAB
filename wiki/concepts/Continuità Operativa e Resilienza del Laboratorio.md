---
type: concept
title: "Continuità Operativa e Resilienza del Laboratorio"
created: 2026-06-13
updated: 2026-06-13
tags:
  - laboratorio-medico
  - concept
  - normativa
  - continuità-operativa
status: developing
address: c-000156
complexity: intermediate
domain: laboratorio-medico
aliases:
  - "Business Continuity"
  - "BCMS"
  - "Continuità operativa"
  - "Resilienza organizzativa"
related:
  - "[[ISO 15189]]"
  - "[[Sistema di Gestione per la Qualità]]"
  - "[[Gestione del Rischio (ISO 31000)]]"
  - "[[UNI EN ISO 22301-2019 - Sistemi di Gestione per la Continuità Operativa - Requisiti]]"
  - "[[Salute e Sicurezza sul Lavoro (SSL) nel Laboratorio Clinico]]"
  - "[[Sistema Informativo di Laboratorio (LIS)]]"
sources:
  - "[[.raw/unlocked_UNI EN ISO 22301_2019 - Sicurezza e resilienza - Sistemi di gestione per la continuità operativa - Requisiti.pdf]]"
  - "[[.raw/unlocked_UNI ISO 31000_2018 - Gestione del rischio - Linee guida.pdf]]"
---

## Definizione

La **continuità operativa** è la capacità di un'organizzazione di continuare l'erogazione dei propri prodotti e servizi, entro tempi accettabili e a una capacità produttiva predefinita, durante un'**interruzione** (disruption) — un evento che causa una deviazione negativa e non pianificata rispetto all'erogazione prevista. Per un laboratorio medico, "erogazione dei servizi" significa innanzitutto **continuità della refertazione diagnostica**: la sospensione, anche parziale o temporanea, della capacità analitica di un laboratorio può avere conseguenze cliniche dirette su pazienti in attesa di referti per decisioni terapeutiche urgenti.

**[[UNI EN ISO 22301-2019 - Sistemi di Gestione per la Continuità Operativa - Requisiti|ISO 22301:2019]]** è la norma di riferimento — generica e certificabile — per istituire un **Sistema di Gestione per la Continuità Operativa (BCMS)** secondo la struttura ad alto livello (HLS) comune alle altre norme di sistemi di gestione (ISO 9001, ISO 45001, ecc.) e al ciclo PDCA.

## Perché è rilevante per un laboratorio clinico

Un laboratorio medico, nell'ambito di un percorso diagnostico-terapeutico-assistenziale, è esposto a numerose potenziali **interruzioni**:

- **blackout elettrico** o interruzione dell'alimentazione che compromette strumentazione analitica, sistemi di conservazione di campioni/reagenti (frigoriferi, congelatori) e sistemi informativi;
- **guasto della strumentazione analitica principale** (analizzatori chimici, ematologici, immunometrici), specialmente se non ridondata;
- **indisponibilità del Sistema Informativo di Laboratorio (LIS)** o di altri sistemi IT (interfacciamento con cartella clinica, refertazione elettronica) — si veda [[Sistema Informativo di Laboratorio (LIS)]];
- **indisponibilità di reagenti o materiali di consumo** (carenze di fornitura, problemi nella catena di approvvigionamento);
- **assenza di personale critico** su larga scala (epidemie/pandemie, scioperi, eventi climatici);
- **eventi catastrofici** (incendi, alluvioni, terremoti) che danneggiano la sede o i locali del laboratorio.

ISO 15189 richiede che il laboratorio gestisca le interruzioni del servizio in modo da non compromettere la sicurezza del paziente; ISO 22301 fornisce il framework strutturato per pianificare, prepararsi e rispondere a queste situazioni.

## Gli elementi chiave del BCMS applicati al laboratorio

1. **Analisi di impatto operativo (Business Impact Analysis - BIA)**: per ogni processo del laboratorio (pre-analitico, analitico, post-analitico — v. ISO 15189 clausola 7), si valuta l'impatto nel tempo di un'eventuale interruzione e si determinano:
   - le **attività prioritarie** (es. esami con valori critici, esami urgenti/STAT, esami per pazienti in terapia intensiva);
   - il **massimo periodo tollerabile di interruzione (MTPD)**: oltre quale soglia temporale l'indisponibilità di un esame diventa clinicamente inaccettabile;
   - l'**obiettivo di tempo di recupero (RTO)**: entro quanto tempo l'attività deve essere ripristinata a un livello minimo accettabile.

2. **Valutazione del rischio di interruzione**: applicando i principi e il processo di [[Gestione del Rischio (ISO 31000)]], il laboratorio identifica, analizza e valuta i rischi che minacciano le attività prioritarie e le risorse necessarie (strumentazione, IT, personale, reagenti, fornitori).

3. **Strategie e soluzioni di continuità**: ad esempio:
   - **ridondanza strumentale** (back-up analitici per i parametri critici, anche tramite accordi con altri laboratori della rete);
   - **procedure manuali di emergenza** per la refertazione in caso di indisponibilità del LIS;
   - **gruppi elettrogeni/UPS** per la continuità elettrica di strumentazione e sistemi di conservazione;
   - **accordi con laboratori di riferimento** per l'invio di campioni urgenti in caso di guasto prolungato;
   - **scorte di sicurezza** di reagenti critici.

4. **Piani per la continuità operativa**: documenti operativi che definiscono ruoli, responsabilità, criteri di attivazione, procedure di allerta/comunicazione (verso clinici, direzione, pazienti) e procedure di recupero, con la **salvaguardia della vita come priorità assoluta**.

5. **Programma di esercitazione**: simulazioni periodiche (es. simulazione di blackout, di guasto dello strumento principale, di indisponibilità del LIS) per validare l'efficacia dei piani.

## Relazione con ISO 31000 e con il Sistema di Gestione per la Qualità

ISO 22301 richiama esplicitamente **ISO 31000** per il processo di valutazione del rischio (punto 8.2.3): il "come" della valutazione del rischio è comune ai due ambiti, mentre ISO 22301 specifica il "cosa" in relazione al rischio di interruzione operativa — si veda [[Gestione del Rischio (ISO 31000)]].

La continuità operativa si integra nel [[Sistema di Gestione per la Qualità]] del laboratorio non come adempimento separato, ma come componente della gestione dei rischi operativi: gli output della BIA e della valutazione del rischio di interruzione alimentano la pianificazione (clausola 5/6) e il riesame di direzione (clausola 8.9 di ISO 15189), così come avviene per gli altri tipi di rischio (clinico, di sicurezza del personale — v. [[Salute e Sicurezza sul Lavoro (SSL) nel Laboratorio Clinico]]).
