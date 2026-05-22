# Review — actuarial-reserving-expert

**Reviewer:** actuarial-reserving-expert
**Artifact:** `whitepaper/claim-cost-containment-v2-draft.md`
**Date:** 2026-05-22
**Verdict:** ACCEPT WITH REVISIONS

## What works

- §1.4 finally states the paid-vs-incurred-vs-ultimate distinction explicitly. This is the actuarially correct frame.
- "Every program launch is a process change" is the right warning shot for chain-ladder users; it correctly implies that the launch cohort needs BF or expected-loss reweighting.
- Coordination with stop-loss attachment sizing is named.

## Findings

1. **"On-leveling" is named but not explained.** Non-actuary readers will glide past it. Add a sentence: on-leveling restates historical losses to current benefit / rate level so that triangles compare apples to apples.
2. **Credibility weighting is absent.** Mid-size and small blocks lack full credibility and must blend observed experience with a complement (manual / industry). The paper claims savings against "ultimate" without naming this constraint, which understates how much actuarial judgment sits behind a single number.
3. **GLM and modern trend-modeling are absent.** Chain-ladder, BF, and Cape Cod are named in the agent spec but the paper only implies "triangulation". A line on GLM-based trend (now common in WC and large group health) modernizes the framing.
4. **IBNER vs pure IBNR collapsed.** The paper treats IBNR as one bucket. IBNER (development on known claims) often dominates pure IBNR in mature blocks and is where cost-containment-induced reserve development *appears*. Worth a parenthetical.
5. **"Acceleration of payment" warning is right but understated.** Worth elevating into the executive summary — many programs are sold on paid-loss-ratio improvement that does not survive to ultimate.

## Required edits

- One-sentence "on-leveling" definition in §1.4.
- Sentence on credibility weighting + complement for small/mid blocks.
- Elevate "paid acceleration ≠ ultimate savings" warning into Executive Summary.

## Out of scope

Worked GLM examples; full reserve triangle methodology — these belong in a technical appendix, not a positioning paper.
