# Review — payment-integrity-auditor

**Reviewer:** payment-integrity-auditor
**Artifact:** `whitepaper/claim-cost-containment-v2-draft.md`
**Date:** 2026-05-22
**Verdict:** ACCEPT WITH MINOR REVISIONS

## What works

- §2.6 names the leakage taxonomy comprehensively.
- "Shift left" is correctly named; the 100% vs 25–60% recovery comparison is correct and persuasive.
- DRG validation, modifier abuse, J-code adjudication all called out.

## Findings

1. **PoS-vendor structural betrayal not named explicitly.** A plan that leaves a known recurring leak in post-pay because the recovery vendor is paid PoS is structurally betraying the plan. Say it. The paper hints at this in §4 but should connect it specifically to §2.6.
2. **Pre-pay edit governance is missing.** Pre-pay edits must be governed (false-positive rate, provider-appeal volume, escape-hatch for legitimate exceptions). Pre-pay shift without governance generates provider rebellion. Worth one sentence.
3. **Physician-reviewer requirement for DRG validation.** The agent spec is explicit: nurse-only DRG validation is a defensibility weakness. The paper doesn't say so. Worth a line — many vendors run nurse-only review and lose appeals.
4. **State prompt-pay interaction.** Late post-pay clawbacks can violate state prompt-pay statutes (some states bar recoupment after fixed windows). Worth a parenthetical.

## Required edits

- Add explicit PoS-vendor betrayal line in §2.6 (or strengthen §4 to make the link).
- Pre-pay edit governance sentence.
- Physician-reviewer requirement for DRG validation.
- State prompt-pay parenthetical.

## Out of scope

Pre-pay edit catalog by code family — service-line deliverable.
