---
aliases: 
name: Blood red clasps
summary: "Red stone cape clasps"
known_by: [  ]
found_at: [ fctt ]
tags: [ sec ]
---
`=this.summary`

A group of Tyr worshippors hang around the temple after a service.  Several, but not all, of the group have cloak clasps made of a red stone (Bloodstone) in various different designs.  The forms are different enough that you would be unlikely to notice unless you were aware of it.

Clasp wearers
- [[Malerakas Xandax]]
- [[Gakrern Tallore]]

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
