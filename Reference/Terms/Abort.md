---
title: Abort
term: Abort
tags:
  - glossary
collection:
  - Student Pilot
definition: To terminate a preplanned aircraft maneuver, e.g., an aborted takeoff.
aliases:
  - Stop
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
