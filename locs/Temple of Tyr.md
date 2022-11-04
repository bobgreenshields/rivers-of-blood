---
name: Temple of Tyr
map_code: 30
parent_loc: fc
loc_code: fctt
tags: [loc, cult, temple]
---

## NPCs
```dataview
LIST role FROM #npc and -"templates"
FLATTEN location
WHERE location = "fctt"
```

#### Clues here
```dataview
LIST summary from #sec and -"templates"
FLATTEN found_at
WHERE found_at = this.loc_code
```