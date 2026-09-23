---
description: 'Implement the next phase from an approved plan'
---

# Implement

Execute the next phase from the approved implementation plan using strict TDD:

1. Read the plan from `docs/plans/` to identify the current phase
2. Write the failing test(s) specified in the phase
3. Run tests to verify they fail for the RIGHT reason
4. Write the minimum implementation to make tests pass
5. Run tests to verify they pass
6. Run `task lint` and `task format` to verify code quality

## Iron Law of TDD

No production code without a failing test first. If you wrote code before the test — delete it and start over.

## Phase to Implement

{{input}}
