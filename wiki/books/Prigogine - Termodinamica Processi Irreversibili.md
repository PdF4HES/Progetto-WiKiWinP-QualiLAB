---
type: book
address: c-000007
status: in-coda
domain: termodinamica-irreversibile
tags:
  - book
  - Prigogine
  - TIP
  - Onsager
  - termodinamica-lineare
  - italiano
created: 2026-05-19
updated: 2026-05-19
related:
  - "[[Termodinamica dei Fenomeni Irreversibili]]"
  - "[[Kondepudi Prigogine - Modern Thermodynamics]]"
  - "[[De Groot Mazur - Non-Equilibrium Thermodynamics]]"
  - "[[Prigogine Nicolis - Self-Organization Non-Equilibrium]]"
---

# Prigogine — Termodinamica dei Processi Irreversibili

Navigation: [[Wiki/books/_index]] | [[Termodinamica dei Fenomeni Irreversibili]] | [[index]]

---

## Scheda

| Campo | Valore |
|-------|--------|
| Autore | Ilya Prigogine (1917–2003) |
| Titolo originale | *Introduction to Thermodynamics of Irreversible Processes* (Wiley, 1955; 3ª ed. 1967) |
| Titolo IT | *Termodinamica dei Processi Irreversibili* |
| File vault | `.raw/I. Prigogine - Termodinamica dei Processi Irreversibili.pdf` (scansione italiana) |
| Nota | Contenuto da conoscenza di addestramento |
| Rilevanza | **Alta** — il testo tecnico fondativo della TIP lineare |

---

## Sommario

Prigogine presenta la termodinamica dei processi irreversibili (TIP) in modo sistematico, estendendo la termodinamica classica ai sistemi fuori equilibrio. Questo è il testo che ha fondato il campo formalmente, sviluppato a partire dai lavori di Onsager (1931) e dalla scuola di Bruxelles.

**Contenuto centrale**: la TIP lineare (prossima all'equilibrio) con le relazioni di reciprocità di Onsager, il teorema della minima produzione di entropia, e i coefficienti di trasporto accoppiati. La 3ª edizione aggiunge i primi risultati sui regimi non lineari.

---

## Struttura

| Capitolo | Tema |
|----------|------|
| 1 | Principi base della termodinamica; entropia |
| 2 | Sistemi aperti; bilancio di entropia |
| 3 | Forze e flussi termodinamici; produzione di entropia |
| 4 | Relazioni di reciprocità di Onsager |
| 5 | Applicazioni: termosmosi, effetto Dufour/Soret, diffusione termica |
| 6 | Sistemi chimici; affinità e produzione di entropia |
| 7 | Teorema di minima produzione di entropia |
| 8 (3ª ed.) | Instabilità lontane dall'equilibrio; anticipazione delle strutture dissipative |

---

## Concetti Fondamentali

**Bilancio di entropia per sistemi aperti**:
```
dS/dt = d_e S/dt + σ
σ = Σ_k J_k X_k ≥ 0
```
- σ: produzione interna (sempre ≥ 0)
- J_k: flussi (calore, materia, carica, reazione)
- X_k: forze coniugate (gradiente di temperatura, potenziale chimico, affinità)

**Relazioni di Onsager**: L_ij = L_ji (simmetria del tensore dei coefficienti fenomenologici). Derivano dal principio di bilancio microscopico dettagliato (microscopic reversibility). Permettono di collegare fenomeni come diffusione termica e effetto Soret.

**Teorema di minima produzione di entropia**: per un sistema in regime stazionario nel regime lineare, con almeno una forza fissa e una libera, lo stato stazionario corrisponde al minimo della produzione di entropia compatibile con i vincoli. Criterio evolutivo: il sistema "sceglie" la configurazione meno dissipativa permessa.

> [!key-insight] Limite del teorema
> Il teorema vale solo in regime lineare (vicino all'equilibrio). Nel regime non lineare (lontano dall'equilibrio), non esiste in generale un principio di minimo per la produzione di entropia — e qui emergono le strutture dissipative.

---

## Connessioni nel Wiki

- [[Termodinamica dei Fenomeni Irreversibili]]: il capitolo di wiki sulla TIP si basa in larga misura su questo testo
- [[Kondepudi Prigogine - Modern Thermodynamics]]: la rielaborazione moderna e più completa (con strutture dissipative)
- [[De Groot Mazur - Non-Equilibrium Thermodynamics]]: approccio alternativo, più formale e completo sulla TIP classica
- [[Prigogine Nicolis - Self-Organization Non-Equilibrium]]: il passo successivo: strutture dissipative e auto-organizzazione
- [[Demirel - Nonequilibrium Thermodynamics]]: testo moderno con applicazioni ingegneristiche dei concetti introdotti qui
