# Git Commands Cheat Sheet

This repository provides a list of commonly used Git commands along with their descriptions.

## Git Commands

- **`git add .`** - Stages all changes (new, modified, deleted files) for the next commit.
- **`git checkout -b <branch_name>`** - Creates and switches to a new branch.
- **`git clone <repo_url>`** - Copies a remote repository to your local machine.
- **`git commit -m "<commit_message>"`** - Saves staged changes with a descriptive message.
- **`git fetch origin`** - Retrieves updates from the remote repository without merging.
- **`git log`** - Displays the commit history of the repository.
- **`git merge dev`** - Merges changes from the `dev` branch into the current branch.
- **`git pull`** - Fetches and merges changes from the remote repository to the local branch.
- **`git push origin <branch_name>`** - Uploads local commits to the specified remote branch.
- **`git revert <commit_id>`** - Creates a new commit that undoes changes from a specific commit.
- **`git stash pop`** - Applies the most recent stashed changes and removes them from the stash.
- **`git stash`** - Temporarily saves uncommitted changes without committing them.
- **`git status`** - Shows the working directory and staging area status.

## How to Use
Clone this repository and use these Git commands to manage your project efficiently.

```sh
# Clone the repository
git clone <repo_url>
cd <repo_directory>
```
