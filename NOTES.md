Github Default Branching Naming

Master(adjective)main: principal


> git switch <branch-name>

> git switch -c <branch-name>  # create

> git checkout -b <branch-name> 


## rename branch 

> git branch -m <current name> < new name>
>
> git branch -m < new name for current branch>

## Delete branch

> git branch -d <branchname>

## Force delete 

> git branch -D <branchname>


## Merging

### Fast forward merge



> git checkout <target-branch>

> git merge <source-branch>

### Non fast forward merge

git merge --no-ff <source-branch>

## compare branches

> git diff <branch1> <branch2>

> git show <hash> to see file

> git diff --cached 
> git diff HEAD # changes since last commit

ignore whitespace  differences

> git diff -w 

> git log --oneline

git diff <commit hash> # Specific commit and current

git diff --cached <commit hash> # Specific commit and staged

git diff <commit hash> < commit hash> # Difference between two commits

git diff feature main # Difference between two branches
git diff feature...main # changed in main since feature was start off of it

git diff quickfix main filename


