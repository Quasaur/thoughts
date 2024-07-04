---
title: "Table: PASSAGES"
draft: true
tags:
- table
---
# Table: PASSAGES (hidden)
```dataview
TABLE
	source AS "Verse(s)",
	level AS "Passage Level",
	ptopic AS "Topic",
	ptopic.level AS "Topic Level"
   FROM "content/BIBLE"
   SORT ID ASC
```


## Dataview
type:: #type/table
parent:: [[content/index]]

## Snippets

```dataview
 WHERE type != "#type/thought"

social AS "Social Tags"
```