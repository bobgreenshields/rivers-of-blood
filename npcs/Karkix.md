---
aliases: 
name: Karxik
role: Street urchin
location: [fc]
tags: [npc]
spell_code: 
npc_code: karkix
---
A male Tiefling street urchin.  Quite small but very gregarious, befriending strangers to "help" them settle in to [[Fallcrest]].

#### Knows
```dataview
LIST summary from #sec and -"templates"
FLATTEN known_by
WHERE known_by = this.npc_code
```

### Orc
Sword +4 S `dice: 1d8+4 |render`