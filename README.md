# UltimateGitCheatSheet
A sort of ultimate cheat sheet for git commands that I mostly use

# **Markdown**
- **#** -heading (increasing hash -> decreasing size)
- \** ** -bold
- \* * -italics
- \*** *** -bold and italics
- **\-(space)** -unordered list
- **1.(space)** -ordered list

# **Start**
- **git clone < url > [< localname >]** -clone a git repo (I prefer this)

- **git add remote < remotename > < url >** -add remote repo to your local repo

# **Essentials**
- **git add < filename >** -add files

- **git add .** -add all files

- **git status** -check status

- **git push [-u] [< remote repo >] [< remote branch >]** - push to remote repo

- **git log [ attributes ]** - shows commit log

- **git log --oneline --graph** - shorthand commit log with graph

# **Branch**
- **git branch <[ branch name ]>** -creates a branch

- **git checkout <[ branch name ]>** -sets HEAD to branch

- **git checkout -b <[ branch name ]>** - creates and checkouts a new branch.

- **git branch -d < branch name>** - delete a branch

# **Merge**
- **Fast Forward Merge (Default)** 
    - **git checkout master**
    - **git merge < branch name >**
    - **git branch -d < branch name >**

- **Merge Commit** 
    - **git checkout master**
    - **git merge < branch name >**
    - **git branch -d < branch name >**

- **Merge Commit (No Fast Forward)** 
    - **git checkout master**
    - **git merge --no-ff < branch name >**
    - **git branch -d < branch name >**