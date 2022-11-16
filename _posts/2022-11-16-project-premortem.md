---
title: Project Premortem — how to predict and mitigate risk
date: 2022-11-16 11:00:00 +1000
categories: [General]
tags: [Introduction]     # TAG names should always be lowercase
---

![A group of people brainstorming](/assets/img//posts/brainstorming.jpeg)
Photo by <a href="https://unsplash.com/@jasongoodman_youxventures?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Jason Goodman</a> on <a href="https://unsplash.com/s/photos/brainstorm?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  

Failures are a natural event in the life cycle of a product, but they’re especially painful when a whole project ends up unsuccessful.

When a digital product fails, the team usually performs an inspection called a postmortem. The team gathers, analyzes what went wrong, tries to conclude, and creates a note. The learnings from that failure **help the company adjust the processes so as not to repeat the same mistake**.

But what if we could look into the future before the project failed? At nomtek, we use a premortem — an attempt to predict and mitigate problems *before* they happen.

## What is a Postmortem?

Before explaining what a premortem is, let’s take a closer look at a **postmortem**.

In medical language, a postmortem describes the procedure after the patient’s death, where doctors and pathologists try to understand the cause of their demise. The detailed analysis of why something as complex as a human body has failed can be applied to multiple contexts.

**For example, when you need to understand what exactly went wrong to be able to avoid it in the future**.

Software development loves postmortems because they’re a great learning tool.

## What is a Premortem?

The main purpose of a premortem is to simulate failure before it happens.

More specifically, **a premortem is a meeting that takes place before the first line of code is written**. All team members involved in a project attend it:

* account manager

* development team

* moderator

Depending on the size of the project and the team, a premortem meeting lasts **one to two hours**. We follow these steps:

### **1. The scope of the project is explained so that each participant has a full picture of the situation and potential threats.**

At nomtek, we do a premortem after the kick-off meeting, when the team already had a chance to familiarize themselves with the current state and plans for the future.

### **2. The moderator announces that the project has failed.**

This is important, we are talking in the past tense: the project has ended. Participants must feel that the action has already happened.

### **3. By using sticky notes or an agile retrospective tool, participants list the reasons why the project failed.**

These reasons can be the obvious ones like exceeding the budget, the less obvious ones that all fell ill with COVID and the timeline crumbled, or the totally abstract ones like a falling meteorite.

We throw out all ideas until we can move on to the next stages.

### **4. Then we proceed as in a typical agile retro. We group similar cards and vote for the most important problems.**

‍A good criterion is to vote on things that have the best chance of occurrence, and ones that we influence on. Sorry, we won’t upvote the meteorite scenario ;)

### **5. Here we discuss and come up with solutions.**

There are different techniques for how to carry out this step.

We simply give participants a moment to come up with specific actions and then post them simultaneously on the Slack channel where we can review the available solutions.

Experience tells us that sometimes the most unconventional ideas end up on the action point list, so it’s important not to reveal solutions too early, so as not to disturb the creative phase.

The selected solutions must be **actionable, precise, and measurable**. We can select more than one way of mitigating the risk of a single problem.

### **6. The action points are assigned to the appropriate people.**

Additionally, we set a regular checkpoint to check the progress, e.g., in two weeks or at the beginning of a regular retrospective if it’s a repetitive activity.

## A Practical Example of a Premortem

How does it work in practice? Let’s take a hypothetical mobile application design where:

* The designs were made before the development team had a chance to give their input.

* The project timeline is extremely ambitious and contains a small margin of error.

* The application contains a demanding business part (e.g., AI elements) that hasn’t yet been specified.

The team may have noticed the following reasons why the project failed:

* The designs covered only the “happy path.” Many hidden requirements emerged only when creating a detailed backlog and application behavior.

* Random events forced people related to the project (stakeholders, developers) to take time off. We were late with the release of the application for an important event.

* The AI part strongly influenced the shape of the project. It appeared so late that a large part of the already created application went to the trash and required changes, exceeding the budget.

What actions can be taken:

* Perform regular scoping sessions with developers and ask designers for input to find gaps in the requirements.

* Create a vacation calendar that helps assess the team’s capacity in the future. Decide to scale the team in advance or reduce the scope to meet the deadline.

* Organize a workshop with a client and an AI expert where the team specifies the feature’s shape, what are the possible threats, and the influence on the already developed parts of the app. The outputs are the requirements backlog and a list of topics that need research.

You can use a premortem in virtually any company or private project. **Before taking expensive actions, think about what can go wrong in a project and mitigate any problems long before they happen**.

This post has originally been published on nomtek.com as [*Premortem — A Core Part of Your Digital Product](https://www.nomtek.com/blog/project-premortem)*
