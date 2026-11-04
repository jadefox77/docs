# ADR-011: World built from OSM, procedural tools, photos and modular kits

- **Status:** Accepted
- **Date:** 2026-11-01

## Context
The world must feel recognisably Nigerian without a large environment team, and every asset must be legally clean.

## Decision
Use OpenStreetMap data (via BlenderGIS or Blosm), Geometry Nodes generators, modular kits and own photography. Distances are compressed, not 1:1. No generative AI in shipped environments; no geometry or imagery from Google Maps or Google Earth.

## Alternatives considered
- **Hand-placing everything:** too slow.
- **Map imagery and 3D captures from Google:** not licensed for this use.

## Consequences
- OpenStreetMap is credited in the game credits (ODbL).
- Photo trips become part of production.

## Revisit if
Licences or tools change; re-check at each stage gate.
