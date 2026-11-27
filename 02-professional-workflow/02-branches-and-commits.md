# Branches and Commits

- **Phase:** 2 — Professional Workflow
- **Status:** Learning

## What is a branch?

A **branch** is a separate line of work in a Git repository. It lets a developer work on a change without directly changing the main branch.

Example: You want to add an account-blocking feature. You can create a branch for that feature and work there.

## What is a commit?

A **commit** records a set of changes in Git. A useful commit message says what the change does.

Example message: `Add account blocking validation`.

## A common workflow

```text
main branch
    |
create feature branch
    |
make and review local changes
    |
commit changes
    |
push branch to GitHub
    |
open Pull Request
```

## Why use branches?

- Keep unfinished work separate.
- Allow different developers to work in parallel.
- Make review easier.
- Reduce the risk of accidentally mixing unrelated changes.

## Important terms

- **Working tree:** Your current files.
- **Staging area:** The changes selected for the next commit.
- **Remote:** A copy of the repository hosted elsewhere, often on GitHub.
- **Merge:** Combine changes from one branch into another.

## Key idea

A branch is a place to develop a change; a commit records a point in that work.