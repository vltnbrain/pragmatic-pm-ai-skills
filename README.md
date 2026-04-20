# Pragmatic PM AI Skills

Pragmatic behavioral guidelines for AI assistants used by product managers, IT professionals, and career-focused operators.

Inspired by the structure of [forrestchang/andrej-karpathy-skills](https://github.com/forrestchang/andrej-karpathy-skills), but focused on non-coding PM and career execution in real organizational environments.

## The Problem

Generic AI advice often sounds polished but fails in practice:
- Long outputs nobody reads.
- Frameworks without decision leverage.
- "Best practices" that ignore incentives, politics, and time constraints.

## The Solution

This repository ships a reusable instruction set that makes AI:
- audit incentives before proposing work;
- reduce friction instead of adding process;
- prioritize hard signals over narrative noise;
- define real-world verification criteria.

The core content is in:
- [`PM.md`](./PM.md) for chat grounding.
- [`CLAUDE.md`](./CLAUDE.md) for project-level instruction files.
- [`skills/karpathy-guidelines/SKILL.md`](./skills/karpathy-guidelines/SKILL.md) for plugin compatibility with the source layout.
- [`skills/pragmatic-pm-guidelines/SKILL.md`](./skills/pragmatic-pm-guidelines/SKILL.md) as a project-named variant.
- [`EXAMPLES.md`](./EXAMPLES.md) for bad vs pragmatic scenario patterns.
- [`BENCHMARK.md`](./BENCHMARK.md) for before/after outcome measurement.
- [`CHANGELOG.md`](./CHANGELOG.md) for release history.

English | [简体中文](./README.zh.md)

## Core Principles

| Principle | What it prevents |
|---|---|
| **Intent-First Discovery** | Silent assumptions about what people want |
| **Friction Reduction and MVP** | Process bloat and overbuilt artifacts |
| **Signal-to-Noise Ratio** | Soft storytelling without decision signals |
| **Evidence-Based Outcomes** | "Looks good" outputs with no behavioral impact |

## Install

Option A: Claude Code plugin (recommended)

```text
/plugin marketplace add vltnbrain/pragmatic-pm-ai-skills
/plugin install pragmatic-pm-ai-skills@pragmatic-pm-skills
```

Option B: Per-project instruction file

```bash
curl -o CLAUDE.md https://raw.githubusercontent.com/vltnbrain/pragmatic-pm-ai-skills/main/CLAUDE.md
```

Option C: Manual grounding in any chat

Copy [`PM.md`](./PM.md) into your first message and add:
"Follow these principles for all future responses in this thread."

## Cursor Support

This repository includes a committed Cursor rule:
- [`.cursor/rules/karpathy-guidelines.mdc`](./.cursor/rules/karpathy-guidelines.mdc) for source-compatible naming
- [`.cursor/rules/pragmatic-pm-guidelines.mdc`](./.cursor/rules/pragmatic-pm-guidelines.mdc) for project naming

See [`CURSOR.md`](./CURSOR.md) for setup and portability instructions.

## Repository Structure

```text
.
├── .claude-plugin/
│   ├── marketplace.json
│   └── plugin.json
├── .cursor/rules/
│   ├── karpathy-guidelines.mdc
│   └── pragmatic-pm-guidelines.mdc
├── skills/pragmatic-pm-guidelines/
│   └── SKILL.md
├── skills/karpathy-guidelines/
│   └── SKILL.md
├── CLAUDE.md
├── CHANGELOG.md
├── CURSOR.md
├── BENCHMARK.md
├── EXAMPLES.md
├── PM.md
└── README.md
```

## License

MIT
