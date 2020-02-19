## Git and GitHub Demo

Test repository for exposing new users to Git and version control.

### Prerequisites

Your system needs to have git. By default Mac OS and Linux operating systems (like Ubuntu) will have Git. If you're following this on Windows you'll need to install git first. You can do that here: https://git-scm.com/download/win

### Steps:

- `git clone https://github.com/raghavp96/ds-hub-git-demo.git`
- `cd ds-hub-git-demo`
- `git remote -v`
- open collaborators.txt
- add your name, and hit enter
- create a new file in this directory, `test.txt`
- `git status`
- `git add .` or `git add collaborators.txt test.txt`
- `git status`
- `git commit -m "Adding my name to collaborators and also including a new file"`
- `git log`