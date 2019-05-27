## Git staging area

By using `git add` files are moved to the staged area. By using different options with `git add` (for example `-p`) one can control which files are moved to the staged area. Committing moves the files from the staged area to 
![alt text](file_states.png)


## Git branches

[Notes](https://coderefinery.github.io/git-intro/06-branches/)

Command `git branch branchname` creates a new branch from **the current branch**. Each branch has their own staging areas etc and they can be merged together a later point in time.

- When merging we need to be in the branch **That the other branch is merged to**
 
