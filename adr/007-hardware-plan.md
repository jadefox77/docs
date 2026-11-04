# ADR-007: Start on the current laptop; migrate to a GPU machine in January 2027

- **Status:** Proposed
- **Date:** 2026-11-01

## Context
The current machine is a Lenovo V15-ADA: 8 GB RAM, integrated graphics, exact processor still to confirm. Unity scenes and character work need a dedicated GPU.

## Decision
Do code, backend, design and Blender basics on the laptop now; raise RAM to 12 GB if affordable; move to a dedicated-GPU desktop planned for January 2027. The budget is still open.

## Alternatives considered
- **Wait for new hardware before starting:** loses two months of learning.
- **Gaming laptop:** usually less performance per naira than a desktop, and harder to upgrade.

## Consequences
- Heavy Unity scenes, high-detail sculpting and face rigs wait for the new machine.
- Everything lives in Git and Git LFS, so migrating means cloning, not rebuilding.

## Revisit if
The upgrade slips well past January 2027; then re-plan the order of work.
