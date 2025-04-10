<% '---' %>
<%* let title = await tp.system.prompt('Enter the title:');
tR += "title: " + title %>
category: "Aviation"
status: "Active"
created_at: <% tp.file.creation_date('YYYY-MM-DD[T]HH:mm:ssZ') %>
modified_at: <% tp.file.last_modified_date('YYYY-MM-DD[T]HH:mm:ssZ') %>
type: "Resource"
program:
topic:
tags:
  - aviation
  - classnotes
<% '---' %>
# `= this.title`

> [[🏠 Homepage]]

> **Type**: `INPUT[inlineSelect(option(Resource), option(Lecture), option(Lab), option(Reference)):type]`  
> **Status**: `INPUT[inlineSelect(option(Active), option(Planned), option(In Progress), option(Completed), option(Archived)):status]`
> **Program**: `INPUT[inlineSelect(option(PPL), option(A&P)):program]`

---
