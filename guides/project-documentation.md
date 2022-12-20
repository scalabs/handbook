# Guide on Project Documentation and Feature Engineering

## Project Documentation
In every project we have two different types of communication:
1. Client-facing communication
2. Internal communication.

For both, we need documentation in files and different software tools.
- Our client-facing documentation is mostly done in different Office / Google Docs files.
- Our internal documentation is mostly on GitHub, as **feature requests** and project boards.

![](https://github.com/scalabs/documentation/blob/main/assets/images/proj-documentation.png)

Our most important detail planning files, that we provide to our clients:

**Requirements Documentation**

This is a document where we systematically collect all the client's needs, dependencies, and technical details that it entails.

- Identify the relevant stakeholders.
- Establish project goals and objectives.
- Elicit requirements from stakeholders.
- Document the requirements.
- Confirm the requirements.
- Prioritize the requirements.


**Solution Design (Concept)**  

The solution design is a **confidential** document between our client and us which contains a concrete solution with a clear scope (based on the requirements documentation) and software design (taken in all the dependencies and limitations).
We have a **template** document (MS Office, Google Docs), that we use for it.
This is the table of contents:

```
1. Executive Summary
2. Solution & scope
3. Project-Deliverables
4. Restrictions, risks incl. information security risks
5. Dependencies
6. Acceptance Criteria
7. Software-Design und -Architecture
8. Setup and onboarding
9. Infrastructure requirements
10. Testing strategy
```

**Execution Plan / Timeline / Milestones**

Our execution plan outlines project phases with soft deadlines, as well as feedback-, testing- and other meetings.
The contents of the execution plan are based on the [iterations/sprints and milestones/"epics"](https://github.com/scalabs/documentation/blob/main/guides/project-manangement.md#iterations--sprints) that are planned by our project managers.

We create the execution plan as Word documents or Google Docs for a textual version:

<img width="1991" alt="Screenshot 2022-12-20 at 13 53 23" src="https://user-images.githubusercontent.com/10634693/208677768-ea507665-eec3-4c04-8471-aeddc13f2126.png">


For bigger project we create Gantt charts, which is a visualisation of project timeline, with Google Sheets. [Documentation: How to create timeline views](https://support.google.com/docs/answer/12935277?visit_id=638071393366253531-4129096414&p=timeline_view&rd=1#topic=1382883)


## Feature Engineering

Our main project management tool is GitHub. For our project tasks, we use **GitHub Issues**. We have different types of issues, as described [here: Project tasks (types of GitHub issues)](https://github.com/scalabs/documentation/blob/main/guides/project-manangement.md#project-tasks-types-of-github-issues).

For new features or enhancements, we have a template called "Feature request". The process of transforming all of the client requirements into these feature requests, is called **feature engineering**. This envolves following:

### Create a feature request

1. First step is classification. We choose the type `Feature request` to distinguish this type of entity. 
<img width="1991" alt="Screenshot 2022-12-20 at 13 53 23" src="https://user-images.githubusercontent.com/10634693/208672269-56009bb9-c70a-41c9-8f8c-b07cf0212623.png">

Then, we **fill out** our feature request **template**.

2. In this step we need to further elaborate about this feature and tell if it is a new feature, or an enhancement / improvement of an existing feature. 

```markdown
**Type of Issue**  
- [ ] New Feature Implementation
- [ ] Addition / Enhancement / Improvement
```


3. The next step involves defining the place this feature has in software / the type of work that is needed. 
```markdown
**Type of Work**  
- [ ] Screen  
- [ ] Widget/Component  
- [ ] Business Logic (Service, Repository, BloC)  
- [ ] Backend Service
- [ ] DevOps
- [ ] Documentation
```

4. The description
```markdown
**Description**  
*Describe in simple sentences the functionality*  

As a [type of user],  
I want to [perform an action],  
so that I can [achieve a goal].  
```

5. Actionable tasks

```markdown
**Actionable Tasks**  
- [ ] Implement a Cubit/BloC for [action] with states [...] and methods [...]  
- [ ] Implement Widget to trigger [action]  
- [ ] Implement Widget to display [result of the action]  
- [ ] ...
```

6. Acceptance criteria

```markdown
**Acceptance criteria**  
- [ ] Screen should render the initial UI properly  
- [ ] After [action is performed] state should change  
- [ ] New UI is properly rendered  
- [ ] ...
```
