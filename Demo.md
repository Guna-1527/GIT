# GIT BASIC COMMANDS
    git status
    git log --oneline
    git diff commit-id commit-id
    git commit -am "commit message"

# GIT STASH
    git stash
    git stash pop
    git stash list
    git stash clear
    git stash save "name"
    git stash apply "id"

    -- "git restore "file name" // it help to retore the file to the last commit

# GIT BRANCH
    git branch "branch name"
    git checkout branch
    git branch
    git checkout -b "branch name"
    git branch -d "branch name"
    git branch -D "branch name" // -D delete the branch even it is not merged
    git push origin --delete "branch name"

# PULL CHANGES AND MERGE BRANCH
    git pull origin main
    git merge "branch name"
    git branch --merged
    git branch --no-merged

