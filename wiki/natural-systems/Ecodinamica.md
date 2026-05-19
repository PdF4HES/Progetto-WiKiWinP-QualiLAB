---
type: concept
status: developing
domain: ecodinamica
tags:
  - concept
  - ecodinamica
  - dinamica-popolazioni
  - reti-trofiche
  - stabilita-ecosistemi
created: 2026-05-17
updated: 2026-05-17
related:
  - "[[Fenomeni Autocooperativi]]"
  - "[[Teoria dei Sistemi]]"
  - "[[Ecofisica]]"
  - "[[Biologia dei Sistemi]]"
  - "[[Sintesi del Campo]]"
---

# Ecodinamica

Navigation: [[Wiki/natural-systems/_index|Natural Systems]] | [[Sintesi del Campo]] | [[index]]

---

## Definizione

L'ecodinamica studia il comportamento dinamico degli ecosistemi nel tempo: come le popolazioni crescono, oscillano e collassano; come le reti trofiche si strutturano e si riorganizzano; come gli ecosistemi rispondono alle perturbazioni; come avanzano i processi di successione. È l'ecologia come sistema dinamico, con attori (specie), interazioni (trofiche, competitive, mutualistiche) e stati variabili nel tempo.

La parola è usata sia per l'ecologia dinamica in senso generale, sia per il framework termodinamico-sistemico sviluppato da Jørgensen e collaboratori.

---

## Fondatori e Contributi Chiave

**Alfred Lotka (1880-1949) & Vito Volterra (1860-1940)**
Le equazioni Lotka-Volterra (1925-1926) modellano l'oscillazione predatore-preda come sistema di ODE non lineari. Primo modello formale di dinamica di popolazione interagente. Fondamento matematico dell'ecodinamica.

**Charles Elton (1900-1991)**
Zoologo britannico, fondatore dell'ecologia delle comunità. Il concetto di *nicchia ecologica* come ruolo funzionale (non solo habitat). Catene alimentari, piramidi di numeri, cicli di abbondanza.

**G. Evelyn Hutchinson (1903-1991)**
Limnologo americano. Ha formalizzato la nicchia come iper-volume n-dimensionale (1957). Il "paradosso del plancton": perché tante specie di fitoplancton coesistono in un ambiente apparentemente omogeneo? Soluzione: non-equilibrio, fluttuazioni, caos.

**Robert May (1936-2020)**
Matematico e biologo australiano. *Stability and Complexity in Model Ecosystems* (1972): dimostra che in modelli matematici la complessità (connettività, diversità) destabilizza gli ecosistemi. Paradosso complessità-stabilità. Ha applicato la teoria del caos all'ecologia delle popolazioni.

**Stuart Pimm (1949-)**
Ecologo americano. Ha operazionalizzato la stabilità ecologica in più componenti (resilienza, resistenza, robustezza) e studiato empiricamente la struttura delle reti trofiche. Cascate trofiche.

**C.S. Holling (1930-2019)**
Ecologo canadese. Ha sviluppato il concetto di *resilienza ecologica* (1973): capacità di un ecosistema di assorbirele perturbazioni mantenendo la propria struttura. Ha proposto il ciclo adattativo (*adaptive cycle*) come modello della dinamica degli ecosistemi a lungo termine.

---

## Concetti Fondamentali

### Dinamica delle Popolazioni

**Crescita logistica**
dN/dt = rN(1 − N/K)
La popolazione cresce esponenzialmente a basse densità, rallenta per densità-dipendenza e si stabilizza alla capacità portante K. Modello base per la conservazione e il management.

**Equazioni Lotka-Volterra**
Per un sistema predatore (P) - preda (N):
- dN/dt = αN − βNP (preda: crescita meno predazione)
- dP/dt = δNP − γP (predatore: guadagno da predazione meno mortalità)

Producono oscillazioni cicliche neutralmente stabili. Estensioni includono la risposta funzionale (Holling) e la risposta numerica.

**Risposta Funzionale (Holling)**
Come cambia il tasso di predazione al variare della densità della preda:
- Tipo I: lineare (artropodi filtratori)
- Tipo II: satura, con plateau (la maggior parte dei predatori)
- Tipo III: sigmoidale, con accelerazione iniziale (vertebrati con apprendimento)

### Reti Trofiche

Una rete trofica è un grafo diretto in cui i nodi sono specie o guilds e gli archi indicano flussi di energia/biomassa. Proprietà:
- **Lunghezza della catena alimentare**: media ~4-5 livelli, limitata dall'efficienza (~10%) e dall'instabilità energetica
- **Omnivoria**: molte specie occupano più livelli; aumenta la complessità
- **Cascate trofiche**: la rimozione di un predatore apicale si propaga verso il basso attraverso la rete
- **Specie chiave di volta** (*keystone species*): specie con impatto sproporzionato alla loro abbondanza

**Topologia delle reti trofiche**
Le reti trofiche reali mostrano proprietà di *small world* (percorsi medi brevi) e distribuzione di grado eterogena, simile alle reti biologiche intracellulari.

### Stabilità degli Ecosistemi

Il concetto di stabilità è multi-dimensionale (Pimm, Holling):
- **Resistenza**: quanto l'ecosistema cambia sotto perturbazione
- **Resilienza (ingegneristica)**: velocità di ritorno all'equilibrio
- **Resilienza (ecologica, Holling)**: ampiezza del bacino di attrazione
- **Robustezza**: persistenza dell'ecosistema rispetto a perdite di specie

**Paradosso complessità-stabilità (May)**
Matematicamente, reti più connesse e diverse sono meno stabili in senso linearizzato (eigenvalue analysis). Empiricamente, gli ecosistemi più diversi sembrano più stabili. La risoluzione: la struttura della rete (non la connettività casuale) determina la stabilità.

### Ciclo Adattativo (Holling & Gunderson)

Modello qualitativo della dinamica a lungo termine degli ecosistemi in quattro fasi:

```
Crescita (r) --> Conservazione (K) --> Rilascio (Ω) --> Riorganizzazione (α) --> Crescita (r) ...
```

- **r (crescita)**: colonizzazione rapida, accumulo di biomassa e connettività
- **K (conservazione)**: climax, alta biomassa e connettività, bassa resilienza
- **Ω (rilascio/collasso)**: disturbanza (fuoco, patogeni, siccità) libera le risorse accumulate
- **α (riorganizzazione)**: fase di incertezza e innovazione, alta resilienza e bassa connettività

Il modello si applica a scale spaziali e temporali multiple (*panarchy*): i cicli a scale diverse sono accoppiati.

### Successione Ecologica

Processo direzionale di cambiamento della composizione delle comunità nel tempo, da stadi pionieri a stadi climax. Meccanismi:
- Facilitazione (le specie pioniere modificano l'ambiente favorendo l'insediamento di specie successive)
- Tolleranza (le specie climax coesistono con le pioniere ma le soppiantano lentamente)
- Inibizione (le specie stabilite resistono all'insediamento di nuove specie)

### Cicli Biogeochimici

L'ecodinamica include i cicli della materia (carbonio, azoto, fosforo, acqua) accoppiati ai flussi energetici. I cicli globali sono il prodotto del metabolismo aggregato di miliardi di organismi e sono essi stessi sistemi dinamici con feedback stabilizzanti e destabilizzanti.

---

## Biforcazioni e Cambiamenti di Regime

Gli ecosistemi possono avere **stati alternativi stabili** separati da soglie (*tipping points*). La transizione tra stati è spesso brusca e difficilmente reversibile (isteresi). Esempi:
- Lago limpido ↔ lago eutrofizzato (alghe)
- Foresta ↔ savana ↔ deserto
- Corallo sano ↔ corallo coperto da alghe

**Segnali precursori** (early warning signals): all'avvicinarsi di una biforcazione, il sistema mostra rallentamento critico (critical slowing down), aumento della varianza e dell'autocorrelazione temporale.

---

## Connessioni con gli Altri Domini

- [[Fenomeni Autocooperativi]]: la successione ecologica come auto-organizzazione; il ciclo adattativo come biforcazione periodica; la rete trofica come rete autocatalitica
- [[Teoria dei Sistemi]]: retroazione, emergenza, gerarchia (panarchy); l'ecosistema come sistema aperto in stato stazionario
- [[Ecofisica]]: la termodinamica dei flussi energetici vincola e spiega la struttura delle reti trofiche
- [[Biologia dei Sistemi]]: analogia strutturale tra reti trofiche (ecosistema) e reti metaboliche (cellula)

---

## Domande Aperte

- Esiste un principio generale che spieghi perché gli ecosistemi reali sono più stabili dei modelli suggeriscano?
- Come si predicono i *tipping points* in ecosistemi reali prima che vengano raggiunti?
- Il ciclo adattativo è un pattern universale o un'analogia utile ma non predittiva?
- Come si integrano le dinamiche a scale temporali molto diverse (giorni-secoli)?

---

## Fonti Disponibili nel Wiki

- [[Begon Townsend Harper - Ecology]] — il testo ecologico di riferimento (Blackwell 2006, 4th ed.)
- [[Odum Odum - Modeling for All Scales]] — modellistica degli ecosistemi; emergy; STELLA (Academic Press 2000)
- [[Weiner Matthews - Environmental Engineering]] — ecologia applicata; DO sag curve; cicli biogeochimici (Elsevier 2003)

## Fonti da Acquisire

- Lotka, A.J. (1925). *Elements of Physical Biology*. Williams & Wilkins.
- May, R.M. (1973). *Stability and Complexity in Model Ecosystems*. Princeton University Press.
- Holling, C.S. (1973). Resilience and stability of ecological systems. *Annual Review of Ecology and Systematics*, 4, 1-23.
- Gunderson, L.H. & Holling, C.S. (2002). *Panarchy: Understanding Transformations in Human and Natural Systems*. Island Press.
- Pimm, S.L. (1982). *Food Webs*. Chapman & Hall.
- Scheffer, M. (2009). *Critical Transitions in Nature and Society*. Princeton University Press.
- Jørgensen, S.E. (2012). *Introduction to Systems Ecology*. CRC Press.
