# Git Basic Concepts

## What is the Git Workflow?

Git is a version control system that records changes in a project.

A typical Git workflow looks like this:

```
Create or edit files

        ↓

Check changes

        ↓

Prepare changes

        ↓

Create a commit

        ↓

View project history
```

Git does not automatically save every change.

Users decide when to record changes.

---

# The Three Areas of Git

Git manages files through three main areas.

Understanding these three areas is the key to understanding Git.

```
Working Directory

        ↓ git add

Staging Area

        ↓ git commit

Repository
```

---

## 1. Working Directory

The Working Directory is the folder where you edit files.

Example:

```
My Project

├── README.md
├── index.html
└── images
```

When you create or modify files, the changes exist in the Working Directory.

At this stage:

```
File changed

but

Git has not recorded it yet
```

---

## 2. Staging Area

The Staging Area is where you prepare changes before committing.

Command:

```
git add
```

Example:

```
Working Directory

README.md changed

        ↓

git add README.md

        ↓

Staging Area
```

The Staging Area allows you to choose which changes should be included in the next commit.

---

## 3. Repository

The Repository stores the official history of your project.

Command:

```
git commit
```

Example:

```
Staging Area

        ↓

git commit

        ↓

Repository

Commit History
```

A commit creates a permanent record of your changes.

---

# Creating a Git Repository

To start using Git in a project folder:

Open the terminal inside your project folder.

Run:

```
git init
```

Example:

```
my-first-project

        ↓

git init

        ↓

.git folder created
```

The `.git` folder contains Git information.

Do not manually edit this folder.

---

# Checking Project Status

The most frequently used Git command is:

```
git status
```

It shows:

- Modified files
- New files
- Staged files
- Current branch information

Example:

```
git status
```

Output:

```
Untracked files:

README.md
```

This means Git sees a file but has not started tracking it.

---

# Adding Changes

To add a file to the Staging Area:

```
git add filename
```

Example:

```
git add README.md
```

To add all changed files:

```
git add .
```

Example workflow:

```
Edit files

↓

git add .

↓

Prepare changes for commit
```

---

# Creating a Commit

A commit saves changes into Git history.

Command:

```
git commit -m "Your message"
```

Example:

```
git commit -m "Create README file"
```

A good commit message explains what changed.

Good examples:

```
Add project introduction

Update installation guide

Fix broken link
```

Avoid unclear messages:

```
update

change

test
```

---

# Viewing Commit History

To view previous commits:

```
git log
```

Example:

```
commit a83f91c

Author: Your Name

Message:
Create README file
```

The commit history allows you to understand how a project developed.

---

# Basic Git Practice

A simple first Git workflow:

## Step 1

Create a project folder:

```
my-first-project
```

---

## Step 2

Initialize Git:

```
git init
```

---

## Step 3

Create a file:

```
README.md
```

---

## Step 4

Check status:

```
git status
```

---

## Step 5

Add the file:

```
git add README.md
```

---

## Step 6

Create the first commit:

```
git commit -m "Create README file"
```

---

## Step 7

View history:

```
git log
```

Congratulations!

You have created your first local Git repository.

---

# Git Workflow Summary

The basic Git workflow:

```
Edit Files

↓

git status

↓

git add

↓

git commit

↓

git log
```

Remember:

- Working Directory = where you work
- Staging Area = what you prepare
- Repository = saved history

---

# Useful Links

## Git Resources

- Git Official Website  
  https://git-scm.com/

- Git Documentation  
  https://git-scm.com/doc

- Git Command Reference  
  https://git-scm.com/docs

---

# Summary

In this chapter, you learned:

- What Git workflow means
- The three Git areas
- How to create a repository
- How to check changes
- How to stage files
- How to create commits
- How to view history

In the next chapter, you will connect Git with GitHub and learn how local projects become online repositories.
