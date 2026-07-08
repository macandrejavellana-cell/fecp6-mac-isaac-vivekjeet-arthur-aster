# Final Project Retrospective

## Team Members
- Student 1: Mac Andre Javellana
- Student 2: Jan Neal Isaac Villamin
- Student 3: Vivekjeet Singh Chambal
- Student 4: Arthur Jed Lluisma
- Student 5: Aster Benedict Mangabat


## 1. How did you divide the work between you and your partner?
_(Who worked on which features? How was the work assigned or negotiated?)_

- Mac Andre Javellana - Feature 1: Filter Products by Attributes
- Jan Neal Isaac Villamin - Feature 2.1: User Registration and Login
- Vivekjeet Singh Chambal - Feature 2.2: User Registration and Login
- Arthur Jed Lluisma - Feature 4: Display Storefront
- Aster Benedict Mangabat - Feature 3: Product Management


We divided the features per person. Due to having more people than the number of features, we split 1 feature into 2, so everyone can have a feature they can work on.


## 2. What Git strategies or commands helped you most during the project?
_(E.g., branching, rebasing, frequent commits, etc.)_

The following commands helped us the most during this project
1. git merge -m "[message]"
2. git checkout [branch-name]
3. git log --oneline
4. git branch
5. git add
6. git commit
7. git push
8. git pull


## 3. Describe a merge conflict you encountered. What caused it and how did you resolve it?
_(Include any lessons learned or techniques used to resolve the issue.)_

Our team encountered a merge conflict while integrating multiple feature branches into the main branch. Because these features required changes to the same files, the first branch merged successfully, but subsequent merges triggered merge conflicts due to overlapping lines of code. To resolve it, we communicated with each other to review the overlapping lines and determine the correct integration. Since it was a relatively straightforward project, our resolution strategy involved either combining the changes or retaining the most updated version of the functions. Once the conflicts were resolved locally, we had other team members review the code to ensure functionality before finalizing the merge.

Another merge conflict was when two separate members were working on user_controller.pseudo. One was implementing create_user while the other was implementing login_user. The member working on create_user pushed the changes to their branch and merged with main after a reviewed PR. Then, the member working on login_user performed a fetch and merge to their computer, resulting in a merge conflict. To resolve this, the member working on login_user combined the two changes by placing the create_user part first, then the login_user part. Finally, a commit was made pushed to their branch, then a merge happened after a reviewed PR, resolving the conflict.


## 4. What were the biggest challenges you faced as a team?
_(This can include communication, Git usage, or coordination.)_

Our biggest challenges as a team centered around mastering collaborative Git workflows and maintaining asynchronous clarity while moving at a fast pace. Early on, we struggled with how to effectively slice features into smaller, manageable tasks, which also resulted in an error when multiple team members needed to build upon the same shared code, like our user_list component. To ensure we could handle these merge errors, we intentionally created and resolved complex merge conflicts. This hands-on exercise forced us to develop a deep, practical understanding of Git branches and gave us the confidence to safely merge concurrent streams of work without losing anyone's progress. Finally, we realized that technical coordination required clear documentation, so we focused heavily on standardizing our communication through descriptive commit messages.


## 5. What did you learn about using Git in a collaborative setting?
_(Any insights or habits you’d apply in future projects?)_

We learned that Git helps teams work on the same project in a more organized way. Each person can work on their own branch, and later the changes can be merged together. I also learned that teamwork and communication are important, especially when resolving conflicts. Besides this, we also learned how Git helps the team review the files being pushed to the main branch. Instead of asking the member which part of the file was edited, the reviewers can see directly which part did a member add or remove.


## 6. How would you improve your workflow next time?
_(Think about technical habits and teamwork practices.)_

In future projects, we would improve by committing changes more often, writing clearer commit messages, and checking for updates from the team regularly. This would help me work more smoothly and avoid bigger merge conflicts.


## 7. Optional: Any feedback on the activity?
_(What worked well? What was confusing or could be improved?)_

The activity was good because it allowed us to see how a collaborative environment works. What was confusing was more on the conventions like the naming convention for the fork, as well as commit message conventions.