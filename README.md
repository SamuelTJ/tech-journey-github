# TechJourney: Learn Git and GitHub

Git is used by every professional software developer in the world. In this curriculum, you will learn how to use it too — from your first command all the way to opening a real Pull Request on GitHub.

---

## Before You Start

**You need two things:**

1. **A GitHub account** — Create a free one at [github.com](https://github.com) if you do not have one yet.
2. **A computer** — Any operating system works: Mac, Windows, or Linux/Chromebook.

**No prior experience required.** Everything runs in your browser — no software to install.

---

## How This Curriculum Works

1. **Fork this repo** (Step 1 explains how) to create your own personal copy on GitHub.
2. **Open the browser editor** — press `.` on your fork to open VS Code in your browser.
3. **Work through each step** in order, at your own pace.
4. **GitHub Actions automatically checks your work** when you commit — you will see a green checkmark or a red X with hints in the Actions tab.
5. **Open a Pull Request** at the end so your instructor can review your work.

> If you get stuck: re-read the step, try Googling the exact error message, ask a classmate, or raise your hand for your instructor.

---

## Curriculum Steps

| Step | Topic | What You Will Do |
|------|-------|-----------------|
| [Step 1](steps/01-fork.md) | Fork the Repo | Make your own copy on GitHub |
| [Step 2](steps/02-open-editor.md) | Open the Editor | Launch VS Code in your browser |
| [Step 3](steps/03-branch.md) | Create a Branch | Start a safe working copy |
| [Step 4](steps/04-add-stage.md) | Create Your File | Add your about-me file |
| [Step 5](steps/05-commit.md) | Commit and Push | Save a snapshot and send it to GitHub |
| [Step 6](steps/06-pull-request.md) | Open a Pull Request | Request a review |

**Start here: [Step 1 - Fork the Repo](steps/01-fork.md)**

---

## How Validation Works

Every time you push code to GitHub, automated checks run in the background. To see your results:

1. Click the **Actions** tab at the top of your forked repository page.
2. Find the most recent workflow run.
3. A **green checkmark** means you passed. A **red X** means something needs fixing — click into the run to see a helpful error message explaining what to do.

> **Important:** When you first fork this repo, GitHub may ask you to enable Actions. Look for a yellow banner on the Actions tab and click **"I understand my workflows, go ahead and enable them."** You must do this before the checks will run.

---

## Git Quick Reference

These are the core git concepts you will learn:

| Concept | What It Means |
|---------|--------------|
| Repository (repo) | A folder tracked by git |
| Fork | Your personal copy of someone else's repo |
| Branch | A parallel timeline of your code |
| Staging | Marking which changes to include in the next commit |
| Commit | A labeled snapshot saved in git's history |
| Push | Sending your commits to GitHub |
| Pull Request | A request to merge your branch into `main` |

**Optional: CLI commands (for the curious)**

| Command | What It Does |
|---------|-------------|
| `git clone <url>` | Download a repository to your computer |
| `git status` | Show what has changed |
| `git checkout -b <name>` | Create and switch to a new branch |
| `git add <file>` | Stage a file |
| `git commit -m "message"` | Save a snapshot with a label |
| `git push origin <branch>` | Send your branch to GitHub |
| `git log --oneline` | See a compact commit history |

---

## For Instructors

<details>
<summary>Click to expand instructor notes</summary>

### Setting Up Your Class Copy

1. Fork or use this repo as a template under your organization.
2. Update the workflow files: replace `OWNER/techjourney-github` with your actual repo path in the workflow `if:` conditions to prevent workflows from running on your source repo.
3. Share your repo URL with students and have them fork from yours, not the original.

### Reviewing Student Work

Students will open Pull Requests from `add-about-me` to `main` on their own forks. You can:
- Navigate to their fork and review the PR there.
- Ask students to share their fork URL with you.
- Have students add you as a collaborator on their fork if you want to leave inline comments.

### Customization Ideas

- Add more steps (merge conflicts, rebasing, issues) for advanced students.
- Change the exercise file (e.g., a `hello-world.py` script instead of `about-me.md`) to tie into another class.
- Add a step requiring students to resolve a merge conflict by pre-creating a conflicting file in the repo.

</details>

---

*Built for the TechJourney STEM program.*
