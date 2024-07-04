---
title: "Table: RECENT"
draft: true
tags:
- table
---
# Table: RECENT (hidden)
```dataview
TABLE 
	level AS "Level",
	ptopic AS "Topic",
	ptopic.level AS "Topic Level",
	dateformat(file.mtime, "yyyy.MM.dd") as "Last Modified*",
	type AS "Type"
   FROM "content"
   WHERE type != "#type/page"
   SORT file.mtime DESC
   LIMIT 15
```


## Dataview
type:: #type/table
parent:: [[content/index]]

## Snippets
```dataview
WHERE type = #type/thought OR #type/quote OR #type/passage OR #type/topic
```