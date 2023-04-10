---
name: "cult priest"
powers: [ Arcane Interference, Rage Of Khorne, Mage Armour, Thirst For Blood, Blood Of Khorne, Muscle Spasm, Spirit Of Khorne ]
tags: monster
---

- **[[Arcane Interference]]** one use
- **[[Spirit Of Khorne]]** one use
- **[[Blood Of Khorne]]**
	- [[Recharge]] 5-6
	- Damage 2 x 1d6 fire


### Powers
```dataview
TABLE range AS Range, save AS Save, concentration AS Concen, level AS Lvl FROM (#power or #spell) and -"templates"
WHERE econtains(this.powers, name)
```