## Spells
```dataview
TABLE level AS Level, casting_time AS "Casting Time", range AS Range, save AS Save, concentration AS Concentration from "5e/spells"
FLATTEN user
WHERE user = "<% tp.frontmatter.spell_code %>"
SORT level ASC
```
