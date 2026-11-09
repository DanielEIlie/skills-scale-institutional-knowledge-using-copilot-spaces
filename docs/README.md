# OctoAcme Project Management Docs

This directory contains the core project management guidance used by OctoAcme. The process documents help teams move from idea to delivery in a consistent, repeatable way and support onboarding, execution, communication, and continuous improvement across projects.

OctoAcme manages work through an Agile-style lifecycle that begins with initiation, continues through planning and iterative execution, and ends with release and retrospective improvement. New initiatives are reviewed for business need, stakeholders, success criteria, and available resources. Approved work is translated into a prioritized backlog with milestones, dependencies, acceptance criteria, and a Definition of Done. Teams maintain a shared project board to track progress and keep work visible.

The project operating model relies on clear roles and regular communication. Product managers define outcomes and priorities, project managers coordinate delivery, schedules, and risk management, and developers, QA, and stakeholders contribute to building and validating the work. Communication is structured through daily standups, weekly delivery syncs, milestone reviews, and stakeholder updates, with escalation paths for blockers and business-impacting issues.

Quality is built into the process through small, reviewable changes, CI checks, testing, and release readiness gates. Pull requests should be small and linked to issues with clear acceptance criteria, and they should pass automated tests, linting, and security checks before merge. Releases require smoke testing, verification, rollback planning, and stakeholder communication. After each sprint, release, or significant milestone, the team runs a retrospective to capture lessons learned and convert them into tracked improvement actions.

## Process documents

- [Project Management Overview](octoacme-project-management-overview.md) — principles, roles, core artifacts, lifecycle, and communication cadence.
- [Project Initiation Guide](octoacme-project-initiation.md) — validate and authorize work, align stakeholders, and define the one-pager and decision gate.
- [Project Planning](octoacme-project-planning.md) — turn approved work into an actionable backlog, estimates, milestones, and delivery plan.
- [Execution & Tracking](octoacme-execution-and-tracking.md) — team rhythm, project-board workflow, quality practices, reporting, and blocker escalation.
- [Risk Management & Communication](octoacme-risks-and-communication.md) — identify, assess, mitigate, monitor, and communicate risks and dependencies.
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — release readiness, deployment checks, verification, and rollback or incident response.
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — run retrospectives and track improvement actions.
- [Roles and Personas](octoacme-roles-and-personas.md) — responsibilities, goals, and communication patterns for core project roles.

Keep this index aligned with the contents of `docs/` as process documents are added or renamed.
