# Guide on Project documentation and feature engineering



## Feature engineering

Our main project management tool is GitHub. For our project tasks, we use **GitHub Issues**. We have different types of issues, as described [here: Project tasks (types of GitHub issues)](https://github.com/scalabs/documentation/blob/main/guides/project-manangement.md#project-tasks-types-of-github-issues).

For new features or enhancements, we have a template called "Feature request". The process of transforming all of the client requirements into these feature requests, is called **feature engineering**. This envolves following:

### Create a feature request

1. First step is classification. We choose the type `Feature request` to distinguish this type of entity. 
<img width="1991" alt="Screenshot 2022-12-20 at 13 53 23" src="https://user-images.githubusercontent.com/10634693/208672269-56009bb9-c70a-41c9-8f8c-b07cf0212623.png">

3. Then, we **fill out** our feature request **template**.
In this step we need to further elaborate about this feature and tell if it is a new feature, or an enhancement / improvement of an existing feature. 

```markdown
**Type of Issue**  
- [ ] New Feature Implementation
- [ ] Addition / Enhancement / Improvement
```


4. The next step involves defining the place this feature has in software / the type of work that is needed. 
```markdown
**Type of Work**  
- [ ] Screen  
- [ ] Widget/Component  
- [ ] Business Logic (Service, Repository, BloC)  
- [ ] Backend Service
- [ ] DevOps
- [ ] Documentation
```

5. The description
```markdown
**Description**  
*Describe in simple sentences the functionality*  

As a [type of user],  
I want to [perform an action],  
so that I can [achieve a goal].  
```

6. Actionable tasks

```markdown
**Actionable Tasks**  
- [ ] Implement a Cubit/BloC for [action] with states [...] and methods [...]  
- [ ] Implement Widget to trigger [action]  
- [ ] Implement Widget to display [result of the action]  
- [ ] ...
```

7. Acceptance criteria

```markdown
**Acceptance criteria**  
- [ ] Screen should render the initial UI properly  
- [ ] After [action is performed] state should change  
- [ ] New UI is properly rendered  
- [ ] ...
```
