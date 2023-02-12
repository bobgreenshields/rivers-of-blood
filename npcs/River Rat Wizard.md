---
aliases: 
name: River Rat Wizard
role: 
location: []
tags: [npc]
spell_code: rrw
---
# River Rat Wizard
- [[#Spells]]
## Stats
- Int +3
- Spell DC 13 Att +5
- AC 12
- HP 3d6+3 or maybe 2d6+9
- 3 1st level slots

## Tactics
- will use [[Mind Sliver]] by default especially on anyone fighting the guards
- [[Magic Missile]] on any casters that he thinks have concentration
- [[Fog Cloud]] to split up the attackers
- as soon as they can will cast [[Mage Armour]]
- if he has success with [[Mind Sliver]] and the target does not make a save he will follow up with [[Hideous Laughter]]

## Spells
```dataview
TABLE level AS Level, casting_time AS "Casting Time", range AS Range, save AS Save, concentration AS Concentration from "5e/spells"
FLATTEN user
WHERE user = "rrw"
SORT level ASC
```
