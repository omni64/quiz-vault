---
title: WQC — World
tags:
  - moc
  - wqc
genre: World
---
# WQC — World (Geography)

The highest-leakage genre for most competitors, so it's seeded first. 30 questions on the paper. Coverage and **geographic breadth** beat depth here — expect Estonian rivers and Indonesian capitals, not an Anglophone bias.

## Syllabus
- [x] Rivers — [[Danube]], [[Worlds-longest-rivers]]
- [x] Mountains — [[Seven-Summits]]
- [x] Countries & borders — [[Landlocked-countries]]
- [x] Capitals — [[Capitals-not-largest-city]]
- [x] Flags — [[Flag-chestnuts]]
- [x] Currencies — [[World-Currency-Chestnuts]]
- [x] Seas, lakes & deserts — [[Seas-Lakes-and-Deserts]]
- [x] Islands & archipelagos — [[Islands-and-Archipelagos]]
- [x] World affairs / supranational bodies — [[Supranational-Bodies]]

## Seeded clusters
```dataview
TABLE sub AS "Sub", askability AS "ROI", review AS "Next review", misses AS "Misses"
FROM #cluster
WHERE genre = "World"
SORT askability DESC, file.name ASC
```

## Where World points leak (fix these first)
- **Capitals ≠ biggest city** — the classic trap. See [[Capitals-not-largest-city]].
- **"Which country has the most X"** superlatives — rivers, borders, time zones.
- **Flags** — cheap points once memorised; most people never drill them. See [[Flag-chestnuts]].
- **Non-Anglophone geography** — force yourself onto Central Asia, the Balkans, West Africa, the Pacific.
