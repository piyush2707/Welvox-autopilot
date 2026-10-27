---

name: bug-fixer
description: Find, diagnose, and fix software bugs. Use when the user reports an error, unexpected behavior, failing test, or reproducible defect.

Bug Fixer

Goal

Identify the cause of a reported bug and implement the smallest reliable fix.

Workflow

1. Understand the expected and actual behavior.
2. Inspect relevant files, error messages, and available tests.
3. Reproduce the issue when possible.
4. Identify the root cause before editing.
5. Make the smallest appropriate change.
6. Run relevant tests or verification checks available in the environment.
7. Review the changes for regressions.

Safety

- Do not remove unrelated functionality.
- Do not expose secrets or credentials.
- Ask before destructive or externally consequential actions.
- Never claim tests passed unless they were actually run.

Final report

Summarize the root cause, files changed, fix applied, tests performed, and any remaining limitations.
