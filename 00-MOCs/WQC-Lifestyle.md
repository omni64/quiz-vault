---
title: WQC — Lifestyle
tags:
  - moc
  - wqc
genre: Lifestyle
---
# WQC — Lifestyle

WQC genre — 30 questions on the paper. Sub-subjects below are the drill syllabus; tick as you build a cluster for each.

## Syllabus
- [ ] Costume
- [ ] Design
- [ ] Fashion
- [ ] Food & drink
- [ ] Handicrafts
- [ ] Health & fitness
- [ ] Hobbies & pastimes
- [ ] Human body
- [ ] New age beliefs
- [ ] Products & brands
- [ ] Tourism

## Clusters in this genre
```dataview
TABLE sub AS "Sub", askability AS "ROI", review AS "Next review"
FROM #cluster
WHERE genre = "Lifestyle"
SORT askability DESC, file.name ASC
```

## Notes to self
- Frontload the recurring chestnuts first; go wide before deep.
- Log every miss to `gap-log.md`, then promote repeats into a cluster here.
