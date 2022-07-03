## Proficiencies
```dataview
TABLE WITHOUT ID prof AS Proficiencies FROM "lmop/pcs"
FLATTEN prof
WHERE name = "<% tp.frontmatter.name %>"
```