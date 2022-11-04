
---
target_level: 2
---

```dataview
LIST FROM #spell AND -"templates"
WHERE level = this.target_level
SORT name asc
```