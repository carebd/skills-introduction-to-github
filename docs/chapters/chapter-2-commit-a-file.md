---
layout: default
title: "Step 2: Commit a File"
parent: Hands-On Exercises
nav_order: 2
---

# Step 2: Commit a File
{: .no_toc }

_You created a branch!_ 🎉
{: .fs-5 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## What is a Commit?

A **commit** is a set of changes to the files and folders in your project. Every commit lives on a branch, and each one records:

- **What** changed (files and lines)
- **When** (timestamp)
- **Who** made the change (author)
- **Why** (commit message)

Think of commits as save points — you can always look back at or restore any previous commit.

{: .note }
> `.md` is a file extension for **Markdown** files — a lightweight markup language for formatting text. Learn more: [Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

📖 Learn more: [About commits](https://docs.github.com/en/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/about-commits)

---

## 🎯 Activity: Your First Commit

Now that you have a branch, let's create a file and make your first commit!

### Step-by-step instructions

**1.** In the **`< > Code`** tab of your repository, make sure you're on the `my-first-branch` branch (check the branch dropdown).

**2.** Click the **Add file** drop-down button and select **Create new file**.

**3.** In the **Name your file...** field, enter:

```
PROFILE.md
```

**4.** In the **Enter file contents here** area, paste the following:

```markdown
Welcome to my GitHub profile!
```

**5.** Click **Commit changes...** in the upper-right corner. A dialog box will appear.

**6.** In the **Commit message** field, replace the default message with:

```
Add PROFILE.md
```

{: .tip }
> A good commit message briefly explains *what* changed and *why*. This is especially helpful when working in teams or revisiting old code.

**7.** Leave the other options as-is and click **Commit changes**.

**8.** GitHub Actions will detect your commit and validate your progress. Keep an eye on the pull request comments for your next instructions.

---

## 📝 About Commit Messages

Writing clear commit messages is a professional habit. Here are some guidelines:

| ✅ Good | ❌ Avoid |
|--------|---------|
| `Add PROFILE.md with welcome message` | `stuff` |
| `Fix typo in README` | `asdfgh` |
| `Update nav links in header` | `changes` |

A common convention is to start with an **imperative verb**: *Add*, *Fix*, *Update*, *Remove*, *Refactor*.

---

## ✅ What You Accomplished

After this step, you have:

- Created a new Markdown file called `PROFILE.md`
- Written your first commit with a clear commit message
- Learned what commits are and why they matter

---

<details markdown="block">
<summary>Having trouble? 🤷</summary>

If you don't get feedback after a minute or two, check the following:

- Make sure you're on the `my-first-branch` branch (not `main`).
- Confirm the file is named exactly `PROFILE.md` (uppercase, `.md` extension).
- Ensure the file is in the **root folder** of the repository, not inside a subfolder.

</details>

---

[← Step 1: Create a Branch](chapter-1-create-a-branch){: .btn } [Next: Step 3 — Open a Pull Request →](chapter-3-open-a-pull-request){: .btn .btn-primary }
