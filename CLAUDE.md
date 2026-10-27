# Welvox AUTOPILOT — Claude Code Instructions

This repository publishes the Welvox AUTOPILOT agent skill.

## Canonical skill

Read `skills/autopilot/SKILL.md` when the user requests a multi-step engineering task that should proceed from planning through implementation and verification.

Follow its execution workflow, recovery rules, verification requirements, and consequential-action boundaries.

## Repository conventions

- Follow `AGENTS.md` for general project guidance.
- Keep `index.html` standalone and dependency-free.
- Do not invent compatibility, test results, or completed work.
- Inspect existing files before editing.
- Preserve unrelated user changes.
- Use the repository's documented checks when available.

## Important distinction

This file references the published skill. It does not automatically install that skill into every Claude Code project.

For native Claude Code skill discovery, install the canonical file under `.claude/skills/autopilot/SKILL.md` in the target project.
