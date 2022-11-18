---
aliases: 
name: Forbidden library
summary: "A collection of illicit occult books"
known_by: [ librarian ]
found_at: [  ]
tags: [ sec ]
---
`=this.summary`

[[Faren Markelhay]]'s great uncle had an unhealthy interest in the power of demons and extraplanar creatures and collected books hich at best had  dubious provenance and at worst were forbidden.

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
