# SIU Java Intro
A simple repo to get used to get used to Git.

# Try This
#### GitHub
- Create new public repo in your GitHub account:
  - Upper right >> Click "+" >> New Repository >> {name}
  - Make sure it's public
  - Click Create Repository
  - Copy the ssh url, for example: `git@github.com:{your github handle}/{name}.git`

#### IntelliJ
- Create a new Maven project in IntelliJ
- File >> New Project >> Maven

#### Connect IntelliJ with Github
- Click in the terminal window in IntelliJ (bottom)
- `git init`
- `git remote add origin {ssh url from above}`
- `git add --all`
- `git commit -m "first push"`
- `git push origin main`

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
```

# Main
![](./docs/main.png)
