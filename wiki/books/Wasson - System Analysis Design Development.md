---
type: book
title: "System Analysis, Design, and Development: Concepts, Principles, and Practices"
authors: ["Charles S. Wasson"]
year: 2006
edition: "1st ed."
publisher: "Wiley-Interscience"
domain: [ingegneria-sistemi]
tags: [book, SADD, SE, requirements, architettura, CONOPS, verification, lifecycle]
status: in-coda
created: 2026-05-18
updated: 2026-05-18
raw_file: ".raw/C. S. Wasson - System Analysis, Design and Development - Concepts, Principles, and Practices.pdf"
related:
  - "[[Ingegneria dei Sistemi]]"
  - "[[SEBoK v2.7]]"
  - "[[Eisner - Essentials SE Management]]"
---

# Wasson — System Analysis, Design, and Development

**Autore:** Charles S. Wasson (1948–)
**Anno:** 2006 | **Editore:** Wiley-Interscience | **pp.** ~812 (57 capitoli)
**ISBN:** 978-0-471-39333-7

> [!key-insight] Punto centrale
> Il testo più completo sull'analisi e sviluppo di sistemi nella tradizione SE classica. Copre l'intero arco dal "cosa è un sistema" (cap. 3) al deployment e operations (cap. 56-57), organizzato in serie tematiche. Il principio guida: capire il problema *prima* di progettare la soluzione.

---

## Struttura (3 parti, 57 capitoli)

### Parte I — System Analysis Concepts

**System Entity Concepts Series** (cap. 3–7)
- Cap. 3: What Is a System?
- Cap. 4: System Attributes, Properties, and Characteristics
- Cap. 5: System Roles and Stakeholders
- Cap. 6: System Acceptability
- Cap. 7: The System/Product Life Cycle

**System Architecture Concepts Series** (cap. 8–12)
- Cap. 8: The Architecture of Systems
- Cap. 9: System Levels of Abstraction and Semantics
- Cap. 10: The System of Interest Architecture
- Cap. 11: The Operating Environment Architecture
- Cap. 12: System Interfaces

**System Mission Concepts Series** (cap. 13–17)
- Cap. 13: Organizational Roles, Missions, and System Applications
- Cap. 14: Understanding the Problem, Opportunity, and Solution Spaces
- Cap. 15: System Interactions with its Operating Environment
- Cap. 16: System Mission Analysis
- Cap. 17: System Use Cases and Scenarios

**System Operations Concepts Series** (cap. 18–20)
- Cap. 18: System Operations Model
- Cap. 19: System Phases, Modes, and States of Operation
- Cap. 20: Modeling System and Support Operations

**System Capability Concepts Series** (cap. 21–22)
- Cap. 21: System Operational Capability Derivation and Allocation
- Cap. 22: The Anatomy of a System Capability

**System Concept Synthesis** (cap. 23)

---

### Parte II — System Design and Development Practices

**System Development Strategies Series** (cap. 24–27)
- Cap. 24: The System Development Workflow Strategy
- Cap. 25: System Design, Integration, and Verification Strategy
- Cap. 26: The SE Process Model
- Cap. 27: System Development Models

**System Specification Series** (cap. 28–33)
- Cap. 28–31: Specification practices, requirements, analysis, development
- Cap. 32: Requirements Derivation, Allocation, Flow Down, and Traceability
- Cap. 33: Requirements Statement Development

**System Development Series** (cap. 34–46)
- Cap. 34: Operational Utility, Suitability, and Effectiveness
- Cap. 35: System Design To/For Objectives (DfX)
- Cap. 36: System Architecture Development
- Cap. 37–40: Domain solutions (requirements, operations, behavioral, physical)
- Cap. 41: Component Selection and Development
- Cap. 42: System Configuration Identification
- Cap. 43: System Interface Analysis, Design, and Control
- Cap. 44: Human–System Integration
- Cap. 45: Engineering Standards, Frames of Reference, and Conventions
- Cap. 46: System Design and Development Documentation

**Decision Support Series** (cap. 47–52)
- Cap. 47: Analytical Decision Support
- Cap. 48: Statistical Influences on System Design
- Cap. 49: System Performance Analysis, Budgets, and Safety Margins
- Cap. 50: System Reliability, Availability, and Maintainability (RAM)
- Cap. 51: System Modeling and Simulation
- Cap. 52: Trade Study Analysis of Alternatives

**Verification and Validation Series** (cap. 53–55)
- Cap. 53: System Verification and Validation
- Cap. 54: Technical Reviews
- Cap. 55: System Integration, Test, and Evaluation

**System Deployment, Operations, and Support Series** (cap. 56–57)
- Cap. 56: System Deployment
- Cap. 57: System Operations and Support (O&S)

---

## Concetti Chiave

### Problem, Opportunity, and Solution Spaces (Cap. 14)

Wasson distingue tre spazi di lavoro:
- **Problem Space**: comprensione del problema/opportunità dal punto di vista degli stakeholder; bisogni, aspettative, vincoli
- **Solution Space**: possibili design del sistema; architetture alternative
- **Deployment Space**: come il sistema opera nel mondo reale; uso, supporto, dismissione

La SE inizia sempre nel Problem Space, non nel Solution Space.

### CONOPS — Concept of Operations (Cap. 16, 18)

Il CONOPS descrive *come* il sistema sarà usato nel suo contesto operativo:
- Chi usa il sistema e come
- Le sequenze operative tipiche
- Le fasi operative (startup, normal, degraded, shutdown)
- Le interazioni con l'ambiente e altri sistemi

Il CONOPS precede i requisiti: traduce i bisogni degli stakeholder in una narrativa operativa.

### Use Cases e Scenari (Cap. 17)

- **Use Case**: descrizione astratta di un'interazione tra un attore e il sistema
- **Scenario**: istanza specifica di un use case con valori concreti
- Use cases → requisiti funzionali; scenari → casi di test

### Livelli di Astrazione (Cap. 9)

Wasson formalizza i livelli di astrazione del sistema:
```
System Level
  ↓ decomposizione
Subsystem Level
  ↓ decomposizione  
Component Level
  ↓ decomposizione
Part Level
```

Ogni livello ha la propria semantica (significato dei requisiti) e le proprie interfacce.

### RAM: Reliability, Availability, Maintainability (Cap. 50)

Tre proprietà non funzionali interdipendenti:
- **Reliability**: probabilità che il sistema funzioni correttamente per un periodo dato (MTTF)
- **Availability**: A = MTBF / (MTBF + MTTR) — frazione del tempo in cui il sistema è operativo
- **Maintainability**: facilità e tempo di manutenzione (MTTR — Mean Time To Repair)

---

## Connessioni nel Wiki

- [[Ingegneria dei Sistemi]] — Wasson è la trattazione più dettagliata dei 57 processi SE
- [[SEBoK v2.7]] — il SEBoK è la guida di riferimento; Wasson è il manuale pratico
- [[Eisner - Essentials SE Management]] — complementare: Eisner enfatizza la gestione, Wasson l'analisi tecnica
- [[Holt - Systems Engineering Demystified]] — Holt è introduttivo; Wasson è avanzato

---

## Domande Aperte

- Come si integra il CONOPS di Wasson con il MBSE modeling (SysML use case diagrams)?
- Il framework Problem/Solution/Deployment Space si applica ai sistemi adattativi complessi?
