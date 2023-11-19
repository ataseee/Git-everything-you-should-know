# GIT - EVERYTHING YOU SHOULD KNOW

## `git init` - initialize your first repository

Use `git init` to initialize your **repository**

It means you can use any folder with files as a git repository

Also, you can check is your folder a repository using `git status`. This command will show you a status of your repo.

## `git add` - prepare your files to commit

`git add` prepares your file to commit

If **commit** saves your files, `git add` is the key for **commit**. So you should use a key before saving something. Use `add` before **committing**.

`git add --all` prepares all your files in a repository to **commit**.

Also, you can use `git add .` instead of `git add --all` to prepare all your files to **commit**, including current folder.

## `git commit` - save your files

You might be wondering what **commit** I was talking about. 

`git commit` - saves all your prepared files in a repository.
If `git add` prepares for saving, `git commit` saves.

It is recommended to write a description to all your commits. For this you'll need to add a key `-m`. So your command will end up looking like `git commit -m "your description"`.

To see your history of commits use `git log`. It shows your commits in reverse chronological order.

## Create your GitHub account and link your local repository to remote one

To be added later...

## `git push` - sends your files to remote repository

If you've been working in a **local repository** (a folder on your computer), it's time to send all fruits of your labour with your colleagues. For this purpose is used a remote **repositories** that stored such platforms GitHub, GitLab, etc.

To send your local repo to a remote repository, we use command `git push`.
To push your repo for the **first time** we should use `git push -u origin master`.

Now you can work with **GIT**! Congratulations!
