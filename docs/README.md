# OctoAcme Project Management Docs

This README serves as an entry point for all OctoAcme project management process documentation. Below you'll find a summary of our key project management practices, with links to all detailed process docs.

## Summary of OctoAcme Project Management Processes

### Project Lifecycle and Core Workflows

OctoAcme follows a structured five-phase project lifecycle designed to deliver customer value through iterative, measurable increments. Beginning with **Initiation**, teams validate business needs and align stakeholders around a lightweight Project One-pager before committing resources. The process then moves through **Planning**, where work is broken into shippable increments with clear acceptance criteria and dependencies mapped. During **Execution**, teams follow daily standups and weekly delivery syncs, managing work through a GitHub Projects board with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done). Small pull requests (≤400 lines) with automated CI testing ensure quality gates, while **Release** activities include pre-deployment verification, smoke testing, and rollback planning. Finally, **Retrospectives** capture learnings and convert them into actionable improvements, closing the feedback loop for continuous enhancement.

### Clear Roles and Stakeholder Communication

OctoAcme defines three core delivery roles with distinct responsibilities: **Project Managers** coordinate schedules, risks, and communications to ensure on-time delivery; **Product Managers** define outcomes, prioritize backlogs, and measure success through data-driven decisions; and **Developers** implement features, write tests, and identify technical risks. This structure ensures clear ownership and accountability throughout the project lifecycle. Communication is purposefully orchestrated across multiple cadences—daily standups focus on progress and blockers, weekly syncs between PM and Product Lead drive alignment, and monthly stakeholder updates maintain transparency. Escalation paths are explicit (team-level → PM → Product Lead → Sponsor), with specific protocols for security incidents, enabling rapid resolution of critical issues while maintaining psychological safety.

### Quality Assurance and Risk Management

Quality and testing are woven throughout OctoAcme's execution model. Teams implement unit tests for new logic, integration tests where applicable, and end-to-end smoke tests for critical flows before release. Security scanning is embedded in CI pipelines, and manual QA validates feature acceptance when needed. Complementing this, a formal **Risk Register** tracks identified risks with impact, likelihood, owner, and mitigation plans—reviewed weekly to ensure proactive management rather than reactive response. Blocker escalation follows a three-level triage model, from team standups through PM and Product Lead escalation to sponsor-level involvement for business-impacting issues. This combination of rigorous testing, continuous risk monitoring, and transparent communication creates a resilient delivery framework where quality and predictability reinforce one another.

## Process Documentation Index

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)

## Quick Reference: Key Artifacts

- **Project Charter / One-pager**: Defines problem, goal, success metrics, stakeholders, and timeline
- **Roadmap and Release Plan**: High-level delivery timeline with key milestones
- **Sprint/Iteration Backlog**: Prioritized work items with acceptance criteria and estimates
- **Risk Register**: Tracks identified risks with impact, likelihood, owner, and mitigation plans
- **Retrospective Notes**: Captures learnings and action items for continuous improvement

## Getting Started

New team members should begin with the [Project Management Overview](octoacme-project-management-overview.md) for an introduction to OctoAcme's principles, roles, and key artifacts. From there, use the index above to navigate to the specific process documentation relevant to your project phase or role.
