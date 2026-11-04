# ADR-002: First platforms: Windows PC and Android together

- **Status:** Accepted
- **Date:** 2026-11-01

## Context
Most Nigerian players are on Android phones, often budget models; PC reaches Steam and players with stronger hardware. Consoles need company registration and platform approval.

## Decision
Build Windows PC and Android together from day one. iOS comes second, PlayStation third.

## Alternatives considered
- **PC first, mobile later:** retrofitting touch controls and mobile performance late is expensive.
- **Mobile only:** loses Steam reach and the high-end audience.

## Consequences
- Input uses abstract actions so keyboard, controller and touch map to the same controls.
- Low/Medium/High quality tiers exist from the start; the budget Android phone sets the baseline.
- Every cycle includes a test on a real budget Android phone.
- iOS needs a Mac and $99/year; PlayStation needs partner approval, Unity Pro and certification.

## Revisit if
PC + Android launch metrics show a different platform should come next.
