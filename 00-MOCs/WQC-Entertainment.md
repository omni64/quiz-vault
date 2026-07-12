---
title: WQC — Entertainment
tags:
  - moc
  - wqc
genre: Entertainment
---
# WQC — Entertainment

WQC genre — 30 questions on the paper. Sub-subjects below are the drill syllabus; tick as you build a cluster for each.

## Syllabus
- [x] Ballet — [[Ballet-Chestnuts]]
- [x] Celebrities — [[Celebrity-Real-Names]]
- [x] Classical music — [[Classical-Music-Chestnuts]]
- [x] Film & TV music — [[Film-and-TV-Music]]
- [x] Jazz & world music — [[Jazz-Giants]]
- [x] Opera — [[Opera-Chestnuts]]
- [x] Pop music — [[Pop-Music-Chestnuts]]
- [x] Radio — [[Old-Time-Radio]]
- [x] Television — [[TV-Sitcom-Chestnuts]]
- [x] Theatre (popular / musicals) — [[Theatre-and-Musicals-Chestnuts]]

## Clusters in this genre
```dataview
TABLE sub AS "Sub", askability AS "ROI", review AS "Next review"
FROM #cluster
WHERE genre = "Entertainment"
SORT askability DESC, file.name ASC
```

## Notes to self
- Frontload the recurring chestnuts first; go wide before deep.
- Log every miss to `gap-log.md`, then promote repeats into a cluster here.
