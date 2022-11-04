---
aliases: 
name: Muddy boots
summary: ""
known_by: [  ]
found_at: [ fcss, fcal ]
tags: [ sec ]
---
`=this.summary`
Whilst they have some street muck on them, the boots are caked in two different kinds of mud neither of which look like that covering the streets of [[Fallcrest]].

- dark, almost black mud.  Not thick but with a musty smell.
- very fine, light brown mud.  Almost dust like.

On consulting anyone who travels widely they will tell you that
- the black mud comes from graves
- the brown mud is silt, coming from slower moving reaches of the river upstream of [[Fallcrest]]
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
