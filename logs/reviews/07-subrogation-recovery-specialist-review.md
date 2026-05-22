# Review — subrogation-recovery-specialist

**Reviewer:** subrogation-recovery-specialist
**Artifact:** `whitepaper/claim-cost-containment-v2-draft.md`
**Date:** 2026-05-22
**Verdict:** ACCEPT WITH REVISIONS

## What works

- §2.7 names trigger detection correctly as the yield-gating factor.
- ICD-10 mechanism-of-injury codes named explicitly.
- ERISA plan-document strength named as the determinative factor for made-whole / common-fund posture.

## Findings

1. **MSP/Section 111 treble damages exposure understated.** The paper names MSP but does not name **42 USC §1395y(b)(3)(A) treble damages**. For a self-funded employer audience, this is the single most expensive recovery-program failure: a missed primary-payer obligation can be doubled by CMS demand. Worth elevating.
2. **Trigger detection vs. vendor responsibility tension not named.** Subrogation vendors run PoS. They have a structural incentive to under-invest in trigger detection (high-effort, low per-case yield) and over-invest in chasing known high-dollar files. Most missed recoveries are missed at the *first* claim, not at the vendor. The paper should name this — it is the dominant program failure mode in subro.
3. **Statute of limitations as a hard wall.** The agent spec calls SoL a "hard wall." The paper says "statute-of-limitations discipline" — true but soft. A barred claim is $0 regardless of merit; an inventory inside 90 days of SoL is P0 regardless of dollar size.
4. **WC third-party recovery is a distinct service.** WC third-party is more complex than group-health subro (carrier intervention rights, lien resolution, made-whole interaction with statutory benefits). The paper treats it as a sub-bullet of subro; it deserves at least a sentence on its own.

## Required edits

- Name treble damages risk explicitly in §2.7.
- Name vendor-PoS / trigger-detection tension.
- Strengthen SoL language ("barred claim = $0").
- One distinct sentence on WC third-party as its own discipline.

## Out of scope

Lien-negotiation playbook; MSA / WCMSA worked examples.
