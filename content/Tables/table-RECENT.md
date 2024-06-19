---
title: "Table: RECENT"
draft: true
---
```dataview
TABLE 
	dateformat(file.mtime, "yyyy.MM.dd - HH:mm") as "Last Modified",
	level AS "Level"
   FROM "content/TOPICS" OR "content/THOUGHTS" OR "content/QUOTES" OR "content/BIBLE"
   SORT dateformat, DESC
   LIMIT 10
```


## Dataview
type:: #type/table
