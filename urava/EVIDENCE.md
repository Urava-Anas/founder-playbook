# Evidence Contract

Every imported founder framework is provisional until it survives Urava reality.

## Evidence record

For any meaningful recommendation or learned rule, capture:

- **Claim:** what the framework predicts or recommends.
- **Source module:** exact module/file.
- **Urava context:** company/project/customer segment/stage where it was applied.
- **Action:** what was actually done.
- **Metric/evidence:** observable result from a canonical source.
- **Outcome:** supported / mixed / contradicted / not measurable.
- **Confidence:** low / medium / high.
- **Scope:** where the rule is allowed to generalize.
- **Counterexample:** strongest known case where it failed.
- **Next review trigger:** new sample size, market change, product change, or contradictory evidence.

## Runtime evidence loop

`execution → canonical source read → compact evidence record → framework comparison → confidence/scope update → future routing`

Rules:

1. **Canonical evidence first.** Use the operational source that actually owns the state: CRM/lead system for lead state, Gmail/Relay for communication, billing/payment source for payment, product/runtime data for usage, and project delivery systems for implementation outcomes.
2. **Do not infer stronger outcomes from weaker states.** `READY` is not contacted; `CONTACTED` is not replied; `APPROVED` planning is not paid; a signed agreement is not retention.
3. **Cross-check when possible.** If one system says `CONTACTED`, corroborate through the communication source before treating it as verified outreach evidence.
4. **Store aggregates and decision-relevant facts by default.** Avoid copying unnecessary PII, message bodies, credentials, or private operational detail into the intelligence repository.
5. **Framework attribution must be weaker than observed fact unless the framework was deliberately tested.** A retrospective resemblance is not a controlled experiment.
6. **Negative/absent evidence is evidence about instrumentation.** If a result cannot be verified, record `not measurable` and define the missing event/source needed to make it measurable.
7. **One real result should change confidence only within its context.** Do not globally promote a rule from a single customer or lead set.

## Evidence hierarchy

Prefer, in order:

1. Real payments/retention/usage/delivery outcomes.
2. Verified behavior and commitments.
3. Controlled experiments or repeatable operational tests.
4. Direct qualitative evidence from relevant users/customers.
5. Framework claims and case studies.
6. Opinions, compliments, hypotheticals, vanity metrics.

## Confidence rules

- **Low:** source-only idea, retrospective framework match, absent instrumentation, or one weak anecdote.
- **Medium:** repeated consistent observations, one strong real-world commitment/action, or one strong operational experiment with authoritative evidence.
- **High:** repeated measured Urava outcomes across the same context with no major unresolved contradiction.

Never turn a framework into a locked Urava rule from book authority alone.

## Evidence storage

Durable evidence records live under `urava/evidence/` and should use dated filenames. The evidence record is the compact intelligence artifact; the canonical source remains the operational system itself.

Current records:

- `urava/evidence/2026-09-05-apex-lead-pipeline.md` — current Apex carrier-lead supply/gating evidence and outreach-measurement gap.
- `urava/evidence/2026-08-28-apex-proposal-approval.md` — real Apex B2B planning approval and explicit-advance evidence.

## Learning behavior

When evidence supports a framework, strengthen only the context-specific rule. When evidence contradicts it, retain the contradiction and downgrade the rule instead of deleting inconvenient history. When results are mixed, identify segmentation/context variables before averaging them together.

When evidence is missing, do not fill the gap with theory. Define the exact event that needs to be captured next and improve instrumentation if that event matters commercially.
