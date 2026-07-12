---
title: How spaced repetition works here
tags:
  - review
---
# How spaced repetition works here

Manual, transparent, and plugin-light. Every cluster carries three fields in its frontmatter:

```yaml
review: 2026-07-12   # the date it next surfaces
interval: 1          # current step index (see ladder)
misses: 0            # times you've missed it (leech tracking)
```

## The spacing ladder
When you **recall** an item correctly, advance to the next step and set `review = today + that gap`:

| Step | Gap to next review |
|---|---|
| 1 | **next day** (+1) |
| 2 | **3 days** (+3) |
| 3 | **1 week** (+7) |
| 4 | **3 weeks** (+21) |
| 5 | **monthly** (+30, then keep monthly) |

## The two rules
1. **Recalled it?** → bump `interval` up one step, set `review` to today + the new gap.
2. **Missed it?** → reset `interval` to **1**, set `review` to **tomorrow**, and **`misses += 1`**.

Items with `misses >= 2` are **leeches** — they surface in their own section of [[Review-Queue]]. For a leech, don't just re-read: rebuild the [[Danube|cluster]] around it, add a fresh mnemonic, or split it into smaller facts.

## Daily routine (5–15 min)
1. Open [[Review-Queue]].
2. Cover the note, recall it cold, then check.
3. Apply rule 1 or 2 to its frontmatter dates.
4. New misses from any drill → log to `gap-log.md` first; promote repeat offenders into a cluster.

> [!tip] Why manual beats an automatic plugin here
> You *want* the friction of editing the date — it forces a genuine recall attempt and a self-honest grade, which is the whole point of deliberate practice. If you later prefer automation, the **Spaced Repetition** community plugin reads `#flashcard`-style Q/A and can run alongside this.
