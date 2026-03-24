# OctoAcme Project Management Docs

This README serves as the entry point for all process documentation and resources used by the OctoAcme team to deliver projects efficiently and consistently.

## Project Management Processes Summary

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership. The framework spans five key phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. During initiation, teams validate business needs by creating a lightweight Project One-pager that defines the problem statement, objectives, success metrics, stakeholders, and initial resource estimates. Once stakeholder alignment is confirmed, the project moves into planning, where the work is broken into shippable increments, acceptance criteria are defined, backlog items are prioritized and estimated, and dependencies are identified. This structured handoff ensures that teams begin execution with clarity on scope, timeline, and success measures.

Execution at OctoAcme is managed through a disciplined rhythm of daily standups (15 minutes), weekly delivery syncs, and sprint-based iteration cycles. Teams use GitHub Projects with standardized columns—Backlog, Ready, In Progress, In Review, QA, Done—to maintain transparency and track progress. Pull requests are kept small (≤400 lines when possible) and require at least one approval before merging, with automated CI testing and linting enforced before review. Quality and testing are integral to execution, with requirements for unit tests, integration tests, end-to-end smoke tests for critical flows, and security scanning embedded in the CI pipeline. Risk management is ongoing, with blockers triaged in daily standups and escalated through defined levels: team-level → Project Manager → Product Lead → Sponsor for business-impacting issues.

OctoAcme operates with clear role separation and communication structures. The **Project Manager (PM)** coordinates delivery, schedules, risks, and communications; the **Product Manager (PdM)** defines outcomes and prioritizes the backlog; **Developers** implement features and collaborate on design and testability; and **QA/Testing** validates quality against acceptance criteria. Weekly syncs between PM and PdM, twice-weekly standups for delivery teams, and monthly stakeholder updates ensure alignment across the organization. Communication templates—including weekly status updates, incident response protocols, and escalation paths—standardize how information flows and decisions are made.

Release and deployment practices at OctoAcme emphasize risk reduction and observability. Before release, all acceptance criteria must be met, CI and security scans must pass, release notes must be drafted, and rollback plans must be documented. Deployments follow a staged approach: deploy to staging, run smoke tests, deploy to production via automated pipeline when possible, and conduct post-deploy verifications. After each sprint, release, or significant milestone, teams conduct retrospectives to capture learnings and identify 2–3 prioritized action items for continuous improvement. This closing feedback loop ensures that processes evolve based on team experience and that institutional knowledge is systematically captured and refined.

## Documentation Index

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

---

**Contributing to these docs:** To add or update content in the OctoAcme Project Management Docs, use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template.
