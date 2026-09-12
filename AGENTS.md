# AGENTS.md — Single Source of Truth for tongue-drill

This repository is the **practice trainer** (pre-verbal clarity drills).

The **multi-domain knowledge base** lives in **`Lj1372/johnbrain-kb`**. Read `AGENTS.md` there before adding KB entries.

## Rules for every AI (Codex, Claude, Grokbot, Grok, etc.)

1. **Read first.** Pull latest `index.html` here and `Lj1372/johnbrain-kb` before editing.
2. **Split of work.**
   - Trainer UI / timers / session log → this repo (`index.html`).
   - Domain entries, morning brief, export JSON, collaboration protocol → `Lj1372/johnbrain-kb`.
3. **Write back to the correct repo.** Do not create parallel copies in Drive, OneDrive, or a third repo.
4. **No secrets.** Never commit API keys, tokens, or personal data.
5. **Commit messages.** Short and descriptive.

## Current state
- `index.html` — Tongue Drill Cognitive Hazard Trainer.
- `README.md` — one-line description.
- This file — routing for agents.
- KB + agent sync protocol: `https://github.com/Lj1372/johnbrain-kb`
