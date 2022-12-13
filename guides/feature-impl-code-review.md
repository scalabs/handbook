## Feature implementation process (issue → new branch → commits → PR):  

1. Backlog / Issue: Start with an open issue that is assigned to you, if no one is assigned, go ahead and assign yourself.
<img width="601" alt="Screenshot 2022-07-21 at 10 00 38" src="https://user-images.githubusercontent.com/10634693/180162330-236ed132-2db9-47be-8f98-6e89a18adaa3.png">
<img width="282" alt="Screenshot 2022-07-21 at 10 00 58" src="https://user-images.githubusercontent.com/10634693/180162201-b2c01e28-2bb5-4a03-9032-2e67a583b1bf.png">

---

2. Create a new branch `feature-` from `main`
<img width="315" alt="Screenshot 2022-07-21 at 10 03 55" src="https://user-images.githubusercontent.com/10634693/180162608-3150ce8a-c0b3-4569-94b1-d4066591fcb6.png">

---

3. Create a **draft** pull request
<img width="714" alt="Screenshot 2022-07-21 at 10 06 35" src="https://user-images.githubusercontent.com/10634693/180163036-6acaf9e6-05d5-4470-bc8a-f1a6a5ef18a0.png">  

---

4. Mention associated issues  
<img width="292" alt="Screenshot 2022-07-21 at 10 08 00" src="https://user-images.githubusercontent.com/10634693/180163342-195258c0-d4ed-43ce-9d67-a8b214b0ceb9.png">

---

5. Implement & commit 

---

6. Convert to real PR "ready for review"
<img width="455" alt="Screenshot 2022-07-21 at 10 09 05" src="https://user-images.githubusercontent.com/10634693/180163569-d557b217-1857-4b30-960e-f80309a7eb83.png">

---

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
    
---

8. See that all checks, including CI-runs, unit tests, and merge conflicts are done. Merge conflicts are to be resolved by the **PR-creator/implementer**

---

9. After review & all checks succeeded, maintainer will merge **as squash-merge** into `main`  
    <img width="397" alt="Screenshot 2022-07-21 at 10 22 22" src="https://user-images.githubusercontent.com/10634693/180166473-38ac5d5e-b7f3-4c1f-ba3e-0caf39b6bd2e.png">
    
---

**⚠️ Don't delete your branches after a PR ⚠️**

## Code reviews

We base our code review strategy on Google's Engineering Practices Documentation, [see here for code reviews](https://github.com/google/eng-practices). Although we are a bit stricter with the code review frequency, where our goal is **once to twice per day (12-24 hours)**!

