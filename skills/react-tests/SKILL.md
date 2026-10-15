---
name: react-tests
description: Generate React component and hook tests with happy path, missing data, and invalid data cases.
compatibility: opencode
---

# React tests

Use this skill when creating tests for React components, hooks, or UI flows.

## Required coverage
For each relevant behavior, cover:
- Happy path.
- Missing data or empty state.
- Wrong or invalid data.

## Rules
- Prefer React Testing Library.
- Test from the user perspective.
- Use accessible queries like role, label, and text when possible.
- Use user-event for interactions.
- Mock network calls or external dependencies when needed.
- Include async assertions for loading and error states.

## Expectations
- Verify what the user sees and can do.
- Keep tests readable and scenario-driven.