# Cursor + Claude Code + Codex Setup Log

## Tools Installed

- **Cursor IDE** (from [cursor.com](https://cursor.com/))
- **Claude Code extension** (installed via Cursor Extensions marketplace)
- **Codex extension** (installed via Cursor Extensions marketplace)
- **Git** (used for version control)

## Steps Completed

1. Installed Cursor IDE. *(manual step in desktop app)*
2. Opened Extensions in Cursor and installed the **Claude Code** add-on. *(manual step in desktop app)*
3. Opened Extensions in Cursor and installed the **Codex** add-on. *(manual step in desktop app)*
4. Logged in to both extensions. *(manual authentication step)*
5. Created a public GitHub repository. *(manual step on GitHub web)*
6. Opened the repository in Cursor.
7. Created this `README.md` documenting setup and progress.
8. Initialized local git, committed changes, and prepared to push to GitHub.

## Step-by-Step: How Repository Was Created and Code Was Pushed

### A) Create a Public GitHub Repository

1. Signed in to GitHub at [github.com](https://github.com/).
2. Clicked the `+` icon (top-right) and selected **New repository**.
3. Entered repository name: `100Hires---junior-growth-marketing-specialist`.
4. Set visibility to **Public**.
5. Clicked **Create repository**.
6. Copied the repository URL:
   `https://github.com/Thanuja219/100Hires---junior-growth-marketing-specialist.git`

### B) Push Local Project Code to GitHub

1. Opened the project folder in Cursor terminal (`d:\100Hires`).
2. Initialized git:
   `git init`
3. Added the README file:
   `git add README.md`
4. Created commit(s):
   - `git commit -m "docs: add setup and troubleshooting README"`
   - `git commit -m "docs: clarify manual and local setup steps"`
5. Renamed default branch to `main`:
   `git branch -M main`
6. Added GitHub repository as remote origin:
   `git remote add origin https://github.com/Thanuja219/100Hires---junior-growth-marketing-specialist.git`
7. Pushed code to GitHub and set upstream tracking:
   `git push -u origin main`
8. Verified push success from terminal output:
   `main -> main` and branch tracking set to `origin/main`.

## Issues Encountered and How They Were Solved

- **Issue:** The project folder initially was not a git repository (`fatal: not a git repository`).
  - **Solution:** Ran `git init` in the project root, then staged and committed files.

- **Issue:** GitHub CLI (`gh`) was not available in this environment.
  - **Solution:** Used standard git commands with a remote URL (`git remote add origin <repo-url>` and `git push -u origin main`) instead of `gh`.

- **Issue:** Initial file in workspace was a placeholder (`Readme`) and not a standard `README.md`.
  - **Solution:** Created a proper `README.md` with the required sections.
