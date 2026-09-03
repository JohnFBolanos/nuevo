# Git & GitHub — Essential Terminal Commands

Common commands for working in a GitHub Codespaces terminal.

## Setup & Clone

| Command | What it does |
|---|---|
| `git clone <url>` | copy a repo locally |
| `git init` | start a new repo |
| `gh repo clone <repo>` | clone via GitHub CLI |

## Branching

| Command | What it does |
|---|---|
| `git branch` | list branches |
| `git branch <name>` | create a branch |
| `git checkout -b <name>` | create & switch to it |
| `git switch <name>` | change to a branch |

## Stage & Commit

| Command | What it does |
|---|---|
| `git status` | see changed files |
| `git add <file>` | stage a file |
| `git add .` | stage everything |
| `git commit -m "msg"` | save a snapshot |

## Sync with GitHub

| Command | What it does |
|---|---|
| `git push origin <branch>` | upload commits |
| `git pull` | fetch & merge remote |
| `git fetch` | download refs only |

## Merge & History

| Command | What it does |
|---|---|
| `git merge <branch>` | merge into current branch |
| `git log --oneline` | compact commit history |
| `git diff` | see unstaged changes |

## Undo & Fix

| Command | What it does |
|---|---|
| `git restore <file>` | discard local changes |
| `git reset HEAD~1` | undo last commit (keep changes) |
| `git stash` | shelve work in progress |
