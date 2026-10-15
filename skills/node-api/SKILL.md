---
name: node-api
description: Build and refactor Node.js APIs using clean structure, clear boundaries, and robust error handling.
compatibility: opencode
---

# Node.js API

Use this skill when creating or refactoring Node.js backend code.

## Rules
- Keep routes/controllers thin.
- Move business rules to services or use cases.
- Validate input at the boundary.
- Handle errors consistently.
- Avoid mixing HTTP, persistence, and domain logic.
- Keep modules cohesive and predictable.

## Node guidance
- Use Express, Fastify, Hono, or the project's chosen framework.
- Make async error handling explicit.
- Return stable response shapes.
- Keep dependencies injected or easy to mock.