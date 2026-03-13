---
layout: default
title: "Step 1: Create a Branch"
parent: Hands-On Exercises
nav_order: 1
---

# Step 1: Create a Branch
{: .no_toc }

_Welcome to "Introduction to GitHub"!_ 👋
{: .fs-5 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## What is a Branch?

A **branch** is a parallel version of your repository. By default, your repository has one branch named `main` — this is the definitive, production-ready branch.

Creating a new branch lets you **copy `main` and safely make changes** without disrupting the main project. It's like making a copy of a document to edit while keeping the original safe.

```
main ─────────────────────────────────────► (stable code)
          │
          └─► my-first-branch ────────────► (your changes)
```

{: .note }
> Many people use branches to work on specific features or bug fixes without affecting any other parts of the project. Everyone's work stays safe while you contribute.

📖 Learn more: [About branches](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches)

---

## What is a Profile README?

A [profile README](https://docs.github.com/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme) is an "About me" section on your GitHub profile. GitHub shows it at the top of your profile page — it's a great way to share information about yourself with the community.

In this exercise, you'll create a short Markdown file that you can later use as your profile README.

---

## 🎯 Activity: Your First Branch

Follow these steps to create your first branch on GitHub.

### Step-by-step instructions

**1.** Open a new browser tab and navigate to your copy of this exercise repository. Work on the steps in that tab while you read instructions here.

**2.** Navigate to the **`< > Code`** tab in the header menu of your repository.

**3.** Click on the **`main`** branch drop-down button.

**4.** In the **Find or create a branch...** text box, type:

```
my-first-branch
```

{: .important }
> The branch name must be exactly `my-first-branch` — no spaces, no prefixes, no suffixes.

**5.** Click **Create branch: `my-first-branch` from main** to create your branch.

- The branch will automatically switch to the one you just created.
- The branch drop-down will display your new branch name.

**6.** GitHub Actions will detect your new branch and validate your progress. Give it a moment — you'll see a comment appear with your next instructions.

---

## ✅ What You Accomplished

After this step, you have:

- Created a new branch named `my-first-branch`
- Learned how branches isolate your work from the `main` branch

---

<details markdown="block">
<summary>Having trouble? 🤷</summary>

If you don't get feedback after a minute or two, check the following:

- Make sure the branch is named exactly `my-first-branch` (all lowercase, hyphens, no spaces).
- Navigate to the [Actions tab]({{ site.github.repository_url }}/actions) to check if a workflow is running or has failed.

</details>

---

[← Key Concepts](../introduction/key-concepts){: .btn } [Next: Step 2 — Commit a File →](chapter-2-commit-a-file){: .btn .btn-primary }
