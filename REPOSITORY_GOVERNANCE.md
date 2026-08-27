# Repository Governance Contract

Policy ID: `ng-repo-governance/1.0.0`
Last reviewed: 2026-08-27

## Identity

- Repository: `Yesol-Pilot/ideal-type-calc-og`
- Lifecycle class: `public-service-surface`
- Current owner: `Yesol-Pilot`
- Intended owner: `NeoGenesisAI`
- Canonical branch: `main`
- Visibility: `public`
- Production status: `UNKNOWN`
- Transfer state: `REQUIRED`

`UNKNOWN` means not independently verified and must never be reported as PASS.

## Purpose and current risk

This repository supports a public ideal-type calculator or its sharing metadata. Results may be entertainment-oriented, but inputs, inferred preferences, sharing cards, analytics, and public claims still require privacy and accuracy boundaries.

- Active URL, calculation formula, input retention, analytics, sharing behavior, age suitability, and rollback remain `UNKNOWN`.
- Results must not be framed as scientific, psychological, medical, or compatibility facts without evidence.
- Personal preference inputs must not be stored or transmitted beyond the stated purpose without consent.
- Share images and metadata must not reveal raw answers or identifiers unexpectedly.

## Required remediation

- [ ] Document calculation method, entertainment disclaimer, input data lifecycle, analytics, sharing, age boundary, and active deployment.
- [ ] Run full-history secret, dependency, license, privacy, public-claim, and asset audits.
- [ ] Add deterministic calculation, boundary, localization, privacy, consent, sharing-card, metadata, accessibility, route, deployment, and rollback tests.
- [ ] Prohibit scientific or predictive claims beyond the validated method.
- [ ] Transfer the repository to `NeoGenesisAI` while preserving public URL and metadata integrations.

## Pull-request and branch rules

- One task, one branch, one isolated worktree.
- Draft inactivity limit: 14 days; maximum stack depth: 3.
- PRs declare formula, input, privacy, analytics, public-claim, sharing, and rollback impact.
- Review conversations resolve before squash merge.
- `main` is not force-pushed or deleted.

## Exit criteria

The repository becomes `TRANSFERRED_COMPLIANT` only when organization ownership, transparent method and disclaimers, privacy-safe inputs and sharing, exact deployment, public metadata, accessibility, monitoring, and rollback are proven.

The presence of this file alone is not compliance.
