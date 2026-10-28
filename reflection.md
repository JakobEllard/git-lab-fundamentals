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




1. Why is 'Squash and Merge' preferable over standard merge commits for small feature branches in team
projects?
Because it combines all branch commits into a SINGLE clean commit applied to main.
2. Describe the difference between 'Add single comment' and 'Start a review' on GitHub. Why is batching
important?
Comments are submitted one at a time, a review avoids spamming by sending as a batch.
3. How do Branch Protection Rules prevent accidental production breakage?
They force at least one other team member to review the commit before it is added to the main branch.
4. When a remote conflict occurs in a PR, why is it better to merge origin/main into your feature branch
locally rather than forcing a push?
Resolving the issue locally, as opposed to forcing a push will keep others branches up to date and allow the push to main to go in one larger push.
