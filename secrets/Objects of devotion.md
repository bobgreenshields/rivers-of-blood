---
aliases: 
name: Objects of devotion
summary: "Silver scales etc"
known_by: [ bishop, deacon ]
found_at: [ fctt ]
tags: [ sec ]
---
`=this.summary`
- DC 10 Invest - anyone who has seen the [[Silver sacrificial tools]] in the [[Alchemists house]] can tell that these have been made by the same person.

[[Malerakas Xandax]], the silversmith made these especially for the temple.
This is known by both [[Bishop Taryamre]] and [[Deacon Dasqusti]]

It is widely known that [[Malerakas Xandax]] is both a silversmith and a worshipper of Tyr.

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
