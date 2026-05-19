---
type: book
title: "Essentials of Project and Systems Engineering Management"
authors: ["Howard Eisner"]
year: 2002
edition: "2nd ed."
publisher: "Wiley-Interscience"
domain: [ingegneria-sistemi]
tags: [book, SE, project-management, WBS, requirements, architettura, risk]
status: in-coda
created: 2026-05-18
updated: 2026-05-18
raw_file: ".raw/H. Eisner -  Essentials of Project and Systems Engineering Management.pdf"
related:
  - "[[Ingegneria dei Sistemi]]"
  - "[[SEBoK v2.7]]"
  - "[[Wasson - System Analysis Design Development]]"
---

# Eisner — Essentials of Project and Systems Engineering Management (2nd ed.)

**Autore:** Howard Eisner (George Washington University; ex-presidente di Intercon Systems e Atlantic Research Services)
**Anno:** 2002 | **Editore:** Wiley-Interscience | **pp.** ~500
**ISBN:** 0-471-03195-X

> [!key-insight] Punto centrale
> Il project management e la systems engineering non sono discipline separate: si integrano nella gestione del ciclo di vita del sistema. Eisner fornisce un framework unificato con **30 elementi di SE** (cap. 7) come checklist operativa per gestire la complessità tecnica e organizzativa.

---

## Struttura (4 parti, 15 capitoli)

### Parte I — Overview
- **Cap. 1: Systems, Projects, and Management** — definizioni; problemi nella gestione di progetti ingegneristici; l'approccio sistemico; organizzazione del progetto; ambienti organizzativi
- **Cap. 2: Overview of Essentials** — project management essentials; SE process and management essentials; acquisizione di sistema; standard selezionati (DoD, IEEE, ISO)

### Parte II — Project Management
- **Cap. 3: The Project Plan** — needs/goals/objectives/requirements; SOW e WBS; technical approach; schedule; organizzazione e staffing; budget; risk analysis; proposta
- **Cap. 4: Schedule, Cost, and Situation Analysis** — schedule monitoring; earned value analysis; situation analysis
- **Cap. 5: The Project Manager and Leadership** — attributi del PM; autovalutazione; interazione con supervisori e clienti; leadership
- **Cap. 6: Team Building and Team Interactions** — comunicazione; costruzione del team; team busters; conflict management; riunioni, presentazioni, proposte

### Parte III — Systems Engineering and Management
- **Cap. 7: The Thirty Elements of Systems Engineering** → vedi sotto
- **Cap. 8: Requirements Analysis and Allocation** — prospettive DoD e NASA; organizzazione delle requirements; derivazione e allocazione; tracciabilità
- **Cap. 9: System Architecting: Principles** — architecture descriptions; passi essenziali; trade-offs; modeling & simulation
- **Cap. 10: Software Engineering** — standard SW; strategie di management; CMM; metriche SW
- **Cap. 11: Selected Quantitative Relationships** — probabilità, distribuzioni, affidabilità, disponibilità

### Parte IV — (Ulteriori capitoli)
- Verification and validation; testing; system integration; specialty engineering; system deployment and operations

---

## I 30 Elementi dell'Ingegneria dei Sistemi (Cap. 7)

Eisner identifica 30 elementi come checklist per la pratica SE. Esempi rappresentativi:

**Definizione e requisiti:**
1. Requirements analysis (user needs → system requirements)
2. Requirements management (tracciabilità, change control)
3. Functional analysis & allocation

**Architettura e design:**
4. System architecture
5. Interface management
6. Trade studies (analisi delle alternative)
7. Technical performance measurement (TPM)

**Integration & V&V:**
8. System integration
9. Verification
10. Validation
11. Test planning and execution

**Management:**
12. Risk management
13. Configuration management
14. Data management
15. Quality assurance
16. Technical reviews (SRR, PDR, CDR, TRR...)
17. Work Breakdown Structure (WBS)
18. Integrated Master Plan / Schedule

*(Lista completa nel testo; qui i più critici per un ingegnere dei sistemi)*

---

## Concetti Chiave

### WBS — Work Breakdown Structure (Cap. 3)

La WBS decompone il progetto in una gerarchia di deliverable:
```
Level 0: Sistema completo
Level 1: Elementi principali (HW, SW, Integration & Test, PM)
Level 2: Sottosistemi e attività
Level 3: Work packages (assegnabili a singole persone/team)
```
La WBS è la *struttura di controllo* del progetto: collega schedule, budget, responsabilità, e misurazione dell'earned value.

### Earned Value Analysis (Cap. 4)

Metrica per misurare l'avanzamento del progetto:
- **BCWS** (Budget Cost of Work Scheduled): cosa avrei dovuto spendere
- **BCWP** (Budget Cost of Work Performed): quanto lavoro è stato fatto
- **ACWP** (Actual Cost of Work Performed): quanto ho effettivamente speso
- **SV** = BCWP - BCWS (schedule variance; positivo = avanti)
- **CV** = BCWP - ACWP (cost variance; positivo = sotto budget)

### System Architecting: Passi Essenziali (Cap. 9)

Eisner identifica ~10 passi per l'architecting:
1. Definire la missione del sistema
2. Comprendere i requisiti di più alto livello
3. Identificare vincoli principali (costo, schedule, legge)
4. Identificare le funzioni principali
5. Sviluppare alternative architetturali
6. Valutare alternative con trade studies
7. Selezionare l'architettura preferita
8. Allocare requisiti alle parti dell'architettura
9. Documentare l'architettura (CONOPS, interface control documents)
10. Revisionare con stakeholder (preliminary design review)

### Il "95% Solution" (Cap. 9)

Heuristica di Eisner: l'architettura ottimale è spesso irraggiungibile (100%), ma una soluzione al 95% che soddisfa i requisiti chiave è preferibile a una soluzione "perfetta" che non si può implementare in tempo/budget.

---

## Standard citati (Cap. 2)

- **MIL-STD-499B**: guida SE del DoD (non approvato ufficialmente, ma influente)
- **EIA-632**: standard ANSI/EIA per i processi di sistema
- **IEEE 1220**: standard IEEE per SE (ora ritirato, sostituito da ISO/IEC 15288)
- **ISO/IEC 12207**: processi del ciclo di vita del software

---

## Connessioni nel Wiki

- [[Ingegneria dei Sistemi]] — Eisner copre il lato manageriale della SE con dettaglio pratico
- [[SEBoK v2.7]] — il SEBoK fornisce il framework concettuale; Eisner dà gli strumenti operativi
- [[Wasson - System Analysis Design Development]] — testo complementare, più dettagliato sulle tecniche analitiche
- [[Holt - Systems Engineering Demystified]] — complementare su MBSE/SysML (non trattato da Eisner)

---

## Domande Aperte

- Come si integra l'earned value con un ciclo di sviluppo Agile?
- I 30 elementi di Eisner sono ancora completi, o mancano elementi per sistemi cyber-fisici?
- Come si applica il system architecting a sistemi di sistemi (SoS)?
