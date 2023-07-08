---
aliases: 
name: Za Vorgetsk
role: 
location: [hh]
powers: [ Kraken Arms ]
tags: [npc]
spell_code: 
npc_code: 
---
The priest prime who lives in and runs [[Hadley's Haven]]

### Powers
```dataview
TABLE range AS Range, save AS Save, concentration AS Concen, level AS Lvl FROM (#power or #spell) and -"templates"
WHERE econtains(this.powers, name)
```



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