# Topic

Branching

Types of Merges
- Fast-Forward
When no additional work has been detected on the parent branch

Automatic Merges
- Non-Conflicting Merge
- Preserves both timelines

Manual Merges
- Automatic merger not possible
- Once all conflicts have been resolved, changes are saved as merges commit


### Special Markers
HEAD  
- points to last commit of current branch
- can be moved

git branch

The changes are taken with the new branch  
great to do if the changes should be isolated  
`git checkout -b [new branch name]`

switching back to master  
`git checkout master`

Simple fast forward merge  
`git merge [branch]`

Deleting a branch  
`git branch -d [branch to delete]`

Allows you to select the changes you want to keep
`git mergetool`

NOTE: A `.orig` file may be produced by the process

### Tags
Tags are labels that you put at any arbitrary commit point
git tag [tag name]
git tag --list
git tag -d [tag name]
git tag -a [tag name] -m "message"
git show [tag ]

NOTE: This great for major milestones and you might want to associate some information with it
