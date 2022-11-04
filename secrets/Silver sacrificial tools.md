---
aliases: 
name: Silver sacrificial tools
summary: "Finely made blades and tools"
known_by: [ alch, silver ]
found_at: [ fcal ]
tags: [ sec ]
---
`=this.summary`
The [[Gakrern Tallore|alchemist]] has been using these finely made silver tools to cut, drain the blood from and remove the organs from his sacrificial victims.

- DC 12 Invest - some of the tools were custom made for removing organs (one specifically for the heart)
- DC 15 Invest - they are beautifully made and inlaid with small bloodstones.  They are very reminiscent of the scales and objects of devotion seen in the [[Temple of Tyr]]

The tools are inlaid with small bloodstones and some are obviously custom made for the purpose of removing organs.

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
