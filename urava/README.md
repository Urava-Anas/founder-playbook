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
- `SKILL_MAP.md` — mapping from playbook modules into Developer House skills and Urava systems.
- `EVIDENCE.md` — evidence/confidence contract for validating imported advice against Urava reality.
- `INGESTION.md` — source ingestion and validation pipeline.
- `adapters/diagnose.md` — Urava-specific wrapper for the upstream diagnostic meta-skill.
- `adapters/mom-test.md` — Urava-specific wrapper for customer discovery.

## Source preservation rule

Files outside `urava/` remain upstream/reference material unless a later, explicit Urava reconciliation decision says otherwise. Prefer new overlays/adapters to edits of source skills so upstream can be updated cleanly.
