# OctoAcme Project Management Docs

OctoAcme uses a lightweight, iterative project management lifecycle across initiation, planning, execution, release, and retrospective improvement. Initiation confirms the business need, measurable outcomes, stakeholders, timeline, early risks, and resource expectations before work moves forward. Planning then translates approved work into shippable increments through a prioritized and estimated backlog, clear acceptance criteria, a shared Definition of Done, mapped dependencies, and a release plan.

Execution and tracking are managed through a project board and a steady delivery rhythm. Teams use small pull requests, include issue and acceptance context in PRs, and rely on CI checks (tests, linting, and security scans) before merge. Day-to-day coordination happens through standups, delivery syncs, demos, and status reporting, with blockers escalated through a defined path when team-level resolution is not enough.

Release and deployment require that acceptance criteria are complete, CI and security checks pass, release notes are prepared, rollback planning is documented, staging smoke tests succeed, production is verified, and stakeholders are informed. After each sprint, release, milestone, or incident, retrospectives capture learnings and track a small set of measurable follow-up actions for continuous improvement.

## Key roles and personas
- **Project Manager**: coordinates schedules, risks, dependencies, documentation, and cross-team communication.
- **Product Manager / Product Lead**: defines outcomes, prioritizes roadmap and backlog, and aligns decisions to customer and business value.
- **Developers**: implement and test increments, contribute to estimation/design, and surface technical risks early.
- **QA / Testing**: validates acceptance criteria and quality through automated and manual checks.
- **Stakeholders**: provide requirements, approvals, feedback, and sponsor-level decisions.

## Risk, dependency, communication, and escalation practices
- Maintain a risk register with impact, likelihood, owner, mitigation, and status.
- Track cross-team dependencies in planning and on the project board, and review them in regular syncs.
- Use consistent communication cadences (standups, weekly delivery/PM-product syncs, demos, and stakeholder updates).
- Escalate blockers through team triage -> PM -> Product Lead -> Sponsor, and route security incidents through the security incident process.

## Key project artifacts
- Project one-pager / charter
- Roadmap and release plan
- Prioritized backlog
- Acceptance criteria and Definition of Done
- Risk register
- Regular status updates
- Retrospective notes and action items

## Documentation index
- [OctoAcme Project Management Overview](./octoacme-project-management-overview.md)
- [OctoAcme — Project Initiation Guide](./octoacme-project-initiation.md)
- [OctoAcme — Project Planning](./octoacme-project-planning.md)
- [OctoAcme — Roles and Personas](./octoacme-roles-and-personas.md)
- [OctoAcme — Execution & Tracking](./octoacme-execution-and-tracking.md)
- [OctoAcme — Risks and Communication](./octoacme-risks-and-communication.md)
- [OctoAcme — Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [OctoAcme — Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
