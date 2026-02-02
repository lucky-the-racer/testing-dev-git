## Git Practice Repository (Hands-On)

### Overview
This repository is created as a hands-on Git practice project.
The goal of this repo is to demonstrate my practical understanding of Git commands,
branching strategies, and GitHub workflow.

All work in this repository was done using the Git CLI, and commits are intentionally
kept small and meaningful so that the commit history itself shows real Git usage.



##  Repository Structure

── index.html
── style.css
── commands.txt
── README.md



### File Explanation
- **index.html** – Simple HTML file used to track changes across branches  
- **style.css** – Basic styling for the HTML page  
- **commands.txt** – List of Git commands with short explanations for learning  
- **README.md** – Documentation explaining project purpose and workflow  



##  Branching Strategy Used

This repository uses multiple branches to demonstrate a real Git workflow.

### Branches
- **main**
  - Stable branch
  - Represents production-ready code

- **integration**
  - Used to merge feature branches before pushing to main
  - Helps validate combined changes

- **feature branch**
  - Used for individual changes or experiments
  - Merged into integration branch

- **release-v1.0**
  - Versioned release branch
  - Contains finalized HTML, CSS, and version info

Each branch contains small differences so changes are visible in commit history.



##  Git Commands Practiced

The file `commands.txt` includes:
- Basic Git commands (init, add, commit, status)
- Branching and merging
- Remote repository handling
- Merge conflict resolution
- Stash operations
- Reset, revert, and rebase
- Diff and inspection commands
- `.gitignore` usage
- Git configuration commands



##  What This Project Demonstrates

- Practical Git command usage
- Branch creation and switching
- Feature → Integration → Main workflow
- Merge conflict handling
- Safe undo vs destructive undo
- Clean commit history
- Release versioning mindset

---

##  How to Use This Repository

Clone the repo:
bash

git clone<repository-url>



Switch between branches:
git checkout feature-branch
git checkout integration
git checkout main

Review commit history:
git log --oneline


Practice commands from:
commands.txt

