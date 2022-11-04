---
aliases: 
name: Missing at the catacombs
summary: "An urchin disappeared"
known_by: [ karkix ]
found_at: [  ]
tags: [ sec ]
---
`=this.summary`

An urchin had noticed that some people had been going in and out of the [[Catacombs]] over the space of several days and nights.  He crept in behind them one evening and has never been seen again.

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
