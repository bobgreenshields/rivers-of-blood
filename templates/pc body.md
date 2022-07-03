## Combat
```dataview
TABLE WITHOUT ID 
ac_ds AS "AC/DS",
wis_sv AS "Wis Sv",
dex_sv AS "Dex Sv",
con_sv AS "Con Sv",
spell_dc_atk AS "Spell DC Atk"
FROM "lmop/pcs"
WHERE name = "<% tp.frontmatter.name %>"
```

```dataview
TABLE WITHOUT ID 
acrobatics AS "Acrobatics",
athletics AS Athletics,
stealth AS Stealth,
move AS Move,
psv_percep AS PP
FROM "lmop/pcs"
WHERE name = "<% tp.frontmatter.name %>"
```

## Checks
```dataview
TABLE WITHOUT ID 
str AS Str,
dex AS Dex,
con AS Con,
int AS Int,
wis AS Wis,
cha AS Cha
FROM "lmop/pcs"
WHERE name = "<% tp.frontmatter.name %>"
```

## Saves
```dataview
TABLE WITHOUT ID 
str_sv AS "Str Sv",
dex_sv AS "Dex Sv",
con_sv AS "Con Sv",
int_sv AS "Int Sv",
wis_sv AS "Wis Sv",
cha_sv AS "Cha Sv"
FROM "lmop/pcs"
WHERE name = "<% tp.frontmatter.name %>"
```

## Proficiencies
```dataview
TABLE WITHOUT ID prof AS Proficiencies FROM "lmop/pcs"
FLATTEN prof
WHERE name = "<% tp.frontmatter.name %>"
```

## Skills
```dataview
TABLE WITHOUT ID 
acrobatics AS Acrob,
arcana AS Arcana,
athletics AS Athl,
deception AS Decep,
history AS Hist,
insight AS Insight
FROM "lmop/pcs"
WHERE name = "<% tp.frontmatter.name %>"
```

```dataview
TABLE WITHOUT ID 
intimidation AS Intim,
investigation AS Invest,
medicine AS Medic,
nature AS Nat,
perception AS Percep,
persuasion AS Pers
FROM "lmop/pcs"
WHERE name = "<% tp.frontmatter.name %>"
```

```dataview
TABLE WITHOUT ID 
religion AS Relig,
stealth AS Stealth,
survival AS Surv,
locks_traps AS "Locks Traps",
thieves_tools AS "Thieves tools"
FROM "lmop/pcs"
WHERE name = "<% tp.frontmatter.name %>"
```