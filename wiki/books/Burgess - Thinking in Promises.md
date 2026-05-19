---
type: book
title: "Thinking in Promises: Designing Systems for Cooperation"
authors: ["Mark Burgess"]
year: 2015
edition: "1st ed."
publisher: "O'Reilly Media"
domain: [teoria-sistemi, ingegneria-sistemi]
tags: [book, promise-theory, cooperazione, autonomia, agenti, infrastruttura]
status: in-coda
created: 2026-05-18
updated: 2026-05-18
raw_file: ".raw/M. Burgess -  Thinking in Promises, Designing Systems for Cooperation.epub"
related:
  - "[[Teoria dei Sistemi]]"
  - "[[Ingegneria dei Sistemi]]"
  - "[[Boardman Sauser - Systems Thinking]]"
note: "EPUB binario non leggibile direttamente. Contenuto da conoscenza di training."
---

# Burgess — Thinking in Promises

**Autore:** Mark Burgess (fondatore di CFEngine; informatico e fisico teorico norvegese)
**Anno:** 2015 | **Editore:** O'Reilly | **pp.** ~180
**Contesto:** Burgess ha sviluppato la **Promise Theory** inizialmente per la gestione dell'infrastruttura IT (CFEngine), poi l'ha generalizzata come teoria della cooperazione tra agenti autonomi.

> [!key-insight] Punto centrale
> Gli agenti autonomi cooperano attraverso **promesse** (impegni volontari su comportamento futuro), non attraverso obblighi o comandi. Questo cambia il paradigma di design dei sistemi: invece di progettare controllo centralizzato, si progettano contratti distribuiti di comportamento atteso.

---

## Struttura (8 capitoli circa)

1. **Promises: What They Are** — definizione di promessa; differenza da obbligo e impegno; il concetto di agente autonomo
2. **Agents and Autonomy** — l'agente come unità di analisi; proprietà degli agenti; autonomy come precondizione
3. **Cooperation by Agreement** — come gli agenti cooperano attraverso promesse reciproche; trust e verification
4. **Promises in Scope** — contesti delle promesse; scaling; composizione
5. **Services as Promises** — service-oriented design come promise theory applicata; SLA come promesse
6. **Information and Intent** — come le promesse trasmettono informazione; intention vs. compliance
7. **Designing Cooperative Systems** — principi di design basati su promises; evitare anti-patterns
8. **Applied Promise Theory** — IT infrastructure; reti di computer; sistemi distribuiti

---

## Concetti Chiave

### Definizione di Promessa

Una **promessa** è un impegno *volontario* e *unilaterale* fatto da un agente riguardo al proprio comportamento futuro. È:
- **Unilaterale**: l'agente promette per se stesso, non per altri
- **Volontaria**: non può essere coercita (un obbligo imposto non è una promessa)
- **Localizzata**: riguarda il comportamento dell'agente nel proprio ambito (scope)

Formalmente: π(a → b; body) significa "l'agente a promette all'agente b il comportamento body".

### Promesse vs. Obblighi vs. Comandi

| | Promessa | Obbligo | Comando |
|---|---------|---------|---------|
| Origine | Agente stesso | Autorità esterna | Controllore |
| Tipo | Volontaria | Imposta | Imposta |
| Trust | Self-certified | Delegated | Top-down |
| Scalabilità | Alta | Media | Bassa |

I sistemi basati su comandi centralizzati (es. puppet push) sono fragili: un nodo non raggiungibile non può ricevere comandi. I sistemi basati su promesse (CFEngine pull) sono resilienti: ogni agente controlla il proprio stato.

### Agenti Autonomi

Un **agente** è qualsiasi entità che:
1. Ha uno stato interno
2. Può prendere decisioni
3. Interagisce con l'ambiente

Gli agenti sono la *granularità fondamentale* del design. I sistemi complessi emergono dall'interazione di agenti che mantengono promesse reciproche.

### Services as Promises

Un **servizio** è un insieme di promesse che un agente fa agli utenti del servizio. I livelli di servizio (SLA) sono formalizzazioni di promesse:
- "Il server promette uptime ≥ 99.9%"
- "Il servizio promette tempo di risposta < 100ms al 95° percentile"

I **microservices** sono un esempio architetturale: ogni servizio definisce le proprie promesse (API) e non dipende dall'implementazione interna degli altri.

### Composizione delle Promesse

Le promesse si compongono: se A promette X e B promette Y, il sistema A+B promette X∩Y (l'intersezione delle garanzie). Questo permette di ragionare sulle proprietà dei sistemi composti.

### Anti-patterns del Design Centralizzato

Burgess identifica i problemi del design basato su controllo centralizzato:
- **Single point of failure**: il controllore centralizzato è il collo di bottiglia
- **Brittleness**: un agente irraggiungibile causa fallimento di sistema
- **Scalability ceiling**: il controllore non scala con il numero di agenti
- **Intent vs. Compliance gap**: il controllore non può verificare l'intent degli agenti

---

## Promise Theory e System of Systems

La Promise Theory è particolarmente potente per i **Systems of Systems** (SoS):
- Ogni componente del SoS è un agente autonomo
- La cooperazione avviene attraverso interfacce/contratti (promesse)
- Nessuna autorità centrale richiesta
- Questo corrisponde alla proprietà **Belonging** del modello ABCDE di Boardman (il componente *sceglie* di partecipare)

---

## Connessioni nel Wiki

- [[Teoria dei Sistemi]] — gli agenti autonomi sono l'unità delle teorie CAS (Complex Adaptive Systems)
- [[Ingegneria dei Sistemi]] — le promesse formalizzano i contratti tra componenti; analoga alle interfacce in SysML
- [[Boardman Sauser - Systems Thinking]] — la proprietà B (Belonging) del SoS corrisponde alla voluntariness delle promesse
- [[Hollnagel Woods Leveson - Resilience Engineering]] — sistemi distribuiti basati su promesse sono più resilienti di quelli centralizzati

---

## Domande Aperte

- Come si formalizzano le promesse in un linguaggio come SysML o BPMN?
- La Promise Theory è equivalente o complementare alla teoria dei contratti (Liskov, Meyer)?
- Come si gestisce la violazione di una promessa? Burgess prevede meccanismi di recovery?
