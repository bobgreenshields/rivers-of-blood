---
aliases: 
name: Abamuns Finger
summary: "The skeletal finger of a saint"
known_by: [ hhrt ]
found_at: [  ]
tags: [ sec ]
---
`=this.summary`

This skeletal finger of Saint Abamun of Tarnut protects the faithful that hold it and those close by from arcane power

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
