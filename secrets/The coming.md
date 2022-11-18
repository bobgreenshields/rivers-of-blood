---
aliases: "The merging"
name: The coming
summary: "Summoning Vaddh' akar"
known_by: [ yindrevi ]
found_at: [  ]
tags: [ sec, cult ]
---
`=this.summary`

[[Yindrevi Ruvravrivzu|Yindrevi]] has heard various disparate people takling about "the coming", whatever that is, with a sense of anticipation.

If asked about these specifically she will remember
- "the merging" - they also used the phrase 
- [[Friends of Fallcrest]] - many of them were 
- town guards - some were 
- the disappearances - once it was in the same conversation 

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
