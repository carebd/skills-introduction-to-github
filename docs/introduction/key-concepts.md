---
layout: default
title: Key Concepts
parent: Introduction
nav_order: 2
---

# Key Concepts
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

Before you start the exercises, it helps to understand four fundamental concepts in GitHub. Think of them as the building blocks of everything you'll do on the platform.

---

## 📁 Repository

A **repository** (or "repo") is a project containing files and folders. It tracks versions of files and folders so you can see the complete history of changes over time.

Think of a repository as a **project folder** that remembers every change ever made to every file inside it.

```
my-project/
├── README.md
├── index.html
├── style.css
└── script.js
```

A repository can be:
- **Public** — anyone on the internet can see it
- **Private** — only you and invited collaborators can see it

📖 Learn more: [About repositories](https://docs.github.com/en/repositories/creating-and-managing-repositories/about-repositories)

---

## 🌿 Branch

A **branch** is a parallel version of your repository. By default, your repository has one branch named `main`, which is considered the definitive version of your project.

Creating additional branches allows you to **copy the `main` branch and safely make changes** without disrupting the main project. This is like making a photocopy of a document — you can edit the copy while keeping the original intact.

```
main ─────────────────────────────────► (production-ready code)
          │
          └─► my-feature-branch ──────► (work in progress)
```

Common use cases for branches:
- Working on a new feature
- Fixing a bug
- Experimenting with an idea

📖 Learn more: [About branches](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches)

---

## 💾 Commit

A **commit** is a set of changes to the files and folders in your project. A commit always exists in a branch, and it records:

- **What** changed (which files and lines)
- **When** it changed (timestamp)
- **Who** made the change (author)
- **Why** it changed (commit message)

Think of commits as **save points** in a video game — you can always go back to any previous commit if something goes wrong.

```
commit abc1234
Author: Mona Octocat <mona@github.com>
Date:   Mon Mar 10 2025

    Add PROFILE.md with welcome message
```

{: .tip }
> Write clear, descriptive commit messages! A good message explains *why* a change was made, not just *what* was changed.

📖 Learn more: [About commits](https://docs.github.com/en/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/about-commits)

---

## 🔀 Pull Request

A **pull request** (or "PR") is how you propose changes from one branch to another. It shows the changes you made in your branch and allows others to:

- Review and comment on your code
- Request changes before merging
- Approve and merge your changes into the `main` branch

Pull requests are the heart of GitHub collaboration — they create a space for discussion, review, and feedback.

```
my-feature-branch ──[Pull Request]──► main
```

A pull request includes:
- A **title** describing the change
- A **description** explaining the context and purpose
- A **diff** showing exactly what changed
- A **review** section for comments and approvals

📖 Learn more: [About pull requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)

---

## 🔁 How It All Fits Together

Here's the typical GitHub workflow combining all four concepts:

```
1. Create a REPOSITORY to hold your project
          │
          ▼
2. Create a BRANCH to work on a change
          │
          ▼
3. Make COMMITS to record your progress
          │
          ▼
4. Open a PULL REQUEST to propose the change
          │
          ▼
5. Review, discuss, and MERGE into main
```

This workflow — often called **GitHub Flow** — is used by millions of developers and teams every day.

---

## Ready to Practice?

Now that you know the theory, let's put it into practice! The next section walks you through each step hands-on.

[Next: Step 1 — Create a Branch →](../chapters/chapter-1-create-a-branch){: .btn .btn-primary }
