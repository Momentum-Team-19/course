---
title: Completing Phase 3
phase: 3
layout: daily_post
published: true
---

To wrap up Phase 3, you have three things to do:

1. Finish the Social Cards or QuestionBox project with your team and have it working in production.
2. Pass a short technical interview about the work you contributed to your project.
3. Present your work on the project to the team.

The project is due by {{site.data.phase3.projects.collaborative_project.due_time }} on {{ site.data.phase3.projects.collaborative_project.due_date | date:"%A, %B %-d" }}.

{:.phase-success}

> - You have made a substantive contribution to the project (a substantive contribution means that you have committed meaningful code in the project repo).
> - Your application meets the minimum requirements detailed in the assignment.
> - Your application runs without errors in production.
> - Your application repo includes a README with a link to your production application and instructions for running the application locally.
> - You can talk through code that you wrote during a short individual technical interview.

#### You might not complete the phase if

- You have not made a substantive contribution to the project.
- Your project is incomplete or does not meet the minimum requirements.
- Your project is not running in production.
- You cannot explain how your code works during the technical interview.

If you don't complete the phase, you may be asked to repeat it before you can progress to Phase 4.

---

## End-of-phase Technical Interview

You will meet with an instructor one-on-one to answer questions about your code. We'll ask you a few technical questions in the context of the project you have been working on.

You will need to be able to demo your code **in production,** not running on localhost.

#### What we are assessing in the interview

- The code you are explaining is code that you wrote or co-wrote.
- You can demo your code in production.
- You can explain, in specifics, how your code works, with a reasonable degree of accuracy.
- You can comment, in specifics, on what you need to understand better or work on next.

⭐ The goal is to demonstrate productivity and working knowledge, not perfection.
{:.mmntm-red.text-gamma}

### Interview Format & Content

Each interview will be about 10-15 minutes long and will focus on one of the topics listed below. Your instructor will ask you a question based on your project, and in response, you'll show your code and talk about how it works. The expectation is that you are demoing code that you, yourself, wrote. You should be prepared to share your screen.

Your instructor will let you know at the end of the interview, or shortly after, if you have met the requirements to complete Phase 3.

Interviews slots are available on Thursday morning during our regular meeting time. Please use **[this calendly link to sign up for a time](https://calendly.com/momentumlearn/end-of-phase-interview)** that works for you.


#### Interview Topics

The front-end interview will focus on one of these main topics, and will include specific follow-up questions. You should be able to demo this in the browser AND talk through the code implementation.

1. **Components**. Topics that might come up: what the purpose/responsibility of a component is; when and where it is rendered; what props it receives from its parent; any state the component has, what it's for, and how it changes; any events that component handles; any hooks (built-in to React, built-in to another library, or custom) used in the component besides useState (e.g., useEffect, useRef, useParams, useLocalStorageState).
2. **Fetching Data**. Explain when data is fetched and what you are doing with the response. You should be able to talk about useEffect and how you're handling the initial render of a component before data is fetched. Ideally you are also handling errors and giving feedback in the UI.
3. **Client-side Routing**. How specifically are you using React Router? What URLs can your app handle? How do you anticipate your user will navigate through your app?

**Follow up questions might include:**
- What bugs did you have to solve?
- Did you consider other ways to do this, and why did you decide to do it the way you did?
- Did you seek out something new while working on this that we didn't cover in the course? What was it, and what did you learn?
- Talk about the way you worked with your team. What worked well? What would you do differently next time?

---

## Presenting your project

On Thursday afternoon from 3-4 we will meet in Zoom, and each person will take **5 minutes** to present their contribution to the project to the rest of Team 19. You should be prepared to demo your project in production, show your code, and talk about the following:

- What was your contribution to the project? Show us the finished product and talk about what you did.
- Select one specific thing you implemented and tells us how it works. Show the code and talk through it in enough detail that if someone wanted to implement something similar, they would know how to do it.
- Describe at least one technical challenge that you faced and solved. 
