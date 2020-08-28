# Git Focused

This is a demo-repository showcasing how Git works.

## Commands

- git init
  - creates a new git repo (empty)
- git add
  - stage files to be committed
- git commit
  - create the commit
- git status
  - shows the status of the working directory
- git log
  - shows a history of past commits
- git remote
  - identifies other git repos to push/pull
- git push
  - send new commits to another git repo
- git pull
  - retrieve new commits from another git repo

## Working Directory

- Untracked Files - new to the repository
- Modified Files - known files that have been changed
- Staged Files - ready to be committed

## Sync

> The repository you are pushing/pulling with is referred to as the _remote_
> repository. This is often times on GitHub, but it is not the only option.

Synchronization occurs between two repositories. When you
push or pull, the history of the two repositories are compared.

When pushing, you need to be up to date and have new commits to contribute.

When pulling, the remote needs to have new commits to pull down.

In order for changes to be propagated, they need to be contained within a commit.
