---
title: "Table: Tweets"
---
```dataview
TABLE
	level AS "Level",
	ptopic AS "Topic",
	social AS "Social Tags"
   FROM "Tweets"
   SORT level ASC, ptopic ASC, ID ASC
```


## Dataview
type:: #type/table