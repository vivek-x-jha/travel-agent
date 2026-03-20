# AGENTS.md

## Purpose

This repository is for a travel assistant project. Right now it is mostly a destination-guide content repo, but it should be treated as the foundation for a travel bot.

## Working Rules

- Preserve the existing folder-per-destination structure.
- Put each new city or destination in its own directory.
- Keep Markdown readable both on GitHub and in terminal renderers like `glow`.
- When adding recommendations that may change over time, prefer official sources and direct map links.
- Do not invent fake venue details, addresses, or hours.
- If a place cannot be verified confidently, remove it or mark it as needing verification.

## Content Style

- Write like a practical travel editor, not a generic brochure.
- Optimize for scanability: headings, short lists, and concise guidance.
- Include the why behind recommendations, not just the names of places.
- Prefer neighborhood structure over long undifferentiated lists.
- Add sample itineraries when useful.

## File Conventions

- Top-level project documentation belongs in `README.md` and `AGENTS.md`.
- Destination guides belong under a dedicated folder such as `boston/`.
- If prompts are added later, keep them under `prompts/` and name them by use case.

## If Code Is Added Later

- Keep content and application logic separate.
- Avoid hardcoding destination knowledge inside app code when it can live in Markdown or structured data.
- Prefer small, composable utilities over a large monolithic script.
