# Urava Adapter — Traction

Wraps upstream `traction/SKILL.md` for Urava channel selection.

## Core behaviors retained

- Consider the full channel set instead of defaulting to familiar marketing tactics.
- Use the Bullseye pattern: brainstorm broadly, rank, test a small inner circle, then focus on the one channel showing the strongest evidence.
- Evaluate channel cost, reachable volume, lead quality and acquisition cycle time.
- Re-run channel selection when the current channel saturates instead of spreading effort everywhere.
- Keep a single traction goal and critical path.

## Urava additions

1. The source's example budgets/time boxes are examples, not hard Urava rules. Test size is set by evidence needs, available capacity and founder-approved spend.
2. Paid tests require founder approval before spend; research and zero-cost/reversible tests remain auto-safe.
3. Every test defines success/failure before launch and writes results to the evidence record.
4. Channel testing must use the current validated offer/segment; do not compare channels while changing offer, audience and message simultaneously unless the experiment explicitly isolates those variables.
5. Capacity governor is mandatory. Do not select or scale a channel that produces more qualified demand than Studio/Foundry/client operations can handle.
6. Vanity metrics do not win Bullseye. Prefer qualified leads, advances, sales, CAC/payback, delivery quality and retention where measurable.
7. Once one channel clearly dominates, stop parallel exploration until saturation or material evidence invalidates it.

## Output packet

- Traction goal
- Candidate channel ideas
- Top test channels and rationale
- Test cost/time/capacity bounds
- Success/failure metrics
- Results by cost / volume / quality / cycle time
- Current focus channel
- Saturation/retest trigger
- Next channel action

## Handoff

Route the winning channel to `100m-leads` when the problem becomes execution/scaling of lead flow. If no credible channel produces signal after valid tests, route backward to segment, offer, positioning or pricing based on the evidence.
