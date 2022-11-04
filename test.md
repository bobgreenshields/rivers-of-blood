```dataviewjs
let spells = dv.pages('#spell and -"templates"')
for (let group of spells.groupBy(b => b.level)) {
   dv.header(2, "Level " + group.key.toString());
   dv.list(group.rows.file.link);
}
```