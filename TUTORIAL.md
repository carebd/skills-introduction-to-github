# Introduction to GitHub — A Complete Tutorial

<p align="center">
  <img src="https://octodex.github.com/images/original.png" alt="Octocat" width="200">
</p>

<p align="center"><em>Your step-by-step guide to getting started with GitHub</em></p>

---

**Author:** _[Your Name Here]_
**Date:** _[Date]_
**License:** MIT

> ✏️ **Note to author:** Replace the fields above with your full identity before publishing.

---

## Table of Contents

1. [What is GitHub?](#1-what-is-github)
2. [Key Concepts](#2-key-concepts)
3. [Step 1 — Create a Repository](#3-step-1--create-a-repository)
4. [Step 2 — Create a Branch](#4-step-2--create-a-branch)
5. [Step 3 — Make a Commit](#5-step-3--make-a-commit)
6. [Step 4 — Open a Pull Request](#6-step-4--open-a-pull-request)
7. [Step 5 — Merge a Pull Request](#7-step-5--merge-a-pull-request)
8. [Recap and Next Steps](#8-recap-and-next-steps)
9. [Additional Resources](#9-additional-resources)

---

## 1. What is GitHub?

GitHub is a collaboration platform that uses [Git](https://docs.github.com/get-started/quickstart/github-glossary#git) for version control. It is the most popular place in the world to share and contribute to [open-source](https://docs.github.com/get-started/quickstart/github-glossary#open-source) software — and it's also widely used by companies, teams, and individuals to manage private projects.

At its core, GitHub provides:

- **Version control** — Track every change made to your code over time.
- **Collaboration** — Work with others through branches, pull requests, and code reviews.
- **Project management** — Organize work with issues, project boards, and milestones.
- **Community** — Discover projects, follow developers, and contribute to open source.

🎥 [Watch: What is GitHub? (Video)](https://www.youtube.com/watch?v=pBy1zgt0XPc)

---

## 2. Key Concepts

Before diving in, let's define the core terms you'll encounter throughout this tutorial.

### Repository

A [repository](https://docs.github.com/get-started/quickstart/github-glossary#repository) (or "repo") is a project containing files, folders, and the entire revision history of those files. Repositories can be public (visible to everyone) or private (visible only to you and collaborators).

For more details, see [About repositories](https://docs.github.com/en/repositories/creating-and-managing-repositories/about-repositories).

### Branch

A [branch](https://docs.github.com/en/get-started/quickstart/github-glossary#branch) is a parallel version of your repository. By default, every repository has one branch named `main`, which is considered the definitive branch. You create additional branches to work on features or fixes without affecting the main project.

Key points about branches:

- Branches isolate your work from the `main` branch.
- Everyone's work stays safe while you contribute.
- You can have multiple branches at the same time for different features.

For more details, see [About branches](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches).

### Commit

A [commit](https://docs.github.com/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/about-commits) is a set of changes to files and folders in your project. Each commit is a snapshot that records what changed, who changed it, and when. Commits exist within a branch and build a clear history of your project.

For more details, see [About commits](https://docs.github.com/en/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/about-commits).

### Pull Request

A [pull request](https://docs.github.com/en/get-started/quickstart/github-glossary#pull-request) (PR) is a proposal to merge changes from one branch into another. Pull requests are the heart of collaboration on GitHub — they allow team members to review code, discuss changes, and approve or request modifications before merging.

For more details, see [About pull requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests).

### Merge

A [merge](https://docs.github.com/en/get-started/quickstart/github-glossary#merge) takes the changes from one branch and applies them to another. Once a pull request is approved, you merge it to integrate your work into the `main` branch.

For more details, see [Merging a pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/incorporating-changes-from-a-pull-request/merging-a-pull-request).

### Markdown

[Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) is a lightweight markup language used on GitHub for README files, issues, pull request descriptions, and comments. Files ending in `.md` are Markdown files.

---

## 3. Step 1 — Create a Repository

A repository is the foundation of any project on GitHub.

### How to create a repository

1. Click the **+** icon in the top-right corner of any GitHub page and select **New repository**.
2. Choose a **repository name**. Keep it short and descriptive.
3. Optionally, add a **description** of your project.
4. Choose the visibility: **Public** or **Private**.
5. Check **Add a README file** to initialize the repository with a README.
6. Click **Create repository**.

> 💡 **Tip:** A good README explains what your project does, how to use it, and how to contribute.

---

## 4. Step 2 — Create a Branch

Branches let you work on new features or fixes without affecting the main codebase.

### How to create a branch

1. Navigate to the **< > Code** tab of your repository.
2. Click the **main** branch dropdown at the top-left of the file list.
3. Type a name for your new branch (e.g., `my-first-branch`) in the text field.
4. Click **Create branch: my-first-branch from main**.

Your repository now has two branches: `main` and `my-first-branch`. They are identical at this point, but that will change as you make edits.

> 💡 **Tip:** Use descriptive branch names like `feature/add-login`, `fix/header-bug`, or `docs/update-readme`.

---

## 5. Step 3 — Make a Commit

Now that you have a branch, it's time to make changes and record them with a commit.

### How to commit a file

1. Make sure you're on your new branch (e.g., `my-first-branch`).
2. Click **Add file** → **Create new file**.
3. Name the file (e.g., `PROFILE.md`).
4. Add content to the file. For example:
   ```
   Welcome to my GitHub profile!
   ```
5. Click **Commit changes...** in the upper-right corner.
6. Enter a clear commit message (e.g., `Add PROFILE.md`).
7. Click **Commit changes**.

### Writing good commit messages

A good commit message explains *what* changed and *why*. Follow these conventions:

- **Keep the subject line under 50 characters.**
- **Use the imperative mood** (e.g., "Add feature" not "Added feature").
- **Optionally add a body** with more detail, separated by a blank line.

Example:

```
Add PROFILE.md

Created an introductory profile page with a welcome message.
```

---

## 6. Step 4 — Open a Pull Request

A pull request tells your collaborators about the changes you've made and invites them to review and discuss.

### How to open a pull request

1. Navigate to the **Pull requests** tab of your repository.
2. Click **New pull request**.
3. Set the **base** branch to `main` and the **compare** branch to your feature branch (e.g., `my-first-branch`).
4. Click **Create pull request**.
5. Enter a descriptive **title** (e.g., `Add my first file`).
6. Write a **description** summarizing your changes.
7. Click **Create pull request**.

### Pull request best practices

- **Write a clear title** that summarizes the change.
- **Describe what you did and why** in the description.
- **Reference related issues** using `#issue-number` (e.g., `Closes #42`).
- **Request reviewers** to get feedback before merging.
- **Keep pull requests small** — smaller PRs are easier to review.

---

## 7. Step 5 — Merge a Pull Request

Once your pull request has been reviewed and approved, it's time to merge.

### How to merge

1. Navigate to your pull request.
2. Click **Merge pull request**.
3. Click **Confirm merge**.
4. Once merged, click **Delete branch** to clean up.

> 💡 **Tip:** Deleting a branch after merging keeps your repository tidy. The commit history is preserved in `main`.

### Merge strategies

GitHub supports several merge strategies:

| Strategy | Description |
|---|---|
| **Merge commit** | Creates a merge commit that joins the branch history into `main`. |
| **Squash and merge** | Combines all commits into a single commit before merging. |
| **Rebase and merge** | Re-applies commits on top of `main` for a linear history. |

---

## 8. Recap and Next Steps

Congratulations! 🎉 You've learned the GitHub fundamentals:

| Concept | What You Learned |
|---|---|
| **Repository** | A project containing your files and their history |
| **Branch** | A parallel version for safe, isolated work |
| **Commit** | A snapshot of changes to your files |
| **Pull Request** | A proposal to merge changes with discussion and review |
| **Merge** | Integrating your changes into the main branch |

### Next steps to continue learning

1. **Create a profile README** — Make a public repo with the same name as your GitHub username and add a `README.md`. It will appear on your profile page! See [Managing your profile README](https://docs.github.com/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme).

2. **Try more GitHub Skills exercises** — Visit [GitHub Skills](https://skills.github.com/) for hands-on courses on topics like GitHub Pages, Actions, and more.

3. **Explore open source** — Browse [GitHub Explore](https://github.com/explore) to find projects that interest you and make your first open-source contribution.

4. **Learn Git on the command line** — While this tutorial used the GitHub web interface, learning Git commands gives you more power and flexibility. See [Git Handbook](https://docs.github.com/en/get-started/using-git/about-git).

---

## 9. Additional Resources

- 📖 [GitHub Getting Started Documentation](https://docs.github.com/en/get-started)
- 🎓 [GitHub Skills](https://skills.github.com/)
- 🎓 [GitHub Student Developer Pack](https://education.github.com/pack)
- 📝 [Markdown Guide](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- 💬 [GitHub Community Discussion](https://github.com/orgs/community/discussions)
- 🌐 [GitHub Explore](https://github.com/explore)

---

<p align="center">
  <img src="https://octodex.github.com/images/collabocats.jpg" alt="Collaboration" width="250">
</p>

<p align="center"><strong>Happy coding! 🚀</strong></p>

---

_This tutorial was created as part of the [GitHub Skills: Introduction to GitHub](https://github.com/skills/introduction-to-github) exercise._

_© 2025 — Licensed under the [MIT License](https://gh.io/mit)_
