# Manage Skill Repo

## Goal

Make `agents-md-editor` a traceable perhapsspy-managed skill repository instead of an untracked Codex-only skill folder.

## Scope

- Create the repository shape used by the other perhapsspy skills.
- Keep the skill concise and compatible with current Codex skill guidance.
- Sync the installed runtime copy after the repository is published.

## Current Understanding

- The old installed copy was discoverable by Codex but had no git owner or `.skill-lock.json` source entry.
- The canonical source should be `skills/agents-md-editor/` in this repository.

## Current State

- Repository scaffolding is in progress.
- Validation and install sync still need to run before this task is considered complete.

## Next Step

Validate the skill folder, create the git/GitHub repository, push it, and reinstall the skill from `perhapsspy/agents-md-editor`.

## Working Boundary

- `skills/agents-md-editor/`
- `README.md`
- `README.en.md`
- `docs/reference/skill-ownership.md`
