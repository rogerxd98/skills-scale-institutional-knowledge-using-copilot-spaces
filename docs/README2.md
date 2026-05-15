# OctoAcme Project Management Docs

Welcome! This README serves as an entrypoint for all OctoAcme project management documentation. Use this guide to quickly understand our project management methodology and navigate all related materials.

## Project Management Processes Overview

OctoAcme follows a structured, customer-first project lifecycle that emphasizes iterative delivery, clear ownership, and data-informed decision-making. Our approach is organized around five distinct phases:

### Phase 1: Initiation
Teams validate business needs through a Project One-pager that establishes the problem statement, success metrics, stakeholder list, and high-level timeline. This phase ends with a go/no-go decision before moving into detailed planning.

### Phase 2: Planning
Approved work is broken into shippable increments with clear acceptance criteria, scope estimates, and prioritized backlog items. Teams define their Definition of Done, identify dependencies, and create a release plan with milestone mapping.

### Phase 3: Execution & Tracking
Development teams work in sprints or iterations, using GitHub Projects for workflow visibility. Work progresses through columns: Backlog → Ready → In Progress → In Review → QA → Done. Daily standups surface blockers, and weekly delivery syncs track progress against milestones.

### Phase 4: Release & Deployment
Before release, teams verify acceptance criteria are met, CI and security scans pass, and rollback plans are documented. Deployments follow a staged approach (staging → production) with post-deploy verification and stakeholder notification.

### Phase 5: Retrospective & Continuous Improvement
After each sprint or milestone, teams conduct retrospectives to capture learnings and define prioritized action items. These improvements feed back into the project backlog, creating a continuous feedback loop.

## Core Roles & Responsibilities

- **Project Manager (PM):** Coordinates delivery, manages schedules, risks, communications, and ensures transparent project documentation and status reporting.
- **Product Manager (PdM):** Defines what should be built, prioritizes the backlog, establishes success metrics, and validates solutions through data and user research.
- **Developers:** Implement features, collaborate on design and code reviews, write and maintain tests, and help identify technical risks.
- **QA/Testing:** Validates quality and acceptance criteria across unit, integration, and end-to-end testing.

## Quality & Risk Management

OctoAcme emphasizes quality through:
- Unit tests for new logic and integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI pipelines
- Manual QA for feature acceptance when needed
- A risk register maintained throughout the project lifecycle with escalation paths: team-level triage → PM escalation → sponsor-level escalation

## Communication Cadence

- **Daily:** 15-minute standups (progress, blockers, dependencies)
- **Weekly:** PM-to-PdM alignment and delivery team syncs
- **Sprint/Milestone:** Demo, review, and retrospective sessions
- **Monthly:** Stakeholder updates and status reporting
- **Ad-hoc:** Escalations as needed for blockers and risks

## Available Documentation

Navigate to each process document for detailed guidance:

- [**Project Management Overview**](octoacme-project-management-overview.md) — High-level introduction to OctoAcme's approach, principles, roles, and lifecycle.
- [**Project Initiation**](octoacme-project-initiation.md) — Steps to validate and authorize work, align stakeholders, and create a lightweight plan.
- [**Project Planning**](octoacme-project-planning.md) — How to break work into shippable increments, estimate scope, and define dependencies.
- [**Execution & Tracking**](octoacme-execution-and-tracking.md) — Day-to-day execution guidance, team rhythm, workflows, and quality practices.
- [**Risks & Communication**](octoacme-risks-and-communication.md) — Risk register management, stakeholder communication, and escalation paths.
- [**Release & Deployment**](octoacme-release-and-deployment.md) — Standardized release process, pre-release requirements, and incident playbooks.
- [**Retrospective & Continuous Improvement**](octoacme-retrospective-and-continuous-improvement.md) — How to run retrospectives and convert learnings into actionable improvements.
- [**Roles & Personas**](octoacme-roles-and-personas.md) — Detailed definitions of Project Manager, Product Manager, and Developer personas.

## Quick Start for New Teams

1. **Read** the [Project Management Overview](octoacme-project-management-overview.md) to understand our principles and roles.
2. **Begin Initiation** using the [Project Initiation](octoacme-project-initiation.md) guide to validate your project and create a One-pager.
3. **Move to Planning** following the [Project Planning](octoacme-project-planning.md) document to build your backlog and timeline.
4. **Execute with Confidence** using the [Execution & Tracking](octoacme-execution-and-tracking.md) guide and refer to other docs as needed.
5. **Continuously Improve** by running retrospectives and updating your processes based on team feedback.

## How to Use These Docs

- Keep your Project Charter updated in your project repository.
- Reference these docs during project kickoffs, planning sessions, and team onboarding.
- Use the checklists in each document to ensure completeness (e.g., Initiation Checklist, Planning Checklist, Deployment Checklist).
- Add process-specific docs to `.copilot/` if you want Copilot Spaces to use them as context for team assistance.

---

For questions or process improvements, refer to the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template.
