### Cantrips
```dataview
LIST FROM #spell AND -"templates"
WHERE level = 0
SORT name asc
```
### Level 1
```dataview
LIST FROM #spell AND -"templates"
WHERE level = 1
SORT name asc
```

### Level 2
```dataview
LIST FROM #spell AND -"templates"
WHERE level = 2
SORT name asc
```

### Level 3
```dataview
LIST FROM #spell AND -"templates"
WHERE level = 3
SORT name asc
```

### All
```dataview
LIST FROM #spell AND -"templates"
SORT name asc
```