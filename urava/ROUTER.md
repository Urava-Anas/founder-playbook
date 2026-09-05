# Urava Intelligence Router

## Goal

Retrieve the smallest useful intelligence packet for the current problem. Do not load the full playbook by default.

## Dispatcher sequence

1. Resolve the current objective and canonical evidence source.
2. Apply `AUTHORITY.md`.
3. If the problem category is unclear, consult upstream `diagnose/SKILL.md` through `adapters/diagnose.md`.
4. Select **one primary module**.
5. Add **one secondary module only if it provides a distinct dependency**.
6. Load `SKILL.md` first. Load `frameworks.md`, `examples.md`, `cases.md`, or `integration.md` only when the task needs that depth.
7. Produce one concrete action or decision packet.
8. Record outcome/evidence using `EVIDENCE.md`.

## Routing table

| Problem | Primary | Optional secondary |
|---|---|---|
| Unknown founder/commercial problem | diagnose | none until diagnosed |
| Customer discovery / fake-positive feedback | mom-test | four-steps |
| Business-model discovery / first customers | four-steps | mom-test |
| MVP / experiment / pivot | lean-startup | mom-test |
| Positioning / category / best-fit customer | obviously-awesome | crossing-the-chasm |
| Message clarity / website story | storybrand | made-to-stick |
| Memorable pitch / communication | made-to-stick | storybrand |
| Pricing / willingness to pay | monetizing-innovation | 100m-offers |
| Offer packaging | 100m-offers | monetizing-innovation |
| Unit economics / self-funded acquisition | money-models | 100m-offers |
| Channel selection | traction | 100m-leads |
| Lead generation tactics | 100m-leads | traction |
| B2B sales calls / complex deals | spin-selling | influence |
| Ethical persuasion / decision psychology | influence | spin-selling |
| Early adopters → mainstream | crossing-the-chasm | obviously-awesome |
| Commoditized market / value innovation | blue-ocean-strategy | obviously-awesome |

## Stop conditions

Do not keep stacking frameworks when:

- one validated next action is already clear;
- a decision requires fresh customer/market evidence rather than more theory;
- framework conflicts cannot be resolved from current evidence;
- the issue is primarily technical, legal, financial-accounting, hiring, security, or operational and the playbook has no strong module for it.

In those cases route back to the relevant Developer House skill or Founder decision gate.

## Context budget rule

Default retrieval budget:

`module description → SKILL.md → only one deeper supporting file if required`.

Integration files are for cross-framework conflicts/sequencing, not routine use. Case files are examples, not authority.
