# OctoAcme Project Management Documentation

## Overview
OctoAcme runs projects with a lightweight, repeatable lifecycle that moves work from initiation through planning, execution, release, and retrospective. Initiation begins with a Project One-pager that captures the problem, objectives, success metrics, stakeholders, and a high-level timeline; work moves to planning after a decision gate confirms stakeholder alignment and measurable success criteria. Planning breaks approved initiatives into a prioritized backlog, identifies dependencies and risks, defines the Definition of Done, and creates a release plan and sprint-ready work.

## Workflows & Quality
Work is organized around small, testable increments and a disciplined pull request workflow. Pull requests should be small when possible (<= 400 lines), link to the associated issue and acceptance criteria, run CI (tests, linting, and security scans) before review, and require at least one approval before merging. Releases are classified (patch, minor, major) and follow a deployment checklist that includes staging smoke tests, post-deploy verification, release notes, and a rollback/incident playbook. Execution tracking emphasizes velocity and burndown metrics and dashboards for key product and reliability signals.

## Roles & Communication
Roles and responsibilities are explicit: Product Managers define outcomes and success metrics; Project Managers coordinate delivery, schedules, risks, and communications; Developers implement features and maintain tests; QA validates acceptance criteria; and stakeholders provide approvals and input. Communication is regular and structured: short daily standups for progress and blockers, weekly delivery syncs and demos, PM–PdM weekly alignment, and monthly stakeholder updates. Escalation paths and incident communication templates are documented (team → PM → Product Lead → Sponsor).

## How to use this folder
- Use these documents as the single source of truth for OctoAcme project processes.
- Link the appropriate documents from project READMEs and project boards.
- When adding or updating process docs, use the repository issue template at .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml.

## Documentation (files in this folder)
- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution and Tracking](./octoacme-execution-and-tracking.md)
- [Risks and Communication](./octoacme-risks-and-communication.md)
- [Release and Deployment](./octoacme-release-and-deployment.md)
- [Retrospective and Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)

## Acceptance criteria
- Content aligns with existing process docs
- README improves discoverability and clarity for the docs folder
- Links to each document are correct and relative so they work in the repository
