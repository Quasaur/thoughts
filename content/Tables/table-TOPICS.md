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
let myIndexPages = dv.pages('"content/Indexes"');
let tableMarkdown = dv.markdownTable(
    ["Topic", "Level", "Parent"],
    myIndexPages.map(p => [p.title, p.type, p.ptopic])
);
dv.paragraph(tableMarkdown);
```
## Dataview
type:: #type/table
