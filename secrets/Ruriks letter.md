---
aliases: 
name: Ruriks letter
summary: "A letter found with the manticores"
known_by: [  ]
found_at: [ md ]
tags: [ sec ]
---
#### `=this.summary`

Folded into the letter is a crumpled scrap of paper covered in scribbled notes.  The handwriting of the notes is clearly different to that of the letter.

#### The letter

Rurik,
I know that i asked you to gather information for me in Fallcrest but I have a pressing mission for you that cannot wait.  Once it is completed we can meet up and you can pass on all that you have gleaned so far.

Travel to Sharp Edge, find Balek's latest claim, question him and the other dwarven prospectors about our mystery stone.  Someone must know what it is or have come across it before and those miners are likely candidates.

I'll meet you at the Waystation and we can swap what we have discovered over a tankard of ale and a bowl of Wilda's goat stew.  I'm sure I don't need to say it but be careful, discrete and watch your back.  I fear that there is something more sinister behind this stone and the group of malcontents in Fallcrest, I would hate for you to become another disappearance.

Farewell 

Rarim


#### The notes
- who are the eight by eight?
- ??? how are they linked to [[Vaddh akar]], what or who is that?
- and who are the red priests?
- if they are priests they must have followers?
- what is the ceremony of the merging? 

#### The Dwarves

- only known by aged dwarf
- rarely seen
- naturally occuring or artifact?
- magical properties - stores/focuses power
- physical mutation
- mental transformation - evil?
- Warpstone

#### The background
- met the dwarves of somewhere to ask about the stone
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