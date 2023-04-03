---
name: "cult priest"
powers: [ Necromonculus, Animate Shadow, Bane, Disruption, Mass Disruption, Mind Sliver ]
tags: monster
---

### Powers
```dataview
TABLE range AS Range, save AS Save, concentration AS Concen, level AS level FROM (#power or #spell) and -"templates"
WHERE econtains(this.powers, name)
```