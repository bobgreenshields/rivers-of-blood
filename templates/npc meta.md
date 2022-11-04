---
aliases: 
name: <% tp.file.title %>
role: 
location: []
tags: [npc]
spell_code: 
npc_code: 
---
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