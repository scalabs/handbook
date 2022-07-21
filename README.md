# ScaLabs Wiki

Links and ressources for internal affairs

Please go ahead and improve this! ~ *Lukas*

## Tooling

- GitHub for source code & project management: GitHub Issues, Pull Requests, Code Review, Project Boards, etc.
- VSCode
- Gitpod
- 1Password
- Chrome & Firefox
- Google Workspace

## Tech stack

- Primary programming languages: Dart, TypeScript/JavaScript, Python, C
- Mobile Apps
  - Flutter https://flutter.dev
  - BloC https://bloclibrary.dev
  - Mapbox https://mapbox.com
- Web development
  - JAMStack
  - SvelteKit, Jekyll, 11ty
  - Svelte, React/PReact
  - Vite
  - Dart4Web, JavaScript, TypeScript
  - CSS, SASS/SCSS
  - AMPHTML
  - Shopify
  - Headless CMS
- Cloud
  - TODO

## Guides / Manuals / Ressources

- [Code of Conduct WIP](https://github.com/scalabs/documentation/blob/main/CODE-OF-CONDUCT.md)

## GitHub organisations:
- https://github.com/scalabs - MOST IMPORTANT  
    We have different teams with access to different repos & projects. See [here](https://github.com/orgs/scalabs/teams)
- https://github.com/scalabs-graveyard - retired projects by ScaLabs
- https://github.com/avmverlag - World of Bike
- https://github.com/dartclub - Dart OSS Projects
- https://github.com/opendata-nuernberg - Open Data Projects in and around Nuremberg
- https://github.com/gdgnuernberg - GDG Nuremberg - related projects

--- 

## Development Process
- oriented on Scrum, you can watch the basics here: https://m.youtube.com/watch?v=PPO5GwSo0d4
- for smaller projects no clear sprints, but weekly briefing & de-briefing
- **GitHub is our most important communication channel!** We rely heavily on *public documentation for the whole development team* in our projects! **THIS MEANS:**
   - Always keep your issues and pull requests up to date
   - Resolve conversations, describe problems inside of issues and pull requests, with mentioning all of the people involved, instead of phone calls and private chats. 
   - For work-related time-sensitive conversations, Google Chat is the standard choice!

### Types of projects' tasks
- Feature requests (labeled as enhancement)
- Implementation tasks


### Project management implementation on GitHub
- Each repository's issues are the full **backlog** for a project
- Pull requests and feature branches are used to work on issues from the backlog
- Project boards (Kanban-style) are used for *sprints*.
- Each sprint will be planned in a *kick-off* and *retrospective meeting*.
- Sprints may be accompanied by milestones


### Feature implementation process (issue -> new branch -> commits -> PR):
1. Backlog / Issue
2. Create a new branch `feature-` from `main`
3. Create a **draft** pull request
4. Mention associated issues
5. Implement & commit
6. Convert to real PR "ready for review"
7. Code review / it might help to suggest a reviewer
  - Reviewer comments/requests changes/approves
  - Dev converses in the discussions, makes changes, and **resolves discussions**
  - Another review cycle, until approved!
8. After review & all checks succeeded, maintainer will merge **as squash-merge** into `main`!

**⚠️ Don't delete your branches after a PR ⚠️**

### Softare release process
![Software-Release-Prozess](https://user-images.githubusercontent.com/10634693/178265172-32babf22-71d5-48e4-8e82-06be93d9b1c3.png)

### Branches (naming conventions)
- `main` upstream branch, reviewed / quality control. Merged via squash
- `releases` releases, production branch / protected, controlled, after testing/staging, merged from `main` via squash
- `bug-fix-NUMBER-OF-ASSOCIATED-ISSUE`
- `feature-FEATURE-NAME`

### Meetings:
  - daily 7:45-8:00
  - monday weekly brief 13:00-14:00 -> protocol: meeting notes
  - friday weekly debrief 13:00-14:00 -> protocol: meeting notes

- @lukas-h offers pair-programming sessions as 90-Minute blocks Tue to Fri 13-16:00 https://calendar.google.com/calendar/u/0/appointments/schedules/AcZssZ3Qus7zD8yPWltkMUSg2Ys4RDGfTVQ-oKn-bFJjdIriJc9HZKiDQJ0wVPJXRZ4t5w9vhevHY-MK


---

Contact @lukas-h here: lukas@scalabs.de
