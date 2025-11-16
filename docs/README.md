# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation hub. This folder centralizes the process documents the team uses to initiate, plan, execute, release, and continuously improve cross-functional projects. Use this README as the single entry point to quickly find the procedure you need and to get an at-a-glance summary of how we manage projects.

OctoAcme follows a customer-first, iterative delivery approach. Projects move through a clear lifecycle: Initiation (validate the problem and record a Project One-pager), Planning (kickoff, prioritized backlog, estimates, and a Definition of Done), Execution (development, PR reviews, CI, and demos), Release (pre-release checks, deployment checklist, rollback playbook), and Close & Retrospective (capture learnings and tracked action items). The emphasis is on small, testable increments, data-informed decisions, and psychological safety so teams can learn and adapt quickly.

Roles and accountability are explicit: Project Managers (PMs) coordinate delivery, timelines, risks, and communications; Product Managers (PdMs) own outcomes, success metrics, and prioritization; Developers implement and test features; QA validates acceptance and quality; and Stakeholders provide input and approvals. Regular rituals — daily standups, weekly delivery syncs, sprint demos, and periodic stakeholder updates — keep teams aligned and surface risks early. Project artifacts (one-pager, backlog, risk register, release notes) live in repo docs/ or .copilot/ so Copilot Spaces can consume them.

Quality assurance and risk management are integrated across the lifecycle. PR and CI workflows encourage small, reviewable PRs with linked issues and acceptance criteria, automated tests and security scans before review, and required approvals before merging. Testing includes unit and integration tests plus end-to-end smoke checks for critical flows; manual QA is used when appropriate. Risks are tracked in a Risk Register with owners and mitigations, and escalation paths (team → PM → Product Lead → Sponsor) are defined. Retrospectives capture a small set of actionable improvements that are added back into the backlog.

Project Management Docs (files in this folder)
- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)

How to use these docs
- Keep project-specific artifacts (Project One-pager, Risk Register, release notes) in the project repo's docs/ or `.copilot/` so Copilot Spaces can use them as context.
- When proposing doc changes, use the `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` template so updates follow a consistent review flow.
- For any proposed change, link the issue and include acceptance criteria so reviewers can validate alignment with existing processes.

Acceptance criteria
- Content aligns with existing process docs
- README improves discoverability and onboarding
- README is added to `docs/` and links to the files above
