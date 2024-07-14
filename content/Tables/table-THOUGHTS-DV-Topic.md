---
title: "Table: Thoughts DV - Topic"
draft: true
type: TABLE
---
# Table: Thoughts DV - Topic (hidden)
```dataview
TABLE
	level AS "Level",
	ptopic AS "Topic*",
	ptopic.level AS "Topic Level"
   FROM "content/THOUGHTS"
   SORT ptopic ASC
```


## Dataview
type:: table
parent:: [[content/index|index]]

## Snippets

```dataview
 WHERE type != THOUGHT

tags AS "Social Tags"
```