---
aliases: "The friends"
name: Friends of Fallcrest
summary: "A group trying to takeover Fallcrest"
known_by: [ yindrevi ]
found_at: [  ]
tags: [ sec ]
---
`=this.summary`

- a political group
- comprised of merchants, scholars and minor nobles
- want to take power in [[Fallcrest]]
- for the benefit of the people
- mostly themselves (but they don't see it that way)
- they sometimes meet at the [[Temple of Tyr]]

> [!INFO]- Members
> - [[Malerakas Xandax]]
> - [[Gakrern Tallore]]
> - [[Sergeant Greruga]]
> - [[Deacon Dasqusti]]
> amongst others including members of the guard converted by [[Sergeant Greruga|Vlosvar Greruga]]

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
