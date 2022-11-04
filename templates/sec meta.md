---
aliases: 
name: <% tp.file.title %>
summary: ""
known_by: [  ]
found_at: [  ]
tags: [ sec ]
---
`=this.summary`

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
