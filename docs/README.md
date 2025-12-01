# OctoAcme Project Management Docs

This repository contains OctoAcme's program-level project management guidance. The documents in this folder capture the lightweight, repeatable processes our teams use to initiate, plan, execute, and release work. They emphasize clear ownership, measurable outcomes, short feedback loops, and a single source of truth for decisions and status.

OctoAcme follows an iterative delivery model: work starts with a concise Project One-pager and an initiation checklist to validate the problem, success metrics, stakeholders, and readiness to plan. Approved initiatives are broken into a prioritized backlog, estimated, and planned into releases and sprints. Execution uses a project board workflow (Backlog → Ready → In Progress → In Review → QA → Done) and a disciplined PR/CI pipeline that requires small PRs, linked issues and acceptance criteria, automated tests and linting, and reviewer approvals before merge.

Roles and communication are explicit so teams scale without ambiguity: Product Managers define outcomes and prioritize the backlog; Project Managers coordinate delivery, risks, and stakeholder communications; developers implement and test; QA validates acceptance; and stakeholders receive regular updates. The cadence mixes daily standups, weekly delivery syncs, milestone demos, and monthly stakeholder updates with a single source-of-truth project README or release doc for status.

Quality assurance and continuous improvement are built into every stage. Code-level quality is enforced with unit/integration tests, security scanning in CI, and end-to-end smoke tests for critical flows; manual QA is used where needed. Retrospectives after sprints, releases, or incidents produce prioritized action items that feed back into the backlog so the process continually improves.

## Documentation Index
- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)

## How to use these docs
- Start with the Project Management Overview to understand our lifecycle and roles.
- Create or update a Project One-pager during initiation (see Project Initiation Guide).
- Use the planning and execution docs to run sprints and releases, and add project-specific artifacts to the project repo under docs/ or `.copilot/` for Copilot Spaces context.

## Contributing
If you'd like to improve these process docs, open an issue (use the "Add Content to Project Management Process Docs" template) or submit a PR updating the relevant file. For editorial or process changes that affect multiple teams, please coordinate with your PM and Product Lead.
