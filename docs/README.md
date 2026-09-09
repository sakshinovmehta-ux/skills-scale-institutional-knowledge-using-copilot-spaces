# OctoAcme Project Management Documentation

## Overview
OctoAcme uses a structured, iterative project management approach that emphasizes customer value, clear ownership, data-driven decisions, and psychological safety. This documentation provides guidance for all team members on how we plan, execute, and improve our delivery processes.

## Core Principles
- **Customer-first**: prioritize customer value and usability
- **Iterative delivery**: deliver small, testable increments
- **Clear ownership**: each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: measure impact and iterate based on evidence
- **Psychological safety**: encourage feedback and learning

## OctoAcme Project Management Processes

OctoAcme operates a structured, customer-first project management framework built on iterative delivery and clear ownership. The organization's core principles emphasize customer value, data-informed decision-making, psychological safety, and transparency across all project phases. Five key roles drive execution: **Project Managers (PMs)** coordinate schedules and communications, **Product Managers (PdMs)** define outcomes and prioritize work, **Developers** implement features collaboratively, **QA/Testing** validates quality, and **Stakeholders** provide inputs and approvals. Communication flows through weekly PM-PdM syncs, twice-weekly delivery team standups, and monthly stakeholder updates, ensuring alignment across all levels.

The project lifecycle follows a five-stage progression: **Initiation** begins with a lightweight one-pager defining the problem, success metrics, stakeholders, and timeline; **Planning** breaks work into prioritized, estimated backlog items with clear acceptance criteria and a release roadmap; **Execution** manages day-to-day delivery through daily standups, project boards (GitHub Projects), and pull request workflows that enforce code review and automated testing; **Release** standardizes deployment through pre-release checklists, smoke tests, and rollback plans; and **Closing** captures learnings through retrospectives focused on continuous improvement. Throughout execution, OctoAcme maintains a risk register tracking dependencies and mitigation strategies, escalated through team-level → PM → Product Lead → Sponsor paths as needed.

Quality assurance is deeply embedded in OctoAcme's workflows. Teams implement unit tests, integration tests, and end-to-end smoke tests within CI/CD pipelines, combined with manual QA for feature acceptance. Definition of Done standards, small PR sizes (≤400 lines), and mandatory code review approval gates ensure reliability. Additionally, security scanning in CI and incident-response playbooks with blameless retrospectives address production issues systematically.

Continuous improvement is institutionalized through retrospectives held after each sprint, release, or significant milestone. These sessions identify what went well and what could be improved, generating 2-3 prioritized action items with clear owners and due dates. The organization tracks metric progress, celebrates wins, and integrates learnings into the backlog, fostering a culture where feedback and iterative change drive long-term success.

## Process Documentation

### Initiation & Planning
- [Project Initiation Guide](./octoacme-project-initiation.md) — Define initial steps to validate work and align stakeholders
- [Project Planning](./octoacme-project-planning.md) — Break approved initiatives into actionable plans and backlogs

### Execution & Delivery
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Manage day-to-day execution and progress tracking
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — Standardize feature releases to production

### Management & Oversight
- [Project Management Overview](./octoacme-project-management-overview.md) — High-level introduction to OctoAcme's approach
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Identify, manage, and communicate risks
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and drive improvements

### Roles & Responsibilities
- [Roles and Personas](./octoacme-roles-and-personas.md) — Definitions of typical roles and responsibilities

## Quick Reference Guide

| Topic | Document | When to Use |
|-------|----------|------------|
| Starting a new project | [Project Initiation Guide](./octoacme-project-initiation.md) | You have a new idea or feature proposal ready to explore |
| Breaking down work into sprints | [Project Planning](./octoacme-project-planning.md) | An approved initiative is ready for detailed planning |
| Day-to-day team operations | [Execution & Tracking](./octoacme-execution-and-tracking.md) | You need guidance on standups, PRs, testing, and progress tracking |
| Understanding OctoAcme's PM framework | [Project Management Overview](./octoacme-project-management-overview.md) | You're new to OctoAcme or need a high-level refresher |
| Managing project risks | [Risk Management & Communication](./octoacme-risks-and-communication.md) | You need to identify, track, or escalate risks and dependencies |
| Releasing to production | [Release & Deployment Guide](./octoacme-release-and-deployment.md) | Features are ready to ship and you need release procedures |
| Learning from project outcomes | [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | A sprint, release, or project has concluded |
| Understanding team roles | [Roles and Personas](./octoacme-roles-and-personas.md) | You need clarity on PM, PdM, Developer, or QA responsibilities |

## Getting Started

**For new team members:** Start with the [Project Management Overview](./octoacme-project-management-overview.md) to understand our overall approach, then use the Quick Reference Guide above to dive into topics relevant to your role.

**For project leads:** Reference the Initiation & Planning section when kicking off new work, and use the Management & Oversight section for ongoing project health.

**For individual contributors:** Focus on Execution & Delivery for guidance on how we build, test, and ship features.

---

*Last updated: September 2026*
