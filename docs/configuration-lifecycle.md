# Configuration Lifecycle

This document describes how Rules, Skills, and Commands evolve over time.

## Signals That Trigger Change
- Repeated architecture decisions across features.
- Consistent naming, folder structure, or code style patterns.
- Recurring workflows or requests from teams.

## Consent-First Flow
1. Cursor observes a repeated pattern.
2. Cursor asks for permission with a clear rationale.
3. A user approves or declines the change.
4. Approved changes are made via pull request.

## Versioning Guidance
- Keep changes small and reviewable.
- Use clear commit messages.
- Prefer explicit deprecations rather than silent removals.
