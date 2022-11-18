---
aliases: 
name: Disappearances
summary: "Homeless have disappeared"
known_by: [ yindrevi ]
found_at: [ fcbm, fclg, fcni ]
tags: [ sec ]
---
`=this.summary`

Dandod Meidid, a jocular, popular homeless drunkard has disappeared from his haunts in Low Town prompting folk to notice that several other Low Town drunks have gone missing.

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
