# GitHub Collaboration

## Why Collaboration Matters

Modern projects are usually created by teams.

GitHub provides tools that allow people to work together while keeping project history clear.

A typical collaboration workflow:

```
Multiple Contributors

        ↓

Create Changes

        ↓

Review Changes

        ↓

Merge Into Main Project
```

---

# Fork

## What is a Fork?

A fork is a personal copy of someone else's GitHub repository.

It allows you to:

- Experiment with a project
- Make improvements
- Propose changes

Example:

```
Original Repository

        ↓

Fork

        ↓

Your GitHub Account

Copy of the project
```

Forking does not modify the original repository.

---

# When Do We Use Fork?

Fork is commonly used in:

- Open-source projects
- Community contributions
- Learning projects

Example:

You find an interesting project:

```
Someone else's repository

        ↓

Fork

        ↓

Your own copy

        ↓

Make improvements
```

---

# Clone

## What is Clone?

Clone downloads a GitHub repository to your local computer.

Command:

```
git clone repository-url
```

Example:

```
git clone https://github.com/user/project.git
```

After cloning:

```
GitHub Repository

        ↓

Your Computer

        ↓

Local Repository
```

---

# Fork vs Clone

These two concepts are often confused.

| Fork | Clone |
|---|---|
| Creates a copy on GitHub | Downloads a copy to your computer |
| Online operation | Local operation |
| Used for contribution | Used for development |

Typical workflow:

```
Fork on GitHub

↓

Clone to computer

↓

Edit locally
```

---

# Branch Workflow

After cloning a project, developers usually create a branch.

Example:

```
main

        |

        +---- feature-new-page
```

Work happens inside the feature branch.

Example:

```
Edit files

↓

git add

↓

git commit

↓

git push
```

---

# Pull Request

## What is a Pull Request?

A Pull Request (PR) is a request to merge your changes into another branch.

Example:

```
Your Branch

        ↓

Pull Request

        ↓

Main Branch
```

A Pull Request allows others to:

- Review changes
- Discuss improvements
- Approve modifications

---

# Pull Request Workflow

Typical process:

```
Create Branch

↓

Make Changes

↓

Commit Changes

↓

Push Branch

↓

Open Pull Request

↓

Review

↓

Merge
```

---

# Code Review

Code Review means checking changes before they become part of the main project.

Reviewers check:

- Is the change correct?
- Does it improve the project?
- Are there possible problems?
- Is the code/documentation clear?

Review improves project quality.

---

# Issues

## What is an Issue?

Issues are used to track:

- Bugs
- Tasks
- Questions
- Suggestions

Example:

```
Issue #12

Title:

Fix broken installation link
```

A project can use Issues as a task management system.

---

# Team Collaboration Example

A realistic workflow:

## Step 1

A developer forks a repository.

```
Original Project

↓

Developer Copy
```

---

## Step 2

Clone the project:

```
git clone project-url
```

---

## Step 3

Create a branch:

```
git switch -c new-feature
```

---

## Step 4

Make changes:

```
git add .

git commit -m "Add new feature"
```

---

## Step 5

Push changes:

```
git push
```

---

## Step 6

Create Pull Request.

Team members review and merge.

---

# GitHub Collaboration Workflow

Complete workflow:

```
Fork

↓

Clone

↓

Branch

↓

Commit

↓

Push

↓

Pull Request

↓

Review

↓

Merge
```

This workflow is used by many open-source projects worldwide.

---

# Useful Links

## GitHub Resources

Fork a Repository:

https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks

Pull Requests:

https://docs.github.com/en/pull-requests

Issues:

https://docs.github.com/en/issues

---

# Summary

In this chapter, you learned:

- Why collaboration needs special workflows
- What Fork means
- What Clone means
- How branches support teamwork
- What Pull Requests do
- How Issues help project management
- How teams collaborate on GitHub

In the next chapter, you will learn how to publish projects using GitHub Pages.
