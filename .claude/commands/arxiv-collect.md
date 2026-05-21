---
description: Raccoglie paper recenti da ArXiv e li archivia nel vault come note strutturate. Legge la config da arxiv-agent-config.md, cerca nelle 46 categorie configurate, deduplica contro i paper già presenti.
---

Leggi `Skills/arxiv-collect/SKILL.md` per le istruzioni complete, poi esegui il workflow di raccolta ArXiv.

Parametri dall'argomento del comando (se forniti):
- Nessun argomento → raccolta standard con i parametri di arxiv-agent-config.md
- `--days N` → sovrascrive days_back con N giorni
- `--cat CODICE` → raccoglie solo quella categoria (es. `--cat cs.AI`)

Steps principali:
1. Leggi `arxiv-agent-config.md` (settings + lista categorie abilitate)
2. Calcola date: date_to=oggi, date_from=oggi-days_back
3. Mostra piano all'utente e attendi conferma
4. Per ogni categoria abilitata: chiama l'API ArXiv via WebFetch, deduplica, crea note in `Wiki/papers/`
5. Aggiorna `wiki/log.md`, `wiki/hot.md`, `arxiv-agent-config.md` (last_run)
6. Commit git con messaggio descrittivo e push

Vault path: C:\Users\paolo\Progetti AI\Progetto Ricerche WiKi
