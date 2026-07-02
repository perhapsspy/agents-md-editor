# Agents MD Editor

[한국어](README.md) | [English](README.en.md)

## Summary

`agents-md-editor` keeps always-read agent instruction files such as `AGENTS.md`, `CLAUDE.md`, Cursor rules, and Copilot instructions small and durable.

It keeps only rules that should change future agent behavior in always-read files, and classifies temporary state, onboarding, detailed reference material, and duplicated policy into better-owned surfaces.

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
