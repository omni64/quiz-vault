---
title: WQC — Culture
tags:
  - moc
  - wqc
genre: Culture
---
# WQC — Culture

WQC genre — 30 questions on the paper. Sub-subjects below are the drill syllabus; tick as you build a cluster for each.

## Syllabus
- [ ] Architecture
- [ ] Fine art
- [ ] Museums
- [ ] Mythology
- [ ] Philosophy
- [ ] Religion
- [ ] Theatre (highbrow)
- [ ] World cultures

## Clusters in this genre
```dataview
TABLE sub AS "Sub", askability AS "ROI", review AS "Next review"
FROM #cluster
WHERE genre = "Culture"
SORT askability DESC, file.name ASC
```

## Notes to self
- Frontload the recurring chestnuts first; go wide before deep.
- Log every miss to `gap-log.md`, then promote repeats into a cluster here.
