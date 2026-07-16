# Introduction to VS Code

## What is VS Code?

Visual Studio Code (VS Code) is a free and powerful source code editor developed by Microsoft.

It is widely used for:

- Software development
- Web development
- Data science
- Documentation writing
- Markdown editing
- Project management

Official website:

[Visual Studio Code](https://code.visualstudio.com/)

---

## Why Use VS Code?

Git manages project history, but Git does not edit files.

A complete workflow usually requires:

```
Create and edit files

        ↓

Use Git to record changes

        ↓

Upload to GitHub
```

VS Code provides the environment where you create and manage project files.

---

## Installing VS Code

### Step 1: Download VS Code

Visit the official download page:

[Download Visual Studio Code](https://code.visualstudio.com/download)

Choose the version for your operating system:

- Windows
- macOS
- Linux

---

### Step 2: Install VS Code

During installation:

- Accept the license agreement
- Keep default options if you are unsure
- Enable useful options such as:
  - Add "Open with Code" action
  - Add VS Code to PATH

After installation, open VS Code.

---

# Understanding the VS Code Interface

The main VS Code interface contains several important areas.

```
--------------------------------
| Menu                         |
--------------------------------
| Explorer | Editor             |
|          |                    |
| Files    | Document           |
|          |                    |
--------------------------------
| Terminal                     |
--------------------------------
```

---

## Explorer

The Explorer shows your project files.

Example:

```
My Project

├── README.md
├── docs
│   ├── 01-Introduction.md
│   └── 02-Git-Installation.md
└── images
```

It allows you to:

- Open files
- Create folders
- Rename files
- Manage project structure

---

## Editor Area

The editor area is where you modify files.

For example:

Markdown file:

```
# My Project

This is my first document.
```

VS Code provides:

- Syntax highlighting
- Auto-completion
- Search and replace
- File comparison

---

# Opening a Project Folder

A project in VS Code is usually a folder.

Example:

```
my-first-project

├── README.md
├── src
└── docs
```

To open a project:

1. Open VS Code
2. Select:

```
File → Open Folder
```

3. Choose your project folder

After opening, VS Code will display the complete project structure.

---

# Editing Markdown Files

Markdown is a simple format used for writing documents.

GitHub uses Markdown extensively.

Example:

```markdown
# Title

This is a paragraph.

## Subtitle

- Item 1
- Item 2
```

VS Code supports Markdown preview.

You can open preview with:

```
Ctrl + Shift + V
```

Windows:

```
Ctrl + Shift + V
```

macOS:

```
Command + Shift + V
```

---

# Using the Integrated Terminal

VS Code includes a built-in terminal.

You can open it through:

```
Terminal → New Terminal
```

The terminal allows you to run commands without leaving VS Code.

Example:

```
git --version
```

The integrated terminal will become the main place where you use Git commands in later chapters.

---

# Recommended Extensions

VS Code supports extensions that add new functions.

For beginners, useful extensions include:

## Markdown All in One

Features:

- Markdown shortcuts
- Better editing experience
- Automatic formatting

Extension marketplace:

[VS Code Extensions](https://marketplace.visualstudio.com/vscode)

---

# VS Code in the GitHub Workflow

After this chapter, your workflow becomes:

```
VS Code

Create and edit files

        ↓

Git

Record changes

        ↓

GitHub

Share and collaborate
```

This workflow is the foundation of modern software and documentation projects.

---

# Useful Links

## VS Code Resources

- Official Website  
  https://code.visualstudio.com/

- Download VS Code  
  https://code.visualstudio.com/download

- Official Documentation  
  https://code.visualstudio.com/docs

- VS Code Extensions Marketplace  
  https://marketplace.visualstudio.com/vscode

---

# Summary

In this chapter, you learned:

- What VS Code is
- Why VS Code is useful
- How to install VS Code
- How to open a project folder
- How to edit Markdown files
- How to use the integrated terminal

In the next chapter, you will learn the basic concepts and commands of Git.
