# OctoAcme Project Management Docs

This README collects the OctoAcme project management process documents and provides a brief summary of our approach so team members and contributors can quickly find and use the guidance.

## Summary of OctoAcme Project Management Processes

OctoAcme operates on a structured lifecycle that emphasizes customer value, iterative delivery, and clear ownership. The organization follows five core phases: **Initiation** (validating business need and aligning stakeholders through a Project One-pager), **Planning** (breaking work into shippable increments with prioritized backlogs and risk management), **Execution** (daily standups and weekly syncs with a GitHub Projects board tracking work from Backlog through Done), **Release** (standardized deployment with pre-release checklists and rollback plans), and **Retrospective** (capturing learnings and converting them into actionable improvements). This phased approach ensures that projects move through clear decision gates, with the most critical gate occurring when success metrics are clear, stakeholders align on priority, and team availability is confirmed.

The project ecosystem operates through three interdependent core roles: **Project Managers** coordinate delivery activities, manage schedules and risks, and facilitate stakeholder communication; **Product Managers** define what should be built, prioritize the backlog, and measure outcomes through data-driven decisions; and **Developers** (alongside QA/Testing) implement features, write tests, and collaborate on design. This role clarity—combined with the principle of "clear ownership" where each project has a named PM and Product Lead—prevents ambiguity and enables efficient decision-making across cross-functional teams.

Communication and transparency are woven throughout OctoAcme's rhythm. Teams meet in daily standups (15 minutes, focusing on progress and blockers), weekly delivery syncs (showing progress and flagged risks), and monthly stakeholder updates. A risk escalation ladder (Level 1: team triage, Level 2: PM-to-Product Lead, Level 3: sponsor-level) ensures issues surface quickly. Risks are captured in a formal Risk Register (tracking ID, description, impact, likelihood, owner, and mitigation), updated weekly, and reviewed in syncs—transforming reactive firefighting into proactive management.

Quality assurance is integrated throughout execution rather than treated as a final gate. Teams enforce small PRs (≤400 lines where possible) with required approvals, run automated tests and linting in CI before review, and conduct unit, integration, and end-to-end smoke tests before release. Security scanning is built into the CI pipeline, and manual QA validates feature acceptance when needed. This "shift-left" quality approach, combined with a Definition of Done documented during planning, reduces rework and accelerates time-to-production while maintaining confidence in releases.

## Process Documents

- [Project Management Overview](octoacme-project-management-overview.md) — high-level principles, roles, and lifecycle
- [Project Initiation Guide](octoacme-project-initiation.md) — one-pager template and initiation checklist
- [Project Planning](octoacme-project-planning.md) — backlog templates, planning checklist, and risk/dependency guidance
- [Execution & Tracking](octoacme-execution-and-tracking.md) — team rhythms, PR workflow, testing, and execution checklist
- [Risk Management & Communication](octoacme-risks-and-communication.md) — risk register format and communication templates
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — deployment checklist and rollback playbook
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — retrospective structure and action-tracking
- [Roles & Personas](octoacme-roles-and-personas.md) — role summaries and responsibilities

## How to Use

- Use this README to navigate to the relevant process doc for your current project phase or question.
- If you add or update a process doc, please also update this README to keep links and summaries current.
- For onboarding, start with the [Project Management Overview](octoacme-project-management-overview.md) to understand OctoAcme's core principles and roles.
