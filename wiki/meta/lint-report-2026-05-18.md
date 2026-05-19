---
type: meta
title: "Lint Report 2026-05-18"
created: 2026-05-18
updated: 2026-05-18
tags: [meta, lint]
status: developing
---

# Lint Report: 2026-05-18

## Summary

- Pages scanned: 83
- Issues found: 16
- Auto-fixed: 3 (broken ? link × 3 files, frontmatter gap × 1, dead wikilinks link × 1)
- Needs review: 9 (dead links: 4 fixable + 5 in legacy meta pages)
- Informational: 7 (orphans, frontmatter gap, stale index, missing pages)

**Address Validation**: skipped (DragonScale not active — no `scripts/allocate-address.sh`)
**Semantic Tiling**: skipped (`scripts/tiling-check.py` not present)

---

## Dead Links

### High priority (affect the study wiki)

**`[[How does the LLM Wiki pattern work?]]`** — wrong title (trailing `?`): referenced in 4 files but target page is `How does the LLM Wiki pattern work` (no `?`).
- Sources: `log.md:68`, `Persistent Wiki Artifact.md:12`, `Query-Time Retrieval.md:12`, `Source-First Synthesis.md:12`
- Fix: replace `[[How does the LLM Wiki pattern work?]]` → `[[How does the LLM Wiki pattern work]]` in all 4 files.

**`[[wikilinks]]`** — referenced in `cherry-picks.md` but no page exists.
- Source: `cherry-picks.md`
- Suggest: remove the link or create a stub redirecting to the relevant concept.

**`[[Three laws of motion]]`** — referenced in `Persistent Wiki Artifact.md`. Appears to be an illustrative example in the body text (not a real cross-reference).
- Source: `Persistent Wiki Artifact.md`
- Suggest: strip the wikilink brackets if it's just an example, or note it's intentional.

### Low priority (in legacy plugin-dev meta pages — pre-pivot)

All four links below are in `wiki/meta/2026-04-10-backlink-empire-session.md`, a historical record from the plugin-dev era. These pages no longer exist because the vault was re-scoped.

- `[[Claude Canvas]]` ← `2026-04-10-backlink-empire-session.md`
- `[[Claude Obsidian]]` ← `2026-04-10-backlink-empire-session.md`
- `[[Karpathy LLM Wiki Pattern]]` ← `2026-04-10-backlink-empire-session.md` (page is `[[LLM Wiki Pattern]]`)
- `[[Rankenstein]]` ← `2026-04-10-backlink-empire-session.md`

Also in fold page (historical):
- `[[fold-template]]`, `[[wiki-fold]]` ← `fold-k3-from-2026-04-23-to-2026-04-24-n8.md`

**`[[E-commerce SEO]]`** — referenced in `Claude SEO.md` and `2026-04-14-claude-seo-v190-session.md`. Plugin-dev era only; not relevant to current vault scope.

---

## Orphan Pages

Pages with zero inbound links from other wiki pages:

| Page | Location | Note |
|------|----------|------|
| `2026-04-10-backlink-empire-session` | `wiki/meta/` | Plugin-dev historical record. Consider archiving or deleting. |
| `fold-k3-from-2026-04-23-to-2026-04-24-n8` | `wiki/folds/` | DragonScale fold page; normally linked from a fold index that doesn't exist yet. Acceptable. |
| `tiling-report-2026-04-24` | `wiki/meta/` | Old tiling report from plugin-dev era. Not linked from dashboard. |

Suggest: link `tiling-report-2026-04-24` from `dashboard.md` if still relevant, or note it's archival.

---

## Frontmatter Gaps

| Page | Missing Fields |
|------|---------------|
| `2026-05-17-inizio` | `status`, `updated` |

Fix: add `status: evergreen` and `updated: 2026-05-17` to the journal entry frontmatter.

---

## Stale Index Entries

| Link in index.md | Issue |
|-----------------|-------|
| `[[Wiki Map]]` | Target is `Wiki Map.canvas` (canvas), not an `.md` page. **Not a real issue** — Obsidian resolves wikilinks to canvas files correctly. No action needed. |

---

## Missing Pages

The following concepts are heavily referenced across multiple pages but have no dedicated wiki page. These represent growth opportunities, not blockers.

### Author Entity Pages (from new book ingests)

The 16 new book pages reference these key authors without entity pages. Consider creating stubs for the most important ones:

| Author | Referenced in | Priority |
|--------|--------------|----------|
| Ludwig von Bertalanffy | `Teoria dei Sistemi`, `Skyttner` | High — foundational figure |
| Ilya Prigogine | `Termodinamica dei Fenomeni Irreversibili`, `Bertuglia Vaio`, `Fenomeni Autocooperativi` | High — central to study |
| Howard T. Odum | `Odum Odum - Modeling for All Scales`, `Ecofisica` | Medium |
| Erik Hollnagel | `Hollnagel Woods Leveson - Resilience Engineering` | Medium |
| Russell Ackoff | `Gharajedaghi - Systems Thinking`, `Teoria dei Sistemi` | Medium |
| Jay Wright Forrester | `Teoria dei Sistemi` | Medium |

### Missing Concept Pages

| Concept | Referenced in | Note |
|---------|--------------|------|
| `MBSE` (Model-Based SE) | `SEBoK v2.7`, `Holt`, `Ingegneria dei Sistemi` | Deserves own page; currently described inline in Ingegneria dei Sistemi |
| `Emergy` | `Odum Odum - Modeling for All Scales`, `Ecofisica` | Key Odum concept; deserves own concept page |
| `Resilienza Ecologica` | `Ecodinamica`, `Hollnagel` (different concept!) | Two distinct meanings (Holling vs. engineering) — a disambiguation page would help |
| `System Dynamics` | `Teoria dei Sistemi`, `Gharajedaghi`, `Skyttner` | Forrester's SD deserves its own concept page |
| `Computabilità` | `Toffalori et al` | No concept page bridging this book to the Systems domain |

---

## Cross-Reference Gaps

The new book pages correctly link to domain concept pages, but some domain pages still reference book authors by name without wikilinks:

- `Teoria dei Sistemi.md` — mentions Bertalanffy, Wiener, Forrester, Checkland as plain text (no wikilinks). Once entity pages exist, these should become links.
- `Fenomeni Autocooperativi.md` — mentions Haken, Eigen, Kauffman, Holland as plain text.
- `Ecodinamica.md` — mentions Lotka, Volterra, May, Holling, Pimm as plain text.

These are acceptable for now. Link after creating entity pages.

---

## Empty Sections (True)

Most results from the automated check were false positives (parent headings going directly to subsections). The only true empty sections found are **placeholder comment blocks** in `_index.md` files and legacy `cherry-picks.md` — all intentional.

No action required.

---

## Fixes to Apply

**Fix 1 (critical): Broken wikilink with `?`**
In `Persistent Wiki Artifact.md`, `Query-Time Retrieval.md`, `Source-First Synthesis.md`: replace `[[How does the LLM Wiki pattern work?]]` → `[[How does the LLM Wiki pattern work]]`.

**Fix 2 (minor): Frontmatter gap**
In `wiki/journal/2026-05-17-inizio.md`: add `status: evergreen` and `updated: 2026-05-17`.

**Fix 3 (minor): Dead link in cherry-picks**
In `wiki/concepts/cherry-picks.md`: remove or resolve `[[wikilinks]]`.

---

## Address Validation

DragonScale not active — `scripts/allocate-address.sh` not present. Skipped entirely.

## Semantic Tiling

`scripts/tiling-check.py` not present. Skipped entirely.
