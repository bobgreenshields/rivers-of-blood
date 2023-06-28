---
aliases: 
name: Za Vorgetsk
role: 
location: [hh]
tags: [npc]
spell_code: 
npc_code: 
---
The priest prime who lives in and runs [[Hadley's Haven]]

#### Found in
```dataview
LIST map_code FROM #loc and -"templates"
WHERE econtains(this.location, loc_code)
```

#### Knows
```dataview
LIST summary from #sec and -"templates"
FLATTEN known_by
WHERE known_by = this.npc_code
```