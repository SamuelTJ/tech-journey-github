# Step 5: Commit Your Changes

**Previous step:** [Step 4 - Create Your File](04-add-stage.md)
**Next step:** [Step 6 - Open a Pull Request](06-pull-request.md)

---

## What Is a Commit?

A **commit** is a snapshot saved in git's history — a labeled save point that you can return to at any time.

Every commit has two parts:
1. **The changes** — which files changed and exactly what changed
2. **The commit message** — a short description of *why* you made these changes

Over time, your commit history becomes a log of everything that happened to your project and why. This is incredibly useful when something breaks and you need to trace it back.

When you commit in github.dev, the changes are also **pushed** to GitHub automatically — so your work is saved remotely the moment you commit.

---

## How to Write a Good Commit Message

A commit message should describe what changed, not just say "stuff" or "changes." Here are some examples:

| Bad | Better |
|-----|--------|
| `stuff` | `Add about-me file` |
| `changes` | `Update introduction section` |
| `asdfasdf` | `Fix typo in README` |
| `final` | `Complete step 4 exercise` |

A few conventions professionals follow:
- Use the **imperative mood**: "Add" not "Added", "Fix" not "Fixed"
- Keep it **under 72 characters**
- Capitalize the first word

You do not have to be perfect — the goal is to be clear enough that someone (including future you) can understand what happened.

---

## Your Task: Commit in github.dev

### Step 1: Open Source Control

Click the **Source Control icon** in the left sidebar (it looks like a small node/branch diagram and has a numbered badge showing your staged files).

You will see `exercises/about-me.md` listed under **Changes**.

### Step 2: Write your commit message

At the top of the Source Control panel, there is a text box that says **"Message (Ctrl+Enter to commit)"**.

Type a descriptive message, for example:
```
Add about-me file
```

### Step 3: Commit and push

Click the **Commit & Push** button (the blue button below the message box).

> If you only see a **"Commit"** button, click the dropdown arrow next to it and choose **"Commit & Push"**.

github.dev will save your snapshot and push it to GitHub in one step.

---

## Confirm It Worked

After committing, the Source Control badge should disappear (no more pending changes). You can also:

1. Switch to the GitHub tab in your browser (change `github.dev` to `github.com` in the address bar).
2. Make sure you are on the `add-about-me` branch (check the branch dropdown).
3. You should see `exercises/about-me.md` listed in the repo files.

---

## Check the Automated Validation

1. On your fork on GitHub, click the **Actions** tab.
2. You should see a workflow run called **"Steps 4-5 Check"** triggered by your push.
3. Wait 30-60 seconds for it to finish.
4. A green checkmark means you passed. A red X means something needs fixing — click into the run to read the error message.

---

> **CLI Alternative (optional, for the curious)**
>
> In a terminal, committing and pushing are two separate steps:
> ```bash
> git commit -m "Add about-me file"
> git push origin add-about-me
> ```
> `git commit` saves the snapshot locally. `git push` sends it to GitHub.
> github.dev does both in one click.

---

**You completed Step 5!** Head to [Step 6 - Open a Pull Request](06-pull-request.md).
