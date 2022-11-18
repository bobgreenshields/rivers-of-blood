---
aliases: 
name: Guards at the catacombs
summary: "Guards posted to prevent access"
known_by: [ karkix, yindrevi ]
found_at: [ fccc ]
tags: [ sec ]
---
`=this.summary`

- to prevent people from entering after the disappearance
- placed by [[Sergeant Greruga]]
- will let through those with the correct password
- know that groups have been coming and going
- the groups often stay inside for up to 12 hours
- do not know why the  [[Missing at the catacombs|urchin went missing]]
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
