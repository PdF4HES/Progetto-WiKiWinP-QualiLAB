---
type: book
title: "Nonlinearity, Chaos, and Complexity: The Dynamics of Natural and Social Systems"
authors: ["Cristoforo Sergio Bertuglia", "Franco Vaio"]
year: 2005
edition: "1st ed. (trad. dall'italiano 2003)"
publisher: "Oxford University Press"
domain: [fenomeni-autocooperativi, teoria-sistemi]
tags: [book, nonlinearità, caos, complessità, biforcazione, attrattori, modellistica]
status: in-coda
created: 2026-05-18
updated: 2026-05-18
raw_file: ".raw/C. S. Bertuglia, F. Vaio - Nonlinearity, Chaos, and Complexity. The Dynamics of Natural and Social Systems.pdf"
related:
  - "[[Fenomeni Autocooperativi]]"
  - "[[Teoria dei Sistemi]]"
  - "[[Termodinamica dei Fenomeni Irreversibili]]"
  - "[[Ecodinamica]]"
---

# Bertuglia & Vaio — Nonlinearity, Chaos, and Complexity

**Autori:** C.S. Bertuglia & F. Vaio (Politecnico di Torino)
**Anno:** 2005 (it. 2003) | **Editore:** Oxford University Press | **pp.** ~387

> [!key-insight] Punto centrale
> Caos e complessità sono distinti: il caos è imprevedibilità deterministica in sistemi a pochi gradi di libertà; la complessità è l'emergenza di comportamenti inaspettati in sistemi a molti agenti interagenti. La matematica classica — anche deterministica — incontra i propri limiti di fronte a entrambi i fenomeni.

---

## Struttura (3 parti, 25 capitoli)

### Parte 1 — Processi Lineari e Nonlineari (cap. 1–13)

Cosa significa "sistema" → fisicalismo e scienze sociali → meccanica classica e il problema dei molti corpi → linearità come prima approssimazione → il pendolo come sistema modello (lineare, con attrito, nonlineare) → sistemi dinamici e spazio delle fasi → estensione dei concetti della fisica all'economia (Jevons, Schumpeter) → **modello di due popolazioni interagenti** (modello lineare) → **modello di Volterra-Lotka** (nonlineare, ecologia e regional science)

Capitoli principali:
- **Cap. 5** Il pendolo: modello lineare (Model 1), con attrito (Model 2), sistemi autonomi
- **Cap. 8** Sistemi dinamici e spazio delle fasi: traiettorie, attrattori
- **Cap. 12** Modello Volterra-Lotka: ciclo limite come attrattore non puntuale; carrying capacity; risposta funzionale/numerica del predatore
- **Cap. 13** Volterra-Lotka applicato a dinamiche urbane/regionali (USA, Madrid)

### Parte 2 — Dalla Nonlinearità al Caos (cap. 14–23)

Aspetti teorici del caos → attrattori strani (Lorenz, Rössler) → mappa del baker → caos in sistemi reali → **stabilità** (Poincaré, Lyapunov) → esponenti di Lyapunov → orizzonti di previsione → problema della misura del caos → **mappa logistica**: modello di crescita, legge di Verhulst, dinamica (biforcazioni, cicli), albero di Feigenbaum → concetti chiave del caos

Capitoli principali:
- **Cap. 16** Attrattori strani: Lorenz e Rössler come esempi; mappa del baker (2D)
- **Cap. 18** Stabilità: criterio di Lyapunov; crescita esponenziale delle perturbazioni
- **Cap. 21** Mappa logistica: punti fissi, biforcazioni, periodo raddoppiato
- **Cap. 22** Albero di Feigenbaum; applicazione a modelli di interazione spaziale
- **Cap. 23** Concetti principali del caos

### Parte 3 — Complessità (cap. 24–25+)

Inadeguatezza del riduzionismo → modelli come strumenti (non realtà) → il ruolo della matematica → limiti della matematica → ricerca di regolarità nelle scienze sociali

---

## Concetti Chiave

### Spazio delle Fasi e Attrattori

Lo **spazio delle fasi** è la rappresentazione geometrica di tutti gli stati possibili del sistema. Ogni punto = uno stato; ogni traiettoria = un'evoluzione temporale.

**Tipi di attrattori:**
| Tipo | Forma geometrica | Comportamento |
|------|-----------------|---------------|
| Punto fisso | Punto | Equilibrio stabile |
| Ciclo limite | Curva chiusa | Oscillazione periodica |
| Attrattore strano | Frattale | Comportamento caotico |

### Il Modello di Volterra-Lotka (Cap. 12)

Equazioni per preda *x* e predatore *y*:
```
dx/dt = ax - bxy    (crescita preda - mortalità per predazione)
dy/dt = -cy + dxy   (mortalità predatore + crescita da caccia)
```
Soluzioni: **cicli chiusi nello spazio delle fasi** (ciclo limite); le popolazioni oscillano perpetuamente. Aggiungendo carrying capacity o risposta funzionale si producono dinamiche più ricche (spirali smorzate, caos).

### Il Sistema di Lorenz e l'Effetto Farfalla

3 ODE derivate da un modello di convezione atmosferica:
```
dx/dt = σ(y - x)
dy/dt = x(ρ - z) - y
dz/dt = xy - βz
```
Con σ=10, ρ=28, β=8/3: attrattore strano a forma di "farfalla". **Due traiettorie vicine divergono esponenzialmente** → limite intrinseco alla previsione (≠ randomness: è determinismo + sensibilità).

### Mappa Logistica e Albero di Feigenbaum

Modello discreto di crescita in presenza di risorse limitate:
```
x_{n+1} = r·x_n·(1 - x_n)
```
- r < 3: converge a punto fisso
- 3 < r < 3.57: biforcazioni successive (periodo 2, 4, 8...)
- r > 3.57: caos (con finestre di ordine)
- δ di Feigenbaum ≈ 4.669: costante universale del raddoppio di periodo

### Caos vs Complessità (Distinzione Fondamentale)

| | Caos | Complessità |
|---|---|---|
| Causa | Nonlinearità deterministica | Interazioni tra molti agenti |
| Gradi di libertà | Pochi (3+) | Molti |
| Prevedibilità | Orizzonte di Lyapunov | Molto limitata, emergenza inattesa |
| Modellazione | ODE nonlineari | Difficile, spesso impossibile |
| Esempio | Lorenz, pendolo doppio | CAS, mercati, evoluzione |

> La **complessità** non è caos più qualcosa: i cambiamenti inattesi ("salti") non sono predicibili dalle leggi deterministiche che governano le traiettorie tra un salto e il successivo.

---

## Connessioni nel Wiki

- [[Fenomeni Autocooperativi]] — attrattori, biforcazioni, auto-organizzazione sono il linguaggio di questo dominio
- [[Termodinamica dei Fenomeni Irreversibili]] — le strutture dissipative di Prigogine appaiono nella parte sulla complessità
- [[Ecodinamica]] — Volterra-Lotka è il modello base della dinamica delle popolazioni
- [[Skyttner - General Systems Theory]] — fornisce il quadro storico/concettuale in cui si inserisce la nonlinearità
- [[Odum Odum - Modeling for All Scales]] — anche Odum usa ODE nonlineari per sistemi ecologici

---

## Domande Aperte

- Il caos deterministico nei sistemi sociali è un artefatto del modello o una proprietà reale?
- La criticalità auto-organizzata (SOC, Bak) è un caso speciale di complessità nel senso di Bertuglia-Vaio?
- Come si distingue operativamente complessità da semplice complicatedness?
