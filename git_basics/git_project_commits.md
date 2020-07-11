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
(Mostly found at https://gist.github.com/mindplace/b4b094157d7a3be6afd2c96370d39fad)

## Create the repo on GitHub
1. Log into GitHub
2. At the top right of any Github page, you should see a '+' icon. Click that, then select 'New Repository'.
3. Give your repository a name--ideally the same name as your local project. If I'm building a travel application, its folder will be called 'travel-app' on my computer, and 'travel-app' will be the Github repository name as well.
4. Click 'Create Repository'. The next screen you see will be important, so don't close it.

## Connect your local work to the GitHub Repo
1. Click the green ```Code``` button
2. Copy the link under "Clone with HTTPS"
3. Back in terminal in your project directory, type ```git init``` and hit enter - this creates a git file to manage builds locally
4. Then in terminal, type ```git remote add origin {copied web address}``` and hit 'enter' - this associates that project/folder with the repo created above
5. Push your branch to Github: ```git push origin master```

# Other References

https://yangsu.github.io/pull-request-tutorial/
