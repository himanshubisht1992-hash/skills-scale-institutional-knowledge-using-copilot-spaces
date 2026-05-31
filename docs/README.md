# OctoAcme Project Management Docs README

Welcome to the OctoAcme Project Management Docs! This README serves as a central index and quick reference for all our project and program management process documents.

## OctoAcme Project Management — Overview

OctoAcme uses a lightweight, iterative approach to project management informed by best practices and focused on continuous improvement, clear ownership, and regular communication. The organization follows a structured five-phase project lifecycle: Initiation, Planning, Execution, Release, and Close & Retrospective.

### Core Principles
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

### Key Workflows & Practices

**Roles & Responsibilities**: OctoAcme defines clear roles with distinct responsibilities:
- **Product Managers** own the vision and prioritize the backlog
- **Project Managers** coordinate delivery, manage schedules, risks, and communications
- **Developers** implement features, collaborate on design, and ensure quality
- **QA/Testing** validates acceptance criteria and quality standards

**Communication Cadence**: Regular communication ensures alignment across teams:
- Weekly PM-to-Product Manager syncs
- Twice-weekly delivery standups
- Monthly stakeholder updates
- Ad-hoc escalations as needed (three-tier escalation path: Team → PM → Product Lead → Sponsor)

**Execution & Quality Assurance**: Teams use GitHub Projects with standardized workflows:
- Small PRs (≤400 lines when possible)
- Mandatory CI/CD checks and automated testing
- At least one approval before merging
- Unit tests, integration tests, and end-to-end smoke tests
- Security scanning in CI
- Manual QA for feature acceptance when needed

**Risk Management**: Continuous risk monitoring throughout the project lifecycle:
- Risks captured in a Risk Register during planning
- Weekly review and status updates
- Clear mitigation plans and owners
- Escalation paths for high-impact issues

**Continuous Improvement**: Regular retrospectives after sprints and releases to capture learnings and convert them into actionable improvements.

## 🔗 Process Docs Index

| Document | Purpose |
|----------|------|
| [Project Management Overview](octoacme-project-management-overview.md) | Introduction to OctoAcme's approach, roles, artifacts, and lifecycle |
| [Project Initiation Guide](octoacme-project-initiation.md) | Steps to validate business need, align stakeholders, and authorize work |
| [Project Planning](octoacme-project-planning.md) | Convert approved initiatives into actionable plans and prioritized backlogs |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Manage day-to-day execution, track progress, and maintain team rhythm |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Identify, manage, and communicate risks and dependencies |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Standardize release processes to reduce risk and improve observability |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and convert them into actionable improvements |
| [Roles and Personas](octoacme-roles-and-personas.md) | Define typical roles, responsibilities, goals, and communication patterns |

## Getting Started

**New team members**: Start with the [Project Management Overview](octoacme-project-management-overview.md) to understand our approach and key artifacts.

**Starting a new project**: Follow the [Project Initiation Guide](octoacme-project-initiation.md) to validate the project and align stakeholders.

**Running a project**: Reference the relevant docs for your current phase (Planning → Execution → Release → Retrospective).

**Contributing or updating**: Use the [Process Doc Update issue template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to propose changes or additions to process documentation.

---

*Last updated: 2026-05-31*
