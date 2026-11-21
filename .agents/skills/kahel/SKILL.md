---
name: kahel
description: Respond to a "kahel" request by reviewing, staging, and committing all current workspace changes.
---

# Kahel

When the user says "kahel", update and commit all changes. The word itself is the user's standing approval to commit. It never approves push, amend, or history rewrites.

## Steps

1. Run `git status --short` and `git diff --stat`. Review every changed file.
2. Commit only work this session made or can explain. Name the files when staging. Never use a broad add across a tree with changes you did not make and cannot explain.
3. If status shows changes you did not make and cannot explain, stop and report them instead of committing.
4. Write a short commit message naming what changed.
5. Commit, then run `git status --short` and `git log --oneline -3` to confirm.

## Report

State the commit hash, the files committed, and anything deliberately left uncommitted. Never push.
