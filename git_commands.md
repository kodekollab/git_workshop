# Git Commands Reference

Below is a list of essential Git commands that you can use as a reference:

## Creating and Cloning a Repository

- `git init`: Initialize a new Git repository.
- `git clone <repository_url>`: Clone a remote repository to your local machine.

## Branching and Merging

- `git branch`: List branches in the repository.
- `git branch <branch_name>`: Create a new branch.
- `git checkout <branch_name>`: Switch to the specified branch.
- `git checkout -b <branch_name>`: Create a new branch and switch to it.
- `git merge <branch_name>`: Merge a branch into the current branch (e.g., master branch).
- `git pull origin <branch_name>`: Pull the latest changes from the remote repository to your local branch.

## Staging and Committing

- `git status`: Show the status of your working directory and staged files.
- `git add <file_name>`: Stage a specific file for the next commit.
- `git add .`: Stage all changes in the current directory for the next commit.
- `git commit -m "<commit_message>"`: Commit the staged changes with a descriptive message.
- `git commit --amend`: Amend the last commit with new changes.

## Pushing and Pulling

- `git push <remote> <branch_name>`: Push your local branch and commits to the remote repository.
- `git pull <remote> <branch_name>`: Pull the latest changes from the remote repository to your current branch.

## Resolving Conflicts

- `git diff`: Show the differences between the working directory and the staging area.
- `git diff <branch_name>`: Show the differences between the current branch and the specified branch.
- `git mergetool`: Launch a merge tool to help resolve merge conflicts.
- `git stash`: Stash changes in a dirty working directory for later use.
- `git stash apply`: Apply the most recent stash to the working directory.

## Checking History

- `git log`: Show the commit history.
- `git log --oneline`: Show the commit history in a compact format.
- `git blame <file_name>`: Show who last modified each line of a file.

## Miscellaneous

- `git remote add <remote_name> <repository_url>`: Add a remote repository.
- `git remote -v`: List remote repositories.
- `git fetch`: Fetch changes from a remote repository.
- `git tag <tag_name>`: Create a new tag for a specific commit.

Refer to the [Git documentation](https://git-scm.com/doc) for more details on these commands and additional options.
