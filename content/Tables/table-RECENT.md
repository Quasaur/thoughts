---
title: "Table: RECENT"
draft: true
---
```dataview
TABLE 
	dateformat(file.mtime, "yyyy.MM.dd - HH:mm") as "Last Modified*",
	level AS "Level",
	type AS "Type"
   FROM "content"
   WHERE type != "#type/page"
   SORT dateformat, DESC
   LIMIT 15
```


## Dataview
type:: #type/table

## Snippets
```dataview
WHERE type = #type/thought OR #type/quote OR #type/passage OR #type/topic
```