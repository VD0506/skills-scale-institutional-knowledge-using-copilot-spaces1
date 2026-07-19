# OctoAcme Project Management Docs

This folder contains OctoAcme’s canonical project management process documents. Use these docs as the single source of truth for how we initiate, plan, execute, release, and improve cross-functional projects.

## Overview

OctoAcme follows a lifecycle-driven approach: Initiation (validate ideas with a one‑pager and align stakeholders), Planning (create a prioritized backlog, estimates, Definition of Done, and release plan), Execution & Tracking (work via project boards, CI-backed PR workflow, regular standups and demos, and escalation paths for blockers), Release & Deployment (pre-release checks, automated pipelines where possible, smoke tests, rollback plans), and Retrospective & Continuous Improvement (capture learnings, prioritize action items, measure impact). A simple risk register and clear escalation paths ensure visibility and timely mitigation of issues.

## Key workflows and quality practices

- Work organization: Project boards with columns Backlog → Ready → In Progress → In Review → QA → Done; backlog items include acceptance criteria and an owner.
- PR & CI: Small, testable pull requests with linked issues and acceptance criteria; automated tests, linting, and security scans run in CI before review.
- QA: Unit and integration tests are expected for new logic, smoke tests for critical flows, and manual QA where required. Pre-release checklists enforce passing CI, release notes, and rollback plans.
- Communication: Daily standups for progress and blockers, weekly delivery syncs for status and risk review, demos at the end of sprints/milestones, and monthly stakeholder updates. Decision rationale and follow-ups are recorded in the Decision Log.
- Roles: Clear role definitions for Project Manager (delivery coord.), Product Manager (outcomes & prioritization), Developers (implement & test), QA (validate acceptance), and Stakeholders (inputs & approvals). Each artifact should have an owner and reviewers.

## Links to the docs

- [Overview — octoacme-project-management-overview.md](docs/octoacme-project-management-overview.md)
- [Initiation — octoacme-project-initiation.md](docs/octoacme-project-initiation.md)
- [Planning — octoacme-project-planning.md](docs/octoacme-project-planning.md)
- [Execution & Tracking — octoacme-execution-and-tracking.md](docs/octoacme-execution-and-tracking.md)
- [Risks & Communication — octoacme-risks-and-communication.md](docs/octoacme-risks-and-communication.md)
- [Release & Deployment — octoacme-release-and-deployment.md](docs/octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement — octoacme-retrospective-and-continuous-improvement.md](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas — octoacme-roles-and-personas.md](docs/octoacme-roles-and-personas.md)

## How to contribute

- Use the `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` template to request new content or updates. Link the resulting PR to the issue and add a CHANGELOG entry. For small edits, follow the owner’s approval rules documented in each file.
