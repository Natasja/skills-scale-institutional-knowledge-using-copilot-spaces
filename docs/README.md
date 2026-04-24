# OctoAcme Project Management Docs

Welcome! This README is the entry point for all OctoAcme project management process documentation. Below you'll find a concise overview of our project management philosophy, followed by links to each detailed process guide.

## Overview

OctoAcme's project management approach is designed for consistent, iterative delivery with clear ownership and lightweight, repeatable artifacts. Work moves through a defined lifecycle: **Initiation** (validate the problem and success metrics), **Planning** (turn approved work into a prioritized backlog and release plan), **Execution** (deliver in small increments with clear tracking), **Release** (deploy with standardized checklists), and **Close & Retrospective** (capture learnings and feed improvements back into the process). Core artifacts that keep teams aligned include a **Project One-pager/Charter**, a prioritized **backlog with acceptance criteria**, a **Definition of Done (DoD)**, a **risk register**, and retrospective action items.

Roles and responsibilities are explicitly defined to ensure accountability. The **Project Manager (PM)** coordinates delivery, schedules, risks, and stakeholder communications; the **Product Manager (PdM)** owns outcomes, prioritization, and success measurement; **Developers** design, build, and test in collaboration with product and project leads; **QA/Testing** validates quality and acceptance criteria; and **Stakeholders** provide input and approvals. This role clarity supports "clear ownership" as a guiding principle while keeping decisions data-informed and oriented toward customer value.

Communication is structured around a regular cadence and proven templates. Teams run short daily standups, a weekly PM + PdM delivery sync, and monthly stakeholder updates, supplemented by sprint/milestone demos. Status updates follow a consistent format (progress, next steps, risks/blockers, asks/decisions), and escalations follow a defined path from team triage to PM/Product Lead and, if needed, sponsor-level escalation. Risks and dependencies are tracked in a simple risk register (impact, likelihood, owner, mitigation, status) and reviewed during weekly syncs.

Quality assurance is embedded throughout delivery and release. Pull requests are kept small, include issue links and acceptance criteria, and require CI checks (tests, linting, security scanning) before review and merge. Testing scales by change type—unit tests for new logic, integration tests where applicable, and end-to-end smoke tests for critical flows prior to release—plus manual QA when needed. Releases follow a standardized checklist: acceptance criteria met, scans passing, release notes drafted, rollback plan prepared, staging verification completed, and stakeholder announcements sent. Incidents trigger a blameless retrospective loop to drive continuous improvement.

## Contents

- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)
- [RACI Matrix](./octoacme-raci-matrix.md)
- [Cross-Functional Handoff Checklists](./octoacme-handoff-checklist.md)
