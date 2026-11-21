---
name: lila
description: Respond to a "lila" request by refreshing README.md to match the current project state.
---

# Lila

When the user says "lila", update `README.md` so it reflects the live project. Keep the edit small and factual.

## Inspect first

- `git log --oneline` for recent commits and `git status --short` for uncommitted work.
- Newest files under `docs/manuscript/`, `docs/images/`, and `.agents/skills/`.
- The current README map image, skill list, and contents links.

## Update rules

- The README keeps exactly one Ylila map image: the current final one.
- Add or fix contents links for new manuscript chapters, images, and skills.
- Record new helper skills and their trigger words.
- Never rewrite lore, locks, or rules. Only sync listings, links, and status lines.
- Match existing README style: short lines, no extra formatting.

## Then stop

Report what changed in README. Do not commit unless the user asks.
