# Introduction to GitHub

## What is GitHub?

GitHub is an online platform built around Git.

While Git manages project history on your computer, GitHub provides a place to store, share, and collaborate on projects online.

A simple comparison:

```
Git

Local version control tool

↓

Your Computer
```

```
GitHub

Online collaboration platform

↓

Internet Repository
```

---

# Why Use GitHub?

GitHub helps people:

- Store projects online
- Share knowledge
- Collaborate with others
- Review changes
- Publish projects

GitHub is widely used in:

- Software development
- Research
- Open-source communities
- Documentation projects
- Design and architecture workflows

---

# Creating a GitHub Account

To use GitHub, you need a GitHub account.

Official website:

[GitHub Official Website](https://github.com/)

Sign up page:

[Create GitHub Account](https://github.com/signup)

During registration:

1. Choose a username
2. Provide an email address
3. Create a password
4. Verify your email

---

# Understanding GitHub Interface

After logging in, you will see the GitHub interface.

Important areas include:

```
GitHub Homepage

├── Repositories
├── Profile
├── Issues
├── Pull Requests
└── Settings
```

---

## Profile

Your profile shows:

- Username
- Projects
- Contributions
- Public activity

A GitHub profile can become a professional portfolio.

---

## Repository List

Repositories are projects stored on GitHub.

Example:

```
Your GitHub Account

├── project-one
├── tutorial-project
└── research-notes
```

---

# What is a Repository?

A repository (repo) is a project container.

It contains:

- Files
- Folders
- Version history
- Project information

Example:

```
My Project Repository

├── README.md
├── docs
├── images
└── .git history
```

---

# Local Repository vs Remote Repository

Git projects usually have two locations.

## Local Repository

Located on your computer.

Example:

```
Your Computer

my-project

        ↓

Git history
```

---

## Remote Repository

Located on GitHub.

Example:

```
GitHub

my-project repository

        ↓

Online storage and collaboration
```

---

# Creating a GitHub Repository

To create a repository:

1. Click the "+" button in GitHub
2. Select:

```
New repository
```

3. Enter repository information:

Example:

```
Repository name:

my-first-project
```

Choose:

- Public
- Private

Then click:

```
Create repository
```

---

# Connecting Local Git to GitHub

After creating a GitHub repository, connect it with your local project.

Example:

```
Local Repository

        ↓

git remote

        ↓

GitHub Repository
```

Add remote connection:

```
git remote add origin repository_url
```

Example:

```
git remote add origin https://github.com/username/project.git
```

---

# First Push to GitHub

After connecting the repository:

Upload your local commits:

```
git push -u origin main
```

The workflow becomes:

```
Edit files

↓

git add

↓

git commit

↓

git push

↓

GitHub Repository
```

---

# Understanding Pull

The opposite operation is:

```
git pull
```

It downloads changes from GitHub.

Example:

```
GitHub

↓

git pull

↓

Your Computer
```

This becomes important when working with others.

---

# GitHub Workflow Summary

The complete workflow:

```
Create Files

↓

Git Commit

↓

Push to GitHub

↓

Share and Collaborate
```

---

# Useful Links

## GitHub Resources

GitHub Official Website:

https://github.com/

GitHub Documentation:

https://docs.github.com/

GitHub Signup:

https://github.com/signup

---

# Summary

In this chapter, you learned:

- What GitHub is
- How to create a GitHub account
- What repositories are
- The difference between local and remote repositories
- How to connect Git with GitHub
- How to push a project online

In the next chapter, you will learn how branches allow different versions of a project to develop safely.
