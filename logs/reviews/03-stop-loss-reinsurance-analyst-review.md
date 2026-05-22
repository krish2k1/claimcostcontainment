# Review — stop-loss-reinsurance-analyst

**Reviewer:** stop-loss-reinsurance-analyst
**Artifact:** `whitepaper/claim-cost-containment-v2-draft.md`
**Date:** 2026-05-22
**Verdict:** ACCEPT WITH REVISIONS

## What works

- §2.3 correctly names the 50%-of-attachment notification as the most expensive failure mode in the entire program. This is true and almost never said publicly.
- Run-in / run-out alignment named.
- Lasers named.

## Findings

1. **Stop-loss "savings recognition" mismatch is missing and material.** Several stop-loss carriers will not recognize RBP or OON-negotiated savings as a *paid amount* for reimbursement purposes — they reimburse the *paid* dollar, not the billed-minus-discount notional. A plan that proudly publishes a 60% PPO discount and then submits the discounted paid amount for stop-loss reimbursement can find itself reimbursed against a much smaller base than expected. The paper should warn that **cost-containment lever choice interacts with stop-loss reimbursement**, and that the savings-clause definition in the stop-loss policy must be read in coordination with §2.4 (network) and §2.6 (PI).
2. **Aggregate stop-loss (ASL) is absent.** The paper jumps from "specific" implicitly to "catastrophic". ASL has a role and a reasonable cost-containment user should understand why ASL rarely pays.
3. **Laser pre-negotiation window not mentioned.** The 60-day pre-renewal window is the single highest-leverage moment of the policy cycle; a positioning paper should at least allude to it as part of "structural failure modes".
4. **Disclosure exposure is missing.** Most denied stop-loss claims are *non-disclosure* denials, not coverage denials. The paper does not name this; given the audience (self-insured employers), it should.

## Required edits

- One paragraph in §2.3 on stop-loss savings recognition / lever interaction.
- One line distinguishing ISL vs ASL.
- One line on non-disclosure as the dominant denial driver.

## Out of scope

Captive structures, fronting arrangements — too niche for this paper.
