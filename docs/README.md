# OctoAcme Project Management Docs

Welcome! This README provides a high-level overview of project management processes at OctoAcme and links to detailed reference documents.

## Summary of OctoAcme Project Management Processes

**Lifecycle & Workflow Structure**

OctoAcme follows a structured five-phase project lifecycle: Initiation, Planning, Execution, Release, and Close & Retrospective. During Initiation, teams validate business needs and stakeholder alignment by creating a lightweight Project One-pager that defines the problem, objectives, success metrics, and initial timeline. The Planning phase breaks work into shippable increments using prioritized backlogs with clear acceptance criteria, T-shirt sizing or story points for estimation, and a well-defined Definition of Done. Execution emphasizes daily standups (15 min), weekly delivery syncs, and demos at sprint or milestone ends, with work tracked through GitHub Projects using columns: Backlog, Ready, In Progress, In Review, QA, and Done.

**Roles & Communication**

OctoAcme defines four core personas: Project Managers (who coordinate delivery, manage schedules, risks, and communications), Product Managers (who define what should be built, prioritize backlogs, and measure outcomes), Developers (who implement features, write tests, participate in code reviews, and help estimate work), and QA/Testing teams (who validate quality and acceptance criteria). Cross-functional collaboration is essential, supported by a communication cadence that includes weekly syncs between PM and Product Lead, twice-weekly standups for the delivery team, monthly stakeholder updates, and ad-hoc escalations as needed. A three-level escalation path (Team-level → PM → Product Lead → Sponsor) ensures blockers are addressed systematically.

**Quality & Risk Management**

Quality is embedded throughout the delivery process: unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows before release, and security scanning in CI. Manual QA is performed for feature acceptance when needed. Risk management follows a defined lifecycle—Identify during planning and ongoing execution, Assess impact and likelihood, Mitigate through actions and contingency plans, and Monitor at weekly syncs. Teams maintain a simple Risk Register capturing ID, Description, Impact, Likelihood, Owner, Mitigation plan, and Status. Deployment follows a pre-release checklist ensuring all acceptance criteria are met, CI and security scans pass, release notes are drafted, and smoke tests are prepared. Post-release, the team conducts retrospectives to capture learnings and convert them into actionable improvements with clear owners and timelines.

**Execution Excellence & Continuous Improvement**

Pull Request workflow emphasizes small, focused PRs (≤400 lines when possible) that include issue links, acceptance criteria in PR descriptions, and require at least one approval before merging after CI validation. The team tracks velocity and burndown, monitors success metrics from the Project One-pager, and uses dashboards for key signals like errors, latency, and usage. Retrospectives are conducted after each sprint, release, or important milestone, timeboxed to 45–75 minutes, and prioritize 2–3 top action items to avoid overload. This commitment to continuous improvement, psychological safety, data-informed decisions, and clear ownership enables OctoAcme to deliver customer-first, iterative value consistently.

## OctoAcme Project Management Docs Index

Each document below describes a critical component of our project management approach:

- **[Project Management Overview](./octoacme-project-management-overview.md)** - High-level introduction to OctoAcme's approach, principles, core roles, and key artifacts
- **[Project Initiation Guide](./octoacme-project-initiation.md)** - How to validate business needs, align stakeholders, and create a lightweight project plan
- **[Project Planning](./octoacme-project-planning.md)** - How to break work into shippable increments, estimate scope, and plan releases
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** - Day-to-day execution, team rhythm, workflows, quality gates, and metrics
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** - How to identify, manage, and communicate risks and dependencies
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** - Standardized process for releasing features to production
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** - How to capture learnings and convert them into actionable improvements
- **[Roles and Personas](./octoacme-roles-and-personas.md)** - Definitions of core roles and responsibilities in OctoAcme projects

## Getting Started

- **New to OctoAcme projects?** Start with the [Project Management Overview](./octoacme-project-management-overview.md)
- **Starting a new project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md)
- **Managing an active project?** Reference [Execution & Tracking](./octoacme-execution-and-tracking.md)
- **Preparing a release?** Use the [Release & Deployment Guide](./octoacme-release-and-deployment.md)

For questions or suggestions about these processes, please reach out to your Project Manager or Product Lead.