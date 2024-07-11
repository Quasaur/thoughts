---
title: "Table: RECENT"
draft: true
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
   WHERE type != "#type/page" AND type != "table" AND draft = false
   SORT file.mtime DESC
```


## Dataview
type:: hiddentable
parent:: [[content/index]]

## Snippets
```dataview
WHERE type = #type/thought OR #type/quote OR #type/passage OR #type/topic
```