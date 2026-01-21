# OctoAcme Project Management Process Docs

Welcome! This repository centralizes all process knowledge and decision guidelines for OctoAcme project delivery. Use this README as an entry point to each practice doc and to understand our project management approach at a glance.

## Project Management Process Overview

OctoAcme follows a customer-first, iterative delivery approach to project management that emphasizes clear ownership, data-informed decisions, and psychological safety. The project lifecycle consists of five core phases: **Initiation**, where teams validate business needs and create a Project One-pager with stakeholder alignment; **Planning**, where approved initiatives are broken into actionable backlogs with defined acceptance criteria and dependencies; **Execution**, where teams build, test, and review work in small increments; **Release & Deployment**, where features are safely shipped to production with rollback plans and smoke tests; and **Close & Retrospective**, where teams capture learnings and convert them into actionable improvements. Each project maintains key artifacts including the Project Charter, roadmap, risk register, and retrospective notes to ensure transparency and continuity.

The OctoAcme team structure centers on three primary personas working collaboratively. **Project Managers** coordinate delivery activities, manage schedules and risks, facilitate ceremonies, and maintain transparent status reporting across stakeholders. **Product Managers** define the product vision, prioritize the backlog based on customer and business value, and measure outcomes through success metrics. **Developers** implement features, write tests and documentation, participate in code reviews, and help identify technical risks. Supporting roles include QA/Testing for validation and stakeholders who provide inputs and approvals. This role clarity ensures each team member understands their responsibilities while fostering cross-functional collaboration.

Quality assurance and execution workflows are tightly integrated into OctoAcme's day-to-day practices. Teams use GitHub Projects with a standardized board structure (Backlog, Ready, In Progress, In Review, QA, Done) and follow a pull request workflow that emphasizes small PRs (≤400 lines when possible), automated testing and linting in CI, and peer review before merging. Quality standards include unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, and security scanning in CI. Teams maintain a daily standup rhythm (15 minutes focused on progress and blockers), weekly delivery syncs, and sprint/milestone demos to ensure continuous progress visibility and quick issue resolution.

Communication and risk management are structured to maintain alignment and enable rapid escalation when needed. Teams follow a three-level blocker escalation path: team-level triage in daily standups, PM escalation to Product Leads for cross-team issues, and sponsor-level escalation for business-impacting concerns. Stakeholders receive regular weekly status updates covering progress, next steps, risks, and decisions needed, with monthly broader stakeholder updates and ad-hoc communications as required. The risk register tracks identified risks with impact, likelihood, owners, and mitigation plans, reviewed weekly during syncs. After each sprint, release, or milestone, teams conduct timeboxed retrospectives (45-75 minutes) to capture what went well, what could improve, and 2-3 prioritized action items with clear owners, creating a culture of continuous improvement and learning.

## Key Principles
- **Customer-first**: Prioritize user value, collect feedback, iterate often
- **Clear roles & responsibilities**: Defined PM, Product Manager, Developer, QA, and stakeholder roles
- **Lifecycle-driven**: From Initiation → Planning → Execution & Tracking → Release & Deployment → Retrospective/Continuous Improvement
- **Transparent communication**: Status summaries, risk registers, and regular reviews/demos
- **Consistent artifacts**: Standard templates for one-pager, release notes, risks, checklists, and retros

## Process Documents

- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)

## How to Use These Docs

1. **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md) to understand our approach
2. **Starting a new project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md)
3. **Need a specific template or checklist?** Navigate to the relevant process document above
4. **Want to improve a process?** Use our [issue template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to suggest updates

## Contributing

To suggest improvements or additions to these process docs, please [open an issue](../../issues/new/choose) using the "Add Content to Project Management Process Docs" template.
