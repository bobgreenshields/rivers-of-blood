---
aliases: 
name: Boat charter
summary: "Alchemist charters a boat"
known_by: [  ]
found_at: [ fcal ]
tags: [ sec ]
---
`=this.summary`

A letter lies on the desk in the study.  It regards the chartering of a boat, the Archeron, for a trip up river.

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
