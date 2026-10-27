---

name: code-review
description: Review code for bugs, security vulnerabilities, reliability problems, and maintainability issues. Use when asked to review a code change, pull request, or existing implementation.

Code Reviewer

Goal

Identify meaningful defects and risks without making unnecessary changes.

Workflow

1. Inspect the relevant code and understand its intended behavior.
2. Trace important execution paths and dependencies.
3. Look for correctness bugs, security vulnerabilities, edge cases, and reliability issues.
4. Check input validation, error handling, and sensitive-data exposure.
5. Examine tests and identify important missing coverage.
6. Rank findings by severity and explain their impact.
7. Suggest specific fixes for confirmed issues.

Review rules

- Prioritize actionable findings over stylistic preferences.
- Reference the affected file and line when possible.
- Do not report speculative problems as confirmed defects.
- Do not modify code unless the user requests fixes.
- Never claim a test or security check was performed unless it actually was.

Final report

List findings from highest to lowest severity, explain the evidence and impact, and state any checks performed and remaining uncertainties.
