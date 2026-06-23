# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Extended Personas and Operational Roles

To reduce ambiguity around ownership, handoffs, and operational activities, add the following operational personas to the roles documentation. Each entry below includes: Purpose, Key Responsibilities, Typical Interactions, and an example RACI/notes section.

### Release Coordinator
Purpose: Owns the tactical planning and execution of releases to production and other environments.

Key Responsibilities:
- Maintain and publish release schedules
- Coordinate release checklists and readiness gates across engineering, QA, and operations
- Run release activities, validate deployment success, and execute rollback if needed
- Ensure monitoring and alerting are in place for new releases

Typical Interactions:
- Works with Delivery Lead for timing and resource availability
- Confirms feature gating and sign-offs with Product Owner
- Coordinates with DevOps/Platform for deployment execution
- Notifies Stakeholder Liaison and Project Manager of release outcomes

RACI Notes:
- Primary (R): Release Coordinator for release execution
- Accountable (A): Project Manager (overall release decision)
- Consulted (C): Product Owner, Delivery Lead, DevOps
- Informed (I): Stakeholders, QA

Example checklist (see docs/release-checklist.md for full template):
- Verify feature gating sign-offs
- Confirm rollback plan exists and has been tested
- Validate monitoring and alerting for release
- Confirm stakeholder communication timeline

### Risk Owner
Purpose: Provide single-point ownership for tracking, mitigating, and reporting a specific project risk.

Key Responsibilities:
- Maintain the risk entry with impact, likelihood, and mitigation actions
- Drive mitigation tasks to closure and update status regularly
- Escalate to Project Manager or Program Sponsor when risk thresholds are met

Typical Interactions:
- Reports risk status to the Project Manager
- Coordinates with subject-matter experts to define mitigations
- Works with Stakeholder Liaison for communications when risk impacts external parties

RACI Notes:
- Primary (R): Risk Owner for mitigation tasks
- Accountable (A): Project Manager for overall risk posture
- Consulted (C): SMEs, Engineering Leads
- Informed (I): Sponsor, Stakeholders

### Change Steward
Purpose: Manage scope-change requests and ensure changes are assessed, approved, and communicated.

Key Responsibilities:
- Triage change requests and capture impact information
- Coordinate impact analysis and approval flows
- Update change logs and communication plans
- Ensure approved changes are scheduled and tracked

Typical Interactions:
- Liaises with Product Owner on scope decisions
- Coordinates scheduling with Project Manager
- Works with Stakeholder Liaison on communications for larger changes

RACI Notes:
- Primary (R): Change Steward for intake and tracking
- Accountable (A): Product Owner for scope decisions
- Consulted (C): Engineering Lead, PM
- Informed (I): Stakeholders

### Portfolio Manager
Purpose: Ensure projects align with portfolio priorities, manage cross-project dependencies, and advise on resource allocation.

Key Responsibilities:
- Maintain portfolio-level prioritization and roadmap alignment
- Identify and manage cross-project dependencies
- Advise on resource allocation and conflict resolution

Typical Interactions:
- Coordinates with Project Managers across programs
- Escalates resource conflicts to leadership
- Informs Program Sponsor and stakeholders on portfolio trade-offs

RACI Notes:
- Primary (R): Portfolio Manager for portfolio coordination
- Accountable (A): Program Sponsor for portfolio outcomes
- Consulted (C): PMs, Product Leadership
- Informed (I): Delivery Leads

### Delivery Lead
Purpose: Day-to-day delivery owner for an initiative; operational counterpart to Product Owner.

Key Responsibilities:
- Track sprint/iteration progress and removal of impediments
- Coordinate with engineering leads to unblock work
- Ensure delivery cadence and maintain delivery artifacts

Typical Interactions:
- Works with Product Owner for scope and prioritization
- Collaborates with Engineering Lead on technical execution
- Aligns with Project Manager on schedule commitments

RACI Notes:
- Primary (R): Delivery Lead for day-to-day delivery
- Accountable (A): Product Owner for backlog and priorities
- Consulted (C): Engineering Lead, PM
- Informed (I): Stakeholders

### Product Operations (Product Ops)
Purpose: Provide tooling, metrics, and process automation to increase product delivery efficiency.

Key Responsibilities:
- Maintain product tooling, dashboards, and release observability
- Build and improve delivery runbooks and automation
- Support Product Owners and Delivery Leads with operational metrics

Typical Interactions:
- Supports Product Owners and Delivery Leads
- Works with DevOps on observability and deployment tools

RACI Notes:
- Primary (R): Product Ops for tooling and metrics
- Accountable (A): Product Leadership for operational effectiveness
- Consulted (C): Delivery Leads, DevOps
- Informed (I): PMs, Stakeholders

### Stakeholder Liaison
Purpose: Serve as the primary contact for external or cross-team stakeholders and manage stakeholder communications.

Key Responsibilities:
- Craft stakeholder communications and status updates
- Ensure stakeholder feedback is captured and routed to the appropriate owner
- Coordinate stakeholder briefings and escalate material issues

Typical Interactions:
- Works with Project Manager for status and reporting
- Coordinates with Change Steward for comms related to scope changes
- Aligns messaging with Sponsor for strategic communications

RACI Notes:
- Primary (R): Stakeholder Liaison for communications
- Accountable (A): Project Manager / Sponsor for messaging accuracy
- Consulted (C): Change Steward, Product Owner
- Informed (I): Stakeholders

---

Suggested next steps:
- Add example scenarios and RACI matrices to help teams apply these personas to typical workflows (releases, risk mitigation, change approvals).
- Review with stakeholders and update acceptance criteria when agreed.
