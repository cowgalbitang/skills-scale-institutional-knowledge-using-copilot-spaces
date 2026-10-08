# OctoAcme Project Management Documentation

Welcome to the central hub for OctoAcme's project management process. The
process moves through Initiation, Planning, Execution, Release, and Close &
Retrospective: confirm the need and success measures, shape the work into an
owned plan, deliver and track small increments, release with verification, and
turn lessons into improvements.

The approach is customer-first, iterative, grounded in clear ownership and
data-informed decisions, and supported by psychological safety. During
initiation, teams align on the problem, stakeholders, outcomes, and initial
risks. Planning turns approved work into a prioritized backlog, milestones,
acceptance criteria, and a Definition of Done. Execution tracks progress,
risks, and dependencies while the team builds, tests, reviews, and iterates.
Release guidance covers readiness, deployment, verification, and rollback;
retrospectives capture learnings and assign improvement actions.

## Documentation by lifecycle phase

### Initiation
- [Project Initiation Guide](./octoacme-project-initiation.md) — validate and
  authorize work, align stakeholders, and prepare a lightweight plan.

### Planning
- [Project Planning](./octoacme-project-planning.md) — create an actionable
  plan, prioritized backlog, milestones, and acceptance criteria.

### Execution
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — manage
  day-to-day delivery, project-board workflows, quality, and progress.
- [Risk Management & Communication](./octoacme-risks-and-communication.md) —
  maintain risks and dependencies, report status, and escalate issues.

### Release
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — prepare,
  deploy, verify, announce, or roll back a release.

### Close & Retrospective
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) —
  capture lessons and track owned improvement actions after a sprint, release,
  milestone, or incident.

### Reference
- [Project Management Overview](./octoacme-project-management-overview.md) —
  concise summary of the principles, roles, artifacts, and lifecycle.
- [Roles and Personas](./octoacme-roles-and-personas.md) — detailed role
  responsibilities, goals, and communication patterns.

## Quick start

- Exploring a new project idea? Start with the [Project Initiation
  Guide](./octoacme-project-initiation.md).
- Turning an approved idea into deliverable work? Use [Project
  Planning](./octoacme-project-planning.md).
- Tracking delivery, blockers, or quality? See [Execution &
  Tracking](./octoacme-execution-and-tracking.md) and [Risk Management &
  Communication](./octoacme-risks-and-communication.md).
- Preparing or responding to a deployment? Follow the [Release &
  Deployment Guide](./octoacme-release-and-deployment.md).
- Closing a milestone or reviewing an incident? Use [Retrospective &
  Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md).
- Clarifying who owns a responsibility? Consult [Roles and
  Personas](./octoacme-roles-and-personas.md).

## Key roles

- **Project Manager (PM):** coordinates delivery, schedules, risks,
  dependencies, and communications.
- **Product Manager (PdM):** defines outcomes, prioritizes the backlog, and
  measures success.
- **Developers:** implement features, collaborate on design, and contribute
  tests and reviews.
- **QA/Testing:** validates product quality and acceptance criteria.

See [Roles and Personas](./octoacme-roles-and-personas.md) for detailed
responsibilities. Stakeholders provide input, approvals, and alignment at key
decision points.

## Communication and escalation

- **Team standups:** daily in the execution guidance (or as agreed by the
  team) to surface progress, blockers, and dependencies.
- **PM/PdM alignment:** weekly; review risks and dependencies in the weekly
  sync.
- **Delivery and stakeholder updates:** weekly delivery syncs and regular
  stakeholder updates, either weekly or milestone-based; the overview also
  suggests monthly stakeholder updates.
- **Demos/reviews:** at the end of each sprint or milestone.
- **Escalation:** raise blockers with the team first, then the PM, Product
  Lead, and sponsor for business-impacting issues. For security incidents,
  follow the security incident runbook and notify Security on-call.

Execution quality is built into delivery through small, reviewable pull
requests, automated tests and linting in CI, code review, and appropriate
unit, integration, smoke, security, and manual QA. Releases require acceptance
criteria and CI/security checks to pass, plus release notes, a rollback plan,
and post-deployment verification.
