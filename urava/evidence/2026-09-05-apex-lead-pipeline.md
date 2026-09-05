# Evidence — Apex Lead Pipeline, 2026-09-05

## Record ID

`E-2026-09-05-APEX-LEADS`

## Framework claim under test

Lead generation should distinguish raw/contactable/qualified states, gate bad records, focus on lead quality rather than raw volume, and measure actual movement into engagement rather than treating a lead list as acquisition success.

## Source modules

- `100m-leads/SKILL.md`
- `traction/SKILL.md`
- Urava adapter: `urava/adapters/100m-leads.md`
- Urava adapter: `urava/adapters/traction.md`

## Urava context

Apex Logistics & Dispatch carrier-acquisition pipeline. Evidence was read from the canonical connected Airtable lead base and cross-checked against the connected Gmail account on 2026-09-05.

## Observed facts

Airtable contained **14 Apex lead records** in the current imported set:

- **13 / 14** had authority marked verified.
- **12 / 14** were in `READY` state.
- **1 / 14** was in `CONTACTED` state.
- **1 / 14** was held as `HOLD - AUTHORITY NOT VERIFIED`.
- All 14 records were marked as newly detected FMCSA registrations.
- Lead scores in this set were 95 or 100.
- **11 / 14** had an email address present.
- **12 / 14** had a phone number present.

A Gmail cross-check across all 11 lead email addresses returned **zero messages to or from those addresses** in the connected mailbox.

## Interpretation

### Supported

The operational rule **"gate invalid/unverified leads before outreach and preserve explicit lead states"** is supported in this Apex dataset. The system correctly prevented at least one authority-unverified carrier from entering the ready pool.

### Not yet supported

The current dataset does **not** prove that the lead source, lead score, or READY classification produces replies, meetings, paying customers, or profitable acquisition.

The Airtable `CONTACTED` status is an operational state, but the connected Gmail account did not independently corroborate email outreach to that lead. It may have been contacted through another channel, but that is not verified by the sources checked here.

## Outcome

**Mixed**

- Lead-quality/gating discipline: **supported**.
- Acquisition effectiveness: **not measurable yet**.
- Sales conversion: **not measurable yet**.

## Confidence

**Medium** for the operational gating conclusion because it is based on the full current 14-record set and a canonical system state.

**Low** for any conclusion about market response, because verified outreach/reply/payment evidence is absent.

## Scope

Applies only to the current Apex carrier-acquisition pipeline and this imported lead set. Do not generalize the 95/100 score thresholds or new-registration signal to all Urava markets without response/conversion evidence.

## Strongest counter-case

A high-scored, authority-verified lead can still be commercially worthless if the contact data is stale, the carrier has no active need, the message is weak, or outreach never occurs.

## Next review trigger

Re-evaluate when at least one of these becomes available:

- verified outbound contact events per lead;
- replies or explicit refusals;
- discovery-call outcomes;
- qualified-opportunity states;
- proposal/offer advances;
- payment or retained-customer outcomes.

At that point calculate progression by source/score/status rather than treating lead count as success.
