# Project management

- Our project management is partly oriented on Scrum.  
   - You can watch the basics [here (YouTube)](https://m.youtube.com/watch?v=PPO5GwSo0d4)
- For smaller projects there are no clear sprints, but there will be weekly briefing & de-briefing 

- **GitHub is our most important communication channel**  
We rely heavily on *public documentation for the whole development team* in our projects!  
**THIS MEANS:**
   - Always keep your issues and pull requests up to date
   - Resolve conversations
   - Describe problems inside the issues and pull requests, with mentioning all of the people involved, instead of phone calls and private chats
   - For work-related, time-sensitive conversations, Google Chat is the standard choice

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


## Our team roles

**Project manager**  
The project managers are responsible for:

- Feature engineering (All of the documentation for **feature requests**)
- Managing milestones according to importance of the features
- Creating and project boards, keeping them up-to-date and managing sprints

Project managers need technical know-how in our organization.

**Developer**

- Implementation of features
- Code reviews
- Helping with sprint-planning (evaluating the time budget of features)

**Smaller roles**

- *Quality assurance* – This role is not a separate person, but a skill that is taught to every developer, with additional levels of peer-review (code reviews, acceptance test driven development, user testing, multi-level release systems).
- *DevOps* – This role is not a separate person, but a skill that is taught to every developer for simple automations using GitHub Actions, Infrastructure as code (IaC), or PaaS products. For roles like K8S, we might hire separate people in the future.

## Project management implementation on GitHub


- Each repository's issues represent the full **backlog** of a project
- **GitHub Project Boards** are used for scheduling and tracking the implementation of the features.
- For bigger projects we organize the implementation work in **sprints**/**iterations**.
  - A sprint is a repeatable development phase of 2-3 weeks with a certain scope of implementation tasks planned.
  - Sprint scopes are set by project management and developers.
  - Sprint-participants organize their work in a *kick-off* and *retrospective* meeting, as well as daily standups.
  - dffd



### Working with Project boards

- Each repository is linked to a *Project Board* (the new ones) which should list all the issues 

1. Backlog

TODO

2. Iterations (sprints)

- Refinement (mid-sprint)
- Sprint Demo (after sprint with client)

TODO

https://docs.github.com/en/issues/trying-out-the-new-projects-experience/about-projects

- Only issues are inside projects, and we see linked PRs in the issue tiles

![Screenshot 2022-08-01 at 11 51 02](https://user-images.githubusercontent.com/10634693/182122735-96773bd4-c3ae-4c41-aa31-8d92bbc0ade7.png)
![Screenshot 2022-08-01 at 11 51 16](https://user-images.githubusercontent.com/10634693/182122739-c624fd3a-5398-4d49-ae0e-217f0a024b2c.png)

