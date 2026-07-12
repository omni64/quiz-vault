---
title: Gap Log
tags:
  - gaplog
---
# 📉 Gap Log

Raw capture layer for every miss. Fast in, promote later. One bullet per miss, with inline Dataview fields so loose items can surface in [[Review-Queue]] before you've built a full cluster.

**Entry format** (copy the template in `templates/Gaplog-Entry-Template.md`):
```
- (missed:: YYYY-MM-DD) (genre:: World) (sub:: Rivers) (review:: YYYY-MM-DD) (n:: 1) **Q:** … **A:** … → promote to [[Cluster-Name]]
```

- `missed` — date you got it wrong
- `review` — when to resurface it (start: tomorrow)
- `n` — times missed (bump on repeat)
- Once a fact earns a full cluster note, delete the loose line here (the cluster takes over its review).

---

## Misses

- (missed:: 2026-07-11) (genre:: World) (sub:: Mountains) (review:: 2026-07-12) (n:: 1) **Q:** Highest mountain in Europe? **A:** Elbrus (5,642 m) — *not* Mont Blanc → promoted to [[Seven-Summits]]

- (missed:: 2026-07-11) (genre:: Culture) (sub:: Mythology) (review:: 2026-07-12) (n:: 1) **Q:** Norse world tree connecting the nine realms? **A:** Yggdrasil — said "life tree" (right idea, wrong name — the name itself is the askable fact)
- (missed:: 2026-07-11) (genre:: Entertainment) (sub:: Opera) (review:: 2026-07-12) (n:: 1) **Q:** Puccini opera set in Nagasaki, Cio-Cio-San? **A:** Madama Butterfly — skipped
- (missed:: 2026-07-11) (genre:: Entertainment) (sub:: Ballet) (review:: 2026-07-12) (n:: 1) **Q:** Tchaikovsky ballet, Clara + Nutcracker Prince, after Hoffmann? **A:** The Nutcracker — answered "Hunchback of Notre Dame" (wrong composer, wrong medium — that's Victor Hugo/Disney, not Tchaikovsky)
- (missed:: 2026-07-11) (genre:: History) (sub:: Famous people) (review:: 2026-07-12) (n:: 1) **Q:** English "Virgin Queen," reigned 1558–1603? **A:** Elizabeth I — answered "Anne" (likely conflating with Anne Boleyn, her mother)
- (missed:: 2026-07-11) (genre:: Lifestyle) (sub:: Food & drink) (review:: 2026-07-12) (n:: 1) **Q:** Vinegared rice + raw fish dish? **A:** Sushi — answered "Sashimi" (sashimi is raw fish alone, no rice — classic mix-up)
- (missed:: 2026-07-11) (genre:: Lifestyle) (sub:: Human body) (review:: 2026-07-12) (n:: 1) **Q:** Largest organ in the human body? **A:** The skin — answered "Small Intestine"
- (missed:: 2026-07-11) (genre:: Media) (sub:: Literature) (review:: 2026-07-12) (n:: 1) **Q:** Colombian author, "One Hundred Years of Solitude"? **A:** Gabriel García Márquez — skipped
- (missed:: 2026-07-11) (genre:: Media) (sub:: Comic strips) (review:: 2026-07-12) (n:: 1) **Q:** Belgian cartoonist who created Tintin? **A:** Hergé — skipped
- (missed:: 2026-07-11) (genre:: Media) (sub:: Language) (review:: 2026-07-12) (n:: 1) **Q:** Most-spoken first language by native speakers? **A:** Mandarin Chinese — answered "English" (English wins on total speakers incl. L2; Mandarin wins on native speakers — the question asked native)
- (missed:: 2026-07-11) (genre:: Sciences) (sub:: Fauna) (review:: 2026-07-12) (n:: 1) **Q:** Only mammal capable of true sustained flight? **A:** The bat — skipped
- (missed:: 2026-07-11) (genre:: Sciences) (sub:: Exact sciences) (review:: 2026-07-12) (n:: 1) **Q:** Atomic number of gold? **A:** 79 — answered "48" (that's cadmium) → logged on [[079-Gold|Gold]]
- (missed:: 2026-07-11) (genre:: Sciences) (sub:: Exact sciences) (review:: 2026-07-12) (n:: 1) **Q:** Symbol Sb comes from Latin "stibium" — which element? **A:** Antimony — answered "Tin" (Sn/stannum) → already covered by [[Element-Symbols-from-Latin]], misses bumped
- (missed:: 2026-07-11) (genre:: Sciences) (sub:: Exact sciences) (review:: 2026-07-12) (n:: 1) **Q:** Lightest element that's solid at room temperature? **A:** Lithium — answered "Calcium" (H/He are gases; Li is first solid) → logged on [[003-Lithium|Lithium]]

<!-- Add new misses above this line, newest at the bottom of the list. Run GAPLOG in chat to get clean pre-formatted entries. -->
