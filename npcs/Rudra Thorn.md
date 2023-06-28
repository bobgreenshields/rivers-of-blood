---
aliases: 
name: Rudra Thorn
role: 
location: [hh]
tags: [npc]
spell_code: 
npc_code: hhrt
---
The healer in [[Hadley's Haven]] before the cult arrived.  She did not convert and is now hiding out amongst the derelict homesteads.  Although scared of what will happen to her if found she is making some effort to find her daughter, [[Damiena Thorn]], who has been missing for over a week.

She has *4 poultices* that *heal 2d4+2 HP*.  She can make more but will need to forage for materials.

She does not know the [[Damiena Thorn| Damiena]] has taken up with the cultists and will defend her as the sweet little girl that she knew.

Havenites who have not converted will rally around Rudra as their defacto leader.

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