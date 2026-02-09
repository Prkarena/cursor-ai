# Skill: Frontend Architecture

## When to Activate
Use this skill when designing app structure, folder layout, or cross-cutting architectural decisions.

## How to Think
- Start from product domains and map them to feature boundaries.
- Keep UI, domain logic, and data access separated by clear interfaces.
- Prefer composable patterns that scale from small apps to enterprise systems.

## Examples
- Propose a `features/<domain>/` layout with shared UI in `components/`.
- Recommend a `services/` layer for API clients and a `state/` layer for stores.

## Future Extension
- NodeJS: map domains to service modules and API boundaries.
- Python: align domains to packages and dependency injection boundaries.
- React Native: mirror web features while isolating platform-specific UI.
