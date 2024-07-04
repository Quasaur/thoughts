---
title: "Table: Topics"
draft: true
tags:
- table
---
# Table: TOPICS (hidden)
```dataview
TABLE
   topic AS "Topic",
   level AS "Level",
   ptopic AS "Parent Topic",
ptopic.level AS "Parent Level"
   FROM "content/TOPICS"
   SORT ID ASC
```


## Dataview
type:: #type/table
parent:: [[content/index|index]]