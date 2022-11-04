---
aliases: 
name: Burnt letters
summary: "Scraps of burnt letters"
known_by: [  ]
found_at: [ fcss, fcal ]
tags: [ sec ]
---
`=this.summary`
These burnt scraps of letters contain fragments of information.

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
