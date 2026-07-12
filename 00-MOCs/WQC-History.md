---
title: WQC — History
tags:
  - moc
  - wqc
genre: History
---
# WQC — History

WQC genre — 30 questions on the paper. Sub-subjects below are the drill syllabus; tick as you build a cluster for each.

## Syllabus
- [x] Civilisations — [[Seven-Wonders-and-Ancient-Empires]]
- [x] Current affairs — [[Current-Affairs-2025-26]]
- [x] Exploration — [[Great-Explorers]]
- [x] Famous people — [[Historical-Biopic-Portrayals]]
- [x] General history — [[General-History-Chestnuts]]

## Clusters in this genre
```dataview
TABLE sub AS "Sub", askability AS "ROI", review AS "Next review"
FROM #cluster
WHERE genre = "History"
SORT askability DESC, file.name ASC
```

## Notes to self
- Frontload the recurring chestnuts first; go wide before deep.
- Log every miss to `gap-log.md`, then promote repeats into a cluster here.
