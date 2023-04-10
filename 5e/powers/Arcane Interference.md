---
source: 
monster: 
cr: 
concentration: ✅
duration: "Random"
range: 60ft
range_ft: 60
area: 30ft wall
name: Arcane Interference
save: None
tags: power
---

| **Range** | **Area** | **Duration** | **Save** | **Concentration** |
|:---:|:---:|:---:|:---:|:---:|
| `=this.range` | `=this.area` | `=this.duration` | `=this.save` | `=this.concentration` |

Creates a barrier that interferes with spells.  For each spell passing through the barrier roll a d8 and the result is the number of 10%s that the effectiveness of the spell is reduced by e.g. roll a 4 the effectiveness of the spell is 100 - 4 * 10 = 60%

If a one is rolled the barrier drops **after** the 10% reduction.