# Learning Record

**Number:** 0004
**Date:** 2026-06-25
**Lesson:** 0004 — Connecting to GitHub
**Tags:** git, github, remote, push

## What was learned

- A remote is another copy of the repo hosted on a server (GitHub)
- `git remote add origin <url>` connects local repo to GitHub
- `git push -u origin main` uploads commits and sets upstream tracking
- After `-u`, plain `git push` works because origin/main is tracked
- Files in `.gitignore` (`.agents/`, `skills-lock.json`) are not pushed — they're tooling, not work product
- Deleted branches lose only the label, not the commits (if merged)
- `git branch -vv` shows tracking relationship between local and remote branches

## Why this matters

Pushing to GitHub makes work visible, shareable, and recoverable. Employers judge candidates by their GitHub presence. Remote tracking is the foundation of all team collaboration.

## Points of confusion

- What gets pushed vs ignored — clarified via `.gitignore` role
- Deleting a merged branch doesn't lose history, just the pointer

## Future directions

- Ready for: Pull Requests (the core GitHub collaboration workflow)
- Also ready for: cloning, forking, `git pull`

## Revisions

- **2026-06-25**: Initial record