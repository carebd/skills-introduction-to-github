---
layout: default
title: "Step 3: Open a Pull Request"
parent: Hands-On Exercises
nav_order: 3
---

# Step 3: Open a Pull Request
{: .no_toc }

_Nice work making that commit!_ ✨
{: .fs-5 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## What is a Pull Request?

A **pull request** (PR) is how you propose changes from your branch to another branch (usually `main`). It gives other developers a chance to review, comment on, and approve your changes before they're merged.

In a side-by-side comparison, a pull request shows:
- The **base branch** — where you want the changes to go (e.g., `main`)
- The **compare branch** — where your changes currently live (e.g., `my-first-branch`)

```
my-first-branch ──[Pull Request]──► main
```

Collaboration happens on pull requests. They are the central place for:

- Code review and discussion
- Requesting changes or approvals
- Viewing the complete diff of changes
- Running automated checks (CI/CD)

📖 Learn more: [About pull requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)

---

## 🎯 Activity: Create a Pull Request

After your commit, GitHub may show a banner at the top of your repository suggesting you compare and open a pull request. You can use that shortcut, or follow the steps below manually.

### Option A: Quick path (recommended)

After creating your commit, look for the **"Compare & pull request"** button that appears in a yellow banner near the top of your repository page. Click it and skip to **Step 5** below.

### Option B: Manual path

**1.** Click the **Pull requests** tab in your repository header.

**2.** Click the **New pull request** button.

**3.** Set the branch dropdowns:
   - **base:** `main`
   - **compare:** `my-first-branch`

**4.** Click **Create pull request**.

### Completing the pull request form

**5.** Set the **title** to:

```
Add my first file
```

**6.** In the **description** field, briefly describe what you've done so far. For example:

```
Added PROFILE.md with a welcome message on my-first-branch.
```

{: .tip }
> Descriptions help your teammates understand the context behind a change. Get in the habit of writing them — even for small changes.

**7.** Click **Create pull request**.

**8.** GitHub Actions will validate your pull request. Watch the comments for your next instructions.

---

## 🔍 Anatomy of a Pull Request

Once opened, your pull request page includes several important sections:

| Section | Purpose |
|---------|---------|
| **Conversation** | Discussion thread, comments, and activity timeline |
| **Commits** | List of all commits included in this PR |
| **Files changed** | Line-by-line diff of every file modified |
| **Checks** | Status of automated tests and CI workflows |

---

## ✅ What You Accomplished

After this step, you have:

- Opened your first pull request
- Learned what pull requests are and how they enable collaboration
- Practiced writing a PR title and description

---

<details markdown="block">
<summary>Having trouble? 🤷</summary>

If you don't get feedback after a minute or two, check the following:

- Make sure the pull request title is exactly `Add my first file`.
- Ensure the pull request has a description for this exercise (the workflow checks for one).
- Confirm the base branch is `main` and the compare branch is `my-first-branch`.

</details>

---

[← Step 2: Commit a File](chapter-2-commit-a-file){: .btn } [Next: Step 4 — Merge Your Pull Request →](chapter-4-merge-your-pull-request){: .btn .btn-primary }
