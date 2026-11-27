# Pull Requests and Code Review

- **Phase:** 2 — Professional Workflow
- **Status:** Learning

## What is a Pull Request?

A **Pull Request (PR)** is a request to review a set of changes and consider merging them into another branch, often `main`.

## What is code review?

**Code review** is when another developer examines a proposed change. They may check:
- Does it meet the requirement?
- Is the logic correct?
- Is it understandable?
- Are there security or performance concerns?
- Are useful tests included?

## Common workflow

```text
Developer creates branch
        ↓
Makes a change and commits
        ↓
Pushes branch to GitHub
        ↓
Opens Pull Request
        ↓
Reviewer reads the change
        ↓
 ┌───────────────┬────────────────┐
 ↓               ↓                ↓
Approve       Request changes   Discuss
 ↓               ↓                ↓
Merge         Developer updates  Agree on solution
```

A reviewer does not simply ignore code when they find a problem. They explain the concern and may request a correction. The developer can update the PR with new commits.

## Why review?

Review can catch mistakes, improve clarity, share knowledge, and check whether the change fits the project. It does not replace automated or manual testing.

## Key idea

A PR is the review-and-merge conversation around a proposed change. Code review is the examination and feedback within that process.