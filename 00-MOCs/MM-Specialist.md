---
title: Mastermind — Specialist Subject
tags:
  - moc
  - mastermind
  - specialist
---
# Mastermind — Specialist Subject

Round 1: **2 minutes** to answer as many questions as possible on your chosen subject. Round advantage is won by leaving *nothing on the table*.

> [!todo] Not yet chosen
> You skipped picking a specialist for now. When ready, run **SPECIALIST [candidate]** in chat and we'll pressure-test scope, then build the fact base here.

## Choosing well (the scope test)
A good specialist is:
- **Genuinely loved** — you'll live in it for months.
- **Bounded** — a clear edge, so setters can't wander into the obscure. ("The novels of X" not "20th-century literature".)
- **Deep enough** — sustains ~2 min of hard, *askable* questions: names, dates, firsts, records, controversies, connections.
- **Not too narrow** — or you get freak-obscure questions with no margin for error.

## Once chosen — the exhaustive fact base
Build clusters tagged `#cluster` with `genre: MM-Specialist`. Cover:
- [ ] Core canon (the works / events / people themselves)
- [ ] Dates & chronology (firsts, lasts, order)
- [ ] Records & superlatives
- [ ] Key figures & relationships
- [ ] Controversies & disputes
- [ ] Adjacent / connecting facts setters love

## Clusters
```dataview
TABLE sub AS "Sub", review AS "Next review", misses AS "Misses"
FROM #cluster
WHERE genre = "MM-Specialist"
SORT file.name ASC
```
