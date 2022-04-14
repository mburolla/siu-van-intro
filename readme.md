# SIU Java Intro
A simple repo to get used to Git.

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

# Assignment 

#### GitHub
- Create new public repo in your GitHub account:
  - Upper right corner >> Click "+" >> New Repository >> {name}
  - Make sure it's public
  - Click Create Repository
  - Copy the SSH url, for example: `git@github.com:{your github handle}/{name}.git`

#### IntelliJ
- Create a new Maven project with IntelliJ
  - Upper Right >> New Project
  - Left Menu >> select Maven >> Next
  - Enter a name
  - Create a new directory, something like `C:\my-java-projects\test`

  ![](./docs/new-java-project.png)

  - Click Finish
  - Wait a bit for maven to download dependencies
  - The java folder should be a light blue color, different from the rest of the folders
  - Right click on the java folder (`/src/main/java`):
  - New >> Java Class
    - Specify a class name, something like: `Main`
    - Type `main` >> press tab
    - Type `sout` >> press tab
    - Provide a string to the `println()` function
    
![](./docs/main.png)

  - Click on the Green arrow and run the Java program (`Run 'Main.main()'`).
  - If it works, let's push it to GitHub!
    
#### Connect Code with GitHub
- Open the Terminal window in IntelliJ (bottom tab)
- `git init`
- `git remote add origin {paste ssh url from above}`
- `git add --all`
- `git commit -m "First push."`
- `git push origin main`


- GitHub should resemble something like this:
![](./docs/github.png)


#### Add Readme File
- Add a `readme.md` file in IntelliJ:
  - Right click `pom.xml` >> New >> File
  - Add some [Markdown](https://www.markdownguide.org/basic-syntax/) text to the readme.md file
  - Save it
  - `git add --all`
  - `git commit -m "Add readme.`
  - `git push origin main`

ProTip: Open a Terminal window as a Command Prompt so we can change Git commands together:

![](./docs/cmd-shell.png)

`git add --all && git commit -m "Add readme." && git push origin main`

