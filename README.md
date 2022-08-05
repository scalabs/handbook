# ScaLabs Wiki

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
  - Firebase
- Web apps
  - JAMStack
  - SvelteKit, Jekyll, 11ty
  - Svelte, React/PReact
  - Vite
  - Dart4Web, JavaScript, TypeScript
  - CSS, SASS/SCSS
  - AMPHTML
  - Shopify
  - Headless CMS
- Cloud / Backend / Database
  - gRPC
  - Docker
  - Google Cloud
  - Firebase
  - AWS
  - DigitalOcean
  - SQL (MS, Postgres)
  - NoSQL & Document Databases
  - RabbitMQ / Pub Sub
  - TODO

## Guides / Manuals / Ressources

- [Code of Conduct (WIP)](https://github.com/scalabs/documentation/blob/main/CODE-OF-CONDUCT.md)
- [Flutter Guidelines](https://github.com/scalabs/documentation/blob/main/guides/flutter.md)

## GitHub organisations:

- https://github.com/scalabs - MOST IMPORTANT  
    We have different teams with access to different repos & projects. See [here](https://github.com/orgs/scalabs/teams)
- https://github.com/scalabs-graveyard - retired projects by ScaLabs
- https://github.com/avmverlag - World of Bike
- https://github.com/dartclub - Dart OSS projects
--- 

## Development Process

- oriented on Scrum, you can watch the basics here: https://m.youtube.com/watch?v=PPO5GwSo0d4
- for smaller projects no clear sprints, but weekly briefing & de-briefing
- **GitHub is our most important communication channel!** We rely heavily on *public documentation for the whole development team* in our projects! **THIS MEANS:**
   - Always keep your issues and pull requests up to date
   - Resolve conversations, describe problems inside of issues and pull requests, with mentioning all of the people involved, instead of phone calls and private chats. 
   - For work-related time-sensitive conversations, Google Chat is the standard choice!

### Types of project tasks

- Feature requests (labeled as *feature request*, previously *enhancement*)
- Implementation tasks (typically sub-tasks of feature-requests)
- Exploratory tasks


### Project management implementation on GitHub

- Each repository's issues are the full **backlog** for a project
- Pull requests and feature branches are used to work on issues from the backlog
- Project boards (Kanban-style) are used for *sprints*.
- Each sprint will be planned in a *kick-off* and *retrospective meeting*.

### Working with Project boards

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


### Feature implementation process (issue -> new branch -> commits -> PR):

1. Backlog / Issue: Start with an open issue that is assigned to you, if no one is assigned, go ahead and assign yourself.
<img width="601" alt="Screenshot 2022-07-21 at 10 00 38" src="https://user-images.githubusercontent.com/10634693/180162330-236ed132-2db9-47be-8f98-6e89a18adaa3.png">
<img width="282" alt="Screenshot 2022-07-21 at 10 00 58" src="https://user-images.githubusercontent.com/10634693/180162201-b2c01e28-2bb5-4a03-9032-2e67a583b1bf.png">

2. Create a new branch `feature-` from `main`
<img width="315" alt="Screenshot 2022-07-21 at 10 03 55" src="https://user-images.githubusercontent.com/10634693/180162608-3150ce8a-c0b3-4569-94b1-d4066591fcb6.png">

3. Create a **draft** pull request
<img width="714" alt="Screenshot 2022-07-21 at 10 06 35" src="https://user-images.githubusercontent.com/10634693/180163036-6acaf9e6-05d5-4470-bc8a-f1a6a5ef18a0.png">


4. Mention associated issues
<img width="292" alt="Screenshot 2022-07-21 at 10 08 00" src="https://user-images.githubusercontent.com/10634693/180163342-195258c0-d4ed-43ce-9d67-a8b214b0ceb9.png">


5. Implement & commit
6. Convert to real PR "ready for review"
<img width="455" alt="Screenshot 2022-07-21 at 10 09 05" src="https://user-images.githubusercontent.com/10634693/180163569-d557b217-1857-4b30-960e-f80309a7eb83.png">


7. Code review
  - It might help to suggest a reviewer  
    <img width="262" alt="Screenshot 2022-07-21 at 10 11 25" src="https://user-images.githubusercontent.com/10634693/180164265-e90228fb-6591-41fa-929b-343a093beb5f.png">
    <img width="262" alt="Screenshot 2022-07-21 at 10 11 42" src="https://user-images.githubusercontent.com/10634693/180164273-f6151f55-0580-49a6-9c24-40cea81c01e4.png">

  - Reviewer comments/requests changes/approves  
    <img width="457" alt="Screenshot 2022-07-21 at 10 16 18" src="https://user-images.githubusercontent.com/10634693/180165128-3a4bcdc1-03e6-40bd-959c-e97d959663a7.png">

  - Developer converses in the discussions, makes changes, and **resolves conversations**  
    <img width="359" alt="Screenshot 2022-07-21 at 10 18 50" src="https://user-images.githubusercontent.com/10634693/180165665-3286e124-195d-4890-be0b-6d37e8a7caf6.png">

  - Another review cycle, until approved!  
    <img width="254" alt="Screenshot 2022-07-21 at 10 19 29" src="https://user-images.githubusercontent.com/10634693/180165861-0f6fccfd-1f5e-4ad0-9a9c-b835bc8361a9.png">

8. After review & all checks succeeded, maintainer will merge **as squash-merge** into `main`  
    <img width="397" alt="Screenshot 2022-07-21 at 10 22 22" src="https://user-images.githubusercontent.com/10634693/180166473-38ac5d5e-b7f3-4c1f-ba3e-0caf39b6bd2e.png">

**⚠️ Don't delete your branches after a PR ⚠️**

### Code reviews

We base our code review strategy on Google's Engineering Practices Documentation, [see here for code reviews](https://github.com/google/eng-practices). Although we are a bit stricter with the code review frequency, where our goal is once to twice per day!


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
