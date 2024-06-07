---
title: "Table: Topics"
draft: true
---
```dataview
TABLE
   title AS "Topic",
   type AS "Level",
   ptopic AS "Parent"
   FROM "content/TOPICS"
   SORT type ASC, title ASC
```


```dataviewjs
let myIndexPages = dv.pages('"content/TOPIC"');
dv.table(
    ["Topic", "Level", "Parent"],
    myIndexPages.map(p => [p.title, p.type, p.ptopic])
);
```
## Dataview
type:: #type/table
