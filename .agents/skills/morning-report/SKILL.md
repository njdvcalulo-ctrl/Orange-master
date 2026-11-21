---
name: morning-report
description: Respond to a "Good Morning!" greeting or /report request with a progress summary, today's task list, pending decisions, and revenue summary.
---

# Morning Report

When the user says "Good Morning!" or invokes /report, produce a morning briefing for the light novel project. Keep it concise. Use short sentences and short paragraphs.

Build the briefing from live evidence, not memory alone. Inspect before writing:

- Recent progress: `git log --oneline` for the last few commits, `git status --short` for uncommitted work, and the newest files under `docs/manuscript/` and `docs/images/`.
- Project direction: `README.md`, `docs/story/volume1-outline.md`, and the memory files `lightnovel/project-index.md` and `lightnovel/storytelling-rules.md`.
- Revenue: any sales, royalty, or monetization notes in the workspace. None exist yet.

Output exactly these four sections:

1. **Progress** — what is done and where the project stands right now, grounded in what you actually inspected.
2. **20 tasks for today** — a numbered list of exactly 20 concrete next tasks, ordered by priority. Mix writing, art, and project chores. Each task is one short line.
3. **Decisions I need from you** — open questions only the user can settle. One short line each. Never decide these yourself.
4. **Revenue** — totals and breakdowns if revenue records exist. They do not exist yet, so say plainly that there is no revenue to report and skip the numbers. Do not invent any.

Rules: report only verified facts, mark anything unconfirmed as such, and never fabricate revenue, sales, or progress.
