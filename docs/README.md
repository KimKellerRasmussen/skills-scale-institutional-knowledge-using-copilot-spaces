# OctoAcme Project Management Process Docs

This folder contains OctoAcme’s lightweight, iterative project management playbook. Work generally follows a simple lifecycle: **Initiation → Planning → Execution → Release → Close/Retrospective**. The goal is to keep delivery predictable and transparent by favoring small, testable increments, clear ownership, and a consistent set of shared artifacts.

Projects start with a **Project One-pager/Charter** that defines the problem, SMART objective, success metrics, stakeholders, rough timeline, and initial risks. After approval, planning turns that intent into an actionable plan: a prioritized backlog with acceptance criteria, estimates, dependencies, a **Definition of Done**, and an initial QA/test approach. This keeps scope manageable while aligning milestones and releases.

Execution is tracked on a project board (e.g., **Backlog → Ready → In Progress → In Review → QA → Done**) and reinforced with a disciplined pull request workflow: keep PRs small when possible, link PRs to issues and acceptance criteria, ensure CI (tests/lint/security scans) is green before review, and require approvals before merge (per team policy). Communication follows a regular cadence—standups to surface blockers, weekly delivery syncs for progress and risks, and demos/reviews at sprint or milestone boundaries—so stakeholders have a reliable view of status.

Quality and risk management are continuous. Teams use unit/integration testing, end-to-end smoke tests for critical flows, security scanning, and manual QA when needed. Releases follow a checklist (readiness, notes, rollback plan, staged deploys, post-deploy verification, and announcements). Retrospectives capture learnings and convert them into owned, time-bound action items, feeding improvements back into this documentation.

## How to use these docs
- Treat these documents as the **single source of truth** for how projects run at OctoAcme.
- For a specific project, keep the project’s charter/status (often in the project repo README) up to date and link back to the relevant docs here.
- When you discover gaps or improvements, open an issue using the process-doc update template in `.github/ISSUE_TEMPLATE/`.

## What’s in this folder
- [Project management overview](./octoacme-project-management-overview.md)
- [Project initiation guide](./octoacme-project-initiation.md)
- [Project planning](./octoacme-project-planning.md)
- [Execution & tracking](./octoacme-execution-and-tracking.md)
- [Risk management & communication](./octoacme-risks-and-communication.md)
- [Release & deployment guide](./octoacme-release-and-deployment.md)
- [Retrospective & continuous improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles & personas](./octoacme-roles-and-personas.md)