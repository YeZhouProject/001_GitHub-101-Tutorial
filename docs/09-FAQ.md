# Frequently Asked Questions

This chapter collects common questions from Git and GitHub beginners.

---

# Git and GitHub

## Q: What is the difference between Git and GitHub?

Git and GitHub are related but different.

Git:

- A version control system
- Runs on your computer
- Records project history

GitHub:

- An online platform
- Stores Git repositories
- Supports collaboration

A simple workflow:

```
Edit Files

↓

Git

↓

GitHub
```

---

## Q: Do I need GitHub to use Git?

No.

Git can work completely offline.

Example:

```
Your Computer

Project

↓

Git History
```

GitHub is used when you want to:

- Backup projects online
- Share projects
- Collaborate with others

---

# Repository Management

## Q: Why does Git not upload empty folders?

Git tracks files, not folders.

For example:

```
project

├── README.md
└── images
```

If `images` contains no files, Git ignores it.

A common solution is creating:

```
.gitkeep
```

Example:

```
images

└── .gitkeep
```

This keeps the folder in Git.

---

## Q: What is the difference between local and remote repositories?

Local repository:

```
Your Computer

↓

Git history
```

Remote repository:

```
GitHub

↓

Online copy
```

They are connected through commands:

```
git push

git pull
```

---

# Markdown and Documentation

## Q: Why should I preview Markdown before committing?

Markdown is converted into formatted content when displayed on GitHub.

Before committing, preview your document to check:

- Heading levels
- Code blocks
- Tables
- Links
- Images
- Page structure

Recommended workflow:

```
Edit Markdown

↓

Preview

↓

Check formatting

↓

Commit

↓

Push
```

---

## Q: How can I preview Markdown in VS Code?

Open the Markdown file.

Use:

Windows:

```
Ctrl + Shift + V
```

macOS:

```
Command + Shift + V
```

You can also use the preview button in the top-right corner.

---

# Commit Workflow

## Q: Why do commit messages matter?

Commit messages describe project history.

Good:

```
docs: add Git installation chapter

fix: correct broken link

feat: add website homepage
```

Bad:

```
update

change

test
```

Clear commit messages make projects easier to maintain.

---

## Q: What does "docs:" mean in a commit message?

It is a commit type.

Example:

```
docs: add VS Code chapter
```

means:

- The change is documentation-related
- A new tutorial document was added

Common types:

```
docs: Documentation

feat: New feature

fix: Bug correction

style: Formatting changes
```

---

# VS Code Workflow

## Q: Should I edit GitHub files in the browser or VS Code?

Both methods are possible.

GitHub Web Editor:

Advantages:

- Simple
- No installation required

VS Code:

Advantages:

- Better for larger projects
- Better file management
- Integrated terminal
- Professional workflow

Recommended workflow:

```
VS Code

↓

Git

↓

GitHub
```

---

## Q: Why use VS Code Preview?

Preview helps confirm that Markdown will display correctly before committing.

It prevents:

- Broken formatting
- Missing sections
- Incorrect links

---

# Common Errors

## Q: Why did my push fail?

Common reasons:

- Internet connection problem
- Authentication issue
- Remote repository mismatch
- Local changes conflict with GitHub

Useful commands:

Check status:

```
git status
```

Check remote:

```
git remote -v
```

Download latest changes:

```
git pull
```

---

## Q: Why can't I see my changes on GitHub?

Check:

1. Did you commit?

```
git commit
```

2. Did you push?

```
git push
```

3. Did you refresh the GitHub page?

---

## Q: Why does GitHub Pages show a 404 page after deployment?

If GitHub Pages has been deployed successfully but visiting the website shows a **404 Not Found** page, check the following items.

### Possible Causes

- There is no `index.md` or `index.html` in the publishing directory.
- GitHub Pages is configured to use the wrong branch or folder.
- The website is still being deployed (wait a few minutes after saving the settings).
- The homepage file is not located in the root of the publishing directory.

### Correct Structure

```
Repository

├── README.md
│
└── docs
    ├── index.md
    ├── 01-Introduction.md
    ├── 02-Git-Installation.md
    ├── 03-VSCode.md
    └── ...
```

### Incorrect Structure

```
Repository

└── docs
    └── tutorial
        ├── index.md
        └── ...
```

GitHub Pages only looks for the homepage in the **root of the publishing directory**.

### Solution Checklist

If your GitHub Pages source is set to:

```
Branch: main
Folder: /docs
```

Make sure that:

- `index.md` is directly inside the `docs` folder.
- The publishing source is correctly set to `main` and `/docs`.
- The deployment has completed successfully (green status).
- Wait 1–2 minutes after deployment before refreshing the page.

Once the homepage is in the correct location, GitHub Pages should load the website normally.

---

### Learning Tip

A successful deployment does **not** always mean the homepage exists.

GitHub Pages needs an entry page (`index.md` or `index.html`) to display your website. Without it, visitors may see a **404 Not Found** page even though the deployment itself succeeded.

# Learning Tips

## Start Small

A good learning project:

```
README.md

↓

Documentation

↓

Small Projects

↓

Collaboration
```

---

## Practice the Complete Workflow

The most important habit:

```
Create

↓

Edit

↓

Preview

↓

Commit

↓

Push

↓

Review
```

---

# Summary

Git and GitHub are not only tools.

They represent a professional workflow for managing knowledge and projects.

By understanding:

- Git basics
- GitHub repositories
- Branches
- Collaboration
- Documentation publishing

you can build, manage, and share real projects online.
