---
type: book
title: "Systems Engineering Demystified"
authors: ["Jon Holt"]
year: 2023
edition: "2nd ed."
publisher: "Packt Publishing"
domain: [ingegneria-sistemi]
tags: [book, MBSE, SysML, SE, ontologia, interfacce, lifecycle]
status: in-coda
created: 2026-05-18
updated: 2026-05-18
raw_file: ".raw/J. Holt - Systems Engineering Demystified.pdf"
related:
  - "[[Ingegneria dei Sistemi]]"
  - "[[SEBoK v2.7]]"
  - "[[Eisner - Essentials SE Management]]"
---

# Holt — Systems Engineering Demystified (2nd ed.)

**Autore:** Prof. Jon Holt (Cranfield University; Scarecrow Consultants; INCOSE UK Technical Director)
**Anno:** 2023 | **Editore:** Packt | **pp.** ~400
**ISBN:** 978-1-80461-068-8

> [!key-insight] Punto centrale
> La SE è spesso fraintesa perché gli ingegneri sistemisti non *producono* componenti visibili: il loro prodotto è il *sistema integrato*. Questo libro demistifica la SE attraverso MBSE e l'**ontologia** come fondamento: prima definisci cos'è il sistema (ontologia), poi lo modelli (SysML), poi lo verifichi.

---

## Struttura (2 parti principali)

### Parte I — Introduction to Systems Engineering

**Cap. 1: Introduction to Systems Engineering**
- Brief history of SE
- Defining a System: elements, stakeholders, attributes, boundaries, needs, constraints
- The need for SE: Complexity (element, constraint, SoS), Communication (common languages, SysML), Understanding
- Implementation of SE

**Cap. 2: Model-Based Systems Engineering**
- Abstracting the System; Visualizing the Model; Defining the approach
- 5 stadi di evoluzione MBSE:
  1. Document-Based SE
  2. Document-Centric SE
  3. Model-Enhanced SE
  4. Model-Centric SE
  5. **MBSE** (modello come unica sorgente di verità)
- SysML: diagrammi strutturali e comportamentali; esempio di modeling
- **Ontologia**: cornerstone di MBSE; visualizzazione dell'ontologia

---

### Parte II — Systems Engineering Concepts

**Cap. 3: Systems and Interfaces**
- System hierarchy (Block Definition Diagram); interaction relationships
- **Describing Interfaces**: identificazione, definizione, modeling
  - Structural Breakdown View; Interface Identification View; Port Definition View; Flow Type Definition View; Interface Connectivity View
- Defining the Framework: viewpoints, context view

*(Struttura dei capitoli 4+ non estratta — libro in 2a edizione 2023)*

---

## Concetti Chiave

### Sistema: definizione operativa (Cap. 1)

Un sistema ha 6 caratteristiche fondamentali:
1. **Elements**: componenti fisici, software, persone, processi
2. **Stakeholders**: chi ha interesse nel sistema
3. **Attributes**: proprietà e caratteristiche misurabili
4. **Boundary**: scopo del sistema; cosa è dentro/fuori
5. **Needs**: lo scopo del sistema; perché esiste
6. **Constraints**: limitazioni alla realizzazione

### Complessità (Cap. 1)

Jon Holt identifica 3 tipi di complessità che giustificano la SE:
- **Complessità degli elementi**: quanti e quanto diversi sono i componenti
- **Complessità dei vincoli**: interfacce, requisiti non funzionali, regolamenti
- **Complessità SoS**: sistemi che si combinano in sistemi superiori

> "Identifying Complexity" è il primo passo per giustificare l'investimento in SE.

### MBSE: 5 Stadi di Evoluzione (Cap. 2)

```
Stage 1: Document-Based → documenti Word, tutto in prosa
Stage 2: Document-Centric → documenti strutturati, templates
Stage 3: Model-Enhanced → modelli affiancano i documenti
Stage 4: Model-Centric → il modello guida, i documenti derivano
Stage 5: MBSE → il modello è la sola sorgente di verità
```

La transizione Stage 4→5 richiede cambiamento culturale, non solo strumenti.

### SysML: Diagrammi (Cap. 2)

SysML ha 9 tipi di diagrammi divisi in:
- **Strutturali**: Block Definition Diagram (BDD), Internal Block Diagram (IBD), Package Diagram
- **Comportamentali**: Activity Diagram, Sequence Diagram, State Machine, Use Case Diagram
- **Requisiti**: Requirements Diagram
- **Parametrici**: Parametric Diagram

Holt enfatizza i BDD e IBD per la struttura; SD e AD per il comportamento.

### Ontologia come Fondamento MBSE (Cap. 2)

L'**ontologia** definisce i tipi di cose che esistono nel sistema e le relazioni tra loro. È il "vocabolario" del modello. Senza un'ontologia condivisa, il modello MBSE è ambiguo e non riusabile.

L'ontologia precede la notazione (SysML): prima si decide *cosa* modellare, poi *come* rappresentarlo.

### Interfacce (Cap. 3)

Le interfacce sono il punto critico dell'integrazione. Una **porta** (port) è il punto di connessione su un blocco; un **flow type** specifica cosa passa attraverso la porta. Il modeling delle interfacce in SysML usa:
- BDD: definisce i tipi di porte e flussi
- IBD: mostra le connessioni fisiche tra blocchi

---

## Connessioni nel Wiki

- [[Ingegneria dei Sistemi]] — Holt è il libro introduttivo accessibile per MBSE
- [[SEBoK v2.7]] — il SEBoK fornisce il quadro di riferimento; Holt dà la pratica
- [[Eisner - Essentials SE Management]] — copre il management; Holt copre il modeling
- [[Wasson - System Analysis Design Development]] — più approfondito sulle tecniche SE classiche

---

## Domande Aperte

- Come si costruisce un'ontologia MBSE per un sistema con requisiti emergenti (CAS)?
- Il V-model è compatibile con Agile SE? Come gestire i requisiti che cambiano a ogni sprint?
- SysML v2.0 (in sviluppo) cambierà significativamente l'approccio di Holt?
