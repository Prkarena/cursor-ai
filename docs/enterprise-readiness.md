# Enterprise Readiness Checklist

Use this checklist to validate the repository before rolling into production projects.

## Governance & Ownership
- Assign an owner for Rules, Skills, and Commands.
- Define approval requirements for configuration changes.
- Establish a review cadence (e.g., monthly or per release).

## Security & Compliance
- Ensure Rules prohibit insecure defaults and require input validation.
- Confirm no telemetry or data collection is introduced without approval.
- Map project requirements to Rule updates where necessary.

## Architecture & Standards
- Confirm architectural boundaries match your organization’s standards.
- Add stack-specific Rules only when a stable pattern emerges.
- Keep reasoning in Skills, not Rules.

## Operational Integration
- Align Commands with your team’s common workflows.
- Document how teams request new Rules/Skills/Commands.
- Ensure onboarding materials are accessible to non-experts.

## Change Control
- Require explicit approval for configuration updates.
- Track changes via pull requests in the shared repository.
- Keep a changelog if operating across multiple teams.
