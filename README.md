# Cursor + Claude Code + Codex Setup Log

## Tools Installed

- **Cursor IDE** (from [cursor.com](https://cursor.com/))
- **Claude Code extension** (installed via Cursor Extensions marketplace)
- **Codex extension** (installed via Cursor Extensions marketplace)
- **Git** (used for version control)

## Steps Completed

1. Installed Cursor IDE.
2. Opened Extensions in Cursor and installed the **Claude Code** add-on.
3. Opened Extensions in Cursor and installed the **Codex** add-on.
4. Logged in to both extensions.
5. Created a public GitHub repository.
6. Opened the repository in Cursor.
7. Created this `README.md` documenting setup and progress.
8. Initialized local git (if needed), committed changes, and prepared to push to GitHub.

## Issues Encountered and How They Were Solved

- **Issue:** The project folder initially was not a git repository (`fatal: not a git repository`).
  - **Solution:** Ran `git init` in the project root, then staged and committed files.

- **Issue:** GitHub CLI (`gh`) was not available in this environment.
  - **Solution:** Used standard git commands with a remote URL (`git remote add origin <repo-url>` and `git push -u origin main`) instead of `gh`.

- **Issue:** Initial file in workspace was a placeholder (`Readme`) and not a standard `README.md`.
  - **Solution:** Created a proper `README.md` with the required sections.
