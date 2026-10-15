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

## Delivery Lead

### Role Summary
Coordinates day-to-day delivery across squads and ensures iteration health, unblocker resolution, and dependency tracking.

### Responsibilities
- Monitor sprint health and remove blockers
- Track delivery metrics and escalate risks
- Run iteration ceremonies (when PM unavailable) and ensure commitments are met
- Coordinate cross-team work and handoffs

### Interaction with existing roles
- Works closely with Project Manager and PM to translate roadmap items into execution plans
- Partners with Engineering Lead and QA Lead on readiness and quality
- Escalates unresolved cross-team blockers to the PM or Sponsor as needed

---

## Engineering Lead / Tech Lead

### Role Summary
Owns technical design decisions, architecture trade-offs, code quality, and non-functional requirements.

### Responsibilities
- Own and communicate system design and architecture choices
- Ensure code quality, maintainability, and performance targets
- Review and approve significant technical designs and RFCs
- Identify technical risks and propose mitigation strategies

### Interaction with existing roles
- Partners with Developers during implementation and code reviews
- Works with PM/PdM on feasibility and trade-offs
- Coordinates with Delivery Lead on technical delivery risk and scheduling

---

## UX / Design Lead

### Role Summary
Owns user research, interaction design, accessibility, and design artifacts for implementation.

### Responsibilities
- Lead user research and translate findings into designs
- Define interaction flows, wireframes, and high-fidelity mocks
- Ensure accessibility and usability standards are met
- Provide design handoff artifacts and acceptance criteria

### Interaction with existing roles
- Collaborates with PdM to align designs with user goals and success metrics
- Works with Developers to clarify implementation details and with QA on UX acceptance
- Engages with Delivery Lead to coordinate design timing across sprints

---

## Release Manager / SRE Liaison

### Role Summary
Coordinates deployments, verifies release readiness, and owns rollback/runbook procedures for releases.

### Responsibilities
- Maintain and verify release checklist and runbooks
- Coordinate deployment windows and staging/production verifications
- Validate post-deploy smoke tests and rollback plans
- Triage deployment issues and coordinate incident response if needed

### Interaction with existing roles
- Engages with Developers and QA to confirm readiness and with PM on release timing
- Escalates major release issues to Sponsor/Stakeholders when required
- Works with SRE/ops teams for infrastructure and monitoring needs

---

## Data & Metrics Owner

### Role Summary
Defines success metrics, owns telemetry and dashboards, and ensures data quality for decision-making.

### Responsibilities
- Define and document success metrics and measurement approach
- Implement or verify telemetry instrumentation and data pipelines
- Create dashboards and reports to track feature impact
- Validate data quality and support experimentation analysis

### Interaction with existing roles
- Works with PdM to align metrics with product goals
- Coordinates with Developers to instrument code and with QA to validate data correctness
- Provides input for retrospectives and release reviews based on observed metrics

---

## Security & Compliance Owner

### Role Summary
Surfaces and enforces security and compliance requirements, coordinates security reviews, and tracks remediation.

### Responsibilities
- Conduct security reviews and threat modelling for features
- Define compliance requirements and verification steps
- Track security findings and remediation progress
- Trigger security incident processes when necessary

### Interaction with existing roles
- Coordinates with Engineering Lead and Developers on mitigation and secure design
- Works with PM on scheduling security-related work and with Delivery Lead for release gating
- Engages Security on-call for incidents and compliance questions

---

## QA Lead / Test Owner

### Role Summary
Defines and coordinates the test strategy, ensures quality coverage across automated and manual testing.

### Responsibilities
- Define test strategy and maintain test plans
- Own automated test suites and manual test scopes for releases
- Coordinate QA efforts across teams and validate acceptance criteria
- Ensure testability and adequate observability for features

### Interaction with existing roles
- Works with Developers to improve testability and with Engineering Lead on non-functional tests
- Engages with PM to confirm acceptance criteria and with Delivery Lead to validate release readiness
- Reports quality metrics and test coverage to stakeholders

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
