# Git Project Commits (Download/Upload)

You can follow instructions in the beginning of this YouTube video from Lambda School: https://www.youtube.com/watch?v=4LNf5qcQWHQ;

## Download Onto Machine

### Fork and clone the repo with GitHub:

1. In GitHub: fork the master branch (select the “fork” button toward upper right)
2. In GitHub: get address of the branch addressing by selecting the green Clone or Download button and copying the url of your branch
3. In command prompt / terminal: navigate to desired folder > `git clone {paste copied url from GitHub}`

### Create a branch from repo

1. Get to and pull freshest code for desired branch to branch off

- `git checkout {master or desired branch}`
- `git pull`
- `git checkout -b {desired-branch-name}` - that will create a new branch for you

## Commit changes / Upload back to branch on GitHub

Do these from the command prompt (be in appropriate folder)

1. `git status`

- Should see changed files in red

2. `git add --all` (can all add a specific file, e.g. “git add exercises.js”)
3. `git status`

- Shoud see changed files in green

4. `git commit -m "your commit message"`
5. `git push origin {branch name}`

## Create a pull request

1. In GitHub find your branch
2. Select Pull Request button
3. Fill out the form and send the pull request

# Create and commit a code project from scratch
https://docs.github.com/en/github/importing-your-projects-to-github/adding-an-existing-project-to-github-using-the-command-line

# Other References

https://yangsu.github.io/pull-request-tutorial/
