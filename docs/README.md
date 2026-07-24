# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management guide! This directory contains the complete set of processes and best practices used by OctoAcme teams to deliver projects efficiently and transparently.

## About OctoAcme Project Management

OctoAcme operates on a structured lifecycle approach that moves projects through five distinct phases: **initiation, planning, execution, release, and retrospective**. The framework begins with lightweight validation of business need and stakeholder alignment before significant effort is invested. Each phase includes clear decision gates, defined roles, and explicit communication rhythms to ensure transparency and accountability.

The organization emphasizes **clear ownership** through defined Project Manager and Product Manager roles, **iterative delivery** of small, testable increments, and **data-informed decisions** based on measurable success metrics. Throughout all phases, OctoAcme maintains **psychological safety** and a culture of continuous improvement, enabling teams to deliver reliably while building institutional knowledge. Core principles include:

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Ship small, testable increments
- **Clear ownership**: Named Project Manager and Product Lead for each project
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Transparent communication**: Regular cadence with stakeholders and team
- **Proactive risk management**: Identify, track, and mitigate blockers early
- **Continuous improvement**: Capture learnings and drive process enhancements

## Core Roles

- **Project Manager (PM)**: Coordinates delivery, manages schedules, risks, and communications to ensure projects stay on track
- **Product Manager (PdM)**: Defines outcomes, prioritizes the backlog, and measures success against business and customer goals
- **Developers**: Implement features collaboratively, write tests and documentation, and identify technical risks
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs, approvals, and business context

## Process Documentation

Our project lifecycle is organized into the following phases and supporting processes:

### 1. [Project Management Overview](./octoacme-project-management-overview.md)

A concise introduction to OctoAcme's approach, core roles, key artifacts, and communication cadence. Start here for a high-level understanding of how OctoAcme runs projects.

**Quick Reference**: Principles, roles, artifacts, lifecycle phases, and communication cadence at a glance.

---

### 2. [Project Initiation Guide](./octoacme-project-initiation.md)

Define the initial steps to validate and authorize work, align stakeholders, and create a lightweight plan. Use this guide whenever a new project idea or feature proposal is ready to be explored.

**Key Deliverables**:
- Project One-pager (Problem, Goal, Success Metrics)
- Stakeholder list & communication plan
- High-level timeline and key milestones
- Initial risk list and resource needs

**Quick Reference**: Minimum deliverables checklist, project one-pager template, and decision gate criteria for moving to planning.

---

### 3. [Project Planning](./octoacme-project-planning.md)

Turn an approved initiative into an actionable plan and backlog for delivery. Break work into shippable increments, identify dependencies, and align timelines and responsibilities.

**Key Activities**:
- Kickoff meeting with stakeholders and delivery team
- Create prioritized backlog with acceptance criteria
- Estimate scope and define Definition of Done
- Identify dependencies and integration points
- Create release plan and milestone map

**Quick Reference**: Backlog item template, sprint planning guidance, risk & dependency management, and planning checklist.

---

### 4. [Execution & Tracking](./octoacme-execution-and-tracking.md)

Guidance for managing day-to-day execution and tracking progress toward project milestones. Maintain team rhythm through standups, syncs, and demos while ensuring quality and managing blockers.

**Team Rhythm**:
- Daily standups (15 min) — progress, blockers, dependencies
- Weekly delivery sync — progress updates and flagged risks
- Demo/Review at end of each sprint or milestone

**Quality Standards**:
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows
- Security scanning in CI
- Manual QA for feature acceptance when needed

**Quick Reference**: PR workflow, quality standards, metrics tracking, blocker escalation levels, and execution checklist.

---

### 5. [Risk Management & Communication](./octoacme-risks-and-communication.md)

How to identify, manage, and communicate risks and dependencies throughout the project. Maintain a risk register and establish clear escalation paths.

**Risk Lifecycle**:
- Identify risks during planning and ongoing execution
- Assess impact and likelihood
- Mitigate through actions and contingency plans
- Monitor and update status at weekly syncs

**Escalation Paths**:
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

**Quick Reference**: Risk register template, risk lifecycle stages, stakeholder communication templates, incident communication playbook, and escalation paths.

---

### 6. [Release & Deployment Guide](./octoacme-release-and-deployment.md)

Standardize how OctoAcme releases features to production to reduce risk and improve observability. Define release types, pre-release requirements, and deployment procedures.

**Release Types**:
- Patch: Hotfixes for critical production issues
- Minor: Incremental features and improvements
- Major: Significant functionality or breaking changes

**Pre-Release Requirements**:
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted
- Rollback/mitigation plan documented
- Smoke tests prepared

**Quick Reference**: Release types, pre-release checklist, deployment checklist, rollback & incident playbook, and release notes template.

---

### 7. [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

Capture learnings and convert them into actionable improvements. Conduct structured retrospectives after sprints, releases, or important milestones.

**Retrospective Structure**:
- What went well
- What could be improved
- Action items (owner, due date, success criteria)
- Follow-up on previous action items

**Quick Reference**: Retrospective timing and structure, running guidelines, action item tracking, and continuous improvement culture.

---

### 8. [Roles and Personas](./octoacme-roles-and-personas.md)

Definitions of typical roles and responsibilities used in OctoAcme project docs and exercises. Understand the responsibilities and communication patterns for Developers, Product Managers, and Project Managers.

**Quick Reference**: Role summaries, responsibilities, goals, and typical communication patterns for each persona.

---

## Using These Docs in Copilot Spaces

These process documents are designed to be used as context within a GitHub Copilot Space. Team members can reference these docs to:

- Get guidance on how to structure issues, PRs, and project documentation
- Understand escalation paths and decision gates for their current phase
- Align on communication standards, metrics, and reporting cadence
- Apply consistent processes across projects
- Onboard new team members with clear, searchable process guidance
- Make decisions informed by OctoAcme's principles and best practices

### How to Get Started

1. **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md)
2. **Starting a new project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md)
3. **Executing on an approved plan?** Reference [Execution & Tracking](./octoacme-execution-and-tracking.md) and [Risk Management & Communication](./octoacme-risks-and-communication.md)
4. **Preparing to release?** Consult the [Release & Deployment Guide](./octoacme-release-and-deployment.md)
5. **Wrapping up?** Use the [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) guide

### Key Artifacts by Phase

| Phase | Key Artifacts |
|-------|---------------|
| **Initiation** | Project Charter, One-pager, Stakeholder List |
| **Planning** | Backlog, Release Plan, Definition of Done, Risk Register |
| **Execution** | Project Board, Sprint Backlog, PR Reviews, Risk Updates |
| **Release** | Release Notes, Deployment Checklist, Rollback Plan |
| **Retrospective** | Retrospective Notes, Action Items, Metrics |

---

## Communication Cadence

- **Weekly sync** between PM and Product Manager
- **Twice-weekly standups** for delivery team (or as agreed)
- **Monthly stakeholder updates** for visibility and alignment
- **Ad-hoc escalations** as needed for blockers and risks

---

## Contributing to OctoAcme Processes

To propose updates or additions to these process documents:

1. Open an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template
2. Describe the gap, rationale, and suggested content
3. Work with the team to review and refine
4. Submit a pull request with your proposed changes

This ensures all process improvements are thoughtfully considered and incorporated collaboratively.

---

**Last Updated**: July 2026

For questions or feedback on these processes, please open an issue or contact your Project Manager or Product Lead.
