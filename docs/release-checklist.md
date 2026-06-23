# Release Checklist

A practical checklist to prepare, execute, and validate releases. Tailor to your organization's environments and risk tolerance.

## Pre-release
- Confirm release scope and feature gating sign-offs from Product Owner
- Verify all merge checks and CI pipelines pass for release commits
- Ensure deployment runbook and rollback plan are available and up-to-date
- Confirm test coverage for critical paths and smoke tests
- Validate monitoring and alerting for new or changed services
- Schedule stakeholder communications and confirm recipients

## Release run (execution)
- Notify stakeholders that release is starting
- Execute deployment steps per runbook
- Run smoke tests and validate basic functionality
- Monitor logs and alerts for anomalies
- Record deployment artifacts (timestamps, versions, notes)

## Post-release
- Confirm health checks and user-facing metrics are within expected thresholds
- Monitor for regressions or incidents for agreed observation period
- Communicate release outcome and known issues to stakeholders
- Close any temporary release tasks and update status in project board

## Rollback criteria and plan
- Define clear, measurable criteria that trigger rollback (e.g., error rate spike, major functionality broken)
- Ensure rollback steps are practiced occasionally and reviewed after use
- Document post-rollback incident timeline and remediation steps

## Validation and sign-off
- Release Coordinator: confirms rollout success
- Product Owner: validates feature acceptance in production
- Project Manager: records completion and lessons learned
