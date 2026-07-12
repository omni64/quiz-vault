# Competitive Quizzing Vault

A local Obsidian knowledge network for **World Quizzing Championships (WQC)** breadth and **Mastermind Australia** depth. Facts are organised as small, wikilinked **clusters** so shared entities auto-form a graph, and misses are drilled on a **spaced-repetition** schedule via Dataview.

## Requirements
- [Obsidian](https://obsidian.md) (free).
- **Dataview** plugin (Community Plugins → search "Dataview" → Install → Enable). Turn on *Enable JavaScript Queries* is **not** required — everything here uses plain DQL.
- Optional: **Templater** or core **Templates** plugin, pointed at the `templates/` folder.

## Open it
Obsidian → *Open folder as vault* → select this `Quizzing-Vault` folder. Trust the vault when prompted (needed for Dataview to render).

## How it's laid out
- `00-MOCs/` — one **Map of Content** per WQC genre + Mastermind tracks. Start at [[_Home]].
- `clusters/` — atomic fact clusters, tagged `#cluster`. This is the graph.
- `review/` — the [[Review-Queue]] (Dataview) and [[How-spaced-repetition-works]].
- `gap-log.md` — raw dated misses (GAPLOG capture layer).
- `templates/` — a cluster template and a gap-log-entry template.

## The daily loop
1. Drill (in chat or self-test) → log every miss to `gap-log.md` using the template.
2. Promote recurring misses into a cluster note in `clusters/`.
3. Open [[Review-Queue]] each day → review what's **Due** → advance or reset the interval.

## A note on where the facts come from
These notes are generated and hand-checked for a quizzing syllabus, not copied from any question archive — the wording of published clues is copyrighted; the underlying facts are not. Volatile facts (office-holders, "current/latest" anything, records, contested names) are date-stamped and should be re-verified before a sitting.

> [!warning] Verify volatile items before competition
> Anything tagged `#volatile` carries an "as of" date. Re-check it near your sitting — these change.
# quiz-vault
