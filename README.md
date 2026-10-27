# Welvox AUTOPILOT

**Give coding agents a repeatable path from goal to verified result.**

Welvox AUTOPILOT is an open, instruction-based agent skill for multi-step software engineering tasks.

It guides a coding agent to:

1. Understand the goal and acceptance criteria.
2. Inspect the project and create a focused plan.
3. Implement the requested changes.
4. Recover from ordinary errors when safe.
5. Verify changes using available checks.
6. Report results, limitations, and blockers honestly.

## What's included

- `skills/autopilot/SKILL.md` — canonical reusable skill.
- `index.html` — mobile-first skill browser for GitHub Pages.
- `AGENTS.md` — repository guidance for agents that support it.
- `CLAUDE.md` — Claude Code project instructions.
- `LICENSE` — MIT license.

## Requirements

The website requires a public GitHub repository and a browser with network access.

The skill requires a coding agent that can read its instructions. Actual file editing, shell execution, and testing depend on the host agent's available tools and permissions.

## Install from a phone

### Claude Code

1. Open this repository on GitHub.
2. Open `skills/autopilot/SKILL.md`.
3. Copy the complete file contents.
4. In the target project, create `.claude/skills/autopilot/SKILL.md`.
5. Paste and commit the copied contents.
6. Use a supported Claude Code environment to request the AUTOPILOT workflow.

### OpenAI Codex

1. Open this repository on GitHub.
2. Open `skills/autopilot/SKILL.md`.
3. Copy the complete file contents.
4. In the target project, create `.agents/skills/autopilot/SKILL.md`.
5. Paste and commit the copied contents.
6. Use a Codex environment that has access to the target project.

### Other coding agents

Check the host's current documentation for supported skill discovery, project instructions, or skill import. The standard file format alone does not guarantee that every agent discovers or invokes the skill automatically.

## Publish the website

1. Open the repository's Settings on GitHub.
2. Select Pages.
3. Set the publishing source to Deploy from a branch.
4. Choose `main` and `/(root)`.
5. Save and open the Pages URL displayed by GitHub.

The website reads skill metadata and Markdown from the repository's public `skills/` directory. No application backend or GitHub token is required.

## Safety and limitations

AUTOPILOT works within the host agent's tools, permissions, and execution environment. It cannot independently grant access, run unavailable tests, or guarantee that a change is correct.

It should stop before consequential actions that are outside the user's explicit authorization.

## License

MIT. See `LICENSE`.
