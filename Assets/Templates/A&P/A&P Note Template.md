<% '---' %>
<%* let title = await tp.system.prompt('Enter the title:');
tR += "title: " + title %>
category: "Aviation"
status: "Active"
tags: [aviation, amt, study, prep]
topic:
  - Maintenance
type: "Resource"
program: "AMT"
<%* let chapter = await tp.system.prompt("What's the chapter again?");
tR += "chapter: Chapter " + chapter + "\n"; %>
section: General
book:
created_at: <% tp.file.creation_date('YYYY-MM-DD[T]HH:mm:ssZ') %>
modified_at: <% tp.file.last_modified_date('YYYY-MM-DD[T]HH:mm:ssZ') %>
cssclasses: [meta-bind]
<% '---' %>
# `= this.title`

> [[🏠 Homepage]]
> **[[AMT Class Notes]]**
> **Section**: `INPUT[inlineSelect(option(General), option(Airframe), option(Powerplant)):section]`  
> **Book**: `INPUT[inlineSelect(option(FAA-H-8083-30A), option(FAA-H-8083-31A), option(FAA-H-8083-32A)):book]`  
> **✈️Type**: `INPUT[inlineSelect(option(Resource), option(Lecture), option(Lab), option(Study Note), option(Reference)):type]`  
> **Status**: `INPUT[inlineSelect(option(Active), option(Planned), option(In Progress), option(Completed), option(Archived)):status]`


---

## ✍️ Summary  
_A brief summary of what this lesson covers in your own words._

---

## ✅ Key Concepts & Takeaways
_Bullet points of what you need to remember or understand._

- 
- 
- 

---

## 🧠 Things to Understand
_What’s tricky, confusing, or new?_

- 
- 

---

## 🧪 Examples / Systems
_Diagrams, walkthroughs, processes._

- 

---

## ❓ Questions for Review or Class
_Start building review questions for when class begins._

- 
- 

---

## 🧾 Terms & Definitions
> [[A&P Glossary]]

| Term | Meaning |
|------|---------|
|      |         |
|      |         |

---

## 🔗 Resources  
- [ ] FAA Handbook reference page  
- [ ] Video explanation  
- [ ] FAR/AIM or AC links 