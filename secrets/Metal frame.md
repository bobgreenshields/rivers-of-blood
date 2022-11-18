---
aliases: 
name: Metal frame
summary: "A metal frame for the silversmith"
known_by: [ yindrevi ]
found_at: [ fcss ]
tags: [ sec, cult ]
---
`=this.summary`

The blacksmith made strange metal frames for the silversmith.  Retangular, the same shape and size as a door frame.  Some might know that he has made 5 of then so far.

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
