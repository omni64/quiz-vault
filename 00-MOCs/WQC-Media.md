---
title: WQC — Media
tags:
  - moc
  - wqc
genre: Media
---
# WQC — Media

WQC genre — 30 questions on the paper. Sub-subjects below are the drill syllabus; tick as you build a cluster for each.

## Syllabus
- [x] Comic strips & books — [[Comic-Strip-and-Superhero-Chestnuts]]
- [x] Film — [[Iconic-Film-Quotes]]
- [x] Graphic novels — [[Graphic-Novel-Landmarks]]
- [x] Language — [[Country-Official-Languages]]
- [x] Literature — [[Literature-Opening-Chestnuts]]
- [x] News media — [[World-Newspapers]]
- [x] Periodicals — [[Magazine-Chestnuts]]
- [x] Social media — [[Social-Media-Platform-Facts]]

## Clusters in this genre
```dataview
TABLE sub AS "Sub", askability AS "ROI", review AS "Next review"
FROM #cluster
WHERE genre = "Media"
SORT askability DESC, file.name ASC
```

## Notes to self
- Frontload the recurring chestnuts first; go wide before deep.
- Log every miss to `gap-log.md`, then promote repeats into a cluster here.
