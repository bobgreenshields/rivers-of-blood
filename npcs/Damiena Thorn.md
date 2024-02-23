---
aliases: Damiena
name: Damiena Thorn
role: 
location: [hh]
tags: [npc]
spell_code: 
npc_code: hhdt
---
Lost daughter of [[Rudra Thorn]], Damiena has fully embraced Khorne and is helping the cultists find her [[Rudra Thorn| mother]] along with other Havenites who have gone into hiding rather than convert.

She will be obsessed with the blood of the injured and if a pc is reduced to 0HP will go over to the body, draw a small hidden blade and begin opening up their arteries for the blood to flow more freely.  The damage produced will count as an additional fail to their death saves.

Damiena is smart, she will play the lost upset kid but will endeavour to undermine the party whenever possible.  Accidentally drawing attention to the party when cultists are near by treading on sticks, sneezing, making scared noises etc.

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