# OctoAcme — Cross-Functional Handoff Checklists

Use these lightweight checklists whenever work moves between functional areas. They reduce ambiguity, prevent rework, and make handoffs explicit and auditable.

---

## Design → Dev Handoff

**Triggered when:** A design is approved and ready for implementation.

**Owner:** UX/UI Designer (hands off) · Developer (receives)

### Designer must provide
- [ ] Final, annotated design files linked in the relevant issue or PR (e.g., Figma link)
- [ ] Responsive/breakpoint specifications noted
- [ ] Interactive states documented (hover, focus, error, empty, loading)
- [ ] Assets exported and stored in the agreed location (e.g., repo `/assets` folder)
- [ ] Accessibility notes included (color contrast ratios, ARIA labels, keyboard navigation)
- [ ] Any open design questions flagged or resolved

### Developer confirms receipt
- [ ] Design files reviewed and questions asked before coding begins
- [ ] Design linked in the implementation PR description
- [ ] Ambiguous states clarified with the designer before closing the issue
- [ ] Implementation reviewed against design before moving to QA (self-check or pair review with designer)

---

## Dev → QA Handoff

**Triggered when:** A feature or fix is code-complete, merged to the test branch/environment, and ready for QA validation.

**Owner:** Developer (hands off) · QA Lead (receives)

### Developer must provide
- [ ] PR merged and deployed to the QA/staging environment
- [ ] Issue or ticket updated with the build/environment URL
- [ ] Acceptance criteria listed or linked in the ticket
- [ ] Known limitations, edge cases, or exclusions from this release documented
- [ ] Automated tests passing in CI (link to CI run included)
- [ ] Any test data or setup steps documented (e.g., seed scripts, feature flags)

### QA Lead confirms receipt
- [ ] Build is accessible in the QA environment
- [ ] Test cases mapped to acceptance criteria exist
- [ ] Exploratory test areas noted (based on change risk)
- [ ] Defects logged with severity and steps to reproduce
- [ ] Regression suite run (or waived with documented reason)

---

## QA → Release Handoff

**Triggered when:** QA has completed testing and is providing a go/no-go recommendation for production deployment.

**Owner:** QA Lead (hands off) · Project Manager + Developers (receive)

### QA Lead must provide
- [ ] Test summary: features tested, pass/fail counts, coverage
- [ ] All critical and high-severity defects resolved (or exceptions approved by PdM/PM)
- [ ] Known issues documented with severity and agreed disposition (fix now / defer / accept)
- [ ] Sign-off recorded in the issue, PR, or release ticket
- [ ] Smoke test scripts ready for post-deploy verification

### Project Manager + Developer confirm before deploying
- [ ] QA sign-off received and documented
- [ ] Release notes drafted and reviewed (see [Release & Deployment Guide](./octoacme-release-and-deployment.md))
- [ ] Rollback plan documented and team briefed
- [ ] Deployment window communicated to stakeholders
- [ ] Post-deploy monitoring alerts confirmed active

---

## Related Documents
- [Roles and Personas](./octoacme-roles-and-personas.md)
- [RACI Matrix](./octoacme-raci-matrix.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
