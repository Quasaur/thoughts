---
title: "Table: Tweets"
draft: true
---
```dataview
TABLE
	level AS "Level",
	ptopic AS "Topic"
   FROM "content/THOUGHTS"
   SORT level ASC, ptopic ASC, ID ASC
```


## Dataview
type:: #type/table

## Snippets

```dataview
 WHERE type != "#type/thought"

social AS "Social Tags"
```