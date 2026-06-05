# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. It has been expanded to include additional cross-functional personas commonly required for modern product delivery. Each persona includes responsibilities and how they typically interact with existing roles to improve clarity and accountability.

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

## QA / Testing

### Role Summary
QA validates that the delivered product meets acceptance criteria and quality standards, balancing automated and manual testing.

### Responsibilities
- Develop and run test plans and test cases
- Triage and verify defects
- Collaborate on testability improvements
- Approve acceptance of features based on DoD

### Typical Communication
- Test reports and QA sign-off on releases
- Close coordination with Developers and PMs for acceptance criteria

---

## Stakeholders

Stakeholders provide domain knowledge, funding, or approvals required for the project. Their engagement level varies by project. Stakeholder alignment is coordinated by the PM.

---

## New / Expanded Personas

To address gaps in accountability and cross-functional collaboration, we add the following personas.

### UX Designer

Role Summary
- Responsible for user research, interaction design, and usability validation. Ensures product decisions are user-centered.

Responsibilities
- Conduct user research and synthesize findings into actionable insights
- Produce wireframes, prototypes, and design specs
- Validate solutions via usability testing or prototypes
- Provide design assets and accessibility guidance for Developers

How they interact with existing roles
- Product Manager: collaborate on user needs, acceptance criteria, and prioritization
- Developers: handoff designs, answer design questions during implementation, review UI work
- QA: provide acceptance criteria focused on UX and accessibility
- PM: participate in planning to ensure UX tasks are scheduled and resourced

### Security Lead (or Security Champion)

Role Summary
- Ensures security considerations are integrated into design, development, and deployment phases, and helps coordinate security reviews and incident response.

Responsibilities
- Define security requirements for features and changes
- Perform threat modeling and security reviews for high-risk changes
- Establish secure defaults and best practices (e.g., secrets management, dependency scanning)
- Coordinate with on-call and incident response when security issues arise

How they interact with existing roles
- Developers: code review and security guidance; remediation recommendations
- QA: include security test cases in acceptance criteria
- PM/Product: advise on risks that affect scope or timeline
- Stakeholders: escalate business-impacting security risks when necessary

### Data Analyst

Role Summary
- Aligns product metrics with business goals, instruments analytics, and analyzes user behavior to inform decision-making.

Responsibilities
- Work with Product Managers to define success metrics and instrumentation needs
- Create dashboards and reports that track adoption, retention, and core KPIs
- Conduct ad-hoc analyses to validate hypotheses
- Ensure tracking events are implemented as part of the Definition of Done

How they interact with existing roles
- Product Manager: define metrics and experiment success criteria
- Developers: specify and validate instrumentation and schema
- PM: help prioritize analytics work in planning and retrospectives
- Stakeholders: present data-backed insights for decisions

### Support Engineer (or Customer Support Liaison)

Role Summary
- Serves as the frontline technical contact for users, triaging issues and feeding product and engineering with real-world problems and patterns.

Responsibilities
- Triage incoming issues and escalations
- Reproduce issues, collect diagnostics, and document workarounds
- Communicate frequent or high-impact issues to Project Manager and Developers
- Maintain the knowledge base and contribute release notes from a support perspective

How they interact with existing roles
- Developers: escalate and provide repro steps; collaborate on fixes
- PM: share customer impact and priorities for fixes or improvements
- QA: help validate fixes for customer-reported bugs
- Stakeholders: inform support-sensitivity of releases and communication

---

## Interaction & Communication Matrix (summary)

- Product Manager ↔ Developers: define acceptance criteria, clarify scope, prioritize technical debt.
- Product Manager ↔ UX Designer: shape user research, design and validation.
- Project Manager ↔ Support Engineer: schedule fixes, prioritize critical customer issues.
- Developers ↔ Security Lead: integrate security reviews and fixes into sprints.
- Product Manager ↔ Data Analyst: define metrics, interpret experiments and results.
- QA ↔ Developers & UX: acceptance testing and usability validation.

For each persona added, document:
- Role Summary
- Responsibilities
- Typical Communication and touchpoints
- Primary owners for common artifacts (acceptance criteria, instrumentation, security sign-off)

---

## How these personas are used in exercises and projects

- Use these persona definitions to frame scenarios, onboarding checklists, and to ensure accountability in the project plan.
- Each persona can be used as a persona prompt for Copilot Spaces or other documentation to shape role-specific guidance.
