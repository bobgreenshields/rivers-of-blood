---
name: Temple of Tyr
map_code: 30
parent_loc: fc
loc_code: fctt
tags: [loc, cult]
---

## NPCs
```dataview
LIST role FROM #npc and -"templates"
FLATTEN location
WHERE location = "fctt"
```