
---
name: "this.title"
powers: [  ]
tags: monster
---

### Powers
```dataview
TABLE range AS Range, save AS Save, concentration AS Concen FROM (#power or #spell) and -"templates"
WHERE econtains(this.powers, name)
```