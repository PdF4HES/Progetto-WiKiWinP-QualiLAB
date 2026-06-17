---
type: book
title: "Systems Thinking: Managing Chaos and Complexity — A Platform for Designing Business Architecture"
authors: ["Jamshid Gharajedaghi"]
year: 2011
edition: "3rd ed."
publisher: "Morgan Kaufmann / Elsevier"
domain: [teoria-sistemi, ingegneria-sistemi]
tags: [book, systems-thinking, design-thinking, architettura, complessità, mess]
status: in-coda
created: 2026-05-18
updated: 2026-05-18
raw_file: ".raw/J. Gharajedaghi - Systems Thinking, Managing Chaos and Complexity - A Platform for Designing Business Architecture.pdf"
related:
  - "[[Teoria dei Sistemi]]"
  - "[[Ingegneria dei Sistemi]]"
  - "[[Fenomeni Autocooperativi]]"
---

# Gharajedaghi — Systems Thinking (3rd ed.)

**Autore:** Jamshid Gharajedaghi (Interact Institute, eredità intellettuale di Russell Ackoff)
**Anno:** 2011 | **Editore:** Morgan Kaufmann | **pp.** ~320

> [!key-insight] Punto centrale
> I sistemi sociali complessi non si "gestiscono" con ottimizzazione o controllo: si *progettano*. Il metodo è l'**interactive design** iterativo: si parte dal sistema ideale (come dovrebbe essere) e si approssima iterativamente al realizzabile. Il sistema non ha un'unica natura: è simultaneamente struttura, funzione e processo.

---

## Struttura (4 parti, 12 capitoli + epilogo)

### Parte 1 — System Philosophy: Il Nome del Diavolo
- **Cap. 1: How the Game Is Evolving** — imitazione, inerzia, subottimizzazione → cambiamento del gioco → i due paradigm shift: dalla gerarchia all'interdipendenza; dall'analisi al design

### Parte 2 — Systems Theory: La Natura della Bestia
- **Cap. 2: Systems Principles** — 5 principi fondamentali:
  1. Openness (sistemi aperti)
  2. Purposefulness (scopo, non solo funzione)
  3. Multidimensionality (struttura + funzione + processo)
  4. Emergent Property (proprietà emergenti)
  5. Counterintuitive Behavior (comportamento controintuitivo)
- **Cap. 3: Sociocultural System** — auto-organizzazione, sistemi legati dall'informazione, cultura come sistema operativo
- **Cap. 4: Development** — alienazione, polarizzazione, corruzione, terrorismo come ostruzioni allo sviluppo

### Parte 3 — Systems Methodology: La Logica della Follia
- **Cap. 5: Holistic Thinking** — processo iterativo di indagine; 5 dimensioni sistemiche (ricchezza, potere, bellezza, conoscenza, valore)
- **Cap. 6: Operational Thinking** — complessità (open loop/closed loop, lineare/nonlineare); iThink language; dinamica dei throughput systems
- **Cap. 7: Design Thinking** — design come metodologia sistemica; principi operativi; modular design; interactive design (idealizzazione → realizzazione progressiva → dissoluzione della "second-order machine"); elementi critici (measurement, vertical/horizontal/temporal compatibility, target costing)
- **Cap. 8: Formulating the Mess** — searching (systems analysis, obstruction analysis, system dynamics); mapping; telling the story (caso utility industry)
- **Cap. 9: Business Architecture** — confini e ambiente; purpose; functions; structure (output, input, market dimension, internal market economy); processes (planning/learning/control)

### Parte 4 — Systems Practice: Il Coraggioso
- **Cap. 10: The Oneida Nation** — case study: ricostruzione dell'architettura di una nazione nativa americana
- **Cap. 11: Butterworth Health System** — case study: sistema sanitario
- **Cap. 12: The Marriott Corporation** — case study: catena alberghiera

---

## Concetti Chiave

### Multidimensionalità (Cap. 2.3)

Un sistema ha tre dimensioni simultanee e indistinguibili:

| Dimensione | Domanda | Esempio |
|------------|---------|---------|
| **Struttura** | Come è organizzato? | Gerarchia, divisione del lavoro |
| **Funzione** | Cosa produce? | Output, servizi |
| **Processo** | Come opera? | Flussi, decisioni, cicli |

Affrontare solo una dimensione fallisce sempre. Le soluzioni "strutturali" (ristrutturazione) ignorano funzione e processo; le soluzioni "di processo" ignorano struttura.

### Mess vs Problem

Un **mess** è un'insieme di problemi interdipendenti che si manifestano come un'unica situazione caotica. Le sue proprietà:
- I problemi si causano reciprocamente (causalità circolare)
- Risolve un problema singolo → crea o aggrava altri
- Non ha una "soluzione" ottimale: va *dissolto*, non risolto

**Interactive Design** (cap. 7.5):
1. **Idealizzazione**: progetta il sistema ideale come se potessi ricominciare da zero
2. **Realizzazione — Successive Approximation**: identifica il massimo realizzabile oggi
3. **Dissolving the Second-Order Machine**: rimuovi le resistenze sistemiche all'implementazione

### Comportamento Controintuitivo (Cap. 2.5)

I sistemi complessi si comportano in modo opposto all'intuizione:
- Investire dove c'è il problema peggiorano le cose
- Le soluzioni "ovvie" amplificano il problema
- I sintomi sono spesso lontani (nel tempo e nello spazio) dalle cause
- → Forrester (System Dynamics): questo è il motivo per cui le politiche sociali spesso falliscono

---

## Business Architecture (Cap. 9)

Il framework di Gharajedaghi per progettare un'organizzazione:

```
Boundary & Environment
    → Purpose (mission, values, desired specs)
        → Functions (cosa produce il sistema)
            → Structure:
                  Output Dimension (prodotti/servizi)
                  Input Dimension (risorse)
                  Market Dimension (clienti)
                  Internal Market Economy
            → Processes:
                  Planning, Learning & Control
                  Measurement System
```

---

## Connessioni nel Wiki

- [[Teoria dei Sistemi]] — i 5 principi sistemici (cap. 2) sintetizzano la GST applicata al design
- [[Ingegneria dei Sistemi]] — l'architettura di business è analoga all'architettura di sistema
- [[Skyttner - General Systems Theory]] — quadro storico/teorico per i principi di Gharajedaghi
- [[Hollnagel Woods Leveson - Resilience Engineering]] — entrambi trattano sistemi sociotecnici e comportamento emergente
- [[Wasson - System Analysis Design Development]] — tecniche formali SE che complementano il design thinking

---

## Domande Aperte

- Il "mess formulation" ha una struttura formale analizzabile con system dynamics?
- Il design iterativo converge? Esiste un criterio di convergenza formale?
- Come si integra l'interactive design con l'approccio MBSE/SysML in un contesto industriale?
