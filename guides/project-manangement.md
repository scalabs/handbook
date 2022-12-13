# Project management

## Intro

Our project management is partly oriented on Scrum. (You can watch the basics [here (YouTube)](https://m.youtube.com/watch?v=PPO5GwSo0d4)). Although as a small team, we get rid of some of the managerial overhead and have simplified roles and processes.
Our whole project management and project execution happens on GitHub, so this guide mainly describes, how to work with those tools.

## Our team roles

**Project manager**  
The project managers are responsible for:

- Feature engineering (All of the documentation for **feature requests**)
- Managing milestones according to importance of the features
- Creating and project boards, keeping them up-to-date and managing sprints
- Accountability for overall progress

Project managers need technical know-how in our organization.

**Developer**

- Implementation of features
- Code reviews
- Helping with sprint-planning (evaluating the time budget of features)

**Partial roles**

- *Quality assurance* – This role is not a separate person, but a skill that is taught to every developer, with additional levels of peer-review (code reviews, acceptance test driven development, user testing, multi-level release systems).
- *DevOps* – This role is not a separate person, but a skill that is taught to every developer for simple automations using GitHub Actions, Infrastructure as code (IaC), or PaaS products. For roles like K8S, we might hire separate people in the future.

## Project communication

- **GitHub is our most important communication channel**  
We rely heavily on *public documentation for the whole development team* in our projects!  
**THIS MEANS:**
   - Always keep your issues and pull requests up to date
   - Resolve conversations
   - Describe problems inside the issues and pull requests, with mentioning all of the people involved, instead of phone calls and private chats
   - For work-related, time-sensitive conversations, Google Chat is the standard choice


# Project management implementation on GitHub

![Project management](https://raw.githubusercontent.com/scalabs/documentation/main/assets/images/pm.drawio.png)

## Project tasks (types of GitHub issues)

We have a clear set of project tasks. These are:

- Feature requests (labeled as *feature request* or *enhancement*)
- Implementation tasks (typically sub-tasks of feature-requests)
- Exploratory tasks (label?)
- Bug reports (labeled as *bug*)
- Questions (labeled as *question*)

For these types of project tasks we have [issue templates](https://github.com/scalabs/github-workflows/tree/main/.github/ISSUE_TEMPLATE).
Every repository we work on has these templates added by default, if they are not present yet, they can be added from this folder:  
`https://github.com/scalabs/github-workflows/tree/main/.github/ISSUE_TEMPLATE`

These templates provide the project managers and developers:

- comparability of the issues
- a minimum standard for documentation / feature engineering, 
- a clear set of instructions to follow when implementing/reproducing a bug, meaning less uncertainty and inquiries about the tasks at hand
- and clear acceptance criteria, important for testing and quality control


- Each repository's issues represent the full **backlog** of a project
- **GitHub Project Boards** are used for scheduling and tracking the implementation of the features.


## Working with Project boards

Project boards are there to help organise and track the issue. Each repository is linked to a *Project Board* which should list all the issues.

Project boards are organized in different **views** and **columns**.

**Views** are there to show and filter the issues in a different way: As a Kanban-board, by priority, by size, or filtered any other attribute.

The **columns** we use in projects are:

- `New` lists all the new issues that were added to the project.
- `Backlog` lists all the things that have to be done and are not fully engineered.
- `Ready` is for issues that include **actionable** tasks, and are prepared to be assigned and worked on.
- `In Progress` lists all the issues being actively worked on.
- `In Review` lists the issues that are ready for review, in review, or in between reviews (adjustment phase).
- `Done` holds all the issues that are fully done.

#### Creation of project boards 

When we want to create a new project board, we use the default templates provided by GitHub.
It is either the template:
- **Team backlog**, for smaller projects, or projects without clear definition of sprints/iterations.
- or **Feature**, for big projects, that require sprints/iterations.

<img width="952" alt="Screenshot 2022-12-13 at 13 48 07" src="https://user-images.githubusercontent.com/10634693/207322235-f19ba2ea-b999-4995-9178-0e96f87fc6ec.png">



#### Tracking of pull requests

We **do not add pull requests to our Project Boards**, but we track them via their issues. Pull requests can be linked to their respective issues. See in [Feature Implementation Guide](https://github.com/scalabs/documentation/blob/main/guides/feature-impl-code-review.md#4-mention-associated-issues).
Linked pull requests show up in the issue tile in the board.

![Screenshot 2022-08-01 at 11 51 02](https://user-images.githubusercontent.com/10634693/182122735-96773bd4-c3ae-4c41-aa31-8d92bbc0ade7.png)
![Screenshot 2022-08-01 at 11 51 16](https://user-images.githubusercontent.com/10634693/182122739-c624fd3a-5398-4d49-ae0e-217f0a024b2c.png)

## Iterations / Sprints

For bigger projects we organize the implementation work in **sprints**/**iterations**.
  - A sprint is a repeatable development phase of 2-3 weeks with a certain scope of implementation tasks planned.
  - Sprint scopes are set by project management and developers.
  - Sprint-participants organize their work in a *kick-off* and *retrospective* meeting, as well as daily standups.

Each sprint has 
- a Kick-off,
- Refinement (mid-sprint),
- and Sprint Demo (after sprint with client)
event.

