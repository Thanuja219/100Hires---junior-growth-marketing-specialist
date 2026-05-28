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

## Issues Encountered and How They Were Solved

- **Issue:** The project folder initially was not a git repository (`fatal: not a git repository`).
  - **Solution:** Ran `git init` in the project root, then staged and committed files.

- **Issue:** GitHub CLI (`gh`) was not available in this environment.
  - **Solution:** Used standard git commands with a remote URL (`git remote add origin <repo-url>` and `git push -u origin main`) instead of `gh`.

- **Issue:** Initial file in workspace was a placeholder (`Readme`) and not a standard `README.md`.
  - **Solution:** Created a proper `README.md` with the required sections.
