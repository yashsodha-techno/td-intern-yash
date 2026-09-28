# Chapter 03: My top 10 Git commands

Short notes in my own words.

| # | Command | What it does |
|---|---------|--------------|
| 1 | `git clone <url>` | Downloads a copy of a GitHub repository to my computer. |
| 2 | `git status` | Shows which files are changed, staged or not tracked yet. |
| 3 | `git add <file>` | Puts a changed file in the staging area, ready to be committed. |
| 4 | `git commit -m "message"` | Saves the staged changes as a snapshot with a short message. |
| 5 | `git push` | Sends my local commits up to GitHub. |
| 6 | `git pull` | Brings the latest changes from GitHub into my local copy. |
| 7 | `git checkout -b <branch>` | Creates a new branch and switches to it, so I can work without touching main. |
| 8 | `git log --oneline` | Shows the commit history in a short list. |
| 9 | `git diff` | Shows exactly what I changed in files that are not committed yet. |
| 10 | `git merge <branch>` | Combines the changes from another branch into the one I'm on. |

## Things I want to remember
- Make small commits, one idea each, with a clear message like `docs: add intern profile`.
- Never commit `.env` or any secrets.
- Work on a branch, then open a pull request instead of pushing straight to `main`.
