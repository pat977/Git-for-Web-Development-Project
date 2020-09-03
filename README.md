# Github Learning

## Clone A Repository

1. Copy URL from Github of the repository you want to clone git@github.com:jthomps838/github-learning.git
2. Open a Terminal such as [Git Bash (Windows)](https://gitforwindows.org/)
3. Navigate to the directory you want to clone your repo in
4. `git clone git@github.com:jthomps838/github-learning.git [optional folder name]`
5. `ls` to check if the cloned folder is present
6. `cd` down into the newly created folder
7. `code .` will open this folder inside of VS Code

## Branching off of master

1. Open current project in VS Code
2. Use VS Code Terminal at this point
3. Check lower left corner of VS Code. It should show the branch name currently on

   ![Branch Name](/images/branch-name.png)

4. `git checkout -b [branch-name-here]`
5. Now your branch name should change in the bottom left corner
6. Or check using `git branch`

## Process of Committing Changes

1. `git add .` This command will add all files that have changed to staging
2. `git commit -m "[message goes in here]"`
3. `git push`

### Note: First Time Committing branch

- git will prompt you a similar command than this
- `git push --set-upstream origin test-branch`

**_ Using `git status` in each step will show you files and where they are changed _**

## Changing branches

- `git checkout [branch-name]`

## Checking out current branch name

- `git branch`

- this is a test


i see you!!!!!!


