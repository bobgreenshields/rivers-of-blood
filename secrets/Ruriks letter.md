---
aliases: 
name: Ruriks letter
summary: "A letter found with the manticores"
known_by: [  ]
found_at: [ md ]
tags: [ sec ]
---
`=this.summary`

#### A letter
From [[Rarim Chuv]] asking him to question some people (who?) and scout some places (where?)

Rurik,
I have a mission for you my friend.  Well, it might actually be two.  Travel to Sharp Edge, find Balek's latest claim, question him and the other dwarven prospectors about our mystery stone.  Someone must know what it is or have come across it before and those miners are likely candidates.

I'll meet you at the Waystation but won't be there for another week and a half so drop in on as many homesteads as you can and talk to them about travellers, the disappearances and any suspicious happenings.  Folk love to gossip and I'm sure you will be able to pick up something that may help us link these coincidences.

I will pay you the usual rate when we meet at Wilda's.  I'm sure I don't need to say it but be discrete and careful.  I fear that there is something more sinister behind this group of malcontents in Fallcrest and I would hate for you to become another disappearance.

Farewell

Rarim


#### His notes
- who are the eight by eight?
- ceremony of the merging? 
- who are the red priests?
- and who are their followers?
- met the dwarves of somewhere to ask the stone
	- none of the miners knew what it was
	- but a very old dwarf had heard of this stone
	- powerful magical properties
	- ability to store magical power
	- but was shunned because
	- it twists those around it
	- tells a anecdote/story of a dwarf affected by the stone
		- smarter
		- fouler
		- crueler

^info





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
