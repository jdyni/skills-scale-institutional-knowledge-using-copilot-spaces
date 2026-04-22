# OctoAcme Roles and Personas

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

## QA / Testing

### Role Summary
QA/Testing validates that delivered increments meet acceptance criteria, quality standards, and release expectations before production rollout.

### Responsibilities
- Define and maintain test strategy for the project scope
- Validate acceptance criteria across planned and completed work
- Track and communicate defects with severity and repro details
- Coordinate regression and release smoke coverage
- Partner on quality gates in CI and release checklists

### Goals
- Reduce escaped defects and release risk
- Improve confidence in shippable increments
- Keep quality criteria explicit and measurable

### Typical Communication
- Test plans and test execution updates
- Defect triage notes and quality status summaries
- Go/no-go input for release readiness

---

## User Researcher

### Role Summary
User Researchers generate evidence about customer problems, behaviors, and outcomes so product and delivery teams can make better prioritization and implementation decisions.

### Responsibilities
- Plan and run discovery interviews, usability sessions, or surveys
- Synthesize findings into actionable insights and opportunity areas
- Translate findings into requirement candidates with Product Managers
- Highlight user risks and assumptions that require validation
- Maintain traceability from research findings to requirements

### Goals
- Reduce solution risk by validating real user needs early
- Improve requirement quality and product outcome predictability
- Ensure prioritization decisions are evidence-informed

### Explicit Interactions with Core Roles
- **With PM:** Align research timing with project milestones and dependency plans.
- **With PdM:** Co-define research questions, success criteria, and requirement implications.
- **With Developers:** Share behavioral insights that shape technical trade-offs and implementation details.
- **With QA/Testing:** Provide user scenarios and edge cases for test design and acceptance validation.
- **With Stakeholders:** Present findings, assumptions, and recommendation rationale for decision-making.

---

## UX Designer

### Role Summary
UX Designers turn product goals and research findings into usable interaction flows, wireframes, and prototypes that teams can build and validate.

### Responsibilities
- Produce and iterate user flows, wireframes, and prototypes
- Define interaction details and accessibility expectations
- Collaborate on acceptance criteria for UX-critical behavior
- Validate design choices with quick tests and team feedback
- Support implementation review for UX fidelity

### Goals
- Improve usability, clarity, and consistency of delivered experiences
- Reduce ambiguity in requirements and implementation handoffs
- Increase adoption by delivering intuitive user journeys

### Explicit Interactions with Core Roles
- **With PM:** Coordinate design milestones and design-to-build handoff timing.
- **With PdM:** Refine scope and feature intent into concrete user experience outcomes.
- **With Developers:** Clarify implementation-ready design details and constraints.
- **With QA/Testing:** Define UX acceptance checks and expected interaction behavior.
- **With Stakeholders:** Demo design direction and gather feedback before commitment.

---

## Technical Writer

### Role Summary
Technical Writers ensure internal and external documentation is accurate, discoverable, and release-ready when product changes ship.

### Responsibilities
- Define documentation scope for each release increment
- Draft and maintain guides, release notes, and reference content
- Track documentation dependencies in backlog and release planning
- Validate docs against implemented behavior before publication
- Ensure handoff artifacts are complete for support and enablement

### Goals
- Keep user and internal documentation current with product reality
- Reduce support load caused by unclear or missing documentation
- Improve release communication quality and adoption readiness

### Explicit Interactions with Core Roles
- **With PM:** Align documentation milestones with delivery and release schedules.
- **With PdM:** Confirm audience, messaging, and documentation priorities.
- **With Developers:** Validate technical accuracy and implementation details.
- **With QA/Testing:** Confirm documented workflows against tested behavior.
- **With Stakeholders:** Coordinate launch messaging and support enablement assets.

---

## DevOps Engineer

### Role Summary
DevOps Engineers own deployment reliability, environment readiness, and operational guardrails that keep delivery predictable and resilient.

### Responsibilities
- Maintain CI/CD pipelines and release automation
- Prepare and validate deployment environments
- Define and verify monitoring, alerting, and rollback readiness
- Partner on incident response and post-incident follow-through
- Surface infrastructure and operability risks early

### Goals
- Improve deployment reliability and recovery speed
- Reduce operational risk during release and post-release windows
- Increase confidence in repeatable, observable delivery

### Explicit Interactions with Core Roles
- **With PM:** Plan deployment windows, readiness gates, and operational dependencies.
- **With PdM:** Align release sequencing with customer and business priorities.
- **With Developers:** Coordinate build/deploy requirements, observability, and rollback plans.
- **With QA/Testing:** Ensure stable test environments and production-like validation paths.
- **With Stakeholders:** Communicate deployment status, risks, and mitigation plans.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
