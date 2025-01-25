
# Git and GitHub Guide 🌐

Welcome to this comprehensive guide on using Git and GitHub! Below, you'll find a list of commonly used Git commands along with their functions.

## Table of Commands

| **Command**                       | **Description**                                                                                                                                                 |
|-----------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `git --version` 💻                 | Check if Git is installed successfully.                                                                                                                           |
| `git init` 🆕                      | Initialize a new Git repository in the current folder.                                                                                                           |
| `git clone repository-url` 🔄      | Clone an existing repository from a URL.                                                                                                                           |
| `cd` 📂                            | Change the directory to navigate to a different folder.                                                                                                          |
| `pwd` 🧭                            | Print the working directory to display your current folder's path.                                                                                              |
| `git status` 📋                    | Shows the status of changes in the repository.                                                                                                                   |
| `git diff filename` 🖋️            | Shows the changes made to a specific file since the last commit.                                                                                               |
| `git add filename` ➕              | Adds a file to the staging area, preparing it for a commit.                                                                                                      |
| `git commit -m "message"` 📝       | Commit the staged changes with a descriptive message.                                                                                                           |
| `git log` 📜                       | View the commit history of the repository.                                                                                                                       |
| `git log -5` 📄                    | View the last 5 commits in the repository.                                                                                                                        |
| `git show commit-id` 🔍            | View the details of a specific commit.                                                                                                                           |
| `git branch` 🌿                    | Lists all the branches in your repository, highlighting the current one.                                                                                        |
| `git branch -b MyBranch` 🌱       | Create a new branch named "MyBranch" and switch to it.                                                                                                          |
| `git branch -d MyBranch` ❌        | Delete a branch called "MyBranch."                                                                                                                                |
| `git checkout branch_name` 🔀      | Switch to a different branch in your repository.                                                                                                                 |
| `git checkout master` ⬅️          | Switch to the master branch (or main branch).                                                                                                                    |
| `git merge branch_name` 🔗         | Merge the changes from another branch (e.g., `branch_name`) into the current branch.                                                                            |
| `git reset --soft HEAD~1` ↩️       | Undo the last commit but keep the changes staged.                                                                                                               |
| `git reset --hard HEAD~1` 🧹       | Undo the last commit and remove all changes (hard reset).                                                                                                        |
| `git push` ⬆️                     | Push local changes to the remote repository.                                                                                                                    |
| `git pull` ⬇️                     | Fetch the latest changes from the remote repository and merge them into your local branch.                                                                      |
| `git restore --staged filename` ❗  | Unstage changes but keep the file modifications in your working directory.                                                                                      |
| `git restore filename` 🔄          | Discard changes made to the file and restore it to the state from the last commit.                                                                               |
| `git commit --amend` ✏️           | Amend the last commit, for example, to fix a message or add forgotten changes.                                                                                   |

---

## Additional Information 🌟

1. **What is a Repository?**  
   A repository is a directory or storage space where your project files live. You can store your project on GitHub and make it accessible to others.

2. **What is a Branch?**  
   A branch in Git is a separate line of development. It allows you to work on different features or fixes without affecting the main codebase.

3. **Staging and Unstaging**  
   Before you commit, your changes go through two stages:
   - **Staging Area**: The area where you prepare your changes for committing.
   - **Unstaged Area**: Where changes are made but not yet added to the staging area.

4. **What is HEAD?**  
   HEAD refers to the current branch you're working on or the latest commit in that branch. For example, `HEAD~1` means "one commit before the current commit."

5. **Commit and Push Workflow**  
   After staging and committing your changes locally, you push them to a remote repository to share with others. This process ensures all contributors have access to the latest changes.

6. **Undoing Changes**  
   The commands `git reset --soft` and `git reset --hard` help in undoing commits. The difference is:
   - **Soft**: Keeps the changes.
   - **Hard**: Discards the changes.

---

This README provides a detailed walkthrough of Git commands with accompanying icons for clarity. Each section explains its functionality, making it easy for beginners to follow and understand Git and GitHub operations.

