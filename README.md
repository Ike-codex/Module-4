# Git & GitHub Basics: Cloning, Issues, & Branches

## 1. Cloning a Repository
*   **What it does:** Copies an entire existing remote repository from the web (like GitHub) down to your local computer for the first time.
*   **Command:** `git clone <url>`
    *   *Example:* `git clone https://github.com/username/project.git`

## 2. GitHub Issues
*   **What they are:** Built-in tracking tools on GitHub used to track tasks, bugs, feature requests, or project feedback.
*   **How they work:**
    *   Created directly on the GitHub website within a repository.
    *   Can be assigned to team members, tagged with labels, and linked to specific pull requests or commits.

## 3. Branches
*   **What they are:** Independent lines of development that let you build features or fix bugs without messing up the main production code (`main`).
*   **Key Branching Commands:**
    *   `git branch` — Lists all local branches in your repository.
    *   `git checkout -b <branch-name>` (or `git switch -c <branch-name>`) — Creates a new branch and switches to it immediately.
    *   `git checkout <branch-name>` (or `git switch <branch-name>`) — Switches from your current branch to an existing branch.
    *   `git merge <branch-name>` — Combines the changes from the specified branch into your current active branch.
