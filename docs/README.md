# OctoAcme Project Management Process Docs

This README provides a short index and summary of OctoAcme's project management process documents stored in this repository's docs/ folder. It is intended as a single-entry navigation point to help new teammates and contributors find the right process guidance quickly.

OctoAcme follows a lightweight, iterative lifecycle that emphasizes clear ownership, measurable outcomes, and incremental delivery. Projects move through Initiation (one‑pager to validate the idea and align stakeholders), Planning (backlog, estimates, Definition of Done, and release mapping), Execution & Tracking (delivery cadence, small PRs, CI, and progress monitoring), Release & Deployment (pre-release checks, smoke tests, rollback plans), and Close & Retrospective (capture learnings and action items). This approach prioritizes delivering small, testable increments and learning from data.

Work is organized on a project board using columns such as Backlog → Ready → In Progress → In Review → QA → Done, and pull requests are expected to be small, linked to issues, and validated by CI and peer review. Roles are explicit: Product Managers define outcomes and prioritize the roadmap; Project Managers coordinate delivery, schedules, and communications; Developers implement features, own tests and reviews; QA validates acceptance criteria and performs manual or automated testing as appropriate. Clear role definitions support accountability and smoother handoffs.

Communication and quality assurance are built into the cadence and artifacts: daily standups, weekly delivery syncs, sprint demos, and regular stakeholder updates. QA practices include unit and integration tests, end‑to‑end smoke tests for critical flows, CI security scanning, and manual QA where needed. Risk and communication guidance (risk register, escalation paths, incident templates) and release playbooks (pre-release checks, post-deploy verification, rollback steps) help reduce operational risk. Retrospectives capture action items and feed continuous improvements back into the backlog and process docs.

## Links to full docs
- [Project Management Overview](octoacme-project-management-overview.md) — high-level purpose, principles, roles, and lifecycle.  
- [Project Initiation Guide](octoacme-project-initiation.md) — one-pager template, initiation checklist, and decision gate.  
- [Project Planning](octoacme-project-planning.md) — planning activities, backlog template, and risk management.  
- [Execution & Tracking](octoacme-execution-and-tracking.md) — team rhythm, workflows, quality, and execution checklist.  
- [Risk Management & Communication](octoacme-risks-and-communication.md) — risk register, communication templates, and escalation.  
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — pre-release requirements, deployment checklist, and rollback playbook.  
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — retrospective structure and tracking improvements.  
- [Roles & Personas](octoacme-roles-and-personas.md) — role summaries and responsibilities.

## How to use
- Add or update process docs in this folder and update this README to keep the index accurate.  
- Use these docs as the single source of navigation for process guidance; link to specific sections in project READMEs or .copilot/ files for Copilot Spaces context.  
- Keep the one‑pager and key artifacts (project charter, risk register, release notes) in the project repo for traceability.
