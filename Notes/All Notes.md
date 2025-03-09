---
category: Aviation
created_at: 2025-02-23 15:29:49-05:00
cssclasses:
  - cleandoc
dg-publish: true
modified_at: 2025-03-09T09:11:49-04:00
status: Active
tags:
  - aviation
  - classnotes
title: All Notes
topic:
  - Reference
type: Resource
---

# `= this.title`
> [[Private Pilot License (PPL) Notes |All Class Notes]]
## Air Traffic
```dataview  
LIST
WHERE contains(category, "Aviation") AND contains(topic, "Air Traffic")
SORT p.title ASC
```
## Aircraft
```dataview  
LIST
WHERE contains(category, "Aviation") AND contains(topic, "Aircraft")
SORT p.title ASC
```
## Airport Operations
```dataview  
LIST
WHERE contains(category, "Aviation") AND contains(topic, "Airport Operations")
SORT p.title ASC
```
## Communication
```dataview  
LIST
WHERE contains(category, "Aviation") AND contains(topic, "Communication")
SORT p.title ASC
```
## Controlling The Aircraft
```dataview  
LIST
WHERE contains(category, "Aviation") AND contains(topic, "Control")
SORT p.title ASC
```
## Emergencies
```dataview  
LIST
WHERE contains(category, "Aviation") AND contains(topic, "Emergencies")
SORT file.title ASC
```
## Events
```dataview  
LIST
WHERE contains(category, "Aviation") AND contains(topic, "Events")
SORT file.title ASC
```
## Helicopter
```dataview  
LIST
WHERE contains(category, "Aviation") AND contains(topic, "Helicopter")
SORT file.title ASC
```
## Medical
```dataview  
LIST
WHERE contains(category, "Aviation") AND contains(topic, "Medical")
SORT file.title ASC
```
## Navigation
```dataview  
LIST
WHERE contains(category, "Aviation") AND contains(topic, "Navigation")
SORT p.title ASC
```
## Planning
```dataview  
LIST
WHERE contains(category, "Aviation") AND contains(topic, "Planning")
SORT p.title ASC
```
## Safety
```dataview  
LIST
WHERE contains(category, "Aviation") AND contains(topic, "Safety")
SORT p.title ASC
```
## T/O & Landings
```dataview  
LIST
WHERE contains(category, "Aviation") AND contains(topic, "T/O & Landings")
SORT file.title ASC
```
## Weather 
```dataview  
LIST
WHERE contains(category, "Aviation") AND contains(topic, "Weather")
SORT file.title ASC
```
# All Notes
```dataview  
TABLE WITHOUT ID  
link(file.path, title) AS "Note", file.mtime AS "Last Modified"
FROM "Notes"
WHERE contains(category, "Aviation")
    AND !contains(file.path, "Notes/AIM")
    AND !contains(file.path, "Notes/FAR")
    AND !contains(file.path, "Notes/Glossary")
SORT file.name ASC
```