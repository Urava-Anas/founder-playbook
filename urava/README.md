# Urava Founder Intelligence v1

This directory is Urava's overlay on the upstream Founder Playbook. The upstream book-derived skills remain intact. Urava adds routing, authority, evidence, skill mapping, and operating adapters without silently rewriting source material.

## Purpose

Convert useful founder frameworks into bounded, evidence-aware operating intelligence for Urava.

Runtime:

`Founder intent → Developer House Dispatcher → Urava authority check → one primary intelligence module → optional secondary module → concrete action → evidence/result → update confidence`.

## Core files

- `AUTHORITY.md` — precedence, safety, allowed/forbidden use.
- `ROUTER.md` — selective retrieval and one-primary-module routing.
- `COMMERCIAL_CHAIN.md` — gated commercial handoff from discovery through messaging.
- `SKILL_MAP.md` — playbook → Developer House mapping.
- `EVIDENCE.md` — evidence/confidence contract.
- `INGESTION.md` — source-ingestion pipeline.
- `adapters/` — Urava-specific wrappers; source modules outside `urava/` remain untouched.

## Commercial chain

`Mom Test → 100M Offers + Monetizing Innovation → Traction + 100M Leads → SPIN Selling → StoryBrand + Made to Stick`

This is a gated sequence, not seven always-on agents. The Dispatcher loads only the current bottleneck stage; failed evidence routes backward rather than automatically continuing forward.

Active adapters:

- `diagnose`
- `mom-test`
- `100m-offers`
- `monetizing-innovation`
- `traction`
- `100m-leads`
- `spin-selling`
- `storybrand`
- `made-to-stick`

## Validation scope

The v1 chain is structurally reconciled with the source modules and Urava governance. It is not high-confidence Urava commercial truth yet. Confidence rises only through measured Urava execution recorded via `EVIDENCE.md`.

## Source preservation

Files outside `urava/` remain upstream/reference material. Prefer overlay adapters to source edits so upstream updates stay pullable and copyrighted source material is not redistributed through the overlay.
