---
title: "Table: QUOTES"
draft: true
type: hiddentable
---
# Table: QUOTES (hidden)
```dataview
TABLE WITHOUT ID
	file.link AS "File*",
	level AS "Level",
	source AS "Book",
	ptopic AS "Topic",
	ptopic.level AS "Topic Level"
FROM "content/QUOTES"
SORT file.link ASCENDING
```

## Dataview
parent:: [[content/index]]

## Snippets
```dataview

WHERE type != "THOUGHT"

social AS "Social Tags"

```