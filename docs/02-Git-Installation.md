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

# Installing Git

## Official Git Website

Git can be downloaded from the official Git website:

[Git Official Website](https://git-scm.com/)

Download page:

[Download Git](https://git-scm.com/downloads)

Always download Git from the official source to ensure security and reliability.

---

## Windows Installation

For Windows users:

### Step 1: Download Git for Windows

Open the official download page:

[Git for Windows](https://git-scm.com/download/win)

Download the installer and run the installation program.

---

### Step 2: Install Git

During installation:

- Keep the default settings if you are not sure
- Allow Git to install Git Bash
- Allow Git to be added to the system PATH

After installation, Git can be used through:

- Git Bash
- Command Prompt
- PowerShell
- VS Code Terminal

---

## macOS Installation

For macOS users, Git can be installed in several ways.

### Method 1: Official Installer

Visit the official Git download page:

[Git Downloads](https://git-scm.com/downloads)

Download and install the macOS version.

---

### Method 2: Homebrew

If you use Homebrew, you can install Git with:

```
brew install git
```

Homebrew official website:

[Homebrew](https://brew.sh/)

---

## Linux Installation

For Linux users, Git can usually be installed through the system package manager.

Example:

Ubuntu / Debian:

```
sudo apt install git
```

Other Linux distributions may use different package managers.

---

# Checking Git Installation

After installation, open a terminal.

You can use:

- Git Bash (Windows)
- Terminal (macOS/Linux)
- VS Code Terminal

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

# Basic Git Configuration

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

## Why Configure Your Identity?

Every Git commit stores information about:

- Who created the change
- When the change happened
- What was changed

Example:

```
Commit

Author: Your Name
Date: Today

Changed files:
README.md
```

This becomes important when working with others.

---

# Understanding Local Git

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

# Useful Links

## Git Resources

- Git Official Website  
  https://git-scm.com/

- Git Download Page  
  https://git-scm.com/downloads

- Git Documentation  
  https://git-scm.com/doc

## Additional Tools

- Homebrew (macOS package manager)  
  https://brew.sh/

---

# Summary

In this chapter, you learned:

- What Git is
- Why Git is needed before using GitHub
- How to install Git
- Where to download Git safely
- How to check Git installation
- How to configure your Git identity

In the next chapter, you will learn how to use VS Code as your project editing environment.
