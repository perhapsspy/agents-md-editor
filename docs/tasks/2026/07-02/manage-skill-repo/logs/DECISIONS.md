# Decisions

**2026-07-02**

- Background: The installed `agents-md-editor` skill existed only under the Codex skills directory and was not tracked in the global skill lock as a GitHub-sourced skill.
- Decision: Make `skills/agents-md-editor/` in this repository the canonical source and install from `perhapsspy/agents-md-editor`.
- Why: This matches the other perhapsspy skill repositories and keeps future edits, publishing, and install sync traceable.
- Impact: Direct edits to the installed runtime copy should be treated as temporary; durable changes belong in this repository first.
