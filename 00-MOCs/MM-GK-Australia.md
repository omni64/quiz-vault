---
title: Mastermind — GK (Australia-weighted)
tags:
  - moc
  - mastermind
  - gk
---
# Mastermind — General Knowledge (Australia-weighted)

Round 2: **90 seconds** rapid-fire. Broad international GK, but weight Australian material **more heavily than WQC does**. Speed and momentum win; snap-guess a plausible answer rather than pass (passes break ties against you).

## Australian canon to own
- [ ] Federal politics & **PMs** (order, firsts, terms, notable events)
- [ ] States & territories, capitals, geography
- [ ] Australian history (pre-1900 → Federation 1901 → modern)
- [ ] Sport — AFL, NRL, cricket, Olympics/Commonwealth, tennis
- [ ] Australian arts, film, TV, music
- [ ] Flora & fauna, landmarks, Indigenous history & culture

## International GK backbone (shared with WQC breadth)
Pull from the WQC genre MOCs — that breadth *is* your GK engine. See [[_Home]].

## Clusters
```dataview
TABLE sub AS "Sub", askability AS "ROI", review AS "Next review"
FROM #cluster
WHERE genre = "MM-GK-AU" OR contains(tags, "australia")
SORT file.name ASC
```

> [!tip] Cross-training
> A Mastermind specialist vertical also lifts the matching WQC genre, and WQC breadth feeds this round. Build once, score twice.
