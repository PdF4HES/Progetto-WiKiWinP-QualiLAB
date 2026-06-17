---
type: book
title: "Guide to the Systems Engineering Body of Knowledge (SEBoK) v2.7"
authors: ["INCOSE / IEEE / Stevens Institute (editorial board)"]
year: 2022
edition: "v2.7 (Oct 2022)"
publisher: "BKCASE Editorial Board / sebokwiki.org"
domain: [ingegneria-sistemi]
tags: [book, SEBoK, INCOSE, MBSE, SE-lifecycle, standards, reference]
status: in-coda
created: 2026-05-18
updated: 2026-05-18
raw_file: ".raw/SEBoK - A Guide to the Systems Engineering Body of Knowledge (v.2.7).pdf"
related:
  - "[[Ingegneria dei Sistemi]]"
  - "[[Holt - Systems Engineering Demystified]]"
  - "[[Eisner - Essentials SE Management]]"
  - "[[Wasson - System Analysis Design Development]]"
---

# SEBoK v2.7 — Guida al Corpo di Conoscenza dell'Ingegneria dei Sistemi

**Organizzazione:** BKCASE Editorial Board (INCOSE + IEEE + Stevens Institute)
**Anno:** Oct 2022 | **Fonte:** sebokwiki.org (PDF estratto)
**Nota:** Dedicato a Barry Boehm (1935–2022), fondatore dell'ingegneria dei requisiti e del modello COCOMO.

> [!key-insight] Punto centrale
> Il SEBoK è la *mappa complessiva* della disciplina SE: non un manuale operativo ma un'enciclopedia strutturata che definisce la conoscenza fondamentale, le competenze, i processi e i domini di applicazione dell'ingegneria dei sistemi. Il punto di ingresso dipende da chi sei: novizio, praticante, manager, educatore.

---

## Struttura (7 Parti)

```
Part 1: SEBoK Introduction
Part 2: Foundations of Systems Engineering
Part 3: Systems Engineering and Management
Part 4: Applications of Systems Engineering
Part 5: Enabling Systems Engineering
Part 6: Related Disciplines
Part 7: Systems Engineering Research (non sempre inclusa nel PDF)
```

---

## Parte 2 — Fondamenti dell'Ingegneria dei Sistemi

### Knowledge Area: SE Fundamentals
- **SE Core Concepts**: sistema, stakeholder, ciclo di vita, processo
- **SE Principles**: decomposition, integration, abstraction, interfaces
- **SE Heuristics**: regole pratiche empiriche

### Knowledge Area: The Nature of Systems
- **Types of Systems**: fisici, concettuali, aperti/chiusi, naturali/artificiali, sistemi di sistemi
- **Cycles and the Cyclic Nature of Systems**: cicli nei sistemi; variazione e permanenza

### Knowledge Area: Systems Science
- **History of Systems Science**: da Bertalanffy a CAS
- **Systems Approaches**: hard systems, soft systems, critical systems
- **Complexity**: complessità come proprietà dei sistemi; comportamento emergente
- **Emergence**: debole (riducibile) vs forte (irriducibile)

### Knowledge Area: Systems Thinking
- **What is Systems Thinking?**: visione olistica vs riduzionistica
- **Concepts**: feedback, delays, non-linear dynamics, bounded rationality
- **Principles**: mentalità sistemica vs paradigma analitico
- **Patterns**: archetipi sistemici (Senge)

### Knowledge Area: Representing Systems with Models
- **What is a Model?**: astrazione di un sistema per uno scopo specifico
- **Types of Models**: fisici, matematici, computazionali, comportamentali
- **Modeling Standards**: SysML, UML, BPMN, ArchiMate, TOGAF
- **MBSE**: Model-Based Systems Engineering come paradigma dominante

### Knowledge Area: Systems Approach Applied to Engineered Systems
Ciclo iterativo:
1. Identificare/comprendere il problema o l'opportunità
2. Sintetizzare soluzioni possibili
3. Analisi e selezione tra alternative
4. Implementare e dimostrare la soluzione
5. Dispiegare, usare, sostenere il sistema

---

## Parte 3 — SE e Management

### System Lifecycle Models
- **Generic Life Cycle Model**: concept → development → production → utilization → support → retirement
- **Vee Model (V-model)**: decomposition (sinistra) + integration/verification (destra)
- **Incremental**: develop-in-increments con V-model annidati
- **Agile SE**: sprint, backlog, continuous integration; adattamento ai requisiti mutevoli
- **Lean Engineering**: eliminazione degli sprechi; value stream mapping

### MBSE
- Shift dal document-based al model-based: il modello (SysML) è l'artefatto primario
- **Vantaggi**: coerenza, tracing automatico, riuso, simulazione virtuale prima del prototipo fisico

### Systems Engineering Management
- Decision Management, Risk Management, Configuration Management, Quality Management, Measurement

### Architecture Definition
- Functional Architecture → Logical Architecture → Physical Architecture
- System Analysis, Integration, Verification, Validation, Transition, Operation

---

## Parte 4 — Applicazioni

| KA | Descrizione |
|----|-------------|
| Product SE | Prodotti fisici: HW, SW, FW; ciclo di vita del prodotto |
| Service SE | Sistemi di servizio; proprietà dei servizi |
| Enterprise SE | L'impresa come sistema; capability engineering |
| Systems of Systems (SoS) | Autonomia, belonging, architetture SoS |
| Healthcare SE | Applicazioni in sanità; systems biology |

---

## Use Cases (Parte 1)

Il SEBoK si usa in modo diverso secondo il profilo:
- **UC 0: Novice** → percorso di apprendimento sequenziale
- **UC 1: Practicing SE** → riferimento rapido su processi specifici
- **UC 2: Other Engineers** → applicare SE alla propria disciplina
- **UC 3: Customers** → capire cosa aspettarsi dalla SE
- **UC 4: Educators/Researchers** → curricula e research agenda
- **UC 5: General Managers** → ROI della SE

---

## Connessioni nel Wiki

- [[Ingegneria dei Sistemi]] — il SEBoK è la fonte enciclopedica per questa pagina concettuale
- [[Holt - Systems Engineering Demystified]] — introduce MBSE/SysML in modo accessibile; complementa SEBoK Pt.3
- [[Eisner - Essentials SE Management]] — copre SE management (SEBoK Pt.3) con più dettaglio progettuale
- [[Wasson - System Analysis Design Development]] — 57 capitoli di dettaglio pratico sulle attività SE

---

## Note

- Il SEBoK è un *living document* aggiornato ogni 1–2 anni; v2.7 è la versione attuale (2022)
- La versione online (sebokwiki.org) ha link tra knowledge areas; il PDF non li preserva
- Non sostituisce i manuali operativi (INCOSE SE Handbook 5th ed., ISO/IEC 15288)
