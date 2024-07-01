---
title: "Table: Thoughts DV - Level"
draft: true
---
```dataview
TABLE
	level AS "Level*",
	ptopic AS "Topic",
	ptopic.level AS "Topic Level"
   FROM "content/THOUGHTS"
   SORT level ASC
```


## Dataview
type:: #type/table

## Snippets

```dataview
 WHERE type != "#type/thought"

social AS "Social Tags"
```