# Git Branch

## What is a Branch?

A branch is an independent development path in a Git repository.

Branches allow developers to work on different versions of a project without affecting the main project.

Example:

```
main

|
|
Project version A
```

Create a new branch:

```
main

|
|
feature-new-page
```

Now changes can happen separately.

---

# Why Use Branches?

Branches are useful when:

- Developing new features
- Testing new ideas
- Fixing bugs
- Working with other people

Without branches:

```
Main Project

↓

Direct changes

↓

Higher risk of problems
```

With branches:

```
Main Project

        |

        +---- Feature Branch

        +---- Test Branch
```

Each task can be developed safely.

---

# Main Branch

The main branch is the primary version of a project.

Modern Git projects usually use:

```
main
```

as the default branch name.

The main branch usually contains:

- Stable project versions
- Official releases
- Completed work

---

# Viewing Branches

To see existing branches:

```
git branch
```

Example:

```
* main
```

The `*` symbol shows the current branch.

---

# Creating a Branch

Create a new branch:

```
git branch branch-name
```

Example:

```
git branch new-feature
```

Now the repository has:

```
main

new-feature
```

---

# Switching Branches

To move to another branch:

```
git checkout branch-name
```

Example:

```
git checkout new-feature
```

Newer Git versions also support:

```
git switch branch-name
```

Example:

```
git switch new-feature
```

---

# Creating and Switching in One Step

A common command:

```
git checkout -b branch-name
```

Example:

```
git checkout -b feature-login
```

This creates:

```
feature-login
```

and immediately switches to it.

---

# Working on a Branch

After switching branches:

```
feature-login
```

you can edit files normally.

Example:

```
Modify files

↓

git add .

↓

git commit -m "Add login feature"
```

The commit belongs only to this branch.

---

# Merging Branches

After finishing work, you can merge the branch back into main.

First switch to main:

```
git switch main
```

Then merge:

```
git merge feature-login
```

The result:

Before:

```
main

A---B


feature-login

A---B---C
```

After merge:

```
main

A---B---C
```

---

# Branch Workflow Example

A typical workflow:

## Step 1

Start from main:

```
main
```

---

## Step 2

Create a feature branch:

```
git switch -c new-feature
```

---

## Step 3

Develop the feature:

```
Edit files

git add .

git commit -m "Add new feature"
```

---

## Step 4

Return to main:

```
git switch main
```

---

## Step 5

Merge:

```
git merge new-feature
```

---

# Branches on GitHub

GitHub repositories also support branches.

A repository can contain:

```
GitHub Repository

├── main
├── development
├── feature-login
└── feature-design
```

Branches allow teams to work together safely.

---

# Useful Links

## Git Resources

Git Branch Documentation:

https://git-scm.com/docs/git-branch

Git Merge Documentation:

https://git-scm.com/docs/git-merge


## GitHub Resources

Working with Branches:

https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-branches

---

# Summary

In this chapter, you learned:

- What branches are
- Why branches are useful
- What the main branch means
- How to create branches
- How to switch branches
- How to merge branches

Branches allow projects to grow safely and are the foundation of team collaboration.

In the next chapter, you will learn how teams use GitHub for collaboration through Forks, Pull Requests, and Code Review.
