# Skill: State Management

## When to Activate
Use this skill when choosing or structuring client-side state and data flow.

## How to Think
- Separate server state from client UI state.
- Favor predictable, observable updates over implicit mutations.
- Start simple; only add complexity when usage demands it.

## Examples
- Recommend React Query for server state and local hooks for UI state.
- Propose a small store (e.g., Zustand) for shared UI state.

## Future Extension
- NodeJS: align with cache layers or request-scoped state.
- Python: map to service-layer state and caching strategies.
- React Native: consider offline-first state and persistence.
