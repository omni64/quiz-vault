---
title: WQC — Sport & Games
tags:
  - moc
  - wqc
genre: Sport & Games
---
# WQC — Sport & Games

WQC genre — 30 questions on the paper. Sub-subjects below are the drill syllabus; tick as you build a cluster for each.

## Syllabus
- [ ] Sports across the world (not just the popular ones)
- [ ] Board / card / video games
- [ ] Olympics
- [ ] Records
- [ ] Notable figures

## Clusters in this genre
```dataview
TABLE sub AS "Sub", askability AS "ROI", review AS "Next review"
FROM #cluster
WHERE genre = "Sport & Games"
SORT askability DESC, file.name ASC
```

## Notes to self
- Frontload the recurring chestnuts first; go wide before deep.
- Log every miss to `gap-log.md`, then promote repeats into a cluster here.
