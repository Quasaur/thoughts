---
title: "Table: Thoughts DV - File"
draft: true
tags:
- table
---
# Table: THOUGHTS DV - File (hidden)
```dataview
TABLE
	level AS "Level",
	ptopic AS "Topic",
	ptopic.level AS "Topic Level"
   FROM "content/THOUGHTS"
   SORT ID ASC
```


## Dataview
type:: #type/table
parent:: [[content/index]]

## Snippets

```dataview
 WHERE type != "#type/thought"

social AS "Social Tags"
```