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

- (missed:: 2026-07-12) (genre:: Culture) (sub:: Architecture) (review:: 2026-07-13) (n:: 1) **Q:** Ancient wonder — lighthouse on an island near Alexandria? **A:** The Lighthouse (Pharos) of Alexandria — answered "Babylon" (named a different ancient civilisation entirely, likely conflating with the Hanging Gardens of Babylon)
- (missed:: 2026-07-12) (genre:: Culture) (sub:: Philosophy) (review:: 2026-07-13) (n:: 1) **Q:** Greek philosopher, tutor to Alexander the Great, founded the Lyceum? **A:** Aristotle — skipped
- (missed:: 2026-07-12) (genre:: History) (sub:: General history) (review:: 2026-07-13) (n:: 1) **Q:** Year the Berlin Wall fell? **A:** 1989 — answered "1992" (off by 3 years)
- (missed:: 2026-07-12) (genre:: Lifestyle) (sub:: Design) (review:: 2026-07-13) (n:: 1) **Q:** German art school founded by Walter Gropius in 1919? **A:** The Bauhaus — skipped
- (missed:: 2026-07-12) (genre:: Media) (sub:: Periodicals) (review:: 2026-07-13) (n:: 1) **Q:** British weekly satirical magazine (1841) that gave its name to "cartoon"? **A:** Punch — skipped
- (missed:: 2026-07-12) (genre:: Sciences) (sub:: Flora) (review:: 2026-07-13) (n:: 1) **Q:** Plant family shared by potato, tomato, and pepper? **A:** Nightshade family (Solanaceae) — answered "Tuber" (that's the plant structure the potato is, not the taxonomic family)
- (missed:: 2026-07-12) (genre:: World) (sub:: Rivers) (review:: 2026-07-13) (n:: 1) **Q:** River that flows through Baghdad? **A:** The Tigris — answered "Jordan" (confused the river with the country Jordan, the correct answer to a different question in the same set)
- (missed:: 2026-07-12) (genre:: World) (sub:: Capitals) (review:: 2026-07-13) (n:: 1) **Q:** Capital of Kazakhstan? **A:** Astana — answered "Tashkent" (that's the capital of Uzbekistan, not Kazakhstan)

- (missed:: 2026-07-13) (genre:: Culture) (sub:: Traditions) (review:: 2026-07-14) (n:: 1) **Q:** Japanese tea ceremony centred on preparing and serving matcha? **A:** Chanoyu (the "Way of Tea") — skipped
- (missed:: 2026-07-13) (genre:: Lifestyle) (sub:: Fashion) (review:: 2026-07-14) (n:: 1) **Q:** French designer, "little black dress" and No. 5 perfume, founded house 1910? **A:** Coco Chanel — answered "Ralph Lauren" (wrong designer entirely — Ralph Lauren is American, no connection to the little black dress or a No. 5 perfume)
- (missed:: 2026-07-13) (genre:: Sport & Games) (sub:: Card games) (review:: 2026-07-14) (n:: 1) **Q:** Cards dealt to each of four bridge players? **A:** 13 — answered "7" (likely conflating with a different card game's hand size)

- (missed:: 2026-07-14) (genre:: History) (sub:: Ancient history) (review:: 2026-07-15) (n:: 1) **Q:** Ancient wonder — giant bronze statue of the sun god Helios at a Greek harbour? **A:** The Colossus of Rhodes — skipped
- (missed:: 2026-07-14) (genre:: History) (sub:: Revolutions) (review:: 2026-07-15) (n:: 1) **Q:** 1789 storming of a Paris fortress-prison, start of the French Revolution? **A:** The Storming of the Bastille — skipped
- (missed:: 2026-07-14) (genre:: Lifestyle) (sub:: Food & drink) (review:: 2026-07-15) (n:: 1) **Q:** Spongy, sourdough Ethiopian flatbread used as plate and utensil? **A:** Injera — skipped
- (missed:: 2026-07-14) (genre:: Media) (sub:: Journalism) (review:: 2026-07-15) (n:: 1) **Q:** British news agency (1851), one of the world's largest wire services? **A:** Reuters — answered "Telegraph" (that's a newspaper, not a wire service)
- (missed:: 2026-07-14) (genre:: World) (sub:: Currencies) (review:: 2026-07-15) (n:: 1) **Q:** Currency of Mexico? **A:** The Mexican peso — answered "Mexico City" (gave the capital, not the currency)

<!-- Add new misses above this line, newest at the bottom of the list. Run GAPLOG in chat to get clean pre-formatted entries. -->
