---
type: book
address: c-000014
status: in-coda
domain: termodinamica-ingegneristica
tags:
  - book
  - termodinamica
  - ingegneria
  - cicli-termodinamici
  - volume-di-controllo
  - exergia
created: 2026-05-19
updated: 2026-05-19
related:
  - "[[Termodinamica dei Fenomeni Irreversibili]]"
  - "[[Cengel Boles - Thermodynamics Engineering Approach]]"
  - "[[Demirel - Nonequilibrium Thermodynamics]]"
  - "[[Reynolds - Energy]]"
---

# Moran & Shapiro — Fundamentals of Engineering Thermodynamics

Navigation: [[Wiki/books/_index]] | [[index]]

---

## Scheda

| Campo | Valore |
|-------|--------|
| Autori | Michael J. Moran (Ohio State) · Howard N. Shapiro (Iowa State) |
| Titolo | *Fundamentals of Engineering Thermodynamics* |
| Edizione | 5ª ed. (SI), Wiley 2006 (edizioni successive: 7ª 2011, 8ª 2014) |
| File vault | `.raw/M. J. Moran, H. N. Shapiro - Fundamentals of Engineering Thermodynamics.pdf` (53 413 righe estratte) |
| Rilevanza | **Media** — manuale ingegneristico standard; fondamentale per calcoli pratici |

---

## Sommario

Il testo di riferimento per la termodinamica dell'ingegneria (ingegneria meccanica, chimica, aerospaziale). Tratta la termodinamica classica (1° e 2° principio) applicata a sistemi reali: turbine, compressori, cicli Rankine/Brayton/Refrigerazione, combustione. La 5ª ed. include fuel cell e capitoli su exergia.

**Focus**: analisi di sistema ingegneristico (volume di controllo, bilancio di energia e di entropia), calcoli con tavole termodinamiche, efficienza isoentropica, analisi exergetica.

---

## Struttura (capitoli principali)

| Cap. | Tema |
|------|------|
| 1–2 | Sistema termodinamico, proprietà, 1° principio per sistemi chiusi |
| 3 | Proprietà delle sostanze pure; diagrammi p-v, T-s, h-s |
| 4 | Analisi dei volumi di controllo: bilancio di massa ed energia (SFEE) |
| 5 | Il 2° principio; ciclo di Carnot; entropia |
| 6 | Uso dell'entropia: bilancio di entropia per volumi di controllo |
| 7 | Exergia: disponibilità del lavoro; analisi exergetica |
| 8–10 | Cicli a vapore (Rankine); cicli a gas (Otto, Diesel, Brayton); refrigerazione |
| 11 | Miscele gassose; psicrometria |
| 12–13 | Combustione; bilanciamento di reazioni; entalpia di formazione |

---

## Concetti Fondamentali

**SFEE (Steady-Flow Energy Equation)** — bilancio energetico per volume di controllo a regime:
```
Q̇ - Ẇ = Σṁ_out(h + V²/2 + gz) - Σṁ_in(h + V²/2 + gz)
```
Base dell'analisi di turbine, compressori, scambiatori.

**Efficienza isoentropica**:
- Turbina: η_t = ẇ_t / ẇ_t,s (lavoro reale / lavoro isoentropico)
- Compressore: η_c = ẇ_c,s / ẇ_c (lavoro isoentropico / lavoro reale)
Misura le irreversibilità rispetto al caso ideale reversibile.

**Exergia (Available Work)**: massimo lavoro utile estraibile da un flusso di energia portandolo allo "stato morto" (T₀, p₀). Exergia = H - H₀ - T₀(S - S₀). La distruzione di exergia in un processo irreversibile = T₀ × generazione di entropia.

---

## Connessioni nel Wiki

- [[Cengel Boles - Thermodynamics Engineering Approach]]: il testo complementare; stessa materia, stile diverso
- [[Demirel - Nonequilibrium Thermodynamics]]: Demirel estende il concetto di exergia ai sistemi biologici e ai processi accoppiati
- [[Reynolds - Energy]]: termodinamica più accessibile e orientata ai flussi energetici naturali
- [[Termodinamica dei Fenomeni Irreversibili]]: questo testo è la termodinamica di equilibrio; la TIP è il passo successivo
- [[Kondepudi Prigogine - Modern Thermodynamics]]: lo stesso ponte concettuale (dall'equilibrio al non-equilibrio) in Kondepudi/Prigogine
