<% '---' %>
<%* let title = await tp.system.prompt('Enter the title:');
tR += "title: " + title %>
category: "Aviation"
status: "Active"
tags:
  - aviation
  - maintenance
  - general
topic:
  - Maintenance
type: "Resource"
program: "AMT"
class: 
<%* let chapter = await tp.system.prompt("What's the chapter again?");
tR += "chapter: Chapter " + chapter + "\n"; %>
section: PowerPlant
book: FAA-H-8083-32B
created_at: <% tp.file.creation_date('YYYY-MM-DD[T]HH:mm:ssZ') %>
modified_at: <% tp.file.last_modified_date('YYYY-MM-DD[T]HH:mm:ssZ') %>
cssclasses: [meta-bind]
<%* 
// Format chapter number (remove "Chapter " prefix if needed)
let chapterNumber = chapter.replace(/^Chapter\s*/i, '').trim();
let sectionName = "PowerPlant"; // default in case it's not updated live

// Try to read section from the frontmatter if set
const file = tp.file.find_tfile(tp.file.path(true));
await app.fileManager.processFrontMatter(file, (fm) => {
  if (fm["section"]) sectionName = fm["section"];
});

// Final rename string
let newName = `${sectionName} - Ch ${chapterNumber} - ${title}`;
await tp.file.rename(newName);
%>
<% '---' %>
# `= this.title`

> [[🏠 Homepage]] • [[AMT Class Notes]]

> **Book**: [[AMT Handbook - Powerplant (FAA-H-8083-32B).pdf|AMT Handbook - Powerplant (FAA-H-8083-32B)]]
> **✈️ PowerPlant Classes:** `INPUT[inlineSelect(option(Reciprocating Engines),option(Turbine Engines),option(Engine Inspection),option(Engine Instrument Systems),option(Engine Fire Protection Systems),option(Engine Electrical Systems),option(Lubrication Systems),option(Ignition & Starting Systems),option(Engine Fuel & Fuel Metering Systems),option(Reciprocating Engine Induction & Cooling Systems),option(Turbine Engine Air Systems),option(Engine Exhaust & Reverser Systems),option(Propellers)):class]`
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