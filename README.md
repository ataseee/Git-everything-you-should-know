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

## `git push` - send your files to remote repository

If you've been working in a **local repository** (a folder on your computer), it's time to send all fruits of your labour with your colleagues. For this purpose is used a remote **repositories** that stored such platforms GitHub, GitLab, etc.

To send your local repo to a remote repository, we use command `git push`.
To push your repo for the **first time** we should use `git push -u origin master`.

Now you can work with **GIT**! Congratulations!

## `git log` - see information about your commits

If you want to see when, why was created any commit, you just need type `git log`.

```
commit 6cf871d598e6726c5c95ba75c6a863bbd0e3cb32 (HEAD -> master, origin/master)
Author: User atase <atase@gmail.com>
Date:   Sun Nov 19 17:03:53 2023 +0600

commit 234dfsd598e6726c5c95ba75c6a863bbd0edf343
Author: User atase <atase@gmail.com>
Date:   Sun Nov 19 17:03:53 2023 +0600
```

**6cf871d598e6726c5c95ba75c6a863bbd0e3cb32** is a unique ID of a commit, but we call it **hash**. Hash stores the information about a commit. Hash stores when the commit was made, the contents of the files in the repository at the time of the commit, and a link to the previous, or parent, commit.

The inscription **(HEAD -> master, origin/master)** says that **6cf871d598e6726c5c95ba75c6a863bbd0e3cb32** is the latest commit. HEAD is the file file that references to the refs/heads/master service file containing the hash of the last commit.


```Author: User atase <atase@gmail.com>``` - information about the author of the commit.

```Date:   Sun Nov 19 17:03:53 2023 +0600``` - date of creation of the commit.

# `git status` - see a status of your commits

The `git status` command always informs you about the status of a file, such as whether it has been added to the "to be committed" list, is untracked, or has been modified. `git status` explicitly shows the following states of files: untracked, staged, and modified.

```
$ touch fileA.txt
$ git status
On branch master
Untracked files: # found untracked files
  (use "git add <file>..." to include in what will be committed)
        fileA.txt

nothing added to commit but untracked files present (use "git add" to track) 
```
