---
title: "Table: PASSAGES"
draft: true
---
# Table: PASSAGES (hidden)
```dataview
TABLE WITHOUT ID
	file.link AS "Title*",
	source AS "Verse(s)",
	level AS "Passage Level",
	ptopic AS "Topic",
	ptopic.level AS "Topic Level"
   FROM "content/BIBLE"
   SORT file.link ASCENDING
```


## Dataview
type:: hiddentable
parent:: [[content/index]]

## Snippets

```dataview
 WHERE type != "#type/thought"

social AS "Social Tags"
```