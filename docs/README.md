# OctoAcme Project Management Docs

## Overview
OctoAcme follows an iterative, outcomes-driven approach to delivering product features and integrations. Projects begin with a lightweight initiation to validate business need and define measurable success criteria, move into focused planning to create a prioritized backlog and Definition of Done, and then execute in small, testable increments. Clear ownership, data-informed decisions, and psychological safety are core principles that guide how teams plan, build, and learn.

Day-to-day work uses a project board workflow (Backlog → Ready → In Progress → In Review → QA → Done) supported by a predictable team rhythm: short daily standups, a weekly delivery sync, and demos at the end of each sprint or milestone. Pull requests are kept small, linked to issues and acceptance criteria, and gated by CI and at least one approval. Project artifacts (roadmaps, release plans, risk registers) live in this docs/ directory to provide a single source of truth.

Quality assurance is integrated throughout the lifecycle: unit and integration tests for new logic, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for feature acceptance when required. Releases follow a pre-release checklist, rollback planning, staged deployments, and post-deploy verifications. Retrospectives capture learnings and convert them into tracked action items for continuous improvement.

Risk management and communications are explicit: maintain a simple risk register, review risks in weekly syncs, and escalate using defined paths (team → PM → Product Lead → Sponsor). Use the templates and communication examples in this folder for consistent weekly status updates and incident messages.

## Process Documents
- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](./octoacme-roles-and-personas.md)

## Roles & Responsibilities
- Project Manager (PM): coordinates delivery, schedules, risks, and communications.
- Product Manager (PdM): defines outcomes, prioritizes the backlog, and measures success.
- Developers: implement features, maintain tests and docs, and participate in reviews.
- QA/Testing: validate acceptance criteria and perform manual or exploratory testing where needed.

## Getting Started
If you're new to OctoAcme, start with the Project Management Overview for a high-level orientation, then read the Initiation and Planning guides to understand how work is proposed and scoped. Use the Execution & Tracking and Release guides for day-to-day operations and deployment readiness, and follow the Retrospective guide to capture continuous-improvement actions.

## How to Contribute
To propose changes to these process docs, open an issue using the "Add Content to Project Management Process Docs" template in .github/ISSUE_TEMPLATE, or submit a PR with clear rationale and proposed text. See the issue template for required fields and acceptance criteria.
