---
title: "Table: QUOTES (sorted by Book)"
draft: true
type: hiddentable
---
# Table: QUOTES (sorted by Book)
```dataview
TABLE WITHOUT ID
	file.link AS "File",
	level AS "Level",
	source AS "Book*",
	ptopic AS "Topic",
	ptopic.level AS "Topic Level"
FROM "content/QUOTES"
SORT source ASCENDING
```

## Dataview
parent:: [[content/index]]

## Snippets
```dataview

WHERE type != "THOUGHT"

social AS "Social Tags"

```