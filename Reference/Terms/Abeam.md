---
title: Abeam
term: Abeam
tags:
  - glossary
definition: An aircraft is “abeam” a fix, point, or object when it is approximately 90 degrees to the right or left of the aircraft track. Abeam indicates a general position rather than a precise point.
collection:
  - Student Pilot
---

[[Glossary]] / `= this.term`


> **Definition**: `INPUT[text:definition]`  
> **Aliases**: `INPUT[inlineList:aliases]`  
> **Tags**: `INPUT[inlineList:tags]`  
> **Collection**: `INPUT[inlineList:collection]`  
> _Examples: Flight, Maintenance, Student Pilot_  
> **See Also**: `INPUT[inlineList:connections]`

---

# `= this.term`

- **Term**: `= this.term`  
- **Definition**: `= this.definition`  
- **Aliases**: `= join(this.aliases, ", ")`  
- **Collections**: `= join(this.collection, ", ")`  
- **Tags**: `= join(this.tags, ", ")`  
```dataviewjs
let links = dv.current().connections;
if (Array.isArray(links) && links.length > 0) {
  dv.paragraph("**See Also:** " + links.map(t => `[[${t}]]`).join(", "));
}
```

### 📚 Resources – _Images, Links, Connections_

- _Add diagrams, related articles, or Obsidian links here._
- Example: `![Diagram](image.png)` or `[[Related Concept]]`
