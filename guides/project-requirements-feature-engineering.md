# Guide on Project requirements and feature engineering



## Feature engineering

- Feature requests
In this guide we walk you through ScaLabs's feature engineering procedure. 


First step is classification. We choose the type `Feature request` to distinguish this type of entity. 
We tall `about` this feature in a concise fashion give it the `enhancement` label. Other labels are Question, Bug etc.
 
```markdown
---
name: Feature request
about: A new feature to be implemented
label: enhancement
---

```

In the second step we need to further elaborate about this feature and tell if it is of the type `addition`, `improvement`, or `Enhancement`. Enhancement here would mean we are dealing with a new feature and improvement and addition would mean that we are working based on certain already existing features. 
```markdown
**Type of Issue**  
- [ ] New Feature Implementation
- [ ] Addition / Enhancement / Improvement
```

3rd step involves defining the place this feature has in software. 
```markdown
**Type of Work**  
- [ ] Screen  
- [ ] Widget/Component  
- [ ] Business Logic (Service, Repository, BloC)  
- [ ] Backend Service
- [ ] DevOps
- [ ] Documentation
```

**Description**  
*Describe in simple sentences the functionality*  

As a [type of user],  
I want to [perform an action],  
so that I can [achieve a goal].  

**Actionable Tasks**  
- [ ] Implement a Cubit/BloC for [action] with states [...] and methods [...]  
- [ ] Implement Widget to trigger [action]  
- [ ] Implement Widget to display [result of the action]  
- [ ] ...

**Acceptance criteria**  
- [ ] Screen should render the initial UI properly  
- [ ] After [action is performed] state should change  
- [ ] New UI is properly rendered  
- [ ] ...
```
