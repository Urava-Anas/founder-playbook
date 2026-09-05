# Urava Intelligence Router

## Goal

Retrieve the smallest useful intelligence packet for the current problem. Do not load the full playbook by default.

## Dispatcher sequence

1. Resolve the current objective and canonical evidence source.
2. Apply `AUTHORITY.md`.
3. If the problem category is unclear, consult upstream `diagnose/SKILL.md` through `adapters/diagnose.md`.
4. Select **one primary module**.
5. If that module has an Urava adapter, load the adapter with the upstream `SKILL.md`; the adapter constrains application but does not replace the source module.
6. Add **one secondary module only if it provides a distinct dependency**.
7. Load `frameworks.md`, `examples.md`, `cases.md`, or `integration.md` only when the task needs that depth.
8. Produce one concrete action or decision packet.
9. Record outcome/evidence using `EVIDENCE.md`.

## Commercial chain shortcut

For commercial work, first locate the current bottleneck in `COMMERCIAL_CHAIN.md`:

`Mom Test → 100M Offers + Monetizing Innovation → Traction + 100M Leads → SPIN Selling → StoryBrand + Made to Stick`

This is a gated handoff sequence, not permission to load every module. A failed stage routes backward to the missing evidence.

## Routing table

| Problem | Primary | Optional secondary | Urava adapter |
|---|---|---|---|
| Unknown founder/commercial problem | diagnose | none until diagnosed | `adapters/diagnose.md` |
| Customer discovery / fake-positive feedback | mom-test | four-steps | `adapters/mom-test.md` |
| Business-model discovery / first customers | four-steps | mom-test | none yet |
| MVP / experiment / pivot | lean-startup | mom-test | none yet |
| Positioning / category / best-fit customer | obviously-awesome | crossing-the-chasm | none yet |
| Message clarity / website story | storybrand | made-to-stick | `adapters/storybrand.md` |
| Memorable pitch / communication | made-to-stick | storybrand | `adapters/made-to-stick.md` |
| Pricing / willingness to pay | monetizing-innovation | 100m-offers | `adapters/monetizing-innovation.md` |
| Offer packaging | 100m-offers | monetizing-innovation | `adapters/100m-offers.md` |
| Unit economics / self-funded acquisition | money-models | 100m-offers | none yet |
| Channel selection | traction | 100m-leads | `adapters/traction.md` |
| Lead generation tactics | 100m-leads | traction | `adapters/100m-leads.md` |
| B2B sales calls / complex deals | spin-selling | influence | `adapters/spin-selling.md` |
| Ethical persuasion / decision psychology | influence | spin-selling | none yet |
| Early adopters → mainstream | crossing-the-chasm | obviously-awesome | none yet |
| Commoditized market / value innovation | blue-ocean-strategy | obviously-awesome | none yet |

## Stop conditions

Do not keep stacking frameworks when:

- one validated next action is already clear;
- a decision requires fresh customer/market evidence rather than more theory;
- framework conflicts cannot be resolved from current evidence;
- the issue is primarily technical, legal, financial-accounting, hiring, security, or operational and the playbook has no strong module for it.

In those cases route back to the relevant Developer House skill or Founder decision gate.

## Context budget rule

Default retrieval budget:

`Urava adapter → module SKILL.md → only one deeper supporting file if required`.

Integration files are for cross-framework conflicts/sequencing, not routine use. Case files are examples, not authority.
