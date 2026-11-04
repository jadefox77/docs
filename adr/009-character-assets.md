# ADR-009: Characters from CC0 human-made base meshes

- **Status:** Accepted
- **Date:** 2026-11-01

## Context
Professional character art is the biggest bottleneck for a solo developer.

## Decision
Build characters by customising CC0, human-made base meshes (Blender Studio Human Base Meshes; MakeHuman as an alternative). Licensed human-made animations may be placeholders only and are replaced before release. No AI-generated final assets.

## Alternatives considered
- **Modelling from scratch:** slowest beginner stage (anatomy, topology).
- **AI 3D generators (e.g. Tripo):** not used for shipped assets: messy topology that still needs retopology and rigging, store disclosure, and licence uncertainty.

## Consequences
- Every base or third-party asset is logged in `provenance.md`.
- Still expect several attempts before the first game-ready character.

## Revisit if
Revenue allows a freelance character artist or animator.
