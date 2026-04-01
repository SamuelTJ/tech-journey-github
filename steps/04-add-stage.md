# Step 4: Create Your File

**Previous step:** [Step 3 - Create a Branch](03-branch.md)
**Next step:** [Step 5 - Commit Your Changes](05-commit.md)

---

## The Staging Area

Git does not automatically save every change you make. Before you can save a snapshot (a "commit"), you have to tell git which changes to include. This is called **staging**.

Think of it like packing a box to ship:
- Staging puts items in the box.
- Committing (next step) seals the box and writes a label on it.
- You can add and remove items from the box before you seal it.

This two-step process lets you make multiple changes and choose exactly which ones to save together — keeping your history clean and organized.

### The Three States of a File

| State | Meaning |
|-------|---------|
| **Untracked** | Git sees the file exists but is not watching it |
| **Staged** | The file is in the "box" ready to be committed |
| **Committed** | The file has been saved as a snapshot in git's history |

In github.dev, staging happens automatically when you save a file — any modified file shows up in the Source Control panel ready to be included in your next commit.

---

## Your Task: Create Your About Me File

### Step 1: Open the exercises folder

In the github.dev editor, look at the **file explorer** on the left sidebar. Click the `exercises` folder to expand it.

You will see `README.md` and `about-me-template.md` inside. Open `about-me-template.md` to use as a reference.

### Step 2: Create a new file

1. Hover over the `exercises` folder in the sidebar.
2. Click the **New File** icon (it looks like a page with a `+` sign).
3. Type `about-me.md` and press Enter.

The new file opens in the editor. Make sure the path shown at the top says `exercises/about-me.md`.

### Step 3: Add your content

Your file must contain:
1. A line that says `## About Me` (exactly this heading)
2. At least a few lines about yourself

Here is a starter template — paste this in and fill it out:

```markdown
## About Me

**Name:** [Your name or a nickname]

**Why I joined TechJourney:**
[Write 1-2 sentences]

**Something I am interested in:**
[A hobby, subject, game, sport — anything]

**One thing I hope to learn:**
[What do you want to be able to do after this program?]
```

### Step 4: Save the file

Press **Ctrl+S** (Windows/Linux) or **Cmd+S** (Mac) to save.

Once saved, the **Source Control icon** on the left sidebar (the branching icon) will show a badge with the number of changed files — this means your file is staged and ready to commit.

---

## Confirm It Is Staged

Click the **Source Control icon** in the left sidebar. You should see `exercises/about-me.md` listed under **Changes**. This is the github.dev equivalent of the staging area.

If you see your file there, you are ready for the next step.

---

> **CLI Alternative (optional, for the curious)**
>
> In a terminal, after creating the file you would stage it with:
> ```bash
> git add exercises/about-me.md
> ```
> Then verify with:
> ```bash
> git status
> ```
> You would see the file listed under "Changes to be committed."

---

## Automated Check

When you commit and push (Step 5), the **Steps 4-5 Check** workflow runs and verifies:
- `exercises/about-me.md` exists
- It contains the `## About Me` heading
- It has at least 3 lines of content

If something is wrong, the error message in the Actions tab will tell you exactly what to fix.

---

**You completed Step 4!** Head to [Step 5 - Commit Your Changes](05-commit.md).
