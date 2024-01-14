# Basic Version Control

## What is version control:
### Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later.

## Explain difference between git and github:
### Git is the version control system, and GitHub is a web-based platform that leverages Git for version control while adding collaboration and project management features. Developers often use Git locally and then push their repositories to GitHub for centralized hosting and collaboration.

## The three other alternatives to github are:
### GitLab, bitbucket and SourceForge

## What is the difference between git fetch and git pull
###  "git fetch" only updates your local repository, requiring additional steps (such as merging or rebasing) to bring the changes into your working branch. Meanwhile, "git pull" not only fetches the changes but also automatically merges them into your working branch, potentially causing automatic merges and conflicts.

## In simple terms what is git rebase and the command for it:
### "git rebase" is a Git command that helps you organize and streamline your commit history. It allows you to move, combine, or modify your existing commits, making your project's history cleaner and easier to understand.
### The command for git rebase is: git rebase <base-branch>

### git cherry-pick is a Git command that allows you to copy a specific commit from one branch and apply it to another branch. 
### To show the command for git cherry pick. Assuming you have a commit with hash "ABC123" in "branch-A", and you want to apply the changes from this commit to "branch-B":
### git checkout branch-B
### git cherry-pick ABC123


