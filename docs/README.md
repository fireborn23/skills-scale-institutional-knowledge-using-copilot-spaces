# OctoAcme Project Management Documentation

This folder centralizes OctoAcme’s project management processes and guidance. It provides a concise introduction to how OctoAcme runs projects, links to lifecycle-specific process documents, role descriptions, and quick navigation to help new teammates find the right guidance quickly.

OctoAcme follows a lightweight, iterative delivery model that moves work from idea to production while keeping stakeholders aligned. Projects begin with a Project One-pager to confirm the business need, measurable outcomes, and stakeholders, then move into planning only when success criteria and team availability are confirmed. Planning breaks approved initiatives into prioritized backlog items with clear acceptance criteria and a Definition of Done so work is shippable and testable in small increments.

Execution uses a simple project-board workflow (Backlog → Ready → In Progress → In Review → QA → Done) and a disciplined pull-request process that encourages small PRs, links to issues and acceptance criteria, and requires passing CI and peer approval before merging. Releases are classified (patch, minor, major) with pre-release checks (tests, security scans, release notes, rollback plan) and a deployment checklist to stage, smoke-test, and verify production. Retrospectives and a continuous-improvement loop capture learnings as action items that feed back into the backlog.

Roles and responsibilities are explicit to ensure clear ownership: Product Managers define outcomes and prioritize the backlog; Project Managers coordinate schedules, risk, and communications; Developers implement and test features; and QA validates acceptance criteria and critical flows. Communication is cadence-driven and transparent: daily standups for blockers and progress, weekly delivery syncs and PM/PdM alignment, sprint demos for stakeholder visibility, and regular risk reporting. Quality is enforced via unit/integration tests, end-to-end smoke tests, CI security scanning, and manual QA as needed, all guided by the Definition of Done.

Process lifecycle (links)
- Project Initiation
  - OctoAcme — Project Initiation Guide  
    https://github.com/fireborn23/skills-scale-institutional-knowledge-using-copilot-spaces/blob/1257b6566ad3cb057e6fd3137e298b762837fc70/docs/octoacme-project-initiation.md
- Project Planning
  - OctoAcme — Project Planning  
    https://github.com/fireborn23/skills-scale-institutional-knowledge-using-copilot-spaces/blob/1257b6566ad3cb057e6fd3137e298b762837fc70/docs/octoacme-project-planning.md
- Execution & Tracking
  - OctoAcme — Execution & Tracking  
    https://github.com/fireborn23/skills-scale-institutional-knowledge-using-copilot-spaces/blob/1257b6566ad3cb057e6fd3137e298b762837fc70/docs/octoacme-execution-and-tracking.md
- Risks & Communication
  - OctoAcme — Risk Management & Communication  
    https://github.com/fireborn23/skills-scale-institutional-knowledge-using-copilot-spaces/blob/1257b6566ad3cb057e6fd3137e298b762837fc70/docs/octoacme-risks-and-communication.md
- Release & Deployment
  - OctoAcme — Release & Deployment Guide  
    https://github.com/fireborn23/skills-scale-institutional-knowledge-using-copilot-spaces/blob/1257b6566ad3cb057e6fd3137e298b762837fc70/docs/octoacme-release-and-deployment.md
- Retrospective & Continuous Improvement
  - OctoAcme — Retrospective & Continuous Improvement  
    https://github.com/fireborn23/skills-scale-institutional-knowledge-using-copilot-spaces/blob/1257b6566ad3cb057e6fd3137e298b762837fc70/docs/octoacme-retrospective-and-continuous-improvement.md

Reference docs
- Roles & Personas  
  https://github.com/fireborn23/skills-scale-institutional-knowledge-using-copilot-spaces/blob/1257b6566ad3cb057e6fd3137e298b762837fc70/docs/octoacme-roles-and-personas.md

How to use these docs
- Start with the Project Initiation guide when evaluating new initiatives.
- Use Project Planning to create a prioritized backlog and release timeline.
- Follow Execution & Tracking as the day-to-day guide for PR workflow and board states.
- Use Risks & Communication for stakeholder updates and escalation paths.
- Follow Release & Deployment for pre-release checks and deployment steps.
- Run the Retrospective guide after each sprint or release and convert action items into backlog issues.

Propose changes
- To propose updates to any process doc, open a PR and reference the relevant issue or use the repository’s issue template:  
  .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml  
  https://github.com/fireborn23/skills-scale-institutional-knowledge-using-copilot-spaces/blob/1257b6566ad3cb057e6fd3137e298b762837fc70/.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml

Contact / ownership
- Keep the project README and one-pagers in the project repo up-to-date as the single source of truth.
- For questions about these docs or proposed updates, contact the Project Manager or open an issue in this repository.
