# OctoAcme Project Management Docs

This repository contains OctoAcme's project management and delivery process documents. The docs are intended to give new and existing teammates a single, versioned source of truth for how we initiate, plan, execute, release, and continuously improve projects.

OctoAcme follows a lightweight, repeatable approach centered on clear artifacts, short feedback loops, and named ownership. Work begins with a Project One-pager and an initiation checklist to confirm the problem, success metrics, stakeholders, and the go/no‑go to enter planning. Approved initiatives are broken into a prioritized backlog with estimates, acceptance criteria, a Definition of Done, and an explicit release plan so scope and expectations stay visible throughout delivery.

Execution uses a project board workflow (Backlog → Ready → In Progress → In Review → QA → Done) and a disciplined PR/CI pipeline to keep changes small, testable, and reviewable. Pull requests should be small and link to issues with acceptance criteria, automated tests and linting should run in CI, and at least one reviewer approval is required before merging. Releases follow a checklist (staging smoke tests, release notes, rollback plan, and post‑deploy verifications) to reduce risk.

Roles and communications are explicit to scale coordination without ambiguity: Project Managers coordinate delivery and risks, Product Managers own outcomes and prioritization, developers implement and test, QA validates acceptance, and stakeholders receive status and decisions. The cadence mixes daily standups and weekly delivery syncs with demos at sprint/milestone ends and monthly stakeholder updates. Quality assurance is embedded across the lifecycle via unit/integration tests, end‑to‑end smoke tests, CI security scans, manual QA where needed, and retrospectives that produce action items feeding back into the backlog.

## Documentation Index
- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)

## How to contribute
To propose edits or add new process documents, use the "Add Content to Project Management Process Docs" issue template (see .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml). Summarize the change, explain why it's needed, and include example content if possible. Link PRs to the relevant issue and keep changes focused so reviews are fast.

---

*Acceptance criteria for this change:*
- README is placed at docs/README.md and provides a clear overview aligned with existing process docs.
- Documentation Index links to all files in docs/.
- Contributing guidance references the provided issue template.
