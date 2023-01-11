# Guide on Project Documentation and Feature Engineering

## Project Documentation
In every project we have two different types of communication:
1. Client-facing communication
2. Internal communication.

For both, we need documentation in files and different software tools.
- Our client-facing documentation is mostly done in different Office / Google Docs files.
- Our internal documentation is mostly on GitHub, e.g. as **feature requests** and project boards.

![](https://github.com/scalabs/documentation/blob/main/assets/images/proj-documentation.png)

### Most important planning files (shared with our clients):

**Requirements Documentation**

This is a document where we systematically collect all the client's needs, dependencies, and goals. We follow these steps:

- Identify the relevant stakeholders.
- Establish project goals and objectives.
- Elicit requirements from stakeholders.
- Document the requirements.
- Confirm the requirements.
- Prioritize the requirements.


**Solution Design (Concept)**  

The solution design is a **confidential** document between one of our clients and us which contains a concrete solution with a clear scope (based on the requirements documentation) and software design (taken in all the dependencies and limitations).

We have a **template** document (MS Office, Google Docs), that we use for this purpose.  
This is our standard table of contents:

```
1. Executive Summary
2. Solution & Scope
3. Project-Deliverables
4. Restrictions, Risks incl. Information Security Risks
5. Dependencies
6. Acceptance Criteria
7. Software Design and Architecture
8. Setup and Onboarding
9. Infrastructure Requirements
10. Testing Strategy
```

**Execution Plan / Timeline / Milestones**

Our execution plan acts as a communication device to our clients. It outlines project phases and time planning.
It includes soft deadlines as well as meetings for feedback, testing, and other reasons.

The contents of the execution plan are extracted from our [iterations/sprints and milestones/"epics"](https://github.com/scalabs/documentation/blob/main/guides/project-manangement.md#iterations--sprints) that are planned by our project managers on GitHub.

The execution plan is created as a MS Word or Google document:

<img width="680" alt="Screenshot 2022-12-20 at 14 42 41" src="https://user-images.githubusercontent.com/10634693/208680951-f0b86fa6-6e10-472b-b760-b585e387914a.png">


For bigger project, we additionally create Gantt charts, which are visualisations of project timelines. [Google Sheets: How to create timeline views](https://support.google.com/docs/answer/12935277?visit_id=638071393366253531-4129096414&p=timeline_view&rd=1#topic=1382883)


## Feature Engineering

Our main project management tool is GitHub. We use **GitHub Issues** for our project tasks. We have different types of issues, as described [here: Project tasks (types of GitHub issues)](https://github.com/scalabs/documentation/blob/main/guides/project-manangement.md#project-tasks-types-of-github-issues).

For new features or enhancements, we have a template called "Feature request". The process of transforming all of the project's scope and solution design into these feature requests, is called **feature engineering**. This involves the following:

### Create a feature request

1. First step is classification. We choose the type `Feature request` to distinguish it from other types of issues. 
<img width="1991" alt="Screenshot 2022-12-20 at 13 53 23" src="https://user-images.githubusercontent.com/10634693/208672269-56009bb9-c70a-41c9-8f8c-b07cf0212623.png">

Then, we **fill out** our feature request **template**.

2. In this step we need to further elaborate about this feature and tell if it is a new feature, or an enhancement / improvement of an existing feature. 
```markdown
**Type of Issue**  
- [ ] New Feature Implementation
- [ ] Addition / Enhancement / Improvement
```

3. The next step involves defining the type of implementation work that is needed. 
```markdown
**Type of Work**  
- [ ] Screen  
- [ ] Widget/Component  
- [ ] Business Logic (Service, Repository, BloC)  
- [ ] Backend Service
- [ ] DevOps
- [ ] Documentation
```

4. A simple description of the feature from the user's perspective. The second paragraph has a scrum story-like structure and helps reinforcement a uniform style of writing down feature requests.

```markdown
**Description**  
*Describe in simple sentences the functionality*  

As a [type of user],  
I want to [perform an action],  
so that I can [achieve a goal].  
```

5. The implementation work will be divided into smaller **actionable** tasks. It gives the developer clear instructions. 
```markdown
**Actionable Tasks**  
- [ ] Implement a Cubit/BloC for [action] with states [...] and methods [...]  
- [ ] Implement Widget to trigger [action]  
- [ ] Implement Widget to display [result of the action]  
- [ ] ...
```

6. Acceptance criteria consist of the set of requriements that must be met to mark the software complete and functionally sound. Our acceptance criteria are formulated so that they can act as blue prints for acceptance and regression testing.
(more on that in the guide).
```markdown
**Acceptance criteria**  
- [ ] Screen should render the initial UI properly  
- [ ] After [action is performed] state should change  
- [ ] New UI is properly rendered  
- [ ] ...
```
