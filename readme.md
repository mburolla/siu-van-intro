# GitHub Intro with Java
A repository (repo) to help students get used to Git.  Assigments are located [here](assignments.md).

# Getting Started
- Setup your SSH keys
- Accept the invitation for this repo in your email
- Clone this repo 

# Videos
- [Git Tutorial for Beginners: Learn Git in (1h)](https://youtu.be/8JJ101D3knE)
- [Command Prompt Basics: How to use CMD (18m)](https://youtu.be/A3nwRCV-bTU)
- [Learn Git In (15m)](https://youtu.be/USjZcfj8yxE)
- [Git Tutorial for Beginners: Command-Line Fundamentals (30m)](https://youtu.be/HVsySz-h9r4)

# Links
- [Atlassian What is Git?](https://www.atlassian.com/git/tutorials/what-is-git)
- [How Teams Use GitHub](./docs/Intro-to-GitHub.pptx) (Download only)
- [Atlassian Git Cheat Sheet](./docs/SWTM-2088_Atlassian-Git-Cheatsheet.pdf)

# Primary Workflow
- Identify the branch you are on: `git branch`
- Create a branch from the branch you are currently on: `git checkout -b dev-{your initials}-{context}`
- Code Monkey
  - Write code
  - Run code 
  - Test code
- See what has changed: `git status`
  - ProTip: Always run `git status` before you make a commit (to make sure you are not adding "junk" to your commit)
- Stage all files: `git add --all`
- Create a commit: `git commit -m "YOUR_MESSAGE_HERE"`
- Push to GitHub: `git push origin YOUR_BRANCH_NAME`
- Create Pull Request (PR)
- Merge PR
- Update your local dev branch: `git checkout dev && git pull origin dev`
- Delete your branch that was just submitted: `git branch -D YOUR_BRANCH_NAME`

# Common Git Commands
```
git init
git clone <url>
git fetch --all
git push origin <branch name>
git pull origin <branch name>
git remote add origin <url>
git add --all
git branch
git checkout -b <new branch name>
git checkout
git commit -m “your message”
git status
git reset --hard
git clean -f
git stash
```
