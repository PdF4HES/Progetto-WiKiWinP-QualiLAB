---
type: concept
status: developing
domain: termodinamica-irreversibile
tags:
  - concept
  - termodinamica
  - Prigogine
  - entropia
  - irreversibilita
created: 2026-05-17
updated: 2026-05-17
related:
  - "[[Fenomeni Autocooperativi]]"
  - "[[Teoria dei Sistemi]]"
  - "[[Sintesi del Campo]]"
---

# Termodinamica dei Fenomeni Irreversibili

Navigation: [[Wiki/concepts/_index]] | [[Sintesi del Campo]] | [[index]]

---

## Definizione

La termodinamica dei processi irreversibili (TIP, Thermodynamics of Irreversible Processes) studia i sistemi fisici fuori dall'equilibrio termodinamico. Mentre la termodinamica classica (di equilibrio) descrive stati stazionari, la TIP descrive la dinamica dei flussi, le forze generalizzate e la produzione di entropia.

---

## Fondatori e Contributi Chiave

**Lars Onsager (1903-1976) — Premio Nobel Chimica 1968**
Fisico norvegese-americano. Relazioni di reciprocita di Onsager (1931): in regime lineare (vicino all'equilibrio), i coefficienti di accoppiamento incrociato tra flussi e forze sono simmetrici. Base della TIP lineare.

**Ilya Prigogine (1917-2003) — Premio Nobel Chimica 1977**
Fisico-chimico belga-russo. Estensione della TIP ai regimi non lineari e lontani dall'equilibrio. Teorema della minima produzione di entropia (regime lineare). Strutture dissipative: ordine che emerge dal caos lontano dall'equilibrio.

**Isabelle Stengers (1949-)**
Filosofa, collaboratrice di Prigogine. Elaborazione filosofica del concetto di irreversibilita e del "tempo creativo".

---

## Secondo Principio e Produzione di Entropia

Il secondo principio della termodinamica afferma che l'entropia totale di un sistema isolato non diminuisce:

```
dS/dt >= 0  (sistema isolato)
```

Per sistemi aperti, la variazione di entropia si decompone:

```
dS = d_e S + d_i S
```

dove:
- `d_e S`: flusso di entropia dall'ambiente (puo essere negativo)
- `d_i S >= 0`: produzione interna di entropia (sempre non negativa)

Un sistema aperto puo ridurre la propria entropia importando "negentropia" dall'ambiente.

---

## Regimi

### Regime Lineare (vicino all'equilibrio)

- Flussi proporzionali alle forze: J_i = sum_k L_ik X_k
- Relazioni di Onsager: L_ik = L_ki
- Teorema di minima produzione di entropia (Prigogine): lo stato stazionario minimizza la produzione di entropia

### Regime Non Lineare (lontano dall'equilibrio)

- Flussi non proporzionali alle forze
- Possibile instabilita: piccole fluttuazioni possono portare a rottura di simmetria
- Biforcazioni: il sistema sceglie tra piu stati stabili
- Strutture dissipative: strutture ordinate che si mantengono grazie a flussi di energia/materia

---

## Strutture Dissipative

Termine coniato da Prigogine. Strutture spazio-temporali macroscopiche che emergono in sistemi aperti lontani dall'equilibrio. Esempi:

- **Celle di Benard**: convezione organizzata in un fluido riscaldato dal basso
- **Reazione di Belousov-Zhabotinsky**: oscillazioni chimiche periodiche
- **Strutture biologiche**: la vita come struttura dissipativa per eccellenza

La struttura si mantiene dissipando energia: ordine a spese di entropia ambientale.

---

## Connessioni

- [[Fenomeni Autocooperativi]]: le strutture dissipative sono il meccanismo fisico dell'auto-organizzazione
- [[Teoria dei Sistemi]]: i sistemi aperti di Bertalanffy sono termodinamicamente sistemi lontani dall'equilibrio
- Biologia: il metabolismo come mantenimento di struttura dissipativa

---

## Domande Aperte

- Come si raccordano TIP e meccanica statistica a livello microscopico?
- Il teorema di minima entropia vale solo in regime lineare: quali principi valgono nel non lineare?
- Qual e il ruolo delle fluttuazioni nell'innesco delle biforcazioni?

---

## Fonti Disponibili nel Wiki

- [[Reynolds - Energy]] — termodinamica classica (1° e 2° principio, entropia, efficienza di Carnot) come fondamento
- [[Bertuglia Vaio - Nonlinearity Chaos Complexity]] — strutture dissipative come caso di complessità emergente (Parte 3)
- [[Kondepudi Prigogine - Modern Thermodynamics]] — il testo principale di Prigogine sulla TIP e strutture dissipative (2ª ed. 2015)
- [[Prigogine - From Being to Becoming]] — l'irreversibilità come proprietà fisica fondamentale; dinamica hamiltoniana
- [[Prigogine - Le Leggi del Caos]] — presentazione divulgativa dell'irreversibilità e caos (italiano)
- [[Prigogine - Termodinamica Processi Irreversibili]] — testo tecnico fondativo della TIP lineare (italiano)
- [[Prigogine Nicolis - Self-Organization Non-Equilibrium]] — strutture dissipative; ordine attraverso le fluttuazioni
- [[Prigogine Rice - Advances Chemical Physics Vol90]] — operatore entropico; irreversibilità intrinseca; tecnico
- [[De Groot Mazur - Non-Equilibrium Thermodynamics]] — trattato formale completo della TIP; flussi e forze accoppiati
- [[Demirel - Nonequilibrium Thermodynamics]] — TIP applicata a biofisica e ingegneria chimica; exergia
- [[Moran Shapiro - Fundamentals Engineering Thermodynamics]] — termodinamica ingegneristica (equilibrio); base per capire le deviazioni
- [[Cengel Boles - Thermodynamics Engineering Approach]] — manuale ingegneristico complementare a Moran/Shapiro
- [[Tolman - Principles Statistical Mechanics]] — fondamento microscopico classico; il problema H che Prigogine critica
- [[Reichl - Modern Course Statistical Physics]] — meccanica statistica moderna; FDT, Fokker-Planck, fluttuazioni

## Fonti da Acquisire

- Prigogine, I. & Defay, R. (1954). *Chemical Thermodynamics*. Longmans.
- Prigogine, I. & Stengers, I. (1979). *La Nouvelle Alliance*. Gallimard.
