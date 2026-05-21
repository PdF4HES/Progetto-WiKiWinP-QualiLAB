---
agent: arxiv-collect
version: "1.0"
last_run: null
settings:
  max_results_per_category: 5
  days_back: 30
  papers_path: "Wiki/papers"
  sort_by: submittedDate
  sort_order: descending

categories:

  # ── PHYSICS ────────────────────────────────────────────────────────────────
  - code: cond-mat.dis-nn
    name: "Disordered Systems and Neural Networks"
    group: Physics
    enabled: true

  - code: cond-mat.stat-mech
    name: "Statistical Mechanics"
    group: Physics
    enabled: true

  - code: nlin.AO
    name: "Adaptation and Self-Organizing Systems"
    group: Physics
    enabled: true

  - code: nlin.CG
    name: "Cellular Automata and Lattice Gases"
    group: Physics
    enabled: true

  - code: nlin.CD
    name: "Chaotic Dynamics"
    group: Physics
    enabled: true

  - code: nlin.SI
    name: "Exactly Solvable and Integrable Systems"
    group: Physics
    enabled: true

  - code: nlin.PS
    name: "Pattern Formation and Solitons"
    group: Physics
    enabled: true

  - code: physics.bio-ph
    name: "Biological Physics"
    group: Physics
    enabled: true

  - code: physics.chem-ph
    name: "Chemical Physics"
    group: Physics
    enabled: true

  - code: physics.class-ph
    name: "Classical Physics"
    group: Physics
    enabled: true

  - code: physics.comp-ph
    name: "Computational Physics"
    group: Physics
    enabled: true

  - code: physics.data-an
    name: "Data Analysis, Statistics and Probability"
    group: Physics
    enabled: true

  - code: physics.flu-dyn
    name: "Fluid Dynamics"
    group: Physics
    enabled: true

  - code: physics.hist-ph
    name: "History and Philosophy of Physics"
    group: Physics
    enabled: true

  - code: quant-ph
    name: "Quantum Physics"
    group: Physics
    enabled: true

  # ── MATHEMATICS ────────────────────────────────────────────────────────────
  - code: math.AG
    name: "Algebraic Geometry"
    group: Math
    enabled: true

  - code: math.AT
    name: "Algebraic Topology"
    group: Math
    enabled: true

  - code: math.AP
    name: "Analysis of PDEs"
    group: Math
    enabled: true

  - code: math.CT
    name: "Category Theory"
    group: Math
    enabled: true

  - code: math.CA
    name: "Classical Analysis and ODEs"
    group: Math
    enabled: true

  - code: math.DG
    name: "Differential Geometry"
    group: Math
    enabled: true

  - code: math.DS
    name: "Dynamical Systems"
    group: Math
    enabled: true

  - code: math.FA
    name: "Functional Analysis"
    group: Math
    enabled: true

  - code: math.GN
    name: "General Topology"
    group: Math
    enabled: true

  - code: math.GT
    name: "Geometric Topology"
    group: Math
    enabled: true

  - code: math.GR
    name: "Group Theory"
    group: Math
    enabled: true

  - code: math.HO
    name: "History and Overview"
    group: Math
    enabled: true

  - code: math.IT
    name: "Information Theory (Math)"
    group: Math
    enabled: true

  - code: math.LO
    name: "Logic"
    group: Math
    enabled: true

  - code: math-ph
    name: "Mathematical Physics"
    group: Math
    enabled: true

  - code: math.NA
    name: "Numerical Analysis"
    group: Math
    enabled: true

  - code: math.OA
    name: "Operator Algebras"
    group: Math
    enabled: true

  - code: math.QA
    name: "Quantum Algebra"
    group: Math
    enabled: true

  - code: math.RA
    name: "Rings and Algebras"
    group: Math
    enabled: true

  # ── COMPUTER SCIENCE ───────────────────────────────────────────────────────
  - code: cs.AI
    name: "Artificial Intelligence"
    group: CS
    enabled: true

  - code: cs.CL
    name: "Computation and Language"
    group: CS
    enabled: true

  - code: cs.GT
    name: "Computer Science and Game Theory"
    group: CS
    enabled: true

  - code: cs.DM
    name: "Discrete Mathematics"
    group: CS
    enabled: true

  - code: cs.DC
    name: "Distributed, Parallel, and Cluster Computing"
    group: CS
    enabled: true

  - code: cs.ET
    name: "Emerging Technologies"
    group: CS
    enabled: true

  - code: cs.FL
    name: "Formal Languages and Automata Theory"
    group: CS
    enabled: true

  - code: cs.IT
    name: "Information Theory (CS)"
    group: CS
    enabled: true

  - code: cs.LO
    name: "Logic in Computer Science"
    group: CS
    enabled: true

  - code: cs.MA
    name: "Multiagent Systems"
    group: CS
    enabled: true

  - code: q-bio.NC
    name: "Neurons and Cognition"
    group: CS
    enabled: true

  - code: cs.SY
    name: "Systems and Control"
    group: CS
    enabled: true
---

# ArXiv Collect — Configurazione Agente

Per avviare la raccolta: `/arxiv-collect`

## Impostazioni

| Parametro | Valore | Note |
|-----------|--------|------|
| `max_results_per_category` | 5 | Paper per categoria per sessione |
| `days_back` | 7 | Giorni indietro per la ricerca |
| `papers_path` | wiki/papers | Cartella destinazione note |
| `sort_by` | submittedDate | Ordine risultati |

## Come modificare

- **Disabilitare una categoria**: cambia `enabled: true` → `enabled: false`
- **Più paper per categoria**: aumenta `max_results_per_category`
- **Finestra temporale più ampia**: aumenta `days_back` (es. 30 per primo avvio)
- **Aggiungere categorie**: aggiungi un blocco nella sezione corretta

## Categorie per gruppo

| Gruppo | Categorie abilitate |
|--------|---------------------|
| Physics | 15 |
| Math | 19 |
| CS | 12 |
| **Totale** | **46** |
