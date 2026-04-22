# OctoAcme Project Management Overview

## Purpose
Provide a concise, shareable introduction to how OctoAcme runs projects so new teammates can quickly understand our approach, roles, and key artifacts.

## Scope
Applies to all cross-functional projects that deliver product features, services, or integrations.

## Principles
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has a named Project Manager (PM) and Product Lead.
- Data-informed decisions: measure impact and iterate based on evidence.
- Psychological safety: encourage feedback and learning.

## Core Roles
- Project Manager (PM): coordinates delivery, schedules, risk, communications.
- Product Manager (PdM): defines outcomes, prioritizes backlog, and measures success.
- Developers: implement features, collaborate on design and testability.
- QA/Testing: validate quality and acceptance criteria.
- Stakeholders: provide inputs and approvals.

## Key Artifacts
- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

## Lifecycle (high-level)
1. Initiation: problem statement, stakeholders, high-level timeline.
2. Planning: scope, resources, milestones, dependencies.
3. Execution: build, test, review, iterate.
4. Release: deploy, verify, announce.
5. Close & Retrospective: capture learnings and next steps.

## Communication Cadence
- Weekly sync between PM + PdM
- Twice-weekly standups for delivery team (or as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed

## How to use these docs
- Keep the Project Charter updated in the project repo.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.

## Project Management Summary
OctoAcme manages delivery through a lightweight lifecycle of initiation, planning, execution, release, and close/retrospective. In initiation, teams confirm the business need, define measurable outcomes, align stakeholders, and make a go/no-go decision for planning. The core starting artifact is a project one-pager/charter that captures the problem statement, goals, success metrics, stakeholders, initial timeline, and early risks. Once approved, the team sets up a project board or repo structure so planning and execution have a clear source of truth.

Planning turns the approved idea into a workable delivery path. Teams run a kickoff, build and prioritize a backlog with acceptance criteria, estimate scope, define a Definition of Done (DoD), and map dependencies. They also create a release plan with milestones and maintain a risk register that tracks impact, likelihood, ownership, and mitigation actions. This stage formalizes how work is sequenced, how cross-team dependencies are handled, and how risks are monitored throughout delivery.

Execution follows a steady operating cadence and clear role ownership. Project Managers coordinate timelines, risks, dependencies, and communications; Product Managers define outcomes and prioritize the backlog; Developers implement and test increments; QA validates acceptance; and stakeholders provide input and approvals. Team rhythm includes daily standups, weekly delivery syncs, and sprint/milestone demos, supported by project board workflow states (Backlog, Ready, In Progress, In Review, QA, Done). Escalation paths are explicit: team triage first, then PM-to-Product Lead/dependent teams, then sponsor-level escalation for business-impacting blockers.

Quality assurance is embedded in both execution and release. OctoAcme expects small pull requests, issue linkage, clear acceptance criteria in PR descriptions, and passing CI checks before merge. CI checks include automated tests, linting, and security scanning, with approval requirements defined by team policy. Testing spans unit, integration, and end-to-end smoke coverage for critical flows, with manual QA when needed for feature acceptance. Release readiness includes release notes, rollback planning, staging and production verification, and stakeholder announcements. Close and retrospective practices then capture lessons learned and track a small set of owned improvement actions in the backlog.
