# ADR-001: Engine: Unity 6

- **Status:** Accepted
- **Date:** 2026-11-01

## Context
One developer with a web/TypeScript background is building for Windows PC and low-end Android, on a laptop without a dedicated GPU, with no licence cost wanted until real revenue.

## Decision
Use Unity 6 with C# and the Universal Render Pipeline (URP). The editor is pinned to **6000.3.27f2 (Unity 6.3 LTS)**; moving to a newer LTS is a deliberate change, never an automatic update.

## Alternatives considered
- **Unreal Engine 5:** highest graphics ceiling and built-in replication, but heavy on low-end Android, not usable on the current laptop, C++ learning curve; 5% royalty above $1M lifetime gross per product.
- **Godot 4:** free (MIT) and light, but less proven for 3D mobile games at scale, smaller ecosystem, consoles only via third-party porting.

## Consequences
- Lower photoreal ceiling, offset by art direction (ADR-003).
- Multiplayer is assembled from packages (Netcode for GameObjects or Fish-Net).
- Unity Pro is required above $200K revenue plus funding in 12 months, or to build for consoles.

## Revisit if
Part 1 earns enough to hire a team, or the audience proves to be mostly high-end PC.
