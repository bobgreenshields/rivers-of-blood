## NPCs
```dataview
LIST role FROM #npc and -"templates"
FLATTEN location
WHERE location = "<% tp.frontmatter.loc_code %>"
```