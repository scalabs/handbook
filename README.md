# documentation
Links and ressources for internal affairs

Please go ahead and improve this! ~ Lukas

## tooling
- GitHub for source code & project management: GitHub Issues, Pull Requests, Code Review, Project Boards, etc.

- VSCode
- Gitpod
- 1Password
- Chrome & Firefox
- Google Workspace

## guides / manuals / ressources

- **ScaLabs Projects overview**: https://github.com/orgs/scalabs/projects/10

## GitHub Organisations:
- https://github.com/avmverlag - World of Bike
- https://github.com/scalabs - MOST IMPORTANT
- https://github.com/scalabs-graveyard - retired projects by ScaLabs
- https://github.com/dartclub - Dart OSS Projects
- https://github.com/opendata-nuernberg - Open Data Projects in and around Nuremberg
- https://github.com/gdgnuernberg - GDG Nuremberg -related projects

# development process

- oriented on scrum https://m.youtube.com/watch?v=PPO5GwSo0d4
- for smaller projects no clear sprints, but weekly review/feedback rounds
- We rely heavily on *public documentation for the whole development team* in our projects! **THIS MEANS:** Always keep your issues and pull requests up to date, resolve conversations, describe problems inside of issues and pull requests, with mentioning all of the people involved, instead of phone calls and private chats.

### Meetings:
  - daily 7:45-8:00
  - monday weekly brief 13:00-14:00 -> protocol: meeting notes
  - friday weekly debrief 12:00-13:00 -> protocol: meeting notes

- Lukas offers pair-programming sessions as 2-hour blocks Tue-Fri 13-15:00 and 15-17:00

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

### Branches:
- `main` upstream branch, reviewed / quality control. Merged via squash
- `releases` releases, production branch / protected, controlled, after testing/staging, merged from `main` via squash

---

Contact Lukas anytime! +49 173 6107430 / lukas@scalabs.de / https://himsel.me
