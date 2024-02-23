
```dataviewjs
for (let group of dv.pages('#spell and -"templates"').groupBy(s => s.level)) {
	dv.header(3, "Level " + group.key.toString());
	dv.table(["Spell", "Casting Time", "Range", "Area", "Concen"],
		group.rows
			.sort(k => k.name)
			.map(k => [k.file.link, k.casting_time, k.range, k.area, k.concentration]))
}
```

```dataviewjs
dv.table(["Spell", "Lvl"], dv.pages('#spell and -"templates"')
	.sort(s => s.level)
	.map(s => [s.file.link, s.level]))
```