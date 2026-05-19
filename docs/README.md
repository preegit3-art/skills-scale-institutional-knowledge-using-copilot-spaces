# OctoAcme Project Management Docs

Welcome! This README acts as an index and overview for all OctoAcme project management processes. Use this guide to quickly find documentation relevant to your role and current project phase.

## Project Management Summary

OctoAcme operates on a structured lifecycle-based project management approach that emphasizes customer-first delivery, iterative development, and clear ownership. The methodology spans five primary phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Closure & Retrospective**. At its foundation, OctoAcme is guided by principles of psychological safety, data-informed decision-making, and delivering small, testable increments.

### Key Roles & Communication Cadence

OctoAcme defines clear accountability through four primary personas: **Project Managers** coordinate schedules, risks, and communications; **Product Managers** define outcomes and prioritize the backlog; **Developers** implement features and maintain quality; and **QA/Testing** validates acceptance criteria. Communication happens through a consistent cadence: daily standups (15 min) focused on progress and blockers, weekly PM-PdM syncs, twice-weekly delivery team standups, and monthly stakeholder updates. A formal escalation path (Team → PM → Product Lead → Sponsor) ensures blockers move up the chain when needed.

### Execution, Quality & Continuous Improvement

During execution, work flows through a project board with columns (Backlog → Ready → In Progress → In Review → QA → Done), and teams follow a strict pull request workflow: small PRs (≤400 lines), automated CI testing and linting, and at least one approval before merging. Quality assurance is integrated throughout—unit tests for new logic, integration tests where applicable, end-to-end smoke tests before release, and security scanning in CI. After each sprint, release, or milestone, teams conduct timeboxed retrospectives to capture learnings, identify 2–3 action items, and feed improvements back into the process—creating a culture of continuous iteration and transparency.

## Docs Index

Navigate to the process document most relevant to your current project phase or role:

### Foundational Docs

- **[Project Management Overview](./octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, core roles, key artifacts, and lifecycle
- **[Roles and Personas](./octoacme-roles-and-personas.md)** — Detailed descriptions of Developer, Product Manager, and Project Manager roles and responsibilities

### Project Lifecycle

- **[Project Initiation Guide](./octoacme-project-initiation.md)** — How to validate and authorize new work, align stakeholders, and create a lightweight plan
- **[Project Planning](./octoacme-project-planning.md)** — Turn an approved initiative into an actionable plan and backlog for delivery
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Guidance for managing day-to-day execution, standups, workflows, and progress tracking
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Standardize how OctoAcme releases features to production to reduce risk and improve observability
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements

### Cross-Cutting Concerns

- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — How to identify, manage, and communicate risks, dependencies, and stakeholder updates

## Quick Start

**New to OctoAcme?** Start here:
1. Read [Project Management Overview](./octoacme-project-management-overview.md) for a 5-minute orientation
2. Review [Roles and Personas](./octoacme-roles-and-personas.md) to understand your role and peers
3. Navigate to the lifecycle phase most relevant to your current work

**Managing a project?** Follow this order:
1. [Project Initiation Guide](./octoacme-project-initiation.md)
2. [Project Planning](./octoacme-project-planning.md)
3. [Execution & Tracking](./octoacme-execution-and-tracking.md)
4. [Release & Deployment Guide](./octoacme-release-and-deployment.md)
5. [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

Use [Risk Management & Communication](./octoacme-risks-and-communication.md) as a reference throughout all phases.

## Contributing to These Docs

Process docs are living artifacts. To propose updates, improvements, or new sections:
- File an issue using the **"Add Content to Project Management Process Docs"** template (found in `.github/ISSUE_TEMPLATE/`)
- Reference the specific document and explain the gap or improvement
- Include suggested content and rationale
- All updates are reviewed to ensure alignment with OctoAcme principles

---

**Last updated:** 2026-05-19  
For questions or feedback, reach out to your Project Manager or Product Lead.