---
name: node-tests
description: Generate Node.js unit and integration tests covering happy path, missing data, invalid data, and authentication when applicable.
compatibility: opencode
---

# Node.js tests

Use this skill when creating tests for Node.js services, APIs, or server logic.

## Required coverage
For each relevant behavior, cover:
- Happy path.
- Missing data or non-existent resource.
- Wrong or invalid data.
- Authentication success and failure when auth exists.

## Rules
- Use the project's chosen test framework.
- Prefer isolated unit tests for business logic.
- Use integration tests for route-to-database or route-to-service flows.
- Assert status codes, response payloads, and side effects.
- Include auth headers, invalid tokens, and unauthorized cases when applicable.

## Expectations
- Keep test names descriptive.
- Make setup minimal and reusable.
- Test behavior, not internals.