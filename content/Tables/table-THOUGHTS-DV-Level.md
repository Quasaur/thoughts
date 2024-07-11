---
title: "Table: Thoughts DV - Level"
draft: true
---
# Table: THOUGHTS DV - Level (hidden)
```dataview
TABLE
	level AS "Level*",
	ptopic AS "Topic",
	ptopic.level AS "Topic Level"
   FROM "content/THOUGHTS"
   SORT level ASC, file.link ASC
```


## Dataview
type:: table
parent:: [[content/index]]

## Snippets

```dataview
 WHERE type != "#type/thought"

social AS "Social Tags"
```