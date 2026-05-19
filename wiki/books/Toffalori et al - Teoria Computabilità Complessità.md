---
type: book
title: "Teoria della computabilità e della complessità"
authors: ["Carlo Toffalori", "Flavio Corradini", "Stefano Leonesi", "Stefano Mancini"]
year: 2005
edition: "1st ed."
publisher: "McGraw-Hill Italia"
domain: [teoria-sistemi]
tags: [book, computabilità, complessità, Turing, P-NP, algoritmi, fondamenti-informatica]
status: in-coda
created: 2026-05-18
updated: 2026-05-18
raw_file: ".raw/C. Toffalori, F. Corradini, S. Leonesi, S. Mancini - Teoria della Computabilità e Complessità.pdf"
related:
  - "[[Teoria dei Sistemi]]"
  - "[[Fenomeni Autocooperativi]]"
---

# Toffalori, Corradini, Leonesi, Mancini — Teoria della computabilità e della complessità

**Autori:** Docenti di Logica Matematica, Ingegneria del Software, Matematica e Informazione Quantistica — Università di Camerino
**Anno:** 2005 | **Editore:** McGraw-Hill Italia | **pp.** ~300
**ISBN:** 88-386-6228-2

> [!key-insight] Punto centrale
> Tre domande fondamentali: *Che cos'è un algoritmo?* (computabilità), *Quali problemi si possono risolvere algoritmicamente?* (decidibilità), *Quali problemi sono risolvibili in modo efficiente?* (complessità). Il testo tratta queste domande rigorosamente e include un'introduzione alla **computazione quantistica** (cap. finale).

---

## Struttura (2 parti, 12 capitoli)

### Parte A — Teoria della Computabilità (cap. 1–6)

| Cap. | Titolo | Tema |
|------|--------|------|
| 1 | Introduzione | Breve preistoria; problemi matematici; decalogo per buoni algoritmi |
| 2 | Le Macchine di Turing | Definizione formale; alfabeti, stringhe, linguaggi; MT deterministiche/non-deterministiche; Tesi di Church-Turing |
| 3 | Problemi senza Soluzione | Diagonalizzazione; macchina universale; **Problema dell'Arresto**; insiemi decidibili e semi-decidibili; 10° problema di Hilbert; Kleene & Rice |
| 4 | Funzioni Ricorsive | Calcolabilità secondo Church; funzioni parziali ricorsive; equivalenza Church-Turing |
| 5 | Calcolabilità e Grammatiche | Gerarchia di Chomsky; linguaggi regolari/liberi/dipendenti dal contesto; automi |
| 6 | Calcolabilità e Linguaggi di Programmazione | Linguaggio WHILE (tipo Pascal); programmi WHILE-calcolabili; equivalenza con MT |

### Parte B — Teoria della Complessità (cap. 7–12)

| Cap. | Titolo | Tema |
|------|--------|------|
| 7 | Complessità | Misurare la complessità; time e space complexity |
| 8 | Classi di Complessità Temporale | **Classe P**; Tesi di Edmonds-Cook-Karp; **Classe NP**; MT non-deterministiche; **P=NP?**; NP-completezza; **Teorema di Cook-Levin**; altri problemi NP-completi; coNP; gerarchia polinomiale; EXPTIME |
| 9 | Complessità, Logica e Circuiti | Logica proposizionale; formule quantificate (QBF); circuiti booleani; circuiti e NP-completezza |
| 10 | Classi di Complessità Spaziale | PSPACE; L; NPSPACE; NL; **Teorema di Savitch**; NL=coNL; PSPACE-completezza |
| 11 | Classi di Complessità Probabilistiche | Primality testing probabilistico; BPP; RP |
| 12 | Computazione Quantistica | Approccio quantistico; qubits; algoritmo di Shor; algoritmo di Grover |

---

## Concetti Chiave

### Macchina di Turing (Cap. 2)

Una MT è una macchina astratta con:
- Nastro infinito diviso in celle (ogni cella: un simbolo)
- Testina di lettura/scrittura
- Insieme finito di stati Q (inclusi q_initial, q_accept, q_reject)
- Funzione di transizione δ: Q × Σ → Q × Σ × {L, R}

**Tesi di Church-Turing**: tutto ciò che è intuitivamente calcolabile è calcolabile da una MT. (Tesi, non teorema: non dimostrabile formalmente.)

### Il Problema dell'Arresto (Cap. 3)

**Teorema (Turing 1936):** Il problema di determinare se una MT generica si ferma su un input generico è **indecidibile** (non esiste algoritmo che risolva il problema in generale).

**Dimostrazione**: per diagonalizzazione. Supponi esista un programma H che decide l'arresto. Costruisci D che chiama H su se stesso e fa il contrario. Contraddizione → H non può esistere.

**Corollario**: esistono infiniti problemi matematici senza soluzione algoritmica.

### La Classe P (Cap. 8)

**P** = insieme dei problemi decidibili in tempo *polinomiale* da una MT deterministica.
```
P = ∪_{k≥1} DTIME(n^k)
```
**Tesi di Edmonds-Cook-Karp**: P è la classe dei problemi "efficientemente risolvibili" nella pratica (heuristica, non dimostrata formalmente).

### La Classe NP (Cap. 8)

**NP** = problemi la cui soluzione (se esiste) può essere *verificata* in tempo polinomiale.

Equivalentemente: problemi risolvibili in tempo polinomiale da una MT non-deterministica.

**P ⊆ NP** (ovvio). Il quesito fondamentale: **P = NP?** (il problema del millennio del Clay Institute, $1M di premio).

La maggioranza dei teorici crede che P ≠ NP, ma non è stato dimostrato.

### Teorema di Cook-Levin (Cap. 8)

**SAT** (soddisfacibilità di formule booleane in forma normale congiuntiva) è **NP-completo**.

Implicazione: se SAT ∈ P, allora P = NP e tutti i problemi NP sono risolvibili efficientemente.

**Problemi NP-completi notevoli** (via riduzioni da SAT):
- 3-SAT, Vertex Cover, Clique, Independent Set
- Traveling Salesman Problem (TSP)
- Integer Linear Programming
- Graph Coloring

### Teorema di Savitch (Cap. 10)

**NPSPACE = PSPACE**: lo spazio non-deterministico polinomiale coincide con quello deterministico polinomiale. (Molto più facile per lo spazio che per il tempo!)

### Computazione Quantistica (Cap. 12)

- **Qubit**: stato quantistico in sovrapposizione di |0⟩ e |1⟩
- **Algoritmo di Shor**: fattorizzazione in tempo polinomiale quantistico (→ critico per RSA/crittografia!)
- **Algoritmo di Grover**: ricerca non strutturata in O(√N) invece di O(N)

---

## La Gerarchia di Complessità

```
L ⊆ NL ⊆ P ⊆ NP ⊆ PSPACE ⊆ EXPTIME ⊆ ...
```
Non tutte le inclusioni sono note essere strette. È dimostrato che L ≠ PSPACE e P ≠ EXPTIME.

---

## Connessioni nel Wiki

- [[Teoria dei Sistemi]] — la complessità computazionale è il limite formale alla *calcolabilità* dei modelli di sistemi complessi
- [[Fenomeni Autocooperativi]] — molti problemi di ottimizzazione su sistemi auto-organizzanti sono NP-hard
- [[Bertuglia Vaio - Nonlinearity Chaos Complexity]] — la complessità computazionale ≠ la complessità dei sistemi dinamici, ma si toccano nella riflessione sui limiti della matematica (parte 3 di Bertuglia)

---

## Domande Aperte

- Il comportamento caotico implica intrinsecamente NP-hardness nel predire l'evoluzione del sistema?
- La computazione quantistica risolve problemi di ottimizzazione in sistemi complessi che sono oggi NP-hard?
- Esiste un legame formale tra l'indecidibilità di Turing e l'imprevedibilità dei sistemi caotici?
