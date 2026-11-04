# ADR-014: Four-tier NPC model with Ink dialogue

- **Status:** Accepted
- **Date:** 2026-11-01

## Context
The world needs many people, but one developer can only hand-craft a few.

## Decision
NPCs come in four tiers: story characters, named side characters, functional NPCs (police, vendors, enemies) and crowd. All humans share one skeleton and a modular kit. Reputation is tracked per protagonist (campus, street, police, cult). Dialogue is hand-written in Ink; no live AI-generated dialogue. Behaviour starts as state machines; behaviour trees come later.

## Alternatives considered
- **Every NPC custom-made:** impossible for one person.
- **Live AI dialogue:** unpredictable, costly, and conflicts with the hand-written story.

## Consequences
- One skeleton means every animation works on every character.
- Crowd variety depends on the quality of the modular kit.

## Revisit if
NPC behaviour needs exceed what state machines can handle.
