---
title: 'FE + BE Collaborative Project'
phase: 3
layout: daily_post
---

This week you will begin work on a project with both front-end and back-end teammates. This project must be completed by the end of the phase, on {{ site.data.phase3.projects.collaborative_project.due_date | date: "%A, %B %e" }}.

**In order to successfully complete Phase 3 and qualify for Phase 4**:

- This project must meet the minimum requirements to be considered complete.
- It must be deployed and running without errors in production to be considered complete.
- Each team member must make a substantive contribution to the project. This is best demonstrated through frequent, well-formed commits.
- Each team member must be able to explain how the project works (that is, back-end devs know how the back-end works; front-end devs know how the front-end works).

We haven't yet covered everything you'll need to be able to do this project, so that will be our task this week and next.

## 📆 This week's meeting schedule & expectations

Because of the Monday holiday, we will meet on Tuesday, Wednesday, and Thursday this week.

**The back-end class will meet on Thursday from 2-4 with Amy. Front-end will meet at their regular time.**

We'll check in on the projects each day. This week, front-end and back-end teams will continue to meet separately. Next week we may meet as project teams instead of separate front-end and back-end teams, or both teams together, depending on how much progress teams make this week. Next week's meeting schedule will be TBD until later this week.

Everyone is expected to come to meetings prepared to give progress reports and demo what you have built. We're also expecting you to ask for help frequently throughout this extended project.

## 🏗️ Collaborative Project Logistics

You'll work on two combined front-end and back-end teams. Each team will build a different project and will use [GitHub Projects](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects) and [GitHub Issues](https://github.com/features/issues) to track project todos.

### The Teams

**Team leads, your role is to manage team efforts today.** You may rotate this role after today if your team wishes.

| Team Fire 🔥 | Team Ice 🧊 |
| ----------- | ---------- |
| Laura       | Teddy      |
| Alain       | Meagan     |
| Matt        | Steve      |
| Anna        | Q          |
| Alex        |            |

### How to work as one team

Even though you have separate responsibilities on the front-end and back-end, you're working together to ship a single product, on time. You can make product decisions together even though you will implement features separately.

Keep in mind that communicating well with your teammates is a crucial part of this project. You will need to talk to each other frequently so that you aren't duplicating work or building things that will not work together. In discussing how you will do things, you will also be learning about what the front-end and back-end can do.

You are encouraged to work with the other front-end or back-end devs on other teams to share ideas, advice, approaches, and resources.

### Creating the repos

Today you will need the project repo so that you can read the README for each project and decide which one you will do.

On each project team, the back end will work in their own repo and the front end will work in their own repo. So, each team will have _two_ repos, one back-end and one front-end.

**One back-end dev** should accept the assignment invitation and create a new team; name the team something like "Team Yeti Back-end" (whatever your team name is!). Then the other back-end dev(s) should accept the assignment and choose the right team.

**One front-end dev** should accept the assignment invitation and create a new team; name the team something like "Team Yeti Front-end" (whatever your team name is!). Then the other front-end dev(s) should accept the assignment and choose the right team.

⚠️ You have to accept the invitation and join the team your teammate created in order to have write permissions to the repo.

**Today you will not commit or push any code since your main goal is planning**.

### A word about using Git as a team

Working with other developers in a shared codebase means that the workflow you've been using so far will have to change. **We will cover this together tomorrow.**

### 🥅 Your Goals Today 🥅

- Read your project's README.
- Decide which project your team wants to do.
- Read your project's README again, carefully.
- Understand the project requirements thoroughly and discuss with your team what you need to build.
- Front end: make wireframes and sketch out the user flow (see details below).
- Back end: plan and diagram your models and create an initial list of endpoints (see details below).
- Your planning should be documented. You can use any planning tools you find helpful. Some possible tools include Google Docs, Miro, Trello, and Excalidraw. Make sure everyone on your team has access to any planning docs you create. 
- Use [GitHub Projects](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects) to create a new Project in your repo.
- Create code todos for your project as [GitHub Issues](https://github.com/features/issues). Items you add to your GitHub Project can be converted to GitHub Issues in your repo. These should be detailed and labelled (e.g., "front-end" and "back-end") but DO NOT have to be assigned initially. You may find the [GitHub Issues Quickstart Guide](https://docs.github.com/en/issues/tracking-your-work-with-issues/quickstart) helpful.

---
#### Front-end Goals Today

You will need to sketch out the **[user flow](https://signalvnoise.com/posts/1926-a-shorthand-for-designing-ui-flows)** and [draw up some **wireframes**](https://xd.adobe.com/ideas/process/wireframing/wireframe-design-101/) for the application. It can help to ask questions like:

- What does our user see when they first land on our site?
- What will they need to do here?
- How will they accomplish that?
- What will happen next?
- If they click on a button or link, what happens?
- What does the UI look like after the user clicks on something / follows a link / submits a form?

**Every front-end developer on the team should be able to answer these questions.**

##### By tomorrow front-end should have (in writing, diagrams, or sketches)

- A detailed user flow plan/diagram
- Detailed wireframes
- A good initial plan of the components you think you will need

---
#### Back-end Goals Today

You will need to draw ER diagrams to plan out the **models** and create a list of **endpoints** (URLs) you think you will need. It can help to ask questions like:

- What are the _nouns_ in your project requirements? These are likely models.
- What data will you need to save in your database so you can look it up again later?
- What information will the front-end need so they can accomplish the UI that they are planning?
- What CRUD actions will the front-end need to do? You don't necessarily need to build full CRUD for every model. Plan to build _only_ what you need.
- What permissions will need to be in place?

**Every back-end developer on the team should be able to answer these questions.**

##### By tomorrow back-end should have (in writing, diagrams, or sketches)

- ER Diagrams for your models
- A list of endpoints
- A good initial plan for the JSON data you think you will need to return
