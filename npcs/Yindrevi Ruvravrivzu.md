---
aliases: 
name: Yindrevi Ruvravrivzu
role: Information trader
location: [fc, fcni, fcsu, fcbm, fclg]
npc_code: yindrevi
tags: [npc]
spell_code: 
---
- An attractive and charming young half-elven woman who trades information.
- She will sell or swap information with interested parties and moves within many different cirlcles in [[Fallcrest]].
- Socially adept, she has many friends (and business associates) including [[The Cudgel]].
- [[Namhazuu]] is especially fond of her and has made it widely known that she is under his protection.

#### Found in
```dataview
LIST map_code FROM #loc and -"templates"
WHERE econtains(this.location, loc_code)
```

#### Knows
```dataview
LIST summary from #sec and -"templates"
FLATTEN known_by
WHERE known_by = this.npc_code
```