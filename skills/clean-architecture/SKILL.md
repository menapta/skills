---
name: clean-architecture
description: Apply clean architecture with clear layer boundaries and dependency inversion.
---

# Clean architecture skill

Use this skill when structuring or reviewing system boundaries.

## Rules
- Keep domain logic independent of frameworks.
- Make dependencies point inward.
- Separate domain, application, and infrastructure concerns.
- Keep use cases focused.
- Keep controllers, gateways, and repositories thin.
- Avoid leaking persistence or transport details into the domain.

## Suggested layers
- Domain: entities, value objects, business rules.
- Application: use cases, orchestration, ports.
- Infrastructure: databases, frameworks, external services.
- Interface: controllers, routes, presenters, adapters.

## Guidance
- Define contracts at the application boundary.
- Place framework code at the edges.
- Keep business rules testable without infrastructure.