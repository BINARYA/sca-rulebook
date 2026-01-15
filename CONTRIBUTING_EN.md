# How to contribute: create a Pull Request (PR)

This repository accepts contributions via **Pull Requests** (PRs).

✅ Main rule: **do not push to `main`**.  
Changes must be proposed through a PR and will be reviewed and approved by the maintainer.

---

## Method 1 — GitHub only (no terminal)

### 1) Fork the repository
1. Open this repository on GitHub.
2. Click **Fork** (top-right).
3. You will get a copy of the project in *your* GitHub account.

### 2) Create a branch in your fork and make changes
1. In your fork, go to **Code**.
2. Click the branch selector (it usually shows `main`).
3. Type a new branch name, for example:
   - `fix/typo-readme`
   - `feature/improvement-x`
4. Click **Create branch**.
5. Edit files:
   - open a file and click the ✏️ icon to edit it, or upload new files.
6. Save with a commit:
   - write a short, clear commit message
   - confirm the commit **to your branch** (not to `main`)

### 3) Open a Pull Request to this repository
1. In your fork, go to **Pull requests**.
2. Click **New pull request**.
3. Make sure it is set to:
   - **base repository**: this repository (the original one)
   - **base branch**: `main`
   - **head repository**: your fork
   - **compare branch**: your branch (e.g. `fix/typo-readme`)
4. Click **Create pull request**.
5. Fill in the title and description, then submit.

✅ Done! The maintainer will review the PR and (if approved) merge it into `main`.

---

## Method 2 — Using Git from the terminal

### 1) Fork on GitHub
1. Open this repository on GitHub.
2. Click **Fork** (top-right).

### 2) Clone your fork locally
Replace `YOUR-USERNAME` and `REPO-NAME` with the correct values:

```bash
git clone https://github.com/YOUR-USERNAME/REPO-NAME.git
cd REPO-NAME
```

### 3) Create a branch, make changes, and push
```bash
git checkout -b fix/short-description
# make your changes
git add .
git commit -m "Fix: short description"
git push -u origin fix/short-description
```

### 4) Create the PR on GitHub
1. Open your fork on GitHub.
2. GitHub will show a **Compare & pull request** button — click it.
   - Alternatively: **Pull requests** tab → **New pull request**
3. Confirm the PR is:
   - **from your branch** → into **`main`** of this repository
4. Click **Create pull request**.

✅ Done! The maintainer will review and merge the PR.

---

## Quick checklist before opening a PR
- The PR is small and focused (one thing at a time).
- You explained **what** changed and **why**.
- If there are tests or verification commands, you mentioned how you ran them.

---

## PR description template (recommended)
Copy/paste into your PR:

- **What changed:** …
- **Why:** …
- **How to test (if applicable):** …

Thanks for contributing! 🙌