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
- Define Minimum Viable Product (MVP) components.
- Select a pre-made game engine (Married Decision).
- Discuss mobile compatibility and separate HTML layouts.
- Establish data storage strategy (Local Storage vs. SQLite).
- Review project backlog and upcoming task assignments.
- Finalize CI/CD pipeline requirements.

---

## 3. Meeting Notes

### MVP Definition & Frontend Strategy
* **Design Priority:** High. Since this is an investigator/puzzle game, visual design is crucial for player engagement.
* **Mobile Compatibility:** The team will implement separate HTML pages for mobile and desktop in parallel to avoid "porting" debt later.
* **Feedback Loops:** Focus on SFX, VFX, and UI throttling to ensure a responsive feel.

### Game Mechanics (The "Case of the Golden Idol" Type)
* **Genre:** Puzzle/Investigator.
* **Story:** Players act as MIB investigators. Clues are gathered into a "Word box" to fill in overarching story bits.
* **Typing Integration:** Typing will be the main interaction method (Debugging mode and Word box entry).
* **Scale:** Aiming for 3-5 levels with interactive objects/characters containing clues.

### Backend & Technical Decisions
* **Game Engine:** We will use a pre-made engine. Options to review by **5/14**:
    * Pixi.JS
    * Phaser
    * ct.JS
    * ROT.JS
* **Storage:** Initial implementation will use **Local Storage**. We are weighing a move to **SQLite** for cloud sync and better security against user-side data alteration.

---

## 4. Backlog & Task Assignments (5/16 - 5/22)

| Priority | Task | Assigned To |
| :--- | :--- | :--- |
| **Ultra Important** | Overarching story and substories | Darci, Sahana, Pranav |
| **Ultra Important** | Wireframing the look of the game | Shawn, Kabyan |
| **Ultra Important** | Detecting mobile/desktop & Data Fetch | Hojoon, John |
| **Ultra Important** | Accuracy checker & Wordbox update | Quinton, Wayne, Jordan |
| **Important** | UI/Book design & Event checks | TBD |
| **Medium** | Character and item design | TBD |
| **Low** | User skins & Animations | TBD |

---

## 5. Upcoming Individual Responsibilities

- [ ] **Game Engine Choice:** Everyone must review Pixi, Phaser, ct.JS, and ROT.JS. Deadline: **05/14**.
- [ ] **Write ADRs:** Use MADR format for the game engine and database choice.
- [ ] **MVP Workflows:** Design ad hoc diagrams (Miro/Figma/Whiteboard).
- [ ] **CI/CD Pipeline:** Shawn/Hojoon to ensure GitHub Actions are running before major development starts.
- [ ] **Exit Criteria:** MVP with at least one diagram must be completed before development continues.

---

**Next Meeting:** TBD (Weekly schedule to be finalized).
