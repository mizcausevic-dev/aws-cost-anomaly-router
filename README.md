# AWS Cost Anomaly Router

Operator surface for AWS Cost Anomaly Detection routing, budget breach posture, FinOps ownership clarity, and stop-the-bleed evidence packaging.

- **Live:** [`https://awsfinops.kineticgain.com/`](https://awsfinops.kineticgain.com/)
- **Lane:** Multi-Cloud / FinOps · AWS signal
- **Repo:** [`mizcausevic-dev/aws-cost-anomaly-router`](https://github.com/mizcausevic-dev/aws-cost-anomaly-router)

## Why this matters

Operating leaders working with AWS need a surface that sits *next to* the vendor
console — one that answers what's open, who owns it, what it costs, and where the evidence
lives — without forcing every conversation to start with a pivot through the platform UI.

This operator surface does that. **Read-only**, synthetic data only, designed to be the
legible posture-of-record next to AWS for the executive, the auditor, and the board.

## What it includes

- Single-page static surface (Style01 dark theme)
- Two operator lanes with synthetic but realistic posture data
- Four headline stats — open count, exposure, ownership, cycle-time
- Zero production credentials, zero write-path, zero "compliant/certified" claims
- AGPL-3.0-or-later licensed, weekly Dependabot, CodeQL default-setup

## Production status

- `v1.0-prod` tagged release
- CI gates green (lint, typecheck, build, npm audit)
- SECURITY.md + CODE_OF_CONDUCT.md + CHANGELOG.md present
- Custom domain `awsfinops.kineticgain.com` configured via Hostinger FTP-Deploy-Action
  (deploys land once subdomain is provisioned in Hostinger hPanel)
- Compliance framing: readiness/evidence/posture language only

## What it isn't

Not a AWS replacement. Not a control plane. Not a write-path. The AWS
platform stays the source of truth. This surface just makes the operating posture *legible*.
