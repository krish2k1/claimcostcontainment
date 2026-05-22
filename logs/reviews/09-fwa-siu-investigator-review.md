# Review — fwa-siu-investigator

**Reviewer:** fwa-siu-investigator
**Artifact:** `whitepaper/claim-cost-containment-v2-draft.md`
**Date:** 2026-05-22
**Verdict:** ACCEPT WITH REVISIONS

## What works

- §2.9 cleanly distinguishes fraud / abuse / waste / error.
- "Intent or recklessness" is the right inference framing.
- NAIC anti-fraud + state DOI referral named.

## Findings

1. **Whistleblower / qui tam exposure not named.** For any Medicare Advantage or Medicaid MCO reader, this is the largest dollar-exposure in the entire FWA universe — False Claims Act allows treble damages plus per-claim penalties, and *failing to detect* fraud is itself an FCA exposure for some plans. The paper should at least name FCA / qui tam in this section.
2. **Defamation guardrails missing.** Investigative language in customer-facing or discoverable artifacts must be conditional ("consistent with", "warrants further inquiry"), never conclusory. Vendors and internal teams routinely violate this and produce litigation. Worth a line in §4 (failure modes).
3. **Pre-pay suspension due-process gap.** The paper does not name that pre-pay suspension on a flagged provider requires due-process scaffolding under most state UR / claims statutes; absent it, the carrier faces bad-faith and prompt-pay exposure. Worth cross-linking §2.9 ↔ §2.12.
4. **AKS / Stark exposure on COE / direct contracting.** The paper recommends direct contracting and COE in §2.4 but does not flag AKS / Stark implications. Direct contracts must be structured around AKS safe harbors; this is a genuine compliance gate.

## Required edits

- Name FCA / qui tam in §2.9.
- Add "defamation guardrails" item to §4 (failure modes).
- Cross-link §2.9 ↔ §2.12 on pre-pay suspension due process.
- Add AKS / Stark caveat in §2.4 where direct contracts and COE are recommended.

## Out of scope

Specific scheme-detection model architectures; outlier scoring methodology — service-line deliverable.
