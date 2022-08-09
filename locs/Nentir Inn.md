---
name: Nentir Inn
map_code: 4
parent_loc: fc
loc_code: fcni
tags: [loc, inn]
---



A fine new building constructed of fieldstone and strong timber, the Nentir Inn stands on the west bank of the river. Merchants from [Winterhaven](https://rpg.fandom.com/wiki/Winterhaven "Winterhaven") or [Hammerfast](https://rpg.fandom.com/wiki/Hammerfast "Hammerfast") make up the clientele, along with travelers who happen to be passing through. A good room with two single beds goes for 5 sp per night. The Nentir Inn also boasts a lively taproom, which is popular with the folk who live in the vales on the west bank of the river.

## NPCs
```dataview
LIST role FROM #npc and -"templates"
FLATTEN location
WHERE location = "fcni"
```