---
type: concept
status: developing
domain: biologia-sistemi
tags:
  - concept
  - biologia
  - reti-biologiche
  - emergenza
  - biologia-sintetica
created: 2026-05-17
updated: 2026-05-17
related:
  - "[[Teoria dei Sistemi]]"
  - "[[Fenomeni Autocooperativi]]"
  - "[[Biochimica]]"
  - "[[Ecodinamica]]"
  - "[[Sintesi del Campo]]"
---

# Biologia dei Sistemi

Navigation: [[Wiki/natural-systems/_index|Natural Systems]] | [[Sintesi del Campo]] | [[index]]

---

## Definizione

La biologia dei sistemi (systems biology) studia gli organismi come sistemi integrati di componenti in interazione, piuttosto che come somme di parti isolate. L'obiettivo è comprendere le proprietà emergenti — come crescita, omeostasi, differenziazione cellulare — che non sono prevedibili dalla sola conoscenza delle singole molecole.

Nasce dalla convergenza di biologia molecolare, bioinformatica, fisica statistica e teoria dei sistemi, resa possibile dalle tecnologie omiche (genomica, proteomica, metabolomica).

---

## Fondatori e Contributi Chiave

**Denis Noble (1936-)**
Fisiologico britannico, uno dei fondatori. Il cuore come sistema: modellazione computazionale dell'azione del potenziale cardiaco (1960). Autore di *The Music of Life* (2006): critica al gene-centrismo, difesa di una visione sistemica della biologia.

**Leroy Hood (1938-)**
Biologo americano, pioniere delle tecnologie P4 (predictive, preventive, personalized, participatory medicine). Ha sviluppato il sequenziatore automatico di DNA e il concetto di medicina di sistema.

**Hiroaki Kitano (1961-)**
Informatico e biologo giapponese. Ha formalizzato la systems biology come disciplina. Ha fondato il Systems Biology Institute di Tokyo. Autore del manifesto *Systems Biology: A Brief Overview* (Science, 2002).

**Uri Alon (1969-)**
Fisico e biologo israeliano. Ha identificato i *network motifs*: schemi ricorrenti nelle reti di regolazione genica che hanno proprietà funzionali conservate (feed-forward loop, autoregolazione negativa). Autore di *An Introduction to Systems Biology* (2007), testo fondamentale del campo.

---

## Concetti Fondamentali

**Rete di Regolazione Genica (GRN)**
Grafo diretto in cui i nodi sono geni e gli archi rappresentano relazioni di attivazione/repressione trascrizionale. Determina l'identità cellulare e la risposta agli stimoli ambientali.

**Rete Metabolica**
Insieme delle reazioni chimiche di una cellula, organizzate in pathway. L'analisi del flusso metabolico (MFA) e il constraint-based modeling (FBA — Flux Balance Analysis) predicono i fenotipi metabolici senza richiedere parametri cinetici.

**Rete di Interazione Proteica (PPI)**
Grafo non diretto delle interazioni fisiche tra proteine. Proprietà emergente: i nodi ad alto grado (*hubs*) tendono a essere essenziali per la sopravvivenza cellulare.

**Network Motifs (Alon)**
Sottografi statisticamente sovrarappresentati nelle reti biologiche reali rispetto a reti casuali con lo stesso grado. Esempi:
- *Autoregolazione negativa*: accelera la risposta e riduce il rumore
- *Feed-forward loop coerente (C1-FFL)*: filtro passa-basso, ignora segnali transitori
- *Feed-forward loop incoerente (I1-FFL)*: generatore di impulsi, risposta adattiva

**Robustezza e Fragilità**
I sistemi biologici sono robusti rispetto alle perturbazioni tipiche (rumore molecolare, variazioni ambientali moderate) ma fragili rispetto a perturbazioni atipiche (patogeni, mutazioni oncogeniche). Trade-off fondamentale: robustezza ↔ fragilità.

**Modularità**
Le reti biologiche tendono a essere organizzate in moduli funzionali relativamente indipendenti. Consente l'evoluzione per variazione modulare senza rompere il sistema intero.

---

## Approcci Computazionali

| Approccio | Strumento | Scala |
|-----------|-----------|-------|
| ODE (equazioni differenziali ordinarie) | SBML, BioNetGen | pathway, cellula |
| Stocastico (Gillespie) | COPASI, StochKit | reazioni individuali |
| Flux Balance Analysis | COBRApy, Escher | metaboloma intero |
| Boolean networks | BoolNet | GRN qualitativa |
| Agent-based modeling | NetLogo, Repast | multi-cellulare |
| Machine learning | PyTorch, JAX | predizione fenotipo |

---

## Biologia Sintetica

Disciplina complementare: progetta e costruisce reti biologiche artificiali con proprietà desiderate (*design* invece di analisi). Usa i network motifs come mattoni:
- Circuiti oscillatori (repressori a ciclo — Elowitz & Leibler, 2000)
- Toggle switch bistabile (Gardner et al., 2000)
- Sistemi di quorum sensing ingegnerizzato

---

## Connessioni con gli Altri Domini

- [[Teoria dei Sistemi]]: la GRN è un sistema aperto con feedback; emergenza e olismo biologico
- [[Fenomeni Autocooperativi]]: differenziazione cellulare come biforcazione; reti booleane di Kauffman
- [[Biochimica]]: le reti metaboliche sono il substrato molecolare della biologia dei sistemi
- [[Ecodinamica]]: le stesse proprietà delle GRN (modularità, hubs, robustezza) si trovano nelle reti trofiche

---

## Domande Aperte

- Esiste una "teoria del tutto" per la biologia dei sistemi, analoga alla fisica teorica?
- Come si distingue la robustezza evolutivamente selezionata dalla robustezza fisica intrinseca?
- Come integrare dati omici eterogenei (genomica + proteomica + metabolomica) in un modello coerente?
- Il programma evolutivo-sviluppativo (evo-devo) è riducibile alla biologia dei sistemi?

---

## Fonti da Acquisire

- Alon, U. (2007). *An Introduction to Systems Biology*. CRC Press.
- Noble, D. (2006). *The Music of Life*. Oxford University Press.
- Kitano, H. (2002). Systems Biology: A Brief Overview. *Science*, 295(5560), 1662-1664.
- Alon, U. (2007). Network motifs: theory and experimental approaches. *Nature Reviews Genetics*, 8(6), 450-461.
- Elowitz, M.B. & Leibler, S. (2000). A synthetic oscillatory network. *Nature*, 403, 335-338.
- Palsson, B. (2015). *Systems Biology: Constraint-based Reconstruction and Analysis*. Cambridge.
