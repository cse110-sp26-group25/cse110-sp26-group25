# Meeting Minutes: Project 1 Meeting (Sprint 2)

**Team Number/Name:** Group 25 / [KnowIdeas]  
**Date:** 05/16/26  
**Time:** 6:00 PM - 8:30 PM  
**Location:** Zoom  

---

## 1. Attendance

| Member | Status |
| :--- | :--- |
| Shawn Wang | Present |
| Pranav Ganesan | Present |
| Sahana Rangaraj | Present |
| Quinton Fu | Present |
| Wayne Su | Present |
| Kabyan Pathak | Present |
| Chan Han | Present |
| John Hermosura | Present |
| Jordan Tran | Present |
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

## 4. Backlog & Task Assignments (Current Sprint)

| Priority | Task | Assigned To |
| :--- | :--- | :--- |
| **Ultra Important** | Overarching story and substories (Level 1-5) | Darci, Sahana, Pranav |
| **Ultra Important** | Wireframing the UI/Look of the game | Shawn, Kabyan |
| **Ultra Important** | Mobile/Desktop detection & Fetching scene data | Hojoon, John |
| **Ultra Important** | Accuracy checker & Wordbox logic | Quinton, Wayne, Jordan |
| **Important** | UI / "The Book" interface & Pop-up screens | TBD |
| **Important** | Saving states and Tutorial stage | TBD |

---

## 5. Action Items & Upcoming Responsibilities

- [ ] **Finalize ADR:** Document the choice of **ct.js** using the MADR format.
- [ ] **Workflow Diagrams:** Create visual flowcharts for the gameplay loop (Investigate → Wordbox → Story Completion).
- [ ] **GitHub Actions:** Verify CI/CD pipeline is fully operational before pushing major ct.js assets.
- [ ] **Asset Design:** Initiate character/item design to avoid "lack of design" pitfalls identified in MVP goals.
- [ ] **Exit Criteria:** Ensure at least one full level diagram is completed before the next sync (5/20)
