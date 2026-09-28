Why did merging update-message-b cause a conflict, but merging update-message-a did not?
When update-message-a was merged, it was merged with main and had nothing to conflict with, the issue came when update-message-b was trying to commit the same
lines at the same time.

2. In the conflict markers, what does the section under HEAD represent? What does the section under the branch
name represent?
HEAD is the current main branch, branch name is the one you just tried to merge.

4. What command would abort a merge in progress if you decided not to resolve it? (Look up git merge --abort.)
   Look up git merge --abort cancels an active merge
   
6. How does the git log --graph shape from Part C differ from the one in Part B? Why?
   It has a branch for the merge conflict in part C
