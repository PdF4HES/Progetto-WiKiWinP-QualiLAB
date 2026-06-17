---
type: book
title: "Resilience Engineering: Concepts and Precepts"
authors: ["Erik Hollnagel", "David D. Woods", "Nancy Leveson"]
year: 2006
edition: "1st ed."
publisher: "Ashgate"
domain: [ingegneria-sistemi, teoria-sistemi]
tags: [book, resilienza, sicurezza, STAMP, sociotecnico, incidenti, complessità]
status: in-coda
created: 2026-05-18
updated: 2026-05-18
raw_file: ".raw/E. Hollnagel, D. D. Woods, N. Leveson - Resilience Engineering. Concepts and Precepts.pdf"
related:
  - "[[Ingegneria dei Sistemi]]"
  - "[[Teoria dei Sistemi]]"
  - "[[Fenomeni Autocooperativi]]"
  - "[[Gharajedaghi - Systems Thinking]]"
---

# Hollnagel, Woods & Leveson — Resilience Engineering: Concepts and Precepts

**Editori:** Erik Hollnagel (Linköping), David D. Woods (Ohio State), Nancy Leveson (MIT)
**Anno:** 2006 | **Editore:** Ashgate | **pp.** ~414
**Nota:** Volume collettaneo; 21 capitoli + epilogo scritti da ~30 autori. Include mini-capitoli ("vignettes") di Yushi Fujita tra le parti.

> [!key-insight] Punto centrale
> La sicurezza non è l'assenza di fallimenti ma la **capacità di adattarsi con successo** a variazioni, perturbazioni e sorprese. La resilience engineering capovolge l'approccio tradizionale: invece di studiare cosa va storto (reactive), studia cosa va bene (proactive) e come i sistemi mantengono la funzione in condizioni di variazione continua.

---

## Struttura (3 parti, 21 capitoli + prologo/epilogo)

### Prologo: Resilience Engineering Concepts
*(Woods & Hollnagel)*
- Da "Hindsight" (retrovisore, ricerca delle cause) a "Foresight" (prospettiva, anticipazione)
- Da sicurezza reattiva a sicurezza proattiva
- Definizione di resilienza: adattamento e anticipazione, non solo recupero

### Parte I — Emergence (cap. 1–7)

| Cap. | Autore | Tema |
|------|--------|------|
| 1 | Hollnagel | Resilience: the Challenge of the Unstable — Understanding Accidents; Anticipating Risks |
| 2 | Woods | Essential Characteristics of Resilience — Dynamic Balancing Acts |
| 3 | Hale & Heijer | Defining Resilience — Pictures of Resilience; Road Traffic |
| 4 | Pariès | Complexity, Emergence, Resilience — da emergenza a resilienza |
| 5 | Westrum | A Typology of Resilience Situations — Regular/Irregular/Unexampled threats; Foresee/Cope/Recover |
| 6 | Woods & Cook | Incidents — Markers of Resilience or Brittleness? — Decompensation |
| 7 | Dekker | Resilience Engineering: Emergence of Confused Consensus — Drift into Failure; Work as Imagined vs Work as Actually Done |

### Parte II — Cases and Processes (cap. 8–16)

| Cap. | Autore | Tema |
|------|--------|------|
| 8 | Leveson et al. | Engineering Resilience into Safety-Critical Systems — **STAMP** |
| 9 | Hale & Heijer | Is Resilience Really Necessary? Railway Track Maintenance |
| 10 | Axelsson | Structure for Management of Weak and Diffuse Signals |
| 11 | McDonald | Organizational Resilience and Industrial Risk |
| 12 | Dijkstra | Safety Management in Airlines — From Safety to Resilience |
| 13 | Cook & Nemeth | Taking Things in One's Stride — Cognitive Features of Resilient Performances |
| 14 | Flin | Erosion of Managerial Resilience: From Vasa to NASA |
| 15 | Sundström & Hollnagel | Learning How to Create Resilience in Business Systems — Barings case |
| 16 | Amalberti | Optimum System Safety and Optimum System Resilience — Agonistic or Antagonistic? |

### Parte III — Challenges for a Practice of Resilience Engineering (cap. 17–21)

| Cap. | Autore | Tema |
|------|--------|------|
| 17 | Wreathall | Properties of Resilient Organizations |
| 18 | Hale et al. | Auditing Resilience — ARAMIS Audit Model |
| 19 | Woods | How to Design a Safety Organization — The 4 'I's |
| 20 | Cook & Woods | Distancing through Differencing — Obstacle to Organizational Learning |
| 21 | Hollnagel & Sundström | States of Resilience |

### Epilogo: Precepts
*(Hollnagel & Woods)*

---

## Concetti Chiave

### Resilienza: Definizione Operativa

**Resilienza** è la capacità intrinseca di un sistema di adattare il proprio funzionamento prima, durante, o dopo cambiamenti e perturbazioni, per poter continuare ad operare in condizioni attese o inattese.

Le 4 abilità della resilienza (sviluppate in edizioni successive):
1. **Anticipare**: riconoscere rischi potenziali futuri
2. **Monitorare**: tenere traccia degli sviluppi rilevanti
3. **Rispondere**: attivare risposte preplannate e adattate
4. **Imparare**: incorporare le lezioni dell'esperienza

### STAMP — Systems Theoretic Accident Model and Processes (Cap. 8)

Sviluppato da Nancy Leveson (MIT). STAMP considera gli incidenti come perdita di controllo, non come catene causali:

- **Controllo gerarchico**: i sistemi sono governati da strutture di controllo su più livelli
- Un incidente è un comportamento del sistema non controllato (unsafe control action)
- **STPA** (System-Theoretic Process Analysis): analisi dei rischi basata su STAMP; identifica scenari di pericolo strutturali

Differenza con Fault Tree Analysis: FTA cerca *catene di eventi*; STAMP cerca *inadeguatezze strutturali del sistema di controllo*.

### Drift into Failure (Cap. 7 — Dekker)

I sistemi complessi non falliscono per cause singole catastrofiche ma per una **deriva graduale** verso il pericolo:
- Le pressioni operative quotidiane spingono verso l'efficienza
- Piccole deviazioni vengono normalizzate ("normalization of deviance" — Vaughan/Challenger)
- Il sistema rimane funzionante ma diventa sempre più fragile
- Un evento "trigger" relativamente piccolo innesca il collasso

### Work as Imagined vs Work as Actually Done (Cap. 7)

Una distinzione fondamentale in safety science:
- **WAI** (Work as Imagined): come i procedure writers e i manager pensano che il lavoro avvenga
- **WAD** (Work as Actually Done): come il lavoro avviene realmente, con variazioni adattive

La sicurezza emerge dalla capacità dei lavoratori di adattarsi (WAD), non dal rispetto delle procedure (WAI). Standardizzare eccessivamente WAD verso WAI può eliminare le capacità adattive.

### Managerial Resilience (Cap. 14 — Flin)

Il caso Vasa (nave svedese affondata 1628) contrapposto al Columbia disaster (NASA 2003): in entrambi i casi, warning signals erano presenti ma ignorati a causa di pressioni organizzative. La **safety culture** è il predittore più forte della resilienza manageriale.

### Organizational Resilience Properties (Cap. 17 — Wreathall)

Un'organizzazione resiliente ha:
1. Top-level commitment to safety
2. Just Culture (si impara dagli errori senza punire)
3. Learning Culture (feedback attivo)
4. Flexibility (capacità di riconfigurarsi)
5. Awareness (situational awareness a tutti i livelli)

---

## Distinzione Resilienza / Robustezza

| | Robustezza | Resilienza |
|---|---|---|
| Strategia | Resist perturbations | Adapt to perturbations |
| Disegno | Build in margins | Build in flexibility |
| Focus | Known threats | Known + unknown threats |
| Limite | Fails when exceeded | Degrades gracefully |

---

## Connessioni nel Wiki

- [[Ingegneria dei Sistemi]] — la RE è un'estensione del safety engineering classico
- [[Teoria dei Sistemi]] — il drift into failure, il WAI/WAD, l'emergenza: tutti concetti GST applicati
- [[Gharajedaghi - Systems Thinking]] — entrambi trattano il comportamento controintuitivo dei sistemi sociotecnici
- [[Fenomeni Autocooperativi]] — la resilienza come proprietà emergente dall'organizzazione distribuita

---

## Domande Aperte

- La resilienza e la sicurezza sono realmente antagoniste (Amalberti cap. 16)?
- STAMP è applicabile a sistemi cyber-fisici complessi (autonomous vehicles, reti elettriche)?
- Come si misura operativamente la resilienza prima che un incidente la metta alla prova?
