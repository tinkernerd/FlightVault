<% '---' %>
<%* let title = await tp.system.prompt('Enter the title:');
tR += "title: " + title %>
category: "Aviation"
status: "Active"
created_at: <% tp.file.creation_date('YYYY-MM-DD[T]HH:mm:ssZ') %>
modified_at: <% tp.file.last_modified_date('YYYY-MM-DD[T]HH:mm:ssZ') %>
type: "Resource"
program: "PPL"
topic:
tags:
  - aviation
  - classnotes
<%* let chapter = await tp.system.prompt("What's the chapter again?");
tR += "chapter: Chapter " + chapter + "\n"; %>
<%* let lesson = await tp.system.prompt("What's the lesson again?");
tR += "lesson: " + chapter + "\n"; %>


<% '---' %>
# `= this.title`

> [[🏠 Homepage]] • [[Private Pilot License (PPL) Notes]]

> **Type**: `INPUT[inlineSelect(option(Resource), option(Lecture), option(Lab), option(Reference)):type]`  
> **Status**: `INPUT[inlineSelect(option(Active), option(Planned), option(In Progress), option(Completed), option(Archived)):status]`

---
