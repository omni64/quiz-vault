---
title: Home
tags:
  - moc
  - home
---
# 🧠 Quizzing HQ

Central map. Everything hangs off here.

## WQC — the eight genres (240 questions = 8 × 30)
- [[WQC-Culture]] — Architecture, Fine art, Museums, Mythology, Philosophy, Religion, Theatre, World cultures
- [[WQC-Entertainment]] — Ballet, Celebrities, Classical, Film/TV music, Jazz & world, Opera, Pop, Radio, TV, Musicals
- [[WQC-History]] — Civilisations, Current affairs, Exploration, Famous people, general History
- [[WQC-Lifestyle]] — Costume, Design, Fashion, Food & drink, Health, Human body, Products & brands, Tourism…
- [[WQC-Media]] — Comics, Film, Graphic novels, Language, Literature, News media, Periodicals, Social media
- [[WQC-Sciences]] — Exact sciences, Fauna, Flora, Social sciences
- [[WQC-Sport-and-Games]] — World sports, board/card/video games, Olympics, records, figures
- [[WQC-World]] — Geography: countries, capitals, flags, rivers, mountains, borders, currencies ✅ *seeded*

## Mastermind Australia
- [[MM-Specialist]] — choose & build the specialist fact base
- [[MM-GK-Australia]] — general knowledge, Australian-weighted

## Study system
- [[Review-Queue]] — what's due today (Dataview)
- [[How-spaced-repetition-works]] — the schedule & rules
- Capture layer: `gap-log.md`

## The whole graph at a glance
```dataview
TABLE genre AS "Genre", sub AS "Sub-subject", askability AS "ROI"
FROM #cluster
SORT genre ASC, file.name ASC
```
