---
aliases: 
name: Reversible robes
summary: "A dark robe with a bright red lining"
known_by: [  ]
found_at: [ fcss, fcal ]
tags: [ sec ]
---
`=this.summary`
It's immediately clear that these robes can be worn either way around.  One way to avoid notice on the street and the other to present the bright red side.

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
