# Ramp Camp: Ticket Writing [(Slides)](https://docs.google.com/presentation/d/1ELpW7E9ccpW3rDtMEEaq57dvix00ca0GB2dxhrleJOY/edit?usp=sharing)

## Minute-by-Minute

| **Elapsed** | **Time**  | **Activity**                        |
| ----------- | --------- | -------------------------           |
| 0:00        | 0:05      | Overview/Learning Objectives        |
| 0:05        | 0:20      | Initial Exercise                    |
| 0:25        | 0:20      | TT 1                                |
| 0:45        | 0:10      | In Class Activity I                 |
| 0:55        | 0:10      | TT 2                                |
| 1:05        | 0:20      | In Class Activity II                |
| 1:25        | 0:05      | Summary                             |
| TOTAL       | 1:30      |                                     |

## Why you should know this

This is something every software engineer has to deal with in terms of how they get tasks, or write ones for others. Knowing how to describe a feature or bug in enough detail for another engineer to read with minimal external resources is an important communication skill, and will be important as an engineer grows in their career.

If you aren't able to clearly communicate a feature or bug, in the best case you have to have a number of followup conversations with your team to address unknowns and uncertanties. In the worst case, whoever is working on the ticket will implement it incorrectly, and now it has to be redone, which wastes time, resources, and causes a heavy dose of eye-rolling.

## Learning Objectives (5 min)
By the end of this lesson, students should be able to...

1. Explain the value in breaking up a single feature into multiple tickets
1. Evaluate the contents of a ticket to determine if it has sufficient, actionable information
1. Create a feature ticket with basic components such as user stories, requirements, and business values
1. Create a bug ticket with basic components such as diagnostic information, repro steps, and current/expected behavior
1. Apply the ROAM technique to risks in feature tickets

## Initial Exercise (20 min)

### Telephone Activity (15 min)

**Print out the [drawings](https://drive.google.com/open?id=1X8IAuMv84e6-NTYbSzxL67NGFbo-y2KX) before class**

1. Get into groups of 4 and order yourself by birthday (oldest is first, youngest is last)
1. The **first person** will receive a picture. They need to write steps (requirements) on how to draw the picture. **Only the first person can see this picture.**
1. The **second person** will read those requirements and draw a picture according to those requirements
1. The **third person** will take this newly drawn picture and write steps (requirements) on how to draw the picture. **Only the third person can see the second person’s drawing.**
1. The **fourth person** will read those requirements and draw a picture according to those requirements
1. Present the final drawing and see how it compares to the initial one

### Takeaways (5 min)

- See how details can get lost in translation
- If there's more detail, less room for error
- Building features in software is similar: better to start with something simple (MVP) and then iteratively build up to the final deliverable.


## TT I (20 min)

### Overview
- Provide an example of receiving a vague feature ticket
- When only a sentence or two are used to describe a feature, it can raise a lot of questions around the implementation details, which can cause frustration if these questions always have to be repeatedly asked
- As a junior software engineer, you may not be writing tickets every day, but you will absolutely be receiving them, and will be expected to write them as you become more experienced, or if you take on a different role (Product manager, project manager, etc.)
- Knowing how to write a solid ticket will not only help you communicate what you want built, but also will inform you on what to ask for if you receive a poorly worded one.

### How to Write a Feature Ticket

- Requires at least the following 4 components:
    - User story: concise one-liner on what we’re building and why
    - Requirements: What are we building?
    - Business Value: Why are we building this?
    - Edge Cases: What are known problems to keep in mind that would only occur under extreme circumstances?
- **User Stories** should always be written in the following format:
    - As a [user_persona] I want to [interaction_with_feature] so that I can [end_user_goal]
- **Requirements** describe what the feature is and how it should behave.
- A **Business Value** is a concise 2-4 sentence statement as to why we’re building this feature, and what value it adds to the company.
    - A non-technical person (executive, board member, etc.) should be able to read this statement and understand why it’s necessary.
- **Edge Cases** are noted with the expected behavior when they're encountered. It's difficult to think of every edge case initially, but note down the ones that immediately come to mind

### ROAMing Risks

If risks of a feature are known upfront (and even when they're discovered later) they should be addressed using the **[ROAM](https://content.intland.com/blog/agile/safe/roam-risk-management-under-safe)** technique
- Resolve: Risk has been answered/avoided/eliminated
- Own: Risk is now owned by someone who’s responsible for handling it
- Accept: Risk is accepted, and nothing will be done about it
- Mitigate: The impact/likelihood of the risk has been decreased through actions by the team

## In Class Activity I (10 min)

### ROAMing Your Own Risk (7 min)

Work with your team and find at least 1 risk in a feature ticket you have and apply the ROAM technique to it

### Discuss Findings (3 min)

Discuss findings as a class



## TT II (10 min)

### Breaking a Ticket Up

- A ticket shouldn’t feel like a novel
- If it feels bloated, it probably needs to be separated into multiple tickets
- Remember to try to break a feature down to it’s MVP and then iterate from there

### Bug Tickets

Bugs need to be clearly written too, otherwise how will engineers know how to fix them?

They should contain at least the following components:

- Summary: 1-2 sentences describing the issue
- Diagnostic Info: Platform, OS Version, Browser Version, SDK version, etc.
- Repro Steps: Sequential steps on how to reproduce the bug
- Current Behavior: What are you currently seeing?
- Expected Behavior: What should you be seeing?

## In Class Activity II  (20 min)

### Apply What You Learned (15 min)

Get with your team and pick a feature on your project that hasn’t been written yet. Pick a smaller one that could fit in one ticket.

Write the ticket as a group, applying the concepts you learned today

### Present your work (5 min)

Present at the end of class

## Wrap Up (5 min)

- Break tickets up into iterative deliverables (MVP → Final Product)
- Provide enough detail that any engineer can read it and understand what’s needed and why we’re building this feature
- Call out risks up front if they’re known, and how you plan to ROAM them
- Bugs need detail as well: how you found the bug, and what the expected behavior should be
