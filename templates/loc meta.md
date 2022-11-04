---
aliases: 
name: <% tp.file.title %>
map_code: 
parent_loc: 
loc_code: 
tags: [loc]
---
#### NPCs
```dataview
LIST role FROM #npc and -"templates"
FLATTEN location
WHERE location = this.loc_code
```
#### Clues here
```dataview
LIST summary from #sec and -"templates"
FLATTEN found_at
WHERE found_at = this.loc_code
```
