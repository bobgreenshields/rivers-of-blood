---
aliases: silversmith
name: Malerakas Xandax
role: Silversmith and cult member
location: [fc, fcss]
tags: [npc, cult]
spell_code: 
npc_code: silver
powers: [ Arcane Interference, Rage Of Khorne, Mage Armour, Hands Of Khorne, Thirst For Blood, Spirit Of Khorne, Blood Of Khorne, Muscle Spasm, Necromonculus ]
---

The silversmith, a senior cult member.  An early middle aged Tiefling.

**Remember AC+1 and +1 saves from amulet**


### Powers
```dataview
TABLE range AS Range, save AS Save, concentration AS Concen, level AS Lvl FROM (#power or #spell) and -"templates"
WHERE econtains(this.powers, name)
```

- **[[Arcane Interference]]** one use
- **[[Spirit Of Khorne]]** one use
- **[[Necromonculus]]** one use
- **[[Blood Of Khorne]]**
	- [[Recharge]] 5-6
	- Damage 2 x 1d6 fire
 - [[Ring of the Ram]]

### Loot
- [[Ring of the Ram]]
- [[Amulet of Protection]]
- Scroll of Magic Weapon