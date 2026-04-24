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

## Scrum Master

### Role Summary
The Scrum Master facilitates Agile/Scrum ceremonies, removes impediments, and coaches the team on Scrum practices. They serve the team by ensuring a smooth delivery cadence and continuous improvement.

### Responsibilities
- Facilitate sprint planning, daily standups, sprint reviews, and retrospectives
- Identify and remove blockers that impede team progress
- Shield the team from external interruptions during a sprint
- Track and communicate sprint health (velocity, burndown)
- Coach team members and stakeholders on Agile principles

### Goals
- Maintain a predictable, sustainable delivery cadence
- Reduce waste and eliminate process bottlenecks
- Foster a culture of continuous improvement and psychological safety

### Typical Communication
- Daily standups and sprint ceremonies facilitation
- Impediment logs and blocker escalations
- Sprint metrics and retrospective action item tracking

### Interactions with Existing Roles
- **Developers**: Removes technical and organizational blockers; ensures sprint backlog is well-understood before work begins.
- **Product Managers**: Coordinates backlog refinement sessions and ensures user stories meet the Definition of Ready.
- **Project Managers**: Aligns sprint milestones with the broader project timeline; escalates cross-team dependencies.

---

## UX/UI Designer

### Role Summary
UX/UI Designers translate product requirements and user research into intuitive, accessible interfaces. They bridge product vision and engineering implementation through design artifacts and prototypes.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and interactive prototypes
- Define and maintain design system components
- Collaborate with developers on feasibility and implementation fidelity
- Ensure accessibility (WCAG) compliance in design artifacts

### Goals
- Deliver user-centered designs that reduce friction and improve satisfaction
- Maintain consistency across the product through a shared design system
- Enable developers to implement designs accurately with minimal back-and-forth

### Typical Communication
- Design reviews and handoff sessions with engineering
- Prototype links and annotated design files (e.g., Figma)
- Usability test findings and recommendations

### Interactions with Existing Roles
- **Developers**: Provides annotated designs and participates in implementation reviews; uses the [Design → Dev Handoff Checklist](./octoacme-handoff-checklist.md#design--dev-handoff).
- **Product Managers**: Aligns design decisions with product goals and accepts/validates design direction via feature specs.
- **Project Managers**: Communicates design timeline and flags risks when design scope changes during a sprint.

---

## QA Lead

### Role Summary
The QA Lead defines and oversees the quality strategy for a project, ensuring that software meets acceptance criteria and is free of critical defects before release.

### Responsibilities
- Define the test strategy and test plan for each release
- Write, review, and maintain automated and manual test cases
- Coordinate testing across functional and non-functional areas (performance, security, accessibility)
- Triage and prioritize defects; track resolution
- Own the go/no-go quality signal before deployments

### Goals
- Prevent critical defects from reaching production
- Increase test coverage and reduce regression risk over time
- Enable faster, more confident releases through automation

### Typical Communication
- Test plan and coverage reports shared with PM and developers
- Defect triage in sprint planning and daily standups
- Go/no-go sign-off documented before each release; see [Dev → QA and QA → Release Handoff Checklists](./octoacme-handoff-checklist.md)

### Interactions with Existing Roles
- **Developers**: Collaborates on acceptance criteria and Definition of Done; uses the [Dev → QA Handoff Checklist](./octoacme-handoff-checklist.md#dev--qa-handoff) to ensure testable builds are delivered.
- **Product Managers**: Validates acceptance criteria before stories are closed; flags scope or quality trade-off risks.
- **Project Managers**: Provides quality status for stakeholder reports and participates in release go/no-go decisions.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- For a quick view of who is responsible for which activities, see the [RACI Matrix](./octoacme-raci-matrix.md).
- For cross-functional handoff checklists, see the [Handoff Checklist](./octoacme-handoff-checklist.md).

