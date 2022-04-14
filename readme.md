# SIU Java Intro
A simple repo to get used to get used to Git.

# Assignment 

#### GitHub
- Create new public repo in your GitHub account:
  - Upper right >> Click "+" >> New Repository >> {name}
  - Make sure it's public
  - Click Create Repository
  - Copy the SSH url, for example: `git@github.com:{your github handle}/{name}.git`

#### IntelliJ
- Create a new Maven project in IntelliJ
  - Upper Right >> New Project
  - Left Menu >> select Maven >> Next
  - Enter a name
  - Create a new directory, something like `C:\my-java-projects\test`

  ![](./docs/java-projects.png)

  - Click Finish
  - Right click on the java folder (`/src/main/java`):
  - New >> Java Class
    - Give it a name, "Main"
    - Type "main" >> press tab
    - Type "sout" press tab
    - Provide a string to the `println()` function
    
![](./docs/main.png)
    
#### Connect IntelliJ with Github
- Open the Terminal window in IntelliJ (bottom tab)
- `git init`
- `git remote add origin {paste ssh url from above}`
- `git add --all`
- `git commit -m "first push"`
- `git push origin main`

![](./docs/github.png)

- Add a `readme.md` file in IntelliJ (below the `pom.xml` file)
- `git add --all`
- `git commit -m "Add readme.`
- `git push origin main`

ProTip: Open a Terminal window as a Command Prompt:

`git add --all && git commit -m "Add readme. && git push origin main`

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
