---
aliases: 
name: Kidef Bodz
role: 
location: [hh]
tags: [npc]
spell_code: 
npc_code: hhkb
---
- A Havenite hiding from the cultists.
- hiding in derelict buildings and stealing scraps of food
- has been on the run for more than 10 days
- can be found in a derelict homestead
- or captured by the cultists

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