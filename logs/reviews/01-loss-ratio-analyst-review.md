# Review — loss-ratio-analyst

**Reviewer:** loss-ratio-analyst
**Artifact:** `whitepaper/claim-cost-containment-v2-draft.md`
**Date:** 2026-05-22
**Verdict:** ACCEPT WITH REVISIONS

## What works

- §1.1 ratio table correctly distinguishes LR / MLR / Pure LR / LAE / Expense / Combined / Operating / Burning Cost / Pure Premium. This is the single biggest improvement over v1.
- §1.2 LR-vs-LAE tradeoff is stated correctly. Net-of-fees discipline is named.
- §1.3 trend decomposition formula is right and ranges are realistic for current cycle.
- CY vs AY callout is correct and overdue.

## Findings (ranked by importance)

1. **MLR rebate formula is incomplete.** The paper says "85% large group / 80% small group, individual". Correct, but missing the *credibility adjustment* (Federal MLR formula adds a credibility adjustment for small enrollment blocks; rebates do not trigger below a base enrollment of 1,000 life-years). Without that nuance, small-block readers will reach incorrect rebate-exposure conclusions.
2. **ALAE / ULAE split should be named.** §1.2 says "LAE" but does not distinguish ALAE (claim-tied: bill review, UR, case management) from ULAE (claims department overhead). This matters because cost-containment vendor fees are almost entirely ALAE and are the part that moves with volume.
3. **"Pure Premium" definition is too terse.** WC readers will read this and assume payroll-based; group-health readers will assume PMPM. Spell out both denominators inline.
4. **Trend ranges should be cited or hedged.** "+3 to +4% unit cost" reads as confident; the paper's own credibility-discipline argument requires either a citation (KFF, Mercer, Milliman trend survey) or a hedge ("typical industry-survey ranges").
5. **Self-insured "premium-equivalent" concept is missing.** The paper assumes a "premium" denominator throughout. Self-funded employers, a stated audience, do not have premium — they have budget-rate / premium-equivalent. The ratios behave differently and the rebate framework does not apply. Add a paragraph in §1.1.

## Required edits before publication

- Add "ALAE vs ULAE" sentence to §1.2.
- Add credibility-adjustment caveat to MLR row in §1.1 table.
- Add self-insured premium-equivalent note in §1.1.
- Hedge trend ranges in §1.3.

## Out of scope for this paper

Detailed reserve-development triangles and AY-restatement worked examples belong in a service-specific briefing, not a positioning white paper.
