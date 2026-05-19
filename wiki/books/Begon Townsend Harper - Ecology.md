---
type: book
title: "Ecology: From Individuals to Ecosystems"
authors: ["Michael Begon", "Colin R. Townsend", "John L. Harper"]
year: 2006
edition: "4th ed."
publisher: "Blackwell Publishing"
domain: [ecodinamica, natural-systems]
tags: [book, ecologia, popolazioni, comunità, ecosistemi, food-webs, biodiversità]
status: in-coda
created: 2026-05-18
updated: 2026-05-18
raw_file: ".raw/M. Begon, C. R. Townsend, J. L. Harper - Ecology, from Individuals to Ecosystems.pdf"
related:
  - "[[Ecodinamica]]"
  - "[[Ecofisica]]"
  - "[[Biologia dei Sistemi]]"
  - "[[Odum Odum - Modeling for All Scales]]"
---

# Begon, Townsend & Harper — Ecology: From Individuals to Ecosystems (4th ed.)

**Autori:** Michael Begon (Liverpool), Colin R. Townsend (Otago), John L. Harper (Exeter)
**Anno:** 2006 | **Editore:** Blackwell | **pp.** ~738
**ISBN:** 978-1-4051-1117-1

> [!key-insight] Punto centrale
> L'ecologia è la scienza della distribuzione e abbondanza degli organismi e delle interazioni che le determinano. Opera su tre livelli gerarchici: organismo, popolazione, comunità/ecosistema. Il testo integra storia naturale, sperimentazione, modellistica matematica e applicazioni conservazionistiche.

---

## Struttura (3 parti, 22 capitoli + 3 capitoli applicati)

### Parte 1 — Organisms (cap. 1–7)

| Cap. | Titolo | Tema |
|------|--------|------|
| 1 | Organisms in their Environments: the Evolutionary Backdrop | Adattamento, nicchia, tradeoffs |
| 2 | Conditions | Temperature, pH, salinità: legge di Liebig, fattori limitanti |
| 3 | Resources | Risorse rinnovabili/non rinnovabili; accaparramento |
| 4 | Life, Death and Life Histories | r-selection vs K-selection; tabelle di vita (life tables) |
| 5 | Intraspecific Competition | Density-dependence; carrying capacity K; modello logistico |
| 6 | Dispersal, Dormancy and Metapopulations | Metapopolazioni (Levins); dispersione; frammentazione habitat |
| 7 | Applied ecology: Restoration, Biosecurity, Conservation | — |

### Parte 2 — Species Interactions (cap. 8–15)

| Cap. | Titolo |
|------|--------|
| 8 | Interspecific Competition |
| 9 | The Nature of Predation |
| 10 | The Population Dynamics of Predation |
| 11 | Decomposers and Detritivores |
| 12 | Parasitism and Disease |
| 13 | Symbiosis and Mutualism |
| 14 | Abundance |
| 15 | Applied: Pest Control and Harvest Management |

### Parte 3 — Communities and Ecosystems (cap. 16–22)

| Cap. | Titolo |
|------|--------|
| 16 | The Nature of the Community: Patterns in Space and Time |
| 17 | The Flux of Energy through Ecosystems |
| 18 | The Flux of Matter through Ecosystems |
| 19 | The Influence of Population Interactions on Community Structure |
| 20 | Food Webs |
| 21 | Patterns in Species Richness |
| 22 | Applied: Management Based on Succession, Food Webs, Ecosystem Functioning, Biodiversity |

---

## Concetti Chiave

### Crescita della Popolazione e Density Dependence (Cap. 5)

Modello logistico (Verhulst-Pearl):
```
dN/dt = rN · (K - N)/K
```
- N = dimensione della popolazione
- r = tasso intrinseco di crescita (max growth rate senza limiti)
- K = carrying capacity (capacità portante dell'ambiente)

Quando N → K: crescita rallenta → punto fisso stabile. Forma sigmoide della curva di crescita.

### Life Tables e Tabelle Vitali (Cap. 4)

Tabella vitale di una coorte (cohort life table):
| x | l(x) | m(x) | l(x)·m(x) |
|---|------|------|-----------|
| Classe d'età | Sopravvivenza | Fecondità | Contributo a R₀ |

- **R₀** = net reproductive rate (numero medio di figlie per femmina in una vita)
- **λ** = finite rate of increase (R₀ per generazione)
- **r** = intrinsic rate of natural increase (continuo)

### Modello di Lotka-Volterra (Cap. 10)

Equazioni classiche predatore-preda (→ vedi anche Bertuglia Vaio cap. 12):
```
dN/dt = rN - aNP   (preda)
dP/dt = baNP - mP  (predatore)
```
Oscillazioni periodiche nello spazio delle fasi. La realtà è più ricca: la risposta funzionale (Holling, tipi I/II/III) e il delay temporale producono dinamiche più complesse, incluso il caos.

### Reti Trofiche e Food Webs (Cap. 20)

Le reti trofiche descrivono chi mangia chi:
- **Produttori** (autotrofi) → **Erbivori** → **Carnivori** → **Decompositori**
- **Livelli trofici**: energia si perde ad ogni trasferimento (~90%)
- **Lunghezza delle catene alimentari**: limitata dall'efficienza energetica
- **Keystone species**: specie con impatto sproporzionato sulla struttura della comunità
- **Cascate trofiche**: la rimozione di un predatore apicale propaga effetti verso il basso

### Flusso di Energia (Cap. 17)

```
Produzione Primaria Lorda (GPP) 
  - Respirazione piante 
= Produzione Primaria Netta (NPP)
  → erbivori → carnivori → decompositori
```
- **Efficienza ecologica**: ~10% di energia trasferita da un livello trofico al successivo
- **Biomassa** e **energia** diminuiscono ad ogni livello

### Flusso di Materia (Cap. 18)

Cicli biogeochimici: carbonio, azoto, fosforo, acqua. A differenza dell'energia (che fluisce linearmente), la materia è ciclica. Perturbazioni antropiche (eutrofizzazione, acidificazione) alterano i cicli.

### Metapopolazioni (Cap. 6 — Levins 1969)

Una **metapopolazione** è un insieme di sottopopolazioni locali collegate da dispersione:
- Ogni patch può ospitare/perdere una sottopopolazione (colonizzazione/estinzione locale)
- La metapopolazione persiste anche quando singole patch si estinguono
- Critica per la biologia della conservazione: frammentazione dell'habitat aumenta il rischio di estinzione globale

---

## Connessioni nel Wiki

- [[Ecodinamica]] — Begon è la fonte principale per questa pagina concettuale
- [[Ecofisica]] — il flusso di energia (cap. 17) si collega alla legge di allometria di West
- [[Odum Odum - Modeling for All Scales]] — Odum usa gli stessi concetti (NPP, reti trofiche) in chiave di modellistica
- [[Bertuglia Vaio - Nonlinearity Chaos Complexity]] — il modello Volterra-Lotka appare in entrambi
- [[Biologia dei Sistemi]] — le reti trofiche sono un caso di rete biologica (network motifs)

---

## Domande Aperte

- Le reti trofiche reali mostrano comportamento caotico (come previsto da Volterra-Lotka)? Come si riconosce?
- Il concetto di resilienza ecologica (Holling) è formalmente equivalente alla resilienza ingegneristica di Hollnagel?
- Come si modella la scomparsa di una keystone species in un sistema SysML o con system dynamics?
