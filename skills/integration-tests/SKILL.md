---
name: integration-tests
description: Generate integration tests with a happy path, missing data case, invalid data case, and authentication coverage when applicable.
compatibility: opencode
---

# Integration tests

Use this skill when creating or improving integration tests.

## Required coverage
For each behavior, cover:
- Happy path.
- Missing data or absent input.
- Invalid or wrong data.
- Authentication scenario, when the resource requires auth.

## Rules
- Test the integration between real components.
- Use fakes, containers, or test doubles only when appropriate for external systems.
- Keep the test environment close to production behavior.
- Verify HTTP status, payload shape, and side effects when relevant.
- Include auth success and auth failure when authentication is part of the flow.

## Expectations
- Use framework-native test style.
- Mirror the project’s existing integration test pattern.
- Keep setup minimal and reusable.