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
- git clone
  - creates a local copy of a remote repository for you on your computer
- git branch
  - if given a name, creates a new branch with that name
  - if not given a name, it will list branches and indicate the current branch
- git checkout
  - switch to another branch
  - ... and does like fifty other things (we'll get to those in time)

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

## Branching

Each branch represents a different "stream" of work. This can be anything
ranging from having a "stable" stream to a "I'm-working-on-this-feature" stream
to a "experimental" stream.

To make a new branch, type `git branch $BRANCH_NAME_HERE`. For instance, to
create a `develop` branch, you can type `git branch develop`.

To switch to a branch, type `git checkout $BRANCH_NAME_HERE`. For instance, to
switch to the `develop` branch, you can type `git checkout develop`.

### Common Conventions

- master
  - the default, the stable, the ready-to-ship
- develop
  - the experimental -- work is shared here
- feat-xxx
  - focused on a single feature
