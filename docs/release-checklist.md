# Release Checklist

A lightweight release checklist to support the Delivery Coordinator and teams preparing for a deployment.

## Pre-release (2-7 days before)
- [ ] Confirm feature branch merges and release candidate build
- [ ] Run end-to-end and smoke tests on staging
- [ ] Verify security scan results and remediation status
- [ ] Ensure runbook and rollback plan exist and are reviewed
- [ ] Confirm all required sign-offs (Product, QA, Security)
- [ ] Announce planned release window to stakeholders

## Release Day
- [ ] Confirm deployment window and responsible contacts
- [ ] Verify monitoring and observability dashboards are ready
- [ ] Execute deployment steps from runbook
- [ ] Run post-deploy smoke tests
- [ ] Communicate release completion and any action items

## Post-release (0-3 days after)
- [ ] Monitor incidents and error rates closely
- [ ] Run a short post-release retrospective and capture any fixes to the runbook
- [ ] Close release notes and update project status
