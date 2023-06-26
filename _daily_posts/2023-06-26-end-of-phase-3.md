---
title: Completing Phase 3
phase: 3
layout: daily_post
---

To wrap up Phase 3, we have three things to do:

1. Finish the Social Cards or QuestionBox project and have it working in production.
2. Pass a short technical interview about your project.
3. Provide feedback to your peers.

The project is due by EOD on {{ site.data.phase3.projects.collaborative_project.due_date | date:"%A, %B %-d" }}.

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

### End-of-phase Technical Interview

You will meet with an instructor one-on-one to answer questions about your code. We'll ask you a few technical questions in the context of the project you have been working on.

You will need to be able to demo your code **in production,** not running on localhost.

#### What we are assessing in the interview

- The code you are explaining is code that you wrote or co-wrote.
- You can demo your code in production.
- You can explain, in specifics, how your code works, with a reasonable degree of accuracy.
- You can comment, in specifics, on what you need to understand better or work on next.

⭐ The goal is to demonstrate productivity and working knowledge, not perfection.
{:.mmntm-purple.text-gamma}

### Interview Format & Content

Each interview will be about 10-15 minutes long and will focus on one of the topics listed below. Your instructor will ask you a question based on your project, and in response, you'll show your code and talk about how it works. The expectation is that you are demoing code that you, yourself, wrote. You should be prepared to share your screen.

Your instructor will let you know at the end of the interview, or shortly after, if you have met the requirements to complete Phase 3.

Interviews slots are available on Thursday afternoon and Friday morning. Please use **[this calendly link to sign up for a time](https://calendly.com/amy-at-momentum/end-of-phase-interview)** that works for you.

#### Back End

The back-end interview will focus on one of these topics, and will include specific follow-up questions. You should be able to demo this in Insomnia or the Django shell AND talk through the code implementation.

1. **Endpoints & Serializers**. How did you design and customize endpoints for the front-end application? You might talk about some or all of these topics: the url patterns; the HTTP methods that are handled; serializers; permissions; querysets and any filtering you may have done.
2. **Models**. Why did you design your model(s) the way you did? Some things you probably want to talk about: the relationships a model has with other models, and why you need them; any custom methods you wrote for a model; any queries you did with your models that were tricky or interesting; anything you learned about how to work with models doing your project.
3. **Features**. Explain the functionality and implementation of a feature (e.g., creating a new card or marking an answer as accepted). Describe what it does, why it is important, and explain how you wrote the code to achieve that goal.

#### Front End

The front-end interview will focus on one of these topics, and will include specific follow-up questions. You should be able to demo this in the browser AND talk through the code implementation.

1. **Components**. Topics that might come up: what the purpose/responsibility of a component is; when and where it is rendered; what props it receives from its parent; any state the component has, what it's for, and how it changes; any events that component handles; any hooks (built-in to React, built-in to another library, or custom) used in the component besides useState (e.g., useEffect, useRef, useParams, useLocalStorageState).
2. **Fetching Data**. Explain when data is fetched and what you are doing with the response. You should be able to talk about useEffect and how you're handling the initial render of a component before data is fetched. Ideally you are also handling errors and giving feedback in the UI.
3. **Client-side Routing**. How specifically are you using React Router? What URLs can your app handle? How do you anticipate your user will navigate through your app?

---

## Peer Feedback

Peer feedback is often included in workplace review processes (sometimes it's called a 360º review), focusing on the collaborative nature of work. In software engineering, effective collaboration skills make you a valuable employee and contributor.

We're piloting an assessment of collaboration skills in Phase 3 that asks your teammates to evaluate the experience they have had working with you.

The feedback will be anonymous. Each person will submit feedback for teammates and at least one other person on the other team. Feedback forms will be made available later this week.

### Collaboration Skills on the Feedback Form

Your peers will give you feedback about their experience of working with you, rating their agreement with the following statements on a scale of 1-5 (from strongly disagree to strongly agree).

- They communicate effectively.
    - An effective communicator does things like:
        - responds to messages on Slack promptly
        - checks in with teammates often
        - proactively provides information that others need to know without waiting to be asked
        - lets teammates know what they are working on
        - explains and shares their ideas
- They collaborate effectively.
    - An effective collaborator does things like:
        - asks what others think
        - listens carefully to other people's ideas
        - revises their ideas based on the ideas of others
        - compromises and seeks consensus
        - finds ways to share the work
- I can rely on them to do what they say they will do and to meet deadlines.
- They take on a fair or equal share of the work.
- They are considerate about not blocking the progress of others.
- They offer and provide help if needed and readily share what they know.
- They demonstrate that they care about delivering a great product.
- They treat me and others with respect.
- They show initiative and creativity in solving problems and finding solutions.
- I enjoy collaborating with them and would work with them again.

There is one open-ended question on the feedback form:

_What is the best thing about working with this person? What do you appreciate most about the work they do, or the way they work?_

{:.lt-blue}
💬 All the feedback about you will be shared with you.
