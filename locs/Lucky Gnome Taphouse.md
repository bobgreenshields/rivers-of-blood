---
name: Lucky Gnome Taphouse
map_code: 28
parent_loc: fc
loc_code: fclg
tags: [loc, inn]
---
The Lucky Gnome is widely regarded as the cheapest and coarsest of Fallcrest’s drinking establishments. It caters to the porters and laborers who work the nearby docks, and fistfights are a nightly occurrence.

The owner of the Lucky Gnome is a character named [[Kelson]]

## NPCs
```dataview
LIST role FROM #npc and -"templates"
FLATTEN location
WHERE location = "fclg"
```