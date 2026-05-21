# ArXiv Category Reference

Mappa completa: nome leggibile → codice API ArXiv.

## Physics

| Nome | Codice ArXiv |
|------|-------------|
| Disordered Systems and Neural Networks | `cond-mat.dis-nn` |
| Statistical Mechanics | `cond-mat.stat-mech` |
| Adaptation and Self-Organizing Systems | `nlin.AO` |
| Cellular Automata and Lattice Gases | `nlin.CG` |
| Chaotic Dynamics | `nlin.CD` |
| Exactly Solvable and Integrable Systems | `nlin.SI` |
| Pattern Formation and Solitons | `nlin.PS` |
| Biological Physics | `physics.bio-ph` |
| Chemical Physics | `physics.chem-ph` |
| Classical Physics | `physics.class-ph` |
| Computational Physics | `physics.comp-ph` |
| Data Analysis, Statistics and Probability | `physics.data-an` |
| Fluid Dynamics | `physics.flu-dyn` |
| History and Philosophy of Physics | `physics.hist-ph` |
| Quantum Physics | `quant-ph` |

## Mathematics

| Nome | Codice ArXiv |
|------|-------------|
| Algebraic Geometry | `math.AG` |
| Algebraic Topology | `math.AT` |
| Analysis of PDEs | `math.AP` |
| Category Theory | `math.CT` |
| Classical Analysis and ODEs | `math.CA` |
| Differential Geometry | `math.DG` |
| Dynamical Systems | `math.DS` |
| Functional Analysis | `math.FA` |
| General Topology | `math.GN` |
| Geometric Topology | `math.GT` |
| Group Theory | `math.GR` |
| History and Overview | `math.HO` |
| Information Theory | `math.IT` |
| Logic | `math.LO` |
| Mathematical Physics | `math-ph` |
| Numerical Analysis | `math.NA` |
| Operator Algebras | `math.OA` |
| Quantum Algebra | `math.QA` |
| Rings and Algebras | `math.RA` |

## Computer Science

| Nome | Codice ArXiv |
|------|-------------|
| Artificial Intelligence | `cs.AI` |
| Computation and Language | `cs.CL` |
| Computer Science and Game Theory | `cs.GT` |
| Discrete Mathematics | `cs.DM` |
| Distributed, Parallel, and Cluster Computing | `cs.DC` |
| Emerging Technologies | `cs.ET` |
| Formal Languages and Automata Theory | `cs.FL` |
| Information Theory | `cs.IT` |
| Logic in Computer Science | `cs.LO` |
| Multiagent Systems | `cs.MA` |
| Neurons and Cognition | `q-bio.NC` |
| Systems and Control | `cs.SY` |

## ArXiv API

Endpoint: `https://export.arxiv.org/api/query`

Query per categoria con filtro data:
```
search_query=cat:{CODE}+AND+submittedDate:[{YYYYMMDD}0000+TO+{YYYYMMDD}2359]
&sortBy=submittedDate&sortOrder=descending
&max_results={N}&start=0
```

Esempio — ultimi 7 giorni di cs.AI:
```
https://export.arxiv.org/api/query?search_query=cat:cs.AI+AND+submittedDate:[202605140000+TO+202605212359]&sortBy=submittedDate&sortOrder=descending&max_results=5
```

La risposta è XML Atom. Campi rilevanti per entry:
- `<id>` → URL completo (estrai l'ID dopo l'ultimo `/`)
- `<title>` → titolo paper
- `<author><name>` → autori (uno o più)
- `<summary>` → abstract
- `<published>` → data submission (es. `2025-01-15T00:00:00Z`)
- `<arxiv:primary_category term="...">` → categoria primaria
- `<category term="...">` → tutte le categorie
