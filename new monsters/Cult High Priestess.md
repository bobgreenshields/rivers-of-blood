---
name: "cult priest"
powers: [ Spell Shield, Rage Of Khorne, Thirst For Blood, Blood Of Khorne, Breath of Khorne, Spirit Of Khorne, Death Armour ]
tags: monster
---

- **[[Spell Shield]]** one use
- **[[Death Armour]]** one use
- **[[Spirit Of Khorne]]** one use
- **[[Blood Of Khorne]]**  [[Recharge|recharge]] 5-6
	- Damage 2 x 1d6 fire
 - **[[Breath of Khorne]]** [[Recharge|recharge]] 5-6


### Powers
```dataview
TABLE range AS Range, save AS Save, concentration AS Concen, level AS Lvl FROM (#power or #spell) and -"templates"
WHERE econtains(this.powers, name)
```

### Magic Items
#### Bracers of Shield
Allows the wearer to cast [[Shield]] 3 times per day.