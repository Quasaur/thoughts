---
title: "Table: Thoughts DV - Modified"
draft: true
type: hiddentable
---
# Table: Thoughts DV - Modified (hidden)

```dataview
TABLE
	level AS "Level",
	dateformat(file.mtime, "yyyy.MM.dd") as "Last Modified*",
	ptopic AS "Topic",
	ptopic.level AS "Topic Level"
   FROM "content/THOUGHTS"
   SORT file.mtime DESC
```


## Dataview
parent:: [[content/index|index]]
## Snippets

```dataview
 WHERE type != THOUGHT

tags AS "Social Tags"
```