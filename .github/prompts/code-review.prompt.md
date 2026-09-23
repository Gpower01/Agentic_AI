---
description: 'Run a code quality review on recent changes'
---

# Code Review

Review the current changes for code quality issues. Focus on:

1. Correctness — logic errors, off-by-one, incorrect assumptions
2. Readability — clear naming, sensible structure
3. Tests — meaningful assertions that verify behaviour
4. Error handling — appropriate for context, not over-engineered
5. Security — no injection, no hardcoded secrets, no unsafe patterns
6. DRY — flag genuine duplication only

Use severity levels:
- **CRITICAL** — Must fix before merge (security, data loss, crashes)
- **MAJOR** — Should fix before merge (logic errors, missing validation)
- **MINOR** — Nice to fix (naming, style, minor refactoring)

Output format:
```
## [SEVERITY] Issue Title
File: path/to/file.py (line X)
Problem: Description of the issue
Suggestion: How to fix it
```