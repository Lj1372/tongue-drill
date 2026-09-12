# AGENTS.md — Single Source of Truth for tongue-drill

This repository is the **only** shared workspace for the Multi-Domain Knowledge Base and related projects.

## Rules for every AI (Codex, Claude, Grokbot, Grok, etc.)

1. **Read first.** Before editing, pull the latest `index.html` (and any other files) from this repo. Never assume you have the current version.
2. **Write back here.** All changes go into this repo via commit. Do not create parallel copies in Google Drive, OneDrive, local folders, or other repos unless explicitly asked.
3. **One file at a time for big edits.** Prefer small, focused commits. Update `index.html` for app changes; keep data separate if it grows.
4. **Seed data lives in the app.** The knowledge base entries are generated inside `index.html` (or a `data/` folder if added). Keep them versioned here.
5. **Export format.** When exporting to JohnBrain, produce JSON with these fields: `title`, `domain`, `summary`, `source`, `confidence`, `date`. Save as `exports/johnbrain-YYYY-MM-DD.json`.
6. **No secrets.** Never commit API keys, tokens, or personal data.
7. **Commit messages.** Short and descriptive, e.g. "Add seed data for physics domain" or "Add export button for JohnBrain sync".

## Current state
- `index.html` — the Multi-Domain Knowledge Base app (shell + seeded entries).
- `README.md` — basic description.
- This file — instructions for all agents.

If you are unsure what to do, ask the user before creating new files or repos.
