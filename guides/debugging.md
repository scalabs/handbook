# Guide on Debugging and Troubleshooting

## "Triage" and "Escalation" levels

1. **Try to solve it on your own.** Try writing unit tests, debugging via breakpoints, etc. Narrow down the sources of the issue as much as possible.
2. **When you are stuck, take the time to document the problem** as a *Bug report*.
    - Another person can voluntarily jump in to help with the problem.
    - It's not about skills or not living up to the standards, but time transparency. Delays are normal, but if they are not communicated clearly, they upset people.
    - It Helps to plan future iterations/sprints more realistically.
    - Don't be afraid to open a "stupid sounding" issue. Mistakes or knowledge gaps are normal and only if you ask, you learn from them.
3. **Ask team members to review the problem**, by mentioning them on GitHub.
4. **Communicate with the team leader**, so they know about the obstacles. 

## Bug Reporting

We have different types of issues, as described here: [Project tasks (types of GitHub issues)](https://github.com/scalabs/documentation/blob/main/guides/project-manangement.md#project-tasks-types-of-github-issues).

For new bug reports, we have a template called "Bug report". This involves the following:

1. First step is classification. We choose the type `Bug report` to distinguish it from other types of issues.

<img width="1140" alt="Screenshot 2023-01-11 at 14 39 47" src="https://user-images.githubusercontent.com/10634693/211820892-adbcf14b-6ba0-4da4-b373-87f3d526e21d.png">

Then, we **fill out** our bug report **template**.

2. Give a brief description of the bug.
```md
**Description**
A clear and concise description of what the bug is.
```

3. Provide steps to reproduce. For developers to start working on the bug, it is important that they can locate it in the application.

```md
**Steps To Reproduce**

1. Go to '...'
2. Click on '....'
3. Scroll down to '....'
4. See error
```

4. Provide an explanation, what the software should do, if the bug is not present.

```md
**Expected Behavior**
A clear and concise description of what you expected to happen.
```

5. Attach/Upload screenshots, if possible.

```md
**Screenshots**
If applicable, add screenshots to help explain your problem.
```

6. If there are other issues already open that have to do with this bug, you can mention them here.

```md
**Additional Context**
Add any other context about the problem here.
```
