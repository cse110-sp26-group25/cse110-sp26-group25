# Meeting Minutes: Final Sprint Meeting (catchup)

**Team Number/Name:** Group 25 / [KnowIdeas]  
**Date:** 06/04/26  
**Time:** 8:30 PM - 9:15 PM  
**Location:** Zoom  

---

## 1. Attendance

| Member | Status |
| :--- | :--- |
| Shawn Wang | Present |
| Pranav Ganesan | Present |
| Sahana Rangaraj | Present |
| Quinton Fu | Present |
| Wayne Su | Absent |
| Kabyan Pathak | Present |
| Chan Han | Present |
| John Hermosura | Present |
| Jordan Tran | Absent |
| Hojoon Kim | Present |
| Ayla Kurdak (TA) | Invited |

---

## 2. Agenda
- Finalize MVP definition and core project specs.
- Confirm Game Engine selection and next steps for integration.
- Assign high-priority backlog items for the current sprint.
- Review mobile vs. desktop layout strategy.
- Finalize CI/CD and data storage roadmap.

---

## 3. Meeting Notes & Project Specifications

### Major Decisions
* **Game Engine:** The team has officially selected **ct.js**. This is a "married" decision; the corresponding ADR should be finalized immediately.
* **Genre/Theme:** "The Case of the Golden Idol" style puzzle game. Players act as MIB investigators analyzing HTML-based information files.
* **Core Mechanic:** Typing-centric gameplay. Key features include a **Debugging** mode and a **Word box** for clue assembly.
* **Scale:** 3–5 levels. Each level features interactive objects/characters that provide clues to fill in story "blanks" (e.g., *Darci killed [___] and ran off with [___]*).

### Technical Breakdown
* **Frontend:** Mobile and Desktop detection is a priority. We will develop separate layouts in parallel to ensure a seamless experience on both platforms.
* **Backend:** Focus on the Accuracy Checker (validating user input vs. the story answer) and the Scene Data Fetcher.
* **Database:** Starting with **Local Storage** for save states (clues, levels, wordbox) but maintaining a roadmap for a cloud-based SQL migration for security.

---

Meeting Minutes: Final Sprint 

Team Number/Name: Group 25 / [KnowIdeas]
Date: 06/04/2026
Time: 8:30 PM - 9:10 PM
Location: Zoom

1. Attendance

Member	Status
Shawn Wang	Present
Pranav Ganesan	Present
Sahana Rangaraj	Present
Quinton Fu	Present
Wayne Su	Absent
Kabyan Pathak	Present
Chan Han	Present
John Hermosura	Present
Jordan Tran	 Absent
Hojoon Kim	Present
Ayla Kurdak (TA)	Invited

2. Agenda

Communication

3. Meeting Notes

Solified storyline for all three levels
Animations except for one is complete
Level scripts done
character sprites and screens need to be pushed ASAP to the master branch
fix inconsistency between script and reference
cleaned up PRs
current branches: story development, level creation, local storage (waiting on jordan to respond), mobile detection (mobile detection)
all important works needs to be finished by Saturday 7:00am

