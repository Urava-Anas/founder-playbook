# Urava Founder Intelligence v1

This directory is Urava's overlay on the upstream Founder Playbook. The upstream book-derived skills remain intact. Urava adds routing, authority, evidence, skill mapping, and operating adapters without silently rewriting source material.

## Purpose

Convert useful founder frameworks into bounded, evidence-aware operating intelligence for Urava.

The runtime pattern is:

`Founder intent → Developer House Dispatcher → Urava authority check → one primary intelligence module → optional secondary module → concrete action → evidence/result → update confidence`.

## Non-goals

- This is not a replacement for Urava's locked governance.
- This is not permission to apply every framework everywhere.
- This is not a transactional source of truth for company operations.
- This is not a reason to load every book/skill into context on every task.

## Files

- `AUTHORITY.md` — precedence, safety, allowed/forbidden use.
- `ROUTER.md` — selective retrieval and one-primary-module routing.
- `COMMERCIAL_CHAIN.md` — gated commercial handoff from discovery through messaging.
- `SKILL_MAP.md` — mapping from playbook modules into Developer House skills and Urava systems.
- `EVIDENCE.md` — evidence/confidence contract for validating imported advice against Urava reality.
- `INGESTION.md` — source ingestion and validation pipeline.
- `adapters/diagnose.md` — Urava-specific wrapper for the upstream diagnostic meta-skill.
- `adapters/mom-test.md` — Urava-specific wrapper for customer discovery.
- `adapters/100m-offers.md` — validated offer/value design with integrity and delivery-capacity guards.
- `adapters/monetizing-innovation.md` — WTP, packaging, monetization and pricing-evidence wrapper.
- `adapters/traction.md` — bounded channel selection/testing with evidence and spend gates.
- `adapters/100m-leads.md` — focused lead-system execution with qualification/economics/capacity controls.
- `adapters/spin-selling.md` — complex B2B need development and Advance-focused selling.
- `adapters/storybrand.md` — truthful message architecture and CTA/proof guardrails.
- `adapters/made-to-stick.md` — selective SUCCESs communication diagnostic after truth/clarity.

## Commercial chain

`Mom Test → 100M Offers + Monetizing Innovation → Traction + 100M Leads → SPIN Selling → StoryBrand + Made to Stick`

This is a gated sequence. The Dispatcher loads only the current bottleneck stage; failed evidence routes backward rather than automatically continuing forward.

## Validation scope

The current v1 chain is validated for structural consistency against the source modules and Urava governance. It is **not yet high-confidence Urava commercial truth**. Confidence rises only when the adapters are exercised against real discovery, offer, pricing, channel, lead, sales and messaging outcomes and those outcomes are recorded through `EVIDENCE.md`.

## Source preservation rule

Files outside `urava/` remain upstream/reference material unless a later, explicit Urava reconciliation decision says otherwise. Prefer new overlays/adapters to edits of source skills so upstream can be updated cleanly.

## Current implementation checkpoint

This README is part of the `urava/founder-intelligence-v1` branch. Use the branch/PR exact head as the implementation checkpoint rather than copying a SHA into this document, so routine commits do not create stale self-referential metadata.
