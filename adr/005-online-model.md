# ADR-005: Campaign first, session-based online mode soon after

- **Status:** Accepted
- **Date:** 2026-11-01

## Context
Online play matters to Nigerian players, but solo multiplayer development is the hardest part of the plan.

## Decision
Ship the multi-protagonist campaign first and add a session-based online mode soon after. No persistent shared world in Part 1.

## Alternatives considered
- **Persistent shared world:** always-on servers, world-state database, moderation; years of extra work.
- **Hybrid hub plus sessions:** the hub needs persistence and population.

## Consequences
- The architecture is online-ready from day one: the backend API is the gatekeeper, and pure C# core rules can run on a game server.
- The campaign plays offline.
- Game servers run only during matches.

## Revisit if
The player base is large enough to justify a shared hub (hybrid model).
