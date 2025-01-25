---
draft: true
---

```dataview
TABLE
FROM "content" 
	AND -"content/dataviews" 
	AND -"content/templates"
WHERE draft = true
```
