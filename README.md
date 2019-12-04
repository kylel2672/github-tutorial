# GitHub Tutorial

_by Kyle Lin_

---
## Git vs. GitHub

Git is on the local system which only you can edit your own code as seen here **"Git is a version control system (more on this later) which "tracks changes" for code."**,
while Github is a "cloud" so you can share, revise, and edit codes for others to see.**"GitHub is designed as a Git repository hosting service. "**

---
## Initial Setup

1. Create a [**github account**](github.com)
2. Setup an __ide.cs.50.io__

---
## Repository Setup

1. First you go home by using **cd ~**.
2. Next you go in github-learning by using **cd github-learning**.
3. Then you make a directory by using **mkdir repotest**.
4. Then you go in the repotest by using **cd repotest**.
5. Then you make a file using **touch README.md**.
6. You then init it by using **git init**.
7. Next you go inside the file using **c9 README.md**.
8. After that, write in whatever you want. 
9. Then you save this file using **commmand s**.
10. Then **git add README.md**
11. Then commmit it using **git commit -m "added text in README.md"**
12. Then you go to github.com , log in, and create a new repository.
13. Name then repository that same name you have it for the directory.
14. After that, copy the thing using the clipboard symbol on **"…or push an existing repository from the command line"**
15. Paste that in the terminal, and done!

---
## Workflow & Commands

* **git init** - Intialize the terminal
* **git add file** - Add to the staging area
* **git commit -m "message"** - Permanently stores changes from the staging area inside the repository by a message
* **git diff** - Checks difference between the working directory  and the staging area
* **git log** - Chronologically on the resportitory. Shows all previous commits
* **git checkout -- file** - Rewrite the line but forgot the exact. Discard changes in working directory
* **git reset HEAD file** - Able to upstage the file from the staging area
* **git status** - Optional command to see which files have been edited since the last commit (they will be red)
* **git add** - Adding the remote repo
* **git revert** - Works by undoing changes that were made in the specified by commit by creating another new commit and not actually removing any previous commits. This is ideal for published changes because the true history of the repo is preserved.
* **git help** - use this command for even more commands

