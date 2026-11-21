---
name: chapterpass
description: Respond to a /chapterpass request by creating one image per character in the chapter plus a chapter cover image.
---

# Chapter Pass

When the user says /chapterpass, generate art for a chapter. Ask which chapter if it is not clear from the conversation. One chapter per pass.

## Find the cast

- Read the chapter manuscript in `docs/manuscript/` for who appears.
- Check each appearing character's folder under `docs/characters/` for their portrait and locked look.
- Honor locked visuals: Nochi orange, Greg green, Octo purple, Crow black. Slimes are pure spherical blobs at rest. Modest outfits, kid-safe, no gore. Match the existing storybook portrait style.

## Generate

- One image per appearing character, in-scene but faithful to their locked look.
- One chapter cover image: the chapter's key moment, with the chapter number and title as clean text.
- Save everything under `docs/images/chapters/<chapter-slug>/`, following the existing chapter folder convention.

## Then stop

List every saved file path. Do not commit unless the user asks.
