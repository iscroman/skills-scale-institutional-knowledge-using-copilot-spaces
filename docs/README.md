# OctoAcme Project Management — README

This README provides a single entry point to the OctoAcme project management process documents and a short summary of the processes used across projects.

## Summary

OctoAcme follows an iterative, customer-focused project management approach with clear roles and responsibilities. Key phases include:

- **Initiation**: Capture problem statement, identify stakeholders, create project one-pager, and make go/no-go decision to proceed.
- **Planning**: Create prioritized backlog with acceptance criteria, estimate scope, define Definition of Done, and establish release milestones.
- **Execution & Tracking**: Run sprints using project boards, follow small PR workflows, automate CI testing, and maintain daily/weekly team rhythms.
- **Release & Deployment**: Meet pre-release requirements, deploy via automated pipelines, verify post-deploy, and maintain rollback playbooks.
- **Retrospective & Continuous Improvement**: Capture action items, track improvements, measure impact, and update processes iteratively.
- **Risk & Communication**: Maintain a risk register, communicate regularly to stakeholders, and escalate issues through defined pathways.

## Core Roles

The OctoAcme approach relies on clear role definitions and accountability. For detailed personas and responsibilities, see [Roles & Personas](#docs-in-docs).

## Docs (in docs/)

### Getting Started
- **[Project Management Overview](octoacme-project-management-overview.md)** — Concise introduction to core roles, principles, artifacts, and the project lifecycle. **Start here** if you're new to OctoAcme.

### Project Phases
- **[Project Initiation Guide](octoacme-project-initiation.md)** — How to validate and authorize new projects. Includes the one-pager template and decision gate checklist.
- **[Project Planning](octoacme-project-planning.md)** — Turning approved initiatives into actionable plans and backlogs. Covers backlog templates, estimation, Definition of Done, and the planning checklist.
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Day-to-day execution guidance. Covers team rhythms, PR workflows, quality and testing, reporting, and blocker escalation.
- **[Release & Deployment](octoacme-release-and-deployment.md)** — Standardized release processes. Includes release types, pre-release requirements, deployment checklist, and rollback playbook.
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Running effective retrospectives and tracking improvements. Includes retrospective structure and action item templates.

### Cross-Cutting Concerns
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identifying, assessing, and mitigating risks. Covers the risk register, communication templates, and escalation paths.
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Detailed role summaries and responsibilities used across OctoAcme projects. Includes core roles (Developers, Product Managers, Project Managers, QA/Testing) and extended roles (Stakeholders, Technical Leads, Design/UX, DevOps).

## How to Use These Docs

### For New Team Members
1. Start with [Project Management Overview](octoacme-project-management-overview.md) to understand the framework.
2. Review [Roles & Personas](octoacme-roles-and-personas.md) to understand your role and how you fit into projects.
3. Bookmark the phase-specific docs for reference as you work on projects.

### For Project Managers
- Use [Project Initiation Guide](octoacme-project-initiation.md) and [Project Planning](octoacme-project-planning.md) for project setup.
- Reference [Risk Management & Communication](octoacme-risks-and-communication.md) for weekly updates and escalation.
- Review [Execution & Tracking](octoacme-execution-and-tracking.md) for managing day-to-day execution.

### For Copilot Spaces
- Add relevant process docs to `.copilot/` in your project repository to ground Copilot's knowledge in your team's processes.
- Use these docs as context when creating project artifacts, issue templates, or PR guidance.

## Key Artifacts

OctoAcme projects typically produce:

- **Project Charter / One-pager** — Problem statement, goals, success metrics, stakeholders, timeline, risks, and resource needs.
- **Prioritized Backlog** — User stories or features with acceptance criteria, estimates, and priority.
- **Sprint/Iteration Plan** — Selected backlog items, team capacity, and commitment.
- **Risk Register** — Identified risks with impact, likelihood, mitigation, and status.
- **Definition of Done** — Quality standards and acceptance criteria that work must meet.
- **Release Plan** — Milestones, release timeline, and go/no-go criteria.
- **Retrospective Notes** — Learnings and action items from sprint retros and releases.

## Communication Cadence

- **Daily**: Team standups (15 min focus on progress, blockers, dependencies)
- **Weekly**: PM + PdM sync, engineering standups, risk register review
- **Monthly**: Stakeholder updates and project status briefings
- **Ad-hoc**: Escalations and incident response as needed

## Questions?

If you have questions about a specific process or role, refer to the relevant document above. If you identify gaps or improvements to these processes, open an issue using the [Process Doc Update template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml).

---

**Last Updated**: 2024
**Maintained By**: OctoAcme Project Management Community
