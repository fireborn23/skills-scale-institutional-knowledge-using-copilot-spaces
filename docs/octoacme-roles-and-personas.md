# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional Personas (proposed additions)

These personas address gaps in ownership and handoffs across design, measurement, support, security, and releases. Each entry includes a one-line summary, key responsibilities, and how they interact with existing roles.

- UX Lead
  - Role summary: Owns user experience design, research, and usability validation for features.
  - Responsibilities:
    - Conduct user research and usability testing.
    - Produce wireframes, prototypes, and design specs.
    - Define UX acceptance criteria for features.
    - Review UI implementation during PRs and validate in demos.
  - Interactions:
    - Works with Product Manager to translate requirements into designs.
    - Collaborates with Developers and QA on implementation and acceptance tests.
    - Flags usability risks during planning and backlog refinement.

- Data Analyst
  - Role summary: Defines measurement strategy and builds dashboards and analyses to validate success metrics.
  - Responsibilities:
    - Propose and document success metrics and instrumentation requirements.
    - Build dashboards, queries, and analysis to track experiments and releases.
    - Validate data quality and advise on telemetry changes.
    - Share findings in weekly syncs and post-release reviews.
  - Interactions:
    - Partners with Product Manager to set measurable outcomes.
    - Provides Developers and SRE with instrumentation details and tests.
    - Works with PM/PD to interpret impact and recommend next steps.

- Support Lead (Customer Support Liaison)
  - Role summary: Represents customer-facing support and operational feedback in planning and post-release activities.
  - Responsibilities:
    - Triage customer-reported issues and provide replication steps.
    - Prioritize bugs and escalate customer-impacting incidents.
    - Maintain runbooks and common-issue troubleshooting guides.
    - Contribute to release notes and known-issues documentation.
  - Interactions:
    - Escalates critical issues through the Project Manager and on-call teams.
    - Works with Developers and QA to reproduce and prioritize fixes.
    - Provides customer impact context to Product and PM for prioritization.

- Security Engineer
  - Role summary: Ensures security considerations are integrated into planning, design, and CI/CD.
  - Responsibilities:
    - Perform threat assessments and security reviews for changes.
    - Validate CI security scan results and request remediations.
    - Document residual security risks and mitigations.
    - Recommend secure defaults and review third-party dependencies.
  - Interactions:
    - Engages in planning and design reviews with PM and Product.
    - Partners with Developers on remediation and secure implementation.
    - Notifies stakeholders of critical security issues and recommended actions.

- Release Manager
  - Role summary: Coordinates release activities, deployment windows, and post-release verification.
  - Responsibilities:
    - Maintain release checklist and deployment runbook.
    - Coordinate staging and production deployments and rollback plans.
    - Confirm smoke tests and post-deploy verifications.
    - Notify stakeholders and maintain release communications.
  - Interactions:
    - Coordinates closely with PM, Developers, QA, and Support Lead during release windows.
    - Ensures release readiness and that acceptance criteria are met before production.

Placement and guidance:
- Add this "Additional Personas" section to docs/octoacme-roles-and-personas.md.
- Keep each persona concise (3–6 bullets) and include at least one interaction mapping to existing roles (PM, PdM, Developers, QA).
- Link or reference process-checklist (see docs/process-doc-update-checklist.md) so proposed role additions get stakeholder review and acceptance before being merged.
