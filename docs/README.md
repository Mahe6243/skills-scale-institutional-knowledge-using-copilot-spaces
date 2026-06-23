# OctoAcme Project Management Docs

Welcome to the OctoAcme project management documentation. This folder contains the processes, workflows, and best practices that guide how we run projects and deliver value to our customers.

## Overview: OctoAcme Project Management Approach

OctoAcme follows a structured, lifecycle-based approach to project management grounded in **customer-first principles** and **iterative delivery**. 

### Core Principles
- **Customer-first:** Prioritize customer value and usability
- **Iterative delivery:** Deliver small, testable increments
- **Clear ownership:** Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions:** Measure impact and iterate based on evidence
- **Psychological safety:** Encourage feedback and learning

### Key Workflow Phases
1. **Initiation:** Validate business needs through a Project One-pager and align stakeholders
2. **Planning:** Break work into shippable increments with clear acceptance criteria and risk registers
3. **Execution:** Daily standups and weekly delivery syncs with a GitHub Projects board (Backlog → Ready → In Progress → In Review → QA → Done)
4. **Release:** Standardized deployment checklists and rollback procedures
5. **Closure & Retrospective:** Capture learnings and convert into actionable improvements

### Core Roles
- **Product Managers:** Define what should be built, own the vision, prioritize the backlog, and measure outcomes
- **Project Managers:** Coordinate delivery, manage schedules, risks, and communications
- **Developers:** Design, build, test, and deliver software components
- **QA/Testing:** Validate quality and acceptance criteria

### Communication & Risk Management
- **Team rhythm:** Daily standups, weekly delivery syncs, monthly stakeholder updates
- **Risk management:** Track risks in a register with clear owners and mitigation plans
- **Escalation path:** Team-level → PM → Product Lead → Sponsor

### Quality & Delivery Practices
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests before release
- Security scanning in CI
- Small PRs (≤400 lines when possible) with issue links and acceptance criteria
- Tracking of velocity, burndown, and success metrics

---

## Process Documentation

Below are the detailed process documents that guide OctoAcme project execution:

### Foundational Guidance
- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, roles, and key artifacts

- **[Roles & Personas](octoacme-roles-and-personas.md)** — Definitions of typical roles (Developers, Product Managers, Project Managers) and their responsibilities

### Project Lifecycle

- **[Project Initiation Guide](octoacme-project-initiation.md)** — Initial steps to validate and authorize work, align stakeholders, and create a lightweight plan

- **[Project Planning](octoacme-project-planning.md)** — Turn an approved initiative into an actionable plan and backlog for delivery

- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Guidance for managing day-to-day execution and tracking progress toward milestones

- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardize how OctoAcme releases features to production to reduce risk and improve observability

- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements

### Cross-Cutting Concerns

- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identify, manage, and communicate risks and dependencies

---

## How to Use These Docs

- **New to OctoAcme?** Start with the [Project Management Overview](octoacme-project-management-overview.md) and [Roles & Personas](octoacme-roles-and-personas.md)
- **Starting a new project?** Follow the [Project Initiation Guide](octoacme-project-initiation.md) and [Project Planning](octoacme-project-planning.md)
- **In execution mode?** Reference [Execution & Tracking](octoacme-execution-and-tracking.md) and [Risk Management & Communication](octoacme-risks-and-communication.md)
- **Preparing for release?** Review the [Release & Deployment Guide](octoacme-release-and-deployment.md)
- **Wrapping up a project?** Schedule a retrospective using [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

---

## Contributing to Process Docs

To propose updates or new content for OctoAcme process documentation, please use the **[Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** issue template.

This ensures proposed changes are:
- Aligned with existing processes
- Reviewed for clarity and completeness
- Tracked and acted upon consistently
