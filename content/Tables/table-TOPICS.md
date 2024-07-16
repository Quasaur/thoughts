---
title: "Table: Topics"
draft: true
---
# Table: TOPICS (hidden)
```dataview
TABLE WITHOUT ID
   file.link AS "Topic*",
   level AS "Level",
   ptopic AS "Parent Topic",
ptopic.level AS "Parent Level"
   FROM "content/TOPICS"
   SORT file.link ASC
```


## Dataview
type:: table
parent:: [[content/index|index]]