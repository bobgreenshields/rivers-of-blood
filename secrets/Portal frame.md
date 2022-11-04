---
aliases: 
name: Portal frame
summary: "The unpowered frame of a portal"
known_by: [ silver, deacon ]
found_at: [ fcss ]
tags: [ sec ]
---
`=this.summary`
A metal surround shaped much like a door frame set into a stone base.  The frame is set with small warpstones at roughly equal intervals of 20 cm.

### Known by
```dataview
LIST role FROM #npc and -"templates"
WHERE econtains(this.known_by, npc_code)
```

### Found at
```dataview
LIST  FROM #loc and -"templates"
WHERE econtains(this.found_at, loc_code)
```
