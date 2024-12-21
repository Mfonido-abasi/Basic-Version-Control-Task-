# Basic-Version-Control-Task-
### Version Control
Version Control is the process of organising, tracking and managing changes made to a source code or software codes over a period of time.
### The Difference between Git and GitHub
Git is a system for version control. It is a tool used to track, organise and manage software code over a period of time while GitHub is a developer platform used for collaboration,i.e sharing, storing and working on codes alongside other developers or experts. Developers use GitHub to create, store and share their codes, while they use git to track the changes made and control the version history.
### Three GitHub Alternatives
- GitLab
- Bitbucket
- Gitea
### The Difference between Git Fetch and Git Pull
The Git Fetch command update the local git repository with changes/updates from a remote respository. This is sort of like updating the "storage" with the changes/updates made without implementing it into the working directory. In order to move the changes/updates from the git repository to the working directory after it's been fetched, the git merge command is used. However, the git pull is a one step command to update both the git repository and the working directory at once with the updates/changes from the remote repository. It is a combination of both the git fetch and git merge commands. It is used when the user isn't actively working on the code files.
### Git Rebase Meaning and the Command for it
Git Rebase updates and manage commits, allowing you to change/modifying the history of your repository. The command for it is: git rebase "branch-name" 
###  Git Cherry-pick and the Command for it
 Git cherry-pick command allows developers to selectively apply specific commits between branches. The command for it is: git cherry-pick < commit-hash >