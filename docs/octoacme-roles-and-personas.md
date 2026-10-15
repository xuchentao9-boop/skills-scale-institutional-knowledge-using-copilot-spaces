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

## Additional Personas (proposed)

These additional personas clarify operational responsibilities and cross-team handoffs. Each entry lists responsibilities and how the persona interacts with existing roles.

### Delivery Lead
- Responsibilities:
  - Coordinate day-to-day delivery across squads and track sprint health
  - Remove or escalate blockers, maintain delivery cadence, and track delivery metrics
  - Run iteration ceremonies when the Project Manager is unavailable
  - Maintain dependency trackers and highlight cross-team impacts
- Interaction:
  - Works closely with the Project Manager and Product Manager to translate roadmap priorities into execution plans
  - Coordinates with Engineering Lead and Developers on implementation timelines and technical risks
  - Engages QA Lead for test readiness and with the Release Manager for release scheduling

### Engineering Lead / Tech Lead
- Responsibilities:
  - Own technical design decisions, architecture, and non-functional requirements (performance, reliability, observability)
  - Make trade-off recommendations and review major design proposals
  - Mentor developers and drive code health and maintainability
  - Coordinate technical debt backlog and planning
- Interaction:
  - Partners with Developers on implementation details and code reviews
  - Works with Product Manager and Project Manager on feasibility, effort estimates, and delivery risk
  - Engages Security & Compliance Owner for security reviews and the Release Manager for deployment considerations

### UX / Design Lead
- Responsibilities:
  - Own user research, interaction design, accessibility, and design system consistency
  - Produce design artifacts (mockups, specs, accessibility notes) and acceptance criteria for UX
  - Support usability testing and synthesize findings into actionable changes
- Interaction:
  - Works with Product Manager to translate user goals into designs and acceptance criteria
  - Handoffs design artifacts to Developers and reviews implementation for fidelity
  - Coordinates with QA Lead on UX-related test cases and accessibility verification

### Release Manager / SRE Liaison
- Responsibilities:
  - Coordinate deployments and verify that the release checklist is complete
  - Maintain rollback/runbooks, monitor post-deploy verification, and manage deployment communications
  - Ensure operational readiness (monitoring, runbooks, capacity checks) and coordinate with on-call teams
- Interaction:
  - Engages with Developers and QA Lead before and during releases to confirm readiness
  - Works with Project Manager and Delivery Lead to schedule deployment windows and communicate impacts
  - Escalates to Sponsor or relevant leadership if major release incidents occur

### Data & Metrics Owner
- Responsibilities:
  - Define and own success metrics, dashboards, and telemetry for features
  - Validate data quality, instrumentation coverage, and experiment setup
  - Provide analysis to support product decisions and retrospective insights
- Interaction:
  - Works with Product Manager to set measurable goals and with Developers to instrument telemetry
  - Shares dashboards and insights with PM, Project Manager, and stakeholders for decision making
  - Collaborates with QA Lead to validate event and metrics correctness during testing

### Security & Compliance Owner
- Responsibilities:
  - Identify security and compliance requirements relevant to the project
  - Run security reviews, threat modeling, and coordinate remediation tracking
  - Ensure compliance checks are completed and documented (e.g., data handling, audit controls)
- Interaction:
  - Coordinates with Engineering Lead and Developers on secure design and remediation timelines
  - Works with Project Manager to include security checks in release plans and with the Release Manager on any gated deployments
  - Triggers incident processes and notifies Security on-call when required

### QA Lead / Test Owner
- Responsibilities:
  - Define the test strategy and maintain test plans (manual and automated)
  - Coordinate test execution, triage defects, and track quality metrics
  - Ensure acceptance criteria are testable and met before release
- Interaction:
  - Works with Developers to improve testability and with Product Manager to clarify acceptance criteria
  - Coordinates with Delivery Lead and Release Manager on release readiness and smoke testing
  - Feeds defect and quality metrics into retrospectives and continuous improvement actions

---

## How these additions improve outcomes
- Clear ownership reduces ambiguity during critical moments (releases, incidents, cross-team dependencies)
- Faster handoffs and fewer missed steps (e.g., telemetry instrumentation, security checks, UX sign-off)
- Better alignment on success metrics and observability, enabling data-informed decisions
- Easier onboarding: new team members and stakeholders can quickly identify the right contacts for specific concerns
