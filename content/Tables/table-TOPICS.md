---
title: "Table: Topics"
---
```dataview
TABLE
   title AS "Topic",
   type AS "Level",
   ptopic AS "Parent"
   FROM "content/Indexes"
   SORT type ASC, title ASC
```

```dataviewjs
```
```dataviewjs
```
```dataviewjs
```
```dataviewjs
let myIndexPages = dv.pages('"content/Indexes"');
dv.table(
    ["Topic", "Level", "Parent"],
    myIndexPages.map(p => [p.title, p.type, p.ptopic])
);
```
## Dataview
type:: #type/table
