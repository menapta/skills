---
name: refactor
description: Refactor code safely by reducing complexity, improving readability, and preserving behavior.
---

# Refactoring skill

Use this skill when the task is to improve existing code without changing external behavior.

## Goals
- Reduce complexity.
- Improve readability.
- Improve testability.
- Preserve behavior.

## Approach
- Identify code smells.
- Prefer small, safe steps.
- Extract functions and modules when it improves clarity.
- Remove duplication carefully.
- Keep public contracts stable.
- Suggest tests before and after changes when needed.

## Do
- Simplify conditionals.
- Break large functions into focused units.
- Rename unclear identifiers.
- Isolate side effects.
- Reduce coupling.

## Avoid
- Changing architecture unnecessarily.
- Creating abstractions without clear reuse.
- Mixing refactorings with feature work unless requested.