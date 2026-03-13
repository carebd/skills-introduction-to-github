---
layout: default
title: "Step 4: Merge Your Pull Request"
parent: Hands-On Exercises
nav_order: 4
---

# Step 4: Merge Your Pull Request
{: .no_toc }

_Nicely done!_ 😎
{: .fs-5 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## What is a Merge?

A **merge** takes the changes from your branch and adds them to the target branch (usually `main`). Once your pull request is approved and all checks have passed, you can merge it.

```
main ──────────────────────────────────────►
           │                          ▲
           └─► my-first-branch ───────┘
                   (merged in!)
```

When you merge, GitHub:
1. Applies all commits from your branch to `main`
2. Creates a **merge commit** that records the event
3. Closes the pull request automatically

📖 Learn more: [Merging a pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/incorporating-changes-from-a-pull-request/merging-a-pull-request)

---

## 🎯 Activity: Merge the Pull Request

### Step-by-step instructions

**1.** Scroll to the bottom of your pull request page and click **Merge pull request**.

{: .note }
> If the merge button is grayed out, check if any required workflows or checks are still running. Wait for them to complete.

**2.** Click **Confirm merge** to complete the merge.

{: .tip }
> Notice the confirmation dialog looks similar to the commit dialog! That's because a merge is itself a kind of commit — it records the moment your branches were combined.

**3.** After the merge is confirmed, click **Delete branch** to clean up your `my-first-branch` branch.

   - It's good practice to delete branches after merging — it keeps your repository tidy.
   - Don't worry, all your commits are preserved in `main`.

**4.** GitHub Actions will confirm your completed merge and post final feedback in the pull request comments. 🎉

---

## 🔀 Types of Merges

GitHub supports three merge strategies:

| Strategy | Description | When to use |
|----------|-------------|-------------|
| **Merge commit** | Creates a merge commit preserving full history | Default for most PRs |
| **Squash and merge** | Combines all commits into one | Clean up a messy commit history |
| **Rebase and merge** | Replays commits on top of base branch | Linear history preference |

For this exercise, the default **Merge commit** is used.

---

## ✅ What You Accomplished

After this step, you have:

- Merged your first pull request into `main`
- Learned what a merge is and how it works
- Cleaned up your branch after merging

---

<details markdown="block">
<summary>Having trouble? 🤷</summary>

If you don't get feedback after a minute or two, check the following:

- Make sure the previous steps (branch creation, commit, and PR) were all completed successfully.
- If the merge button is disabled, wait for any running workflows to finish.
- Check the [Actions tab]({{ site.github.repository_url }}/actions) to see if any workflow failed.

</details>

---

[← Step 3: Open a Pull Request](chapter-3-open-a-pull-request){: .btn } [Next: Review & Next Steps →](review){: .btn .btn-primary }
