---
title: "Table: Tweets"
draft: true
---
```dataview
TABLE
	level AS "Level",
	ptopic AS "Topic",
	social AS "Social Tags"
   FROM "content/Thoughts"
   SORT level ASC, ptopic ASC, ID ASC
```


## Dataview
type:: #type/table