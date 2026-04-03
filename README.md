# Therapy Ops Codex Recovery Package

This package is the recovery anchor for the Therapy Ops project.

## What this is
- `therapy_ops_phase5_2.html` = the original working Phase 5.2 base file.
- `AGENTS.md` = project rules and non-negotiables for Codex.
- `WILDFLOWER_REQUIREMENTS.md` = the missing features and fixes that need to be layered onto the Phase 5.2 base without deleting existing working functionality.

## Goal
Patch the original Phase 5.2 file into a fuller Wildflower office system **without removing or replacing existing working pages and views**.

## Important
Do not start over.
Do not reduce it to a dashboard shell.
Do not remove existing scheduling, providers, payers, patients, referrals, or imports views.
Do not leave blank pages.

## Best way to use in Codex
Open this folder as the project root in Codex. Ask Codex to:
1. Preserve all current working Phase 5.2 UI and render functions.
2. Add the requested office workflow features.
3. Keep every page clickable and populated.
4. Return a single-file HTML app unless a split-file refactor is explicitly justified.
