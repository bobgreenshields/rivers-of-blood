---
aliases: 
name: Silversmiths note
summary: "A hidden note"
known_by: [  ]
found_at: [ fcss ]
tags: [ sec ]
---
`=this.summary`

```
That idiot Markelhay is blundering about intrusively.  We need to distract him.  Construct an item that will entice him; he will spend days focused on it and that is all we need.
```
Also
```
The Merging of Eights is nigh. Vaddh’akar approaches.  Make preparations to bring the faithful by the river.
```



### Known by
```dataview
LIST role FROM #npc and -"templates"
WHERE econtains(this.known_by, npc_code)
```

### Found at
```dataview
LIST  FROM #loc and -"templates"
WHERE econtains(this.found_at, loc_code)
```
