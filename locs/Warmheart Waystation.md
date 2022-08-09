---
aliases: waystation
name: Warmheart Waystation
map_code: 
parent_loc: 
loc_code: ww
tags: [loc]
---

Only a day or two out of [[Fallcrest]] it's a frequent and popular stop off for travellers

## NPCs
```dataview
LIST role FROM #npc and -"templates"
FLATTEN location
WHERE location = "ww"
```