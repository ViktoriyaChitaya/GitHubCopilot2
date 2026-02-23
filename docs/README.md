# OctoAcme Project Management Docs

Welcome to the OctoAcme project management documentation. This README serves as your entry point to understanding how OctoAcme runs projects consistently across all initiatives. Whether you're new to the team or looking for specific process guidance, you'll find comprehensive documentation and links to detailed workflows below.

## Overview of OctoAcme Project Management Processes

OctoAcme operates projects through a **structured five-phase lifecycle** designed to ensure consistent, customer-focused delivery with built-in quality controls and continuous improvement:

1. **Initiation**: Validate business needs and establish stakeholder alignment with a lightweight Project One-pager that defines the problem, success metrics, and initial risks.

2. **Planning**: Break work into prioritized, estimable backlog items with clear acceptance criteria. Create a release plan and document dependencies, risks, and team responsibilities.

3. **Execution**: Deliver through iterative, testable increments using GitHub Projects for tracking, small pull requests (≤400 lines), automated CI/CD testing, and daily standups to surface blockers.

4. **Release**: Deploy features to production following a standardized checklist that includes smoke testing, rollback plans, and stakeholder communication.

5. **Close & Retrospective**: Capture learnings and convert them into prioritized action items that feed back into future project planning.

### Key Principles

- **Customer-first**: Prioritize customer value and usability in all decisions
- **Iterative delivery**: Ship small, testable increments rather than large batches
- **Clear ownership**: Every project has named Project Managers and Product Leads
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and continuous improvement

### Core Roles

- **Project Manager (PM)**: Coordinates delivery schedules, manages risks, and drives communication
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlogs, and measures success
- **Developers**: Implement features with focus on quality, testability, and collaboration
- **QA/Testing**: Validate quality and acceptance criteria across all deliverables
- **Stakeholders**: Provide inputs, approvals, and business context

### Communication Cadence

- **Daily standups** (15 min): Progress, blockers, and dependencies
- **Weekly PM-PdM sync**: Strategic alignment and risk review
- **Twice-weekly team standups**: Coordination and delivery updates
- **Monthly stakeholder updates**: High-level progress and decisions
- **Ad-hoc escalations**: Urgent blockers and critical decisions

### Quality Assurance & Risk Management

Quality is embedded throughout delivery:
- Unit tests for new logic
- Integration tests for cross-component interactions
- End-to-end smoke tests before release
- Security scanning in CI pipelines
- Manual QA for feature acceptance

Risks are actively managed through a Risk Register (tracking ID, description, impact, likelihood, owner, and mitigation) with weekly reviews and a clear three-level escalation path (team triage → PM escalation → sponsor-level escalation).

---

## Process Documentation

Click on any of the links below to dive into detailed guidance for each phase and function:

| Process | Purpose |
|---------|---------|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level introduction to OctoAcme's methodology, principles, and key artifacts |
| [Project Initiation Guide](octoacme-project-initiation.md) | Steps to validate business need, align stakeholders, and create a Project One-pager |
| [Project Planning](octoacme-project-planning.md) | Breaking work into actionable backlog items, estimating, and identifying dependencies |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day workflows, PR process, testing strategy, and blocker escalation |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Maintaining risk registers, stakeholder communication templates, and escalation paths |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Pre-release requirements, deployment checklist, and rollback procedures |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Running effective retrospectives and converting learnings into action items |
| [Roles & Personas](octoacme-roles-and-personas.md) | Detailed responsibilities and communication patterns for each role |

---

## Getting Started

**New to OctoAcme?**
1. Start with the [Project Management Overview](octoacme-project-management-overview.md) for a concise introduction
2. Review the [Roles & Personas](octoacme-roles-and-personas.md) to understand your responsibilities

**Starting a new project?**
1. Read the [Project Initiation Guide](octoacme-project-initiation.md)
2. Create a Project One-pager and socialize it with stakeholders
3. Move to [Project Planning](octoacme-project-planning.md) once you have approval

**Actively executing a project?**
1. Reference [Execution & Tracking](octoacme-execution-and-tracking.md) for daily rhythms and workflows
2. Consult [Risk Management & Communication](octoacme-risks-and-communication.md) for managing dependencies and stakeholder updates
3. Use [Release & Deployment Guide](octoacme-release-and-deployment.md) when preparing for launch

**Wrapping up or improving?**
1. Follow [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) to capture learnings
2. Convert action items into issues or backlog entries for the next cycle

---

## Key Artifacts by Phase

| Phase | Primary Artifacts |
|-------|------------------|
| Initiation | Project One-pager, Stakeholder list, Initial risk list |
| Planning | Prioritized backlog, Release plan, Definition of Done, Risk Register |
| Execution | GitHub Projects board, Pull Requests, Daily standup notes, Risk updates |
| Release | Release notes, Deployment checklist, Rollback plan |
| Retrospective | Retrospective notes, Action items (with owners and due dates) |

---

## Questions?


If you have questions about OctoAcme processes or need clarification:
- Reach out to your **Project Manager** for guidance on project execution
- Contact your **Product Manager** for decisions on priorities and success metrics
- Check the issue template in `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` to suggest improvements to these docs

---

**Last updated**: 2026-02-23
