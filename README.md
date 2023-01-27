# git_test

repository for testing git

### git stash
save current state (ex. WIP)  
its data structure is **stack**

- git stash
- git apply, git drop
- git pop (apply + drop)
- git stash list

### git reset
- return to last commit
  - git reset --hard
  - git reset --hard HEAD

- return to second commit from the back
  - git reset --hard HEAD~
  - git reset --hard HEAD~1

- return to N commit from the back
  - git reset --hard HEAD~N
  
### git commit --amend
- help change last commit msg
