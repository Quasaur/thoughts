---
title: "Table: QUOTES"
draft: true
---
```dataview
TABLE
	level AS "Level",
	source AS "Book",
	ptopic AS "Topic",
	ptopic.level AS "Topic Level"
FROM "content/QUOTES"
SORT ID ASC
```

## Dataview
type:: #type/table

## Snippets
```dataview

WHERE type != "#type/thought"

social AS "Social Tags"

```