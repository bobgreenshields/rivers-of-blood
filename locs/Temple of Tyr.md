---
name: Temple of Tyr
loc_code: tt
tags: loc
---
## NPCs
```dataview
LIST role FROM #npc and -"templates"
FLATTEN location
WHERE location = "tt"
```