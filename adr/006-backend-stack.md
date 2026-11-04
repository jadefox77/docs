# ADR-006: Backend: Node.js + TypeScript + Supabase Postgres

- **Status:** Proposed
- **Date:** 2026-11-01

## Context
The developer already builds Node/TypeScript services. The backend handles accounts, saves, wallet, purchases and leaderboards, not real-time gameplay.

## Decision
Fastify API in Node.js + TypeScript; PostgreSQL via Supabase (including Supabase Auth); Next.js for the website, player portal and admin; OpenAPI contracts with a generated C# client. Rust only where profiling proves a need.

## Alternatives considered
- **Rust from the start:** slower to build while also learning C# and Unity.
- **Unity Gaming Services only:** less control over the economy and data, and vendor lock-in.

## Consequences
- The API is the only writer to the database.
- Free tiers during development; about $25/month (Supabase Pro) once players depend on it.

## Revisit if
Profiling shows a Node bottleneck, or costs outgrow the plan.
