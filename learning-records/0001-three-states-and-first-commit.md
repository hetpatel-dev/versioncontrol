# Learning Record

**Number:** 0001
**Date:** 2026-06-25
**Lesson:** 0001 — Your First Git Commit
**Tags:** git, basics, commit, staging, three-states

## What was learned

- Version control tracks changes to files over time, like save points
- Git works in three states: working directory → staging area → repository
- `git status` shows the current state of the working tree
- `git add` moves changes from working directory to staging area
- `git commit` takes a snapshot of staged changes with a message
- `git log` displays the commit history
- Commits have unique hashes (SHA-1 identifiers) and point to the previous commit

## Why this matters

The three-states model is the foundation of all Git work. Every Git operation — branching, merging, reverting, collaborating — builds on the concept of staged snapshots. Understanding this deeply prevents confusion later.

## Points of confusion

- The notion of "staging" may feel unnecessary at first. Why not commit directly? Staging lets you curate what goes into each commit — you might edit 3 files but only commit 2 together, keeping your history clean.
- The commit hash looks cryptic but it's just a unique label for each snapshot.

## Future directions

- Next: See how commits form a chain (the commit graph / DAG)
- Next: Connect this local repo to GitHub (remote repositories)
- Next: Using branches to work on features independently

## Revisions

- **2026-06-25**: Initial record
