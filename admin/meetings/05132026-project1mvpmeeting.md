# Meeting Minutes: Project 1 Meeting (Sprint 2)
**Team Number/Name:** Group 25 / [KnowIdeas]  
**Date:** [05/13/26]  
**Time:** [8:00] - [9:50]  
**Location:** [Giesel]  

---

## 1. Attendance
| Member | Status |
| :--- | :--- |
| Shawn Wang | Present |
| Pranav Ganesan | Present |
| Sahana Rangaraj | Absent (excused) |
| Quinton Fu | Present |
| Wayne Su | Present  |
| Kabyan Pathak | Absent |
| Chan Han | Present (Zoom - Notified)|
| John Hermosura | Present |
| Jordan Tran | Present |
| Hojoon Kim | Present |
| Ayla Kurdak (TA) | Invited |

## 2. Agenda
1. Finish MVP
  - Should we be using a pre made game engine?
2. Start mockup or prototype demo of game
3. Schedule weekly meetings
4. Reinforce existing tasks
  - Filling out standup queries
  - Reacting to announcements
  - Communicating with each other
  - Putting updates in the updates channel
5. Address integrations and how useful they are

## 3. Meeting Notes:
- Minimum viable product is composed of 3 components:
    1. **Frontend** *(things that the user interacts with)*
         - Design => This should be considered high priority. Since we are making an entertaining game, having a lack of design can be a massive pitfall. Of course, it doesn't make sense for us to put everything into game design and nothing into the backend, but we also should not expect that our final product can lack a design.
         - Mobile Compatibility => We are likely going to need to have separate HTML pages for mobile and desktop displays. This will be a little bit of extra work, but we should move forward expecting to implement functionalities for both pages. It would make things a lot easier to do both in parallel rather than finish one and then port everything over to the other because iterative building would be easier to digest than a giant preexisting file.
         - Feedback
             1. Sounds
             2. VFX
             3. Delay (try to use throttling to see the effects of functionality on page load)
    2. **Backend** *(things that the user does not explicitly interact with)*
         - Game engine => We are going to be using a game engine so that we don't have to make one ourselves. It should take a lot of the programming work off of our hands, which will significantly speed up what we're trying to do. This is a "married" decision, so we will be creating an ADR for our use of a game engine. Our options for game engines are as follows:
             1. Pixi.JS
             2. Phaser
             3. ct.JS
             4. ROT.JS
            
            Everyone needs to take a look at these options and choose one that they would be interested in working with. Deadline for this will be tomorrow (5/14)
        - Gameplay loop => We are going to be making a "premade" puzzle-based gameplay loop which means that we will more than likely have to create puzzles for the player to solve. There may be random aspects in the overarching gameplay, but the goal will be to control variables so that we can avoid unfun random edge cases. We may also implement some kind of daily reward system, but that will be considered after we have created some sort of reward first.
    3. **Data storage** *(ability to load in save states)*
         - For now, we are looking to use local storage to maintain player information upon loading the game. However, we do recognize that this could lead to vulnerabilities to do with the player being able to alter their local storage, so we'll have to account for that in our final product.
         - Also note that we are still considering using some kind of database similar to SQLite in order to store player information in the cloud. This would remove the vulnerability of the player altering their local storage, but be advised that this would likely be another "married" decision and a dependency.


<img width="1000" height="1333" alt="IMG_1172" src="https://github.com/user-attachments/assets/b493d88e-483f-434a-a5f8-319d34c2349b" />


## Upcoming Indivudal Responsibilites:
- [ ] Write ADR documents based on game engine decision
- [ ] Use MADR format. Every major technical decision needs an ADR.
- [x] Design workflows for your MVP
- [x] Ad hoc diagramming is fine : with whiteboard, Miro, Figma, etc. all work.
- [x] Break down tasks needed to reach MVP
- [ ] Design, data model, UI components, integrations. Figure out team structure.
- [ ] Build your CI/CD pipeline
- [ ] Get GitHub Actions running before majority of development begins.
- [ ] Exit Criteria: MVP with at least one diagram should be done before development beyond CI-CD pipeline begins.
- [ ] Choose a game engine to use


