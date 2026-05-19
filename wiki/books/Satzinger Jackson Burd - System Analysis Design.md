---
type: book
title: "Systems Analysis and Design in a Changing World"
authors: ["John W. Satzinger", "Robert B. Jackson", "Stephen D. Burd"]
year: 2009
edition: "5th ed."
publisher: "Course Technology / Cengage Learning"
domain: [ingegneria-sistemi]
tags: [book, SDLC, UML, OO, requirements, database, IT-systems]
status: in-coda
created: 2026-05-18
updated: 2026-05-18
raw_file: ".raw/J. W. Satzinger, R. B. Jackson, S. D. Burd - System Analysis & Design in a Changing World.pdf"
related:
  - "[[Ingegneria dei Sistemi]]"
  - "[[Wasson - System Analysis Design Development]]"
---

# Satzinger, Jackson, Burd — Systems Analysis and Design in a Changing World (5th ed.)

**Autori:** John W. Satzinger (Missouri State), Robert B. Jackson (RBJ and Associates), Stephen D. Burd (University of New Mexico)
**Anno:** 2009 (5th ed.) | **Editore:** Cengage Learning | **pp.** ~700
**ISBN:** 978-1-4239-0228-7

> [!key-insight] Punto centrale
> Testo accademico per il corso di **Information Systems** (non SE in senso ingegneristico): copre l'analisi e il design di sistemi informativi aziendali con approcci tradizionale (structured) e orientato agli oggetti (OO). Focus su UML, use cases, database design, user interface — tutti strumenti del software analyst in contesto aziendale.

> [!note] Scopo diverso dai testi SE
> Questo testo è orientato ai sistemi *informatici/aziendali*, non ai sistemi ingegneristici fisici. Il "sistema" è tipicamente un'applicazione software o ERP, non un sistema cyber-fisico. Utile per la parte SE applicata a sistemi IT.

---

## Struttura (4 parti, 17 capitoli)

### Parte 1 — The Systems Analyst
- **Cap. 1: The World of the Information Systems Analyst** — il ruolo dell'analista; sistemi che risolvono problemi di business; strategic planning; il cuore del corso
- **Cap. 2: Approaches to System Development** — SDLC; modelli di sviluppo (waterfall, iterativo, agile); tool e tecniche
- **Cap. 3: The Analyst as Project Manager** — scope, schedule, budget; risk; team management

### Parte 2 — Systems Analysis Activities
- **Cap. 4: Investigating System Requirements** — tecniche di fact-finding; interviste, questionari, osservazione
- **Cap. 5: Modeling System Requirements** — activity diagrams; domain model
- **Cap. 6: The Traditional Approach to Requirements** — DFD (Data Flow Diagrams); structured analysis
- **Cap. 7: The Object-Oriented Approach to Requirements** — use cases; sequence diagrams; class diagrams
- **Cap. 8: Evaluating Alternatives** — make or buy; build or acquire; cloud options

### Parte 3 — Systems Design Tasks
- **Cap. 9: Elements of Systems Design** — architettura del sistema; componenti del design
- **Cap. 10: The Traditional Approach to Design** — struttura modulare; input/output design
- **Cap. 11: Object-Oriented Design: Principles** — principi OO: incapsulamento, ereditarietà, polimorfismo
- **Cap. 12: Object-Oriented Design: Use Case Realizations** — design patterns; collaboration diagrams
- **Cap. 13: Designing Databases** — ER modeling; normalizzazione; SQL; data warehousing
- **Cap. 14: Designing the User Interface** — principi UI/UX; prototyping; form design
- **Cap. 15: Designing System Interfaces, Controls, and Security** — interfacce con sistemi esterni; controlli interni; sicurezza

### Parte 4 — Implementation and Support
- **Cap. 16: Making the System Operational** — testing; conversione; training; deployment
- **Cap. 17: Current Trends in System Development** — SOA, Web services, agile, mobile, cloud

---

## Concetti Chiave

### SDLC — Systems Development Life Cycle (Cap. 2)

Il ciclo di vita classico per lo sviluppo di sistemi informativi:
```
Planning → Analysis → Design → Implementation → Support
```
Varianti:
- **Waterfall**: fasi sequenziali, documenti di output da ciascuna
- **Iterativo/incrementale**: fasi cicliche con consegne parziali
- **Agile** (Scrum, XP): sprint, backlog, continuous delivery

### Use Cases e UML (Cap. 7)

- **Use Case Diagram**: attori + use cases + associazioni. Risponde a "cosa fa il sistema?"
- **Use Case Description**: flusso base (happy path) + flussi alternativi + precondizioni/postcondizioni
- **Sequence Diagram**: mostra le interazioni tra oggetti nel tempo durante un use case
- **Class Diagram**: struttura del sistema OO; attributi, metodi, relazioni

### Database Design (Cap. 13)

- **ER Diagram** (Entity-Relationship): entità, attributi, chiavi, relazioni (1:1, 1:N, M:N)
- **Normalizzazione**: riduzione della ridondanza (1NF → 2NF → 3NF → BCNF)
- **ORM** (Object-Relational Mapping): traduzione tra modello OO e schema relazionale

---

## Differenze con i Testi SE Ingegneristici

| Aspetto | Satzinger (IS) | Wasson/SEBoK (SE) |
|---------|---------------|-------------------|
| Tipo di sistema | Software/IS aziendale | Sistema cyber-fisico |
| Notazione | UML, DFD, ER | SysML, N², CONOPS |
| Orientamento | Business analyst | Systems engineer |
| Ambito | Applicazione informatica | Sistema ingegneristico complesso |
| Standard | Nessuno specifico | MIL-STD, ISO/IEC 15288 |

---

## Connessioni nel Wiki

- [[Ingegneria dei Sistemi]] — il SDLC è un caso speciale del ciclo di vita del sistema
- [[Wasson - System Analysis Design Development]] — approccio SE classico; Satzinger è complementare per la parte IT

---

## Domande Aperte

- Come si raccorda l'analisi OO di Satzinger con MBSE/SysML per sistemi misti HW/SW?
- Il SDLC agile (cap. 17) si applica allo sviluppo di sistemi fisici (cyber-physical systems)?
