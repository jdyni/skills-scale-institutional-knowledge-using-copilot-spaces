# OctoAcme Project Management Docs

The `docs/` folder is the home for OctoAcme program and process documentation. It centralizes the standards, templates, and operating guidance teams use to initiate, plan, execute, release, and improve cross-functional work so everyone can work from a consistent source of truth.

## Project management process overview

OctoAcme follows a lightweight lifecycle of **Initiation → Planning → Execution & Tracking → Release & Deployment → Close & Retrospective**. Work starts with a clear problem statement, success metrics, stakeholder alignment, and a go/no-go decision, then moves into structured planning and delivery with frequent checkpoints to keep outcomes and timelines aligned.

Across that lifecycle, teams maintain a small set of required artifacts that drive clarity and accountability: a **Project One-pager/Charter**, a prioritized **backlog with acceptance criteria**, a **Definition of Done (DoD)**, a **risk register**, a **release plan**, and **retrospective notes with action items**. These artifacts are intentionally lightweight but specific enough to support repeatable execution and transparent decision-making.

Roles and communication are explicit. The **Project Manager (PM)** coordinates schedule, dependencies, risks, and delivery communication; the **Product Manager (PdM)/Product Lead** owns outcomes and prioritization; **Developers** implement and review shippable increments; **QA/Testing** validates quality and acceptance criteria; and **Stakeholders** provide input and approvals. Teams run a regular cadence of standups, weekly delivery syncs, and demos/reviews, with routine stakeholder updates, documented escalation paths, and a shared single source of truth for current status.

Quality assurance is embedded from PR to production. OctoAcme favors small PRs linked to issues, requires CI checks (tests, linting, and security scans), and uses review approvals before merge. Testing combines unit, integration, and end-to-end smoke coverage for critical flows, while release readiness is governed by checklists, post-deploy verification, and rollback/incident playbooks when issues arise.

## Key process documents

- [Project management overview](./octoacme-project-management-overview.md)
- [Project initiation guide](./octoacme-project-initiation.md)
- [Project planning](./octoacme-project-planning.md)
- [Execution & tracking](./octoacme-execution-and-tracking.md)
- [Release & deployment guide](./octoacme-release-and-deployment.md)
- [Risk management & communication](./octoacme-risks-and-communication.md)
- [Retrospective & continuous improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles & personas](./octoacme-roles-and-personas.md)
