---
tags:
  - graphHidden
cssclasses:
  - sidebar
noteType: page
modified_at: 2025-04-09T14:04:32-04:00
---
<br>

# [[🏠 Homepage]]
### ✈️ Note Starters
<br> 

```meta-bind-button
label: New A&P General
icon: ""
style: primary
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: ""
id: ""
hidden: false
actions:
  - type: createNote
    folderPath: Notes/A&P School/General
    fileName: Untitled
    openNote: true
    openIfAlreadyExists: false

```
<br>

```meta-bind-button
label: New A&P Airframe
icon: ""
style: primary
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: ""
id: ""
hidden: false
actions:
  - type: createNote
    folderPath: Notes/A&P School/Airframe
    fileName: Untitled
    openNote: true
    openIfAlreadyExists: false

```
<br>

```meta-bind-button
label: New A&P Powerplant
icon: ""
style: primary
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: ""
id: ""
hidden: false
actions:
  - type: createNote
    folderPath: Notes/A&P School/PowerPlant
    fileName: Untitled
    openNote: true
    openIfAlreadyExists: false

```
<br> 

```meta-bind-button
label: New Flight Lesson
icon: ""
style: primary
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: ""
id: ""
hidden: false
actions:
  - type: createNote
    folderPath: Notes/Flight Training
    fileName: Untitled
    openNote: true
    openIfAlreadyExists: false

```
<br>

```meta-bind-button
label: New Term
icon: ""
style: default
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: ""
id: term
hidden: false
actions:
  - type: createNote
    folderPath: Reference/Glossary
    fileName: Untitled
    openNote: true
    openIfAlreadyExists: false

```
## Notes
- [[All Notes]]
- [[Quote Book]]
- [[Aviation Resources]]
- [[AMT Class Notes]]
- [[Private Pilot License (PPL) Notes]]

## Books
- [[Aeronautical Information Manual]]
- [[Airplane Flying Handbook (FAA-H-8083-3C)|Airplane Flying Handbook]]
- [[Federal Aviation Regulations]]
- [[Pilot’s Handbook of Aeronautical Knowledge (FAA-H-8083-25C)|Pilot’s Handbook of Aeronautical Knowledge]]
### AMT Books
- [[AMT Handbook - General (FAA-H-8083-30B).pdf|AMT Handbook - General]]
- [[AMT Handbook - Airframe (FAA-H-8083-31B).pdf|AMT Handbook - Airframe]]
- [[AMT Handbook - Powerplant (FAA-H-8083-32B).pdf|AMT Handbook - Powerplant]]
### Favorites
```dataview
LIST
FROM #favorite
SORT file.mtime DESC
```
### Quick Notes
```dataviewjs
const notes = dv.pages('"Quick Notes"')
if (notes.length){
  dv.list(notes.file.link)
}
else{
  dv.span('- ? Not any Quick Notes Found')
}
```
### Follow Up Notes
```dataviewjs
const notes = dv.pages('#followup')
if (notes.length){
  dv.list(notes.file.link)
}
else{
  dv.span('- ? Not any FollowUp Notes Found')
}
```
### Recents

#### Last Opened
```dataviewjs
dv.list(app.workspace.recentFileTracker.lastOpenFiles.map(x=>dv.fileLink(x)).slice(0, 7))
```
---
#### Last Modified
```dataview
LIST
FROM ""
SORT file.mtime DESC
LIMIT 7
```
