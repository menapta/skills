---
name: unit-tests
description: Generate unit tests with a happy path, missing data case, and invalid data case for the current codebase.
compatibility: opencode
---

# Unit tests

Use this skill when creating or improving unit tests.

## Required coverage
For each behavior, cover:
- Happy path.
- Missing data or absent input.
- Invalid or wrong data.

## Rules
- Prefer isolated tests.
- Mock external dependencies.
- Test behavior, not implementation details.
- Keep tests small and readable.
- Follow the project's existing framework and conventions.

## Expectations
- Use arrange, act, assert.
- Name tests clearly by scenario.
- Include assertions for expected outputs and errors.
- Add edge cases only when they are relevant to the behavior under test.