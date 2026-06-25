# Learning Record

**Number:** 0003
**Date:** 2026-06-25
**Lesson:** 0003 — Branching Basics
**Tags:** git, branching, merge, merge-conflict

## What was learned

- Branches are lightweight pointers to commits — creating one is instant
- `git switch -c <name>` creates and switches in one step
- Changes on one branch are invisible on another — isolated workspaces
- Fast-forward merge: when target branch hasn't moved since branch-off
- Non-fast-forward merge: creates a merge commit with two parents
- **Merge conflicts** happen when both branches edit the same lines
- Resolving conflicts: edit file → `git add` → `git commit`
- The diamond shape in `git log --graph` is the hallmark of a merge commit

## Why this matters

Branching is the core team collaboration mechanism in Git. Merge conflicts are not a mistake — they're a normal part of parallel work. Knowing how to resolve them confidently is a key career skill.

## Points of confusion

- The merge conflict markers (<<<<<<<, =======, >>>>>>>) can be intimidating at first, but the structure is simple: top half is "ours" (current branch), bottom half is "theirs" (incoming branch)
- VS Code's conflict UI (Accept Current/Incoming/Both) is helpful but manual editing is often cleaner

## Future directions

- Ready for: GitHub remotes (push, pull, pull requests)
- Next: connecting local repo to GitHub, pushing branches, creating PRs

## Revisions

- **2026-06-25**: Initial record
