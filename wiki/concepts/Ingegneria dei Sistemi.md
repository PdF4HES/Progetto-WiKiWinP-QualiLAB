---
type: concept
status: developing
domain: ingegneria-sistemi
tags:
  - concept
  - SE
  - MBSE
  - INCOSE
  - SysML
created: 2026-05-17
updated: 2026-05-17
related:
  - "[[Teoria dei Sistemi]]"
  - "[[Sintesi del Campo]]"
---

# Ingegneria dei Sistemi

Navigation: [[Wiki/concepts/_index]] | [[Sintesi del Campo]] | [[index]]

---

## Definizione

L'ingegneria dei sistemi (Systems Engineering, SE) e una disciplina ingegneristica interdisciplinare che si occupa di progettare, integrare e gestire sistemi complessi durante il loro ciclo di vita. Differisce dall'ingegneria tradizionale (disciplinare, componente per componente) per l'attenzione alle interfacce, all'emergenza e al comportamento del sistema nel suo insieme.

**INCOSE:** International Council on Systems Engineering — organismo di riferimento internazionale.

---

## Ciclo di Vita del Sistema

Il ciclo di vita standard (ISO/IEC 15288) comprende:

1. **Concept**: definizione dei bisogni dello stakeholder
2. **Development**: requirements, architettura, progettazione, integrazione
3. **Production**: realizzazione
4. **Utilization**: uso operativo
5. **Support**: manutenzione, aggiornamenti
6. **Retirement**: dismissione

---

## V-Model

Il modello a V e il processo di sviluppo canonico in SE:

```
Stakeholder Needs
  --> System Requirements
    --> Architecture
      --> Design
        --> Implementation
      --> Component Verification
    --> Integration Verification
  --> System Validation
Stakeholder Satisfaction
```

Ogni freccia discendente (sinistra) ha una corrispondente attivita di verifica/validazione (destra).

---

## Model-Based Systems Engineering (MBSE)

Shift dal document-based al model-based. Il modello (tipicamente in SysML) e l'artefatto primario, non i documenti testuali.

**SysML (Systems Modeling Language):** profilo UML per SE. Diagrammi principali:
- Block Definition Diagram (BDD): struttura del sistema
- Internal Block Diagram (IBD): connessioni interne
- Requirement Diagram: requisiti e tracing
- Activity Diagram: comportamento
- Sequence Diagram: interazioni temporali
- State Machine: comportamento reattivo
- Use Case Diagram: contesto operativo

**Vantaggi MBSE:** consistenza, riuso, tracing automatico, simulazione.

---

## Requirements Engineering

Un requisito specifica cosa il sistema deve fare, non come farlo. Tipi:
- **Stakeholder requirements**: bisogni degli utenti/clienti
- **System requirements**: comportamento funzionale e di prestazione del sistema
- **Design constraints**: vincoli implementativi
- **Non-functional requirements (NFR)**: qualita (-ilita): affidabilita, sicurezza, manutenibilita

**Attributi di un buon requisito:** atomico, verificabile, non ambiguo, tracciabile, consistente.

---

## Architettura dei Sistemi

Definisce la struttura del sistema: componenti, interfacce, responsabilita, principi guida.

**Architettura funzionale:** cosa il sistema fa (funzioni)
**Architettura fisica:** come il sistema e fatto (componenti)
**Allocazione:** mapping funzione -> componente

---

## Connessioni con la Teoria dei Sistemi

- La SE applica operativamente i concetti della [[Teoria dei Sistemi]]
- La gestione delle interfacce e gestione dei confini sistemici
- L'emergenza e il problema centrale dell'integrazione: il sistema integrato ha comportamenti non prevedibili dai componenti
- La [[Termodinamica dei Fenomeni Irreversibili]] offre framework per sistemi dissipatori di energia

---

## Domande Aperte

- Come si modella l'emergenza in SysML?
- Qual e il limite del V-Model per sistemi adattativi/complessi?
- Come si integra SE con approcci agile per sistemi cyber-fisici?

---

## Fonti Disponibili nel Wiki

- [[SEBoK v2.7]] — enciclopedia SE (INCOSE/IEEE); fondamenti, lifecycle, MBSE, applicazioni
- [[Holt - Systems Engineering Demystified]] — MBSE, SysML, ontologie (Packt 2023)
- [[Eisner - Essentials SE Management]] — project management + 30 elementi SE + architecting (Wiley 2002)
- [[Wasson - System Analysis Design Development]] — trattazione sistematica di 57 processi SE (Wiley 2006)
- [[Boardman Sauser - Systems Thinking]] — Conceptagon + System of Systems (CRC 2008)
- [[Satzinger Jackson Burd - System Analysis Design]] — SDLC + UML + OO per sistemi IT (Cengage 2009)
- [[Hollnagel Woods Leveson - Resilience Engineering]] — resilienza in sistemi sociotecnici; STAMP (Ashgate 2006)

## Fonti da Acquisire

- INCOSE (2023). *Systems Engineering Handbook*, 5th ed. Wiley.
- Maier, M.W. & Rechtin, E. (2009). *The Art of Systems Architecting*, 3rd ed. CRC Press.
- Friedenthal, S. et al. (2014). *A Practical Guide to SysML*, 3rd ed. MK/Elsevier.
- Blanchard, B.S. & Fabrycky, W.J. (2011). *Systems Engineering and Analysis*, 5th ed. Pearson.
