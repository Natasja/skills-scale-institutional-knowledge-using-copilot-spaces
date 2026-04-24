# OctoAcme — RACI Role-to-Activity Matrix

This matrix maps key project activities to team roles using the RACI model:
- **R** = Responsible (does the work)
- **A** = Accountable (final decision / sign-off)
- **C** = Consulted (input required)
- **I** = Informed (kept in the loop)

Roles: **Dev** = Developers · **PdM** = Product Manager · **PM** = Project Manager · **SM** = Scrum Master · **UX** = UX/UI Designer · **QA** = QA Lead

---

## Initiation & Planning

| Activity | Dev | PdM | PM | SM | UX | QA |
|---|:---:|:---:|:---:|:---:|:---:|:---:|
| Define problem statement & success metrics | C | A/R | C | I | C | I |
| Prioritize backlog | C | A | R | C | C | C |
| Estimate work items | R | C | C | A | C | C |
| Define Definition of Done (DoD) | R | C | A | R | C | R |
| Create release plan & milestones | C | C | A/R | C | I | C |
| Draft test plan / QA approach | C | C | C | I | I | A/R |

---

## Design

| Activity | Dev | PdM | PM | SM | UX | QA |
|---|:---:|:---:|:---:|:---:|:---:|:---:|
| Conduct user research | I | C | I | I | A/R | I |
| Create wireframes & prototypes | C | C | I | I | A/R | I |
| Review designs for feasibility | A/R | C | I | I | C | I |
| Accessibility review | C | I | I | I | A/R | C |
| Design handoff to development | C | I | I | I | A/R | I |

---

## Execution & Tracking

| Activity | Dev | PdM | PM | SM | UX | QA |
|---|:---:|:---:|:---:|:---:|:---:|:---:|
| Implement features | A/R | I | I | C | C | I |
| Code review | A/R | I | I | I | I | C |
| Facilitate daily standup | I | I | I | A/R | I | I |
| Remove impediments / blockers | C | C | A | R | C | C |
| Update risk register | C | C | A/R | C | I | C |
| Track sprint velocity & burndown | I | I | C | A/R | I | I |
| Write & execute test cases | C | I | I | I | I | A/R |
| Triage and prioritize defects | C | C | C | I | I | A/R |

---

## Release & Deployment

| Activity | Dev | PdM | PM | SM | UX | QA |
|---|:---:|:---:|:---:|:---:|:---:|:---:|
| Merge and prepare release branch | A/R | I | C | I | I | C |
| Deploy to staging | A/R | I | C | I | I | C |
| Execute smoke tests | C | I | C | I | I | A/R |
| Go/no-go sign-off | C | C | A | C | I | R |
| Deploy to production | A/R | I | C | I | I | I |
| Draft & publish release notes | C | R | A | I | I | C |
| Stakeholder release announcement | I | C | A/R | I | I | I |

---

## Retrospective & Improvement

| Activity | Dev | PdM | PM | SM | UX | QA |
|---|:---:|:---:|:---:|:---:|:---:|:---:|
| Facilitate retrospective | I | I | C | A/R | I | I |
| Capture action items | C | C | C | A/R | C | C |
| Track action item completion | C | C | A | C | C | C |
| Update process documentation | C | C | R | C | C | C |

---

## Related Documents
- [Roles and Personas](./octoacme-roles-and-personas.md)
- [Handoff Checklist](./octoacme-handoff-checklist.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
