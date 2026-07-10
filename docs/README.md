# OctoAcme Project Management Docs

Welcome to OctoAcme's centralized project management process documentation. These guides help teams execute projects consistently, manage risks, and continuously improve.

## Quick Start

New to OctoAcme? Start with the [Project Management Overview](octoacme-project-management-overview.md) for a high-level introduction.

## OctoAcme Project Management Overview

OctoAcme follows a structured five-phase project lifecycle: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. The initiation phase validates business need and stakeholder alignment through a lightweight Project One-pager that captures the problem statement, goals, success metrics, and initial resource estimates. Once approved, the planning phase breaks work into shippable increments with prioritized backlogs, clear acceptance criteria, and estimated effort using T-shirt sizing or story points. During execution, work moves through a GitHub Projects board (Backlog → Ready → In Progress → In Review → QA → Done), with small pull requests (≤400 lines) requiring at least one approval before merging. This iterative delivery approach is complemented by a structured release process with pre-release requirements (passing CI, security scans, smoke tests), deployment checklists, and rollback playbooks to minimize production risk.

OctoAcme operates with clearly defined, cross-functional roles: **Project Managers** coordinate delivery schedules, manage risks and dependencies, and ensure stakeholder communication; **Product Managers** define what to build, prioritize the backlog, and measure outcomes through data-driven decisions; **Developers** implement features, write tests, and participate in design reviews; and **QA/Testing** validates quality against acceptance criteria. This clear ownership structure reduces ambiguity and ensures accountability, with each project having a named PM and Product Lead who align weekly and maintain transparency across the organization.

Communication cadence is built into the rhythm through daily standups (15 minutes), weekly delivery syncs, and monthly stakeholder updates. OctoAcme maintains a Risk Register that tracks each risk's ID, description, impact, likelihood, owner, and mitigation plan—reviewed weekly during syncs with a three-level escalation path (team-level → PM → Product Lead → Sponsor). Status is shared transparently using a standard template covering progress, next steps, risks & blockers, and decisions needed, ensuring all stakeholders have visibility into project health.

Quality assurance is embedded throughout delivery with unit tests for new logic, integration tests where applicable, end-to-end smoke tests before release, and security scanning in CI. Each sprint or release concludes with a structured retrospective (45–75 minutes) that captures what went well, what could improve, and 2–3 prioritized action items with clear owners and due dates. This continuous improvement culture, combined with Definition of Done standards and post-deployment verification, creates a learning organization that iterates on both product and process.

## All Process Documents

### 📋 Lifecycle Phases

1. **[Project Initiation Guide](octoacme-project-initiation.md)** — Validate ideas, align stakeholders, authorize work
2. **[Project Planning](octoacme-project-planning.md)** — Define scope, create backlog, identify risks and dependencies
3. **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Daily standups, sprint management, quality assurance
4. **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Prepare releases, deploy to production, handle rollbacks
5. **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings, drive improvements

### 🛠 Cross-cutting Topics

- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Manage risks, escalate issues, communicate with stakeholders
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Understand key roles (PM, PdM, Developers, QA) and responsibilities

## Find the Right Document

- **Starting a new project?** → [Project Initiation Guide](octoacme-project-initiation.md)
- **Planning the work?** → [Project Planning](octoacme-project-planning.md)
- **In active development?** → [Execution & Tracking](octoacme-execution-and-tracking.md)
- **Releasing to production?** → [Release & Deployment Guide](octoacme-release-and-deployment.md)
- **Project complete or lessons learned?** → [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- **Managing blockers or stakeholder updates?** → [Risk Management & Communication](octoacme-risks-and-communication.md)

## Related Resources

- **Issue Templates** — Found in `.github/ISSUE_TEMPLATE/`, these templates standardize how teams request updates to process documentation
- **Copilot Spaces Context** — Add these docs to your Copilot Space to get context-aware guidance aligned with OctoAcme's practices
