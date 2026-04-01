# Step 3: Create a Branch

**Previous step:** [Step 2 - Open the Editor](02-open-editor.md)
**Next step:** [Step 4 - Add and Stage Files](04-add-stage.md)

---

## What Is a Branch?

A **branch** is a parallel timeline of your code.

Imagine you are writing a paper and you want to try a completely different introduction. Instead of deleting your current one and hoping you remember it, you make a photocopy. You write on the copy, and if you like it, you swap it in. If you hate it, throw away the copy — your original is untouched.

Branches work like that. You can have many branches at once and switch between them instantly.

### The `main` Branch

Every repository has a default branch called `main`. Think of it as the "official" version — the one that is always stable. You never work directly on `main`. Instead, you create a new branch for each piece of work, do your work there, and then merge it back into `main` when it is ready.

This is how professional developers work every day.

---

## Your Task: Create a Branch

You need to create a branch called exactly **`add-about-me`**. This name is important — the automated check looks for it.

### In the github.dev Editor

1. Look at the **bottom-left corner** of the editor. You will see the current branch name — it says `main`.
2. Click on `main`.
3. A menu appears at the top of the screen. Click **"Create new branch..."**.
4. Type `add-about-me` and press Enter.
5. A prompt asks "Switch to branch 'add-about-me'?" — click **Switch to Branch**.

The bottom-left corner now shows `add-about-me`. You are on your new branch.

---

### Using the GitHub Website Instead

If you prefer to create the branch on the GitHub website before opening the editor:

1. On your fork's main page, find the **branch dropdown** — a button near the top-left that says `main`.
2. Click it, then type `add-about-me` in the text box.
3. Click **"Create branch: add-about-me from main"**.
4. Then press `.` to open the editor — it will open on your new branch automatically.

---

## Branch Naming Tips

Good branch names are:
- **Lowercase** with hyphens between words (`add-about-me`, not `Add About Me`)
- **Short and descriptive** — someone should be able to guess what the branch is for
- **Action-oriented** — start with a verb like `add-`, `fix-`, `update-`

Avoid generic names like `my-branch`, `test`, or `stuff`.

---

> **CLI Alternative (optional, for the curious)**
>
> In a terminal, the equivalent command is:
> ```bash
> git checkout -b add-about-me
> ```
> This creates the branch and switches to it in one step. To verify:
> ```bash
> git branch
> ```
> The branch with `*` next to it is the one you are on.

---

**You completed Step 3!** Head to [Step 4 - Add and Stage Files](04-add-stage.md).
