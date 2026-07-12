---
title: Review Queue
tags:
  - review
---
# 🔁 Review Queue

Open this every study day. Work top-down. After reviewing an item, update its `review` date per [[How-spaced-repetition-works]].

## ⏰ Clusters due today
```dataview
TABLE WITHOUT ID
  file.link AS "Cluster",
  genre AS "Genre",
  sub AS "Sub",
  misses AS "Misses",
  review AS "Due"
FROM #cluster
WHERE review AND review <= date(today)
SORT misses DESC, review ASC
```

## 🔥 Leeches (missed more than once — drill these hardest)
```dataview
TABLE WITHOUT ID file.link AS "Cluster", misses AS "Misses", genre AS "Genre"
FROM #cluster
WHERE misses >= 2
SORT misses DESC
```

## 📆 Coming up (next 7 days)
```dataview
TABLE WITHOUT ID file.link AS "Cluster", review AS "Due"
FROM #cluster
WHERE review AND review > date(today) AND review <= date(today) + dur(7 days)
SORT review ASC
```

## 📝 Loose misses due (from gap-log, not yet promoted to a cluster)
```dataview
TABLE WITHOUT ID
  item.text AS "Miss",
  item.review AS "Due"
FROM "gap-log"
FLATTEN file.lists AS item
WHERE item.review AND item.review <= date(today)
SORT item.review ASC
```

> [!info] Nothing showing?
> If these tables are empty, either nothing is due (good) or the **Dataview** plugin isn't enabled / the vault isn't trusted. See the README.
