---
aliases: 
name: Skull key
summary: "A skull shaped key"
known_by: [  ]
found_at: [ fcss, fcal ]
tags: [ sec ]
---
`=this.summary`
The skull key opens the ancient crypt of the Alchemist's family housing the portal to [[Hadley's Haven]]

### Known by
```dataview
LIST role FROM #npc and -"templates"
WHERE econtains(this.known_by, npc_code)
```

### Found at
```dataview
LIST FROM #loc and -"templates"
WHERE econtains(this.found_at, loc_code)
```
