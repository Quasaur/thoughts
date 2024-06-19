---
title: "Table: PASSAGES"
draft: true
---
```dataview
TABLE
	source AS "Verse(s)",
	ptopic AS "Topic",
	level AS "Topic Level"
   FROM "content/BIBLE"
   SORT ID ASC
```


## Dataview
type:: #type/table

## Snippets

```dataview
 WHERE type != "#type/thought"

social AS "Social Tags"
```