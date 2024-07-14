---
title: "Table: Thoughts DV - File"
draft: true
type: TABLE
---
# Table: THOUGHTS DV - File (hidden)
```dataview
TABLE WITHOUT ID
	file.link AS "File*",
	level AS "Level",
	ptopic AS "Topic",
	ptopic.level AS "Topic Level"
   FROM "content/THOUGHTS"
   SORT file.link ASC
```


## Dataview
type:: table
parent:: [[content/index]]

## Snippets

```dataview
 WHERE type != THOUGHT

tags AS "Social Tags"
```