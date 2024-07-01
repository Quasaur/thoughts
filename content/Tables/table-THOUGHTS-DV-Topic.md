---
title: "Table: Thoughts DV - Topic"
draft: true
---
```dataview
TABLE
	level AS "Level",
	ptopic AS "Topic*",
	ptopic.level AS "Topic Level"
   FROM "content/THOUGHTS"
   SORT ptopic ASC
```


## Dataview
type:: #type/table

## Snippets

```dataview
 WHERE type != "#type/thought"

social AS "Social Tags"
```