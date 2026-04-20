# Using this repo with Cursor

This repository includes a committed Cursor project rule so the pragmatic PM guidelines apply automatically.

## In this repository

1. Open this folder in Cursor.
2. Confirm [`.cursor/rules/karpathy-guidelines.mdc`](.cursor/rules/karpathy-guidelines.mdc) is loaded.
3. The rule is configured with `alwaysApply: true`.

## Reuse in another project

- Copy `.cursor/rules/karpathy-guidelines.mdc` into the target project's `.cursor/rules/` folder.
- If your tool supports only root instruction files, copy [`CLAUDE.md`](CLAUDE.md) into that project.

## Claude Code vs Cursor

- Claude Code reads plugin and skill metadata in `.claude-plugin/` and `skills/`.
- Cursor reads `.cursor/rules/`.
- Keep `CLAUDE.md`, `SKILL.md`, and the Cursor rule synchronized when principles change.
