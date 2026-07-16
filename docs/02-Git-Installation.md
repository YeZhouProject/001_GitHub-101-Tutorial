# Git Installation

## What is Git?

Git is a distributed version control system that helps users manage changes in their projects.

Before using GitHub, it is important to understand that Git works on your local computer.

Git allows you to:

- Track changes in files
- Save versions of a project
- Compare different versions
- Restore previous versions
- Prepare projects for collaboration

Git is the foundation of the GitHub workflow.

---

## Why Install Git?

GitHub is built around Git.

Although GitHub provides online repositories and collaboration tools, the actual version control system is Git.

A common workflow is:

```
Create files on your computer

        ↓

Use Git to record changes

        ↓

Upload the project to GitHub
```

Therefore, installing Git is the first technical step before working with GitHub.

---

## Installing Git

### Windows

For Windows users:

1. Visit the official Git website.
2. Download the latest Git installer.
3. Run the installer.
4. Keep the default settings unless you have specific requirements.
5. Complete the installation.

After installation, Git can be used through:

- Git Bash
- Command Prompt
- PowerShell
- VS Code Terminal

---

### macOS

For macOS users, Git can be installed in several ways.

Common methods:

- Install through Xcode Command Line Tools
- Install through Homebrew
- Download the official installer

After installation, Git can be accessed through Terminal.

---

## Checking Git Installation

After installation, open a terminal.

Run:

```
git --version
```

If Git is installed successfully, you will see a version number.

Example:

```
git version 2.xx.x
```

This means Git is ready to use.

---

## Basic Git Configuration

Before creating projects, Git needs basic user information.

Configure your name:

```
git config --global user.name "Your Name"
```

Configure your email:

```
git config --global user.email "your_email@example.com"
```

These settings help Git identify who created each change.

You can check your configuration with:

```
git config --list
```

---

## Understanding Local Git

At this stage, Git exists only on your computer.

Example:

```
Your Computer

Project Folder

      |
      |
      Git

Version History
```

Nothing has been uploaded to GitHub yet.

The connection between Git and GitHub will be introduced later.

---

## Summary

In this chapter, you learned:

- What Git is
- Why Git is needed before using GitHub
- How to install Git
- How to check Git installation
- How to configure your Git identity

In the next chapter, you will learn how to use VS Code as your project editing environment.
