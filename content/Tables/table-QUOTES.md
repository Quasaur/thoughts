---
title: "Table: QUOTES"
draft: true
---
# Table: QUOTES (hidden)
```dataview
TABLE WITHOUT ID
	file.link AS "Title*",
	level AS "Level",
	source AS "Book",
	ptopic AS "Topic",
	ptopic.level AS "Topic Level"
FROM "content/QUOTES"
SORT file.link ASCENDING
```

## Dataview
type:: hiddentable
parent:: [[content/index]]

## Snippets
```dataview

WHERE type != "#type/thought"

social AS "Social Tags"

```