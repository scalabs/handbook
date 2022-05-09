# documentation
Links and ressources for internal affairs

Please go ahead and improve this! ~ *Lukas*

## tooling
- GitHub for source code & project management: GitHub Issues, Pull Requests, Code Review, Project Boards, etc.

- VSCode
- Gitpod
- 1Password
- Chrome & Firefox
- Google Workspace

## tech stack
- Primary programming languages: Dart, TypeScript/JavaScript, Python, Rust, C
- Mobile Apps
  - Flutter https://flutter.dev
  - BloC https://bloclibrary.dev
  - Mapbox https://mapbox.com
- Web development
  - JAMStack
  - Jekyll, 11ty, SvelteKit
  - Svelte, React/PReact
  - Vite
  - Dart4Web, vanilla JavaScript, TypeScript
  - CSS, SASS/SCSS
  - AMPHTML
- Cloud
  - TODO

## guides / manuals / ressources

- **ScaLabs Projects overview**: https://github.com/orgs/scalabs/projects/10
- [Code of Conduct WIP](https://github.com/scalabs/documentation/blob/main/CODE-OF-CONDUCT.md)
- **Our organisation backlog**: https://github.com/orgs/scalabs/projects/11
## GitHub Organisations:
- https://github.com/avmverlag - World of Bike
- https://github.com/scalabs - MOST IMPORTANT
- https://github.com/scalabs-graveyard - retired projects by ScaLabs
- https://github.com/dartclub - Dart OSS Projects
- https://github.com/opendata-nuernberg - Open Data Projects in and around Nuremberg
- https://github.com/gdgnuernberg - GDG Nuremberg - related projects

### Teams
We have different teams with access to different repos & projects.
See [here](https://github.com/orgs/scalabs/teams)

# development process

## Types of projects' tasks
- Exploratory (defined dynamically prallel to project development)
- Normal (well-defined ahead of development)

- oriented on Scrum, you can watch the basics here: https://m.youtube.com/watch?v=PPO5GwSo0d4
- for smaller projects no clear sprints, but weekly review/feedback rounds
- **GitHub is our most important communication channel!** We rely heavily on *public documentation for the whole development team* in our projects! **THIS MEANS:**
   - Always keep your issues and pull requests up to date
   - Resolve conversations, describe problems inside of issues and pull requests, with mentioning all of the people involved, instead of phone calls and private chats. 
   - yFor work-related time-sensitive conversations, Google Chat is the standard choice!

### Meetings:
  - daily 7:45-8:00
  - monday weekly brief 13:00-14:00 -> protocol: meeting notes
  - friday weekly debrief 12:00-13:00 -> protocol: meeting notes

- Lukas offers pair-programming sessions as 60-Minute blocks Tue, Thu, and Fri 13-17:00 https://calendar.google.com/calendar/u/0/appointments/schedules/AcZssZ3Qus7zD8yPWltkMUSg2Ys4RDGfTVQ-oKn-bFJjdIriJc9HZKiDQJ0wVPJXRZ4t5w9vhevHY-MK

### Project management implementation on GitHub
- Each repository's issues are the full **backlog** for a project
- Pull requests and feature branches are used to work on issues from the backlog
- Project boards (Kanban-style) are used for *sprints*.
- Each sprint will be planned in a *kick-off* and *retrospective meeting*.
- Sprints may be accompanied by milestones

### Feature implementation process:
1. Backlog / Issue
2. Create a new branch `feature-` from `main`
3. Create a draft pull request, mention associated issues
4. Implement & commit
5. Convert to real PR "ready for review"
6. Code review / it might help to suggest a reviewer
  - Reviewer comments/requests changes/approves
  - Dev converses in the discussions, makes changes, and **resolves discussions**
  - Another review cycle, until approved!
7. After review & all checks succeeded, maintainer will merge into `main`!

**⚠️ Don't delete your branches after a PR ⚠️**

### Branches:
- `main` upstream branch, reviewed / quality control. Merged via squash
- `releases` releases, production branch / protected, controlled, after testing/staging, merged from `main` via squash

##### Naming branches

- `bug-fix-NUMBER_OF_ASSOCIATED_ISSUE`
- `feature-FEATURE_NAME`

# Standards, CSR, CER
This is a work in process at ScaLabs.

---

Contact Lukas anytime! +49 173 6107430 / lukas@scalabs.de / https://himsel.me
