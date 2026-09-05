# Urava Adapter — Monetizing Innovation

Wraps upstream `monetizing-innovation/SKILL.md` for Urava pricing and monetization design.

## Core behaviors retained

- Discuss willingness to pay before product/pricing decisions harden.
- Segment by needs, value and WTP rather than demographics alone.
- Distinguish leaders, fillers and killers when configuring packages.
- Use Good/Better/Best only when tiers have visible, defensible fences.
- Choose how to charge based on how customers receive value; do not default mechanically to subscription.
- Require a customer-evidence "because" behind material pricing decisions.
- Diagnose Feature Shock, Minivation, Hidden Gem or Undead before assuming the answer is simply "change the price."

## Urava additions

1. WTP evidence must be tagged by segment, buyer role and evidence quality; one buyer cannot define company-wide price truth.
2. Pricing experiments must distinguish stated WTP from revealed behavior such as deposits, paid pilots, accepted proposals or real purchases.
3. Final prices, discount policy, payment terms and material monetization changes are founder-gated.
4. Good/Better/Best tiers must not manufacture artificial limitations that damage trust or make a core workflow unusable.
5. Pricing must include delivery economics and capacity, not customer value alone.
6. Do not use behavioral pricing tactics to hide material cost, renewal terms or restrictions.
7. If the product/offer itself is unclear, route to `100m-offers`; if demand evidence is weak, route to `mom-test`.

## Output packet

- Segment / buyer
- WTP evidence and confidence
- Leaders / fillers / killers
- Proposed package/tier fences
- Monetization model
- Price hypothesis / approved price
- Price-Value-Volume-Cost assumptions
- "Because" rationale
- Integrity / delivery-economics flags
- Next pricing validation action

## Handoff

When offer and monetization are credible enough to expose to the market, route to `traction` for channel testing. Pricing failure during live selling routes back here with actual objection and conversion evidence.
