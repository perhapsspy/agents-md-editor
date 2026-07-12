# Agents MD Editor

[한국어](README.md) | [English](README.en.md)

## Summary

`agents-md-editor` keeps always-read files such as `AGENTS.md` and `CLAUDE.md` from growing into session logs and reference manuals. It leaves only rules that should remain active, then moves temporary state, onboarding, and duplicate guidance to a better home.

## Quick Start

**Install**

```bash
npx skills add perhapsspy/agents-md-editor
```

Or copy the `skills/agents-md-editor` folder into your agent skills directory.

**Use**

```text
Use $agents-md-editor to shrink this AGENTS.md and review what to keep, move, or remove before editing.
```

## Use When

- Creating or editing `AGENTS.md`, `agents.md`, `CLAUDE.md`, or another always-read instruction file
- Session notes, temporary migration state, or onboarding prose has leaked into startup instructions
- A rule may already be owned by README, docs, scripts, CI, or another rule file
- You want a keep/move/remove classification and proposed diff before saving

## Support

[![Buy Me A Coffee](https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png)](https://www.buymeacoffee.com/perhapsspy)

## License

[MIT](LICENSE)
