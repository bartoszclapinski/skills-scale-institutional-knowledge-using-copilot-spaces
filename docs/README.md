# OctoAcme Project Management Docs

This README indexes the OctoAcme project management process documents and provides a concise overview of how OctoAcme runs projects. It is intended as the canonical landing page for process guidance to improve discoverability and onboarding.

## Brief overview of OctoAcme project management processes

OctoAcme follows a structured project lifecycle that moves work from initiation through planning, execution, release, and retrospective. Initiation centers on a lightweight Project One-pager that validates the problem, stakeholders, success metrics, and an initial decision gate. Planning translates approved initiatives into a prioritized backlog, estimates, a Definition of Done, and a release/milestone plan so the team can commit to shippable increments.

Execution emphasizes iterative delivery, traceability, and PR discipline. Work is tracked on a project board with columns such as Backlog, Ready, In Progress, In Review, QA, and Done. Pull requests should be small, reference issues and acceptance criteria, and pass CI (tests, linting, security scans) before review. Team rhythm includes daily standups for blockers and progress, weekly delivery syncs for status and risks, and sprint demos to review completed work.

Quality assurance combines automated and manual practices to reduce risk and maintain reliability. Developers are expected to write unit and integration tests; CI enforces automated test suites, linting, and security scans. Releases follow a pre-release checklist (smoke tests, rollback plan, release notes) and post-deploy verifications. Retrospectives after sprints or releases capture action items that feed continuous improvement back into the backlog.

## Docs

- [octoacme-project-management-overview.md](octoacme-project-management-overview.md) — concise introduction to roles, principles, lifecycle, and how to use the docs
- [octoacme-project-initiation.md](octoacme-project-initiation.md) — project initiation guide and one-pager template
- [octoacme-project-planning.md](octoacme-project-planning.md) — planning activities, backlog template, and risk/dependency management
- [octoacme-execution-and-tracking.md](octoacme-execution-and-tracking.md) — team rhythm, workflows, QA, and execution checklist
- [octoacme-release-and-deployment.md](octoacme-release-and-deployment.md) — release types, deployment checklist, and rollback playbook
- [octoacme-retrospective-and-continuous-improvement.md](octoacme-retrospective-and-continuous-improvement.md) — retrospective structure and tracking improvements
- [octoacme-risks-and-communication.md](octoacme-risks-and-communication.md) — risk register guidance and communication templates
- [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md) — role and persona definitions used across the docs

## Suggested next steps

- Link this README from onboarding materials and the project board
- Review the content with stakeholders and add any project-specific links or owners
