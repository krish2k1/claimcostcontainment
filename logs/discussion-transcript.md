# Panel Discussion — v2-draft

**Date:** 2026-05-22
**Artifact reviewed:** `whitepaper/claim-cost-containment-v2-draft.md`
**Moderator:** session orchestrator
**Panel:** all 12 specialist agents
**Verdicts:** 12 / 12 ACCEPT WITH REVISIONS (no full rejections, no APPROVE-AS-IS)

This transcript captures the cross-expert exchanges. Reviews are individually filed in `logs/reviews/`; the value of the panel format is in the places where two experts contradict, reinforce, or extend each other.

---

## Round 1 — "What is the single biggest gap?"

**loss-ratio-analyst:** The paper introduces the loss-ratio family for the first time, which is the right move. But the MLR row is incomplete without the credibility adjustment, and the audience (self-funded employers) has no "premium" at all — just budget-rate. If we don't say that, half the readers will misapply the ratios.

**actuarial-reserving-expert:** Agreed on credibility — but I'd elevate it higher. The paper claims savings are reported against "ultimate", which is correct, but doesn't acknowledge how much actuarial *judgment* sits behind a single ultimate number. Credibility, on-leveling, trend selection — every one is a judgment call. The CFO needs to know that.

**stop-loss-reinsurance-analyst:** The biggest gap from where I sit is the interaction. The paper treats stop-loss as an independent service line. It isn't. RBP and OON negotiation interact directly with how stop-loss reimburses you, because some carriers reimburse on *paid*, not on a notional billed-minus-discount. A plan that aggressively reprices its catastrophic claim can find its stop-loss reimbursement basis quietly cut.

**network-repricing-strategist:** That's important. It's also a reason to elevate exclusivity / lineage even harder — if you can't tell the stop-loss carrier exactly which lever applied to which dollar, you cannot defend the reimbursement basis.

---

## Round 2 — "Where do two service lines collide?"

**utilization-management-reviewer:** Care management and UM. The paper has us as separate service lines — fine — but does not name that UM denial is the wrong tool when clinical management is the right tool. A plan that denies a $40K spine surgery on medical-necessity grounds and offers nothing in its place gets the surgery anyway, six months later, with worse outcomes and the same dollars. The right answer is steerage to a COE under a waived-deductible benefit, not a denial.

**care-management-steerage-strategist:** Agreed. And the same logic runs the other way — care management without UM rigor becomes vendor theater. Every clinical-management touch needs to connect to a measurable action and a matched-cohort outcome. The paper doesn't say that in §2.11.

**utilization-management-reviewer:** Gold-carding too — that's a UM-care-management coordination move. Providers with high approval rates and good clinical outcomes get PA waived. Reduces abrasion at zero savings cost. Some states now mandate it. The paper omits it.

**payment-integrity-auditor:** And retrospective UM overlaps with PI. If we do both retrospectively on the same case, we generate conflicting determinations and provider lawsuits. Cross-link, please.

---

## Round 3 — "Whose recovery is whose?"

**subrogation-recovery-specialist:** The paper underplays MSP. For a self-funded ERISA employer, treble damages under 42 USC §1395y(b)(3)(A) is the single most expensive recovery-program failure. I want it elevated.

**workers-comp-specialist:** And WC third-party is its own discipline. The paper treats it as a sub-bullet under subro. WC third-party has carrier intervention rights, statutory lien rules, made-whole interaction with statutory benefits — it is not group-health subro with a different ICD code.

**stop-loss-reinsurance-analyst:** Stop-loss recovery sits in this bucket too, and it's the highest-dollar item that doesn't trigger off ICD-10 codes — it triggers off the 50%-of-attachment threshold. If that watchlist isn't running, the recovery never happens.

**payment-integrity-auditor:** And overpayment recovery is mine, not subro's — but the paper merges them. Let's keep them separate but cross-linked.

---

## Round 4 — "Who owns regulatory?"

**regulatory-compliance-watchdog:** Almost every other reviewer flagged something that lands in my section. NQTL parity (UM), AKS/Stark (network and FWA), pre-pay-suspension due process (FWA), state PBM (pharmacy), state MPN (WC), MSP reporting (subro). The cleanest fix is a single matrix in §2.12 that maps each service line to its dominant compliance gates.

**fwa-siu-investigator:** Strong agree. And add FCA / qui tam exposure for MA / Medicaid MCO readers — that's where dollar exposure is largest.

**pharmacy-pbm-analyst:** State PBM regulation has changed in 30+ states in 24 months. The paper says "state PBM" without a "rapidly evolving" caveat. That hedge matters.

**network-repricing-strategist:** And the AKS/Stark caveat on direct contracts and COE — the paper recommends those as the strategic lever (§2.4) without naming the safe-harbor design constraint. That's a defensible-by-counsel call, but the paper should at least flag it.

---

## Round 5 — "What did we leave out?"

**workers-comp-specialist:** Indemnity. The paper is medical-cost-flavored throughout. Indemnity (TTD/TPD/PPD/PTD) frequently exceeds medical on a lost-time WC claim. If we claim to cover all services, indemnity has to be in §2.10 as a named layer, not implied.

**care-management-steerage-strategist:** First-touch in WC. The single highest-leverage WC intervention is the first 4–24 hours after injury report. Missing from the paper.

**loss-ratio-analyst:** Trend-range citations or hedges. The paper quotes "+3 to +4% unit cost" with confidence — that needs a Mercer / KFF / Milliman citation or a "typical industry-survey ranges" hedge. Our own credibility-discipline argument demands it.

**actuarial-reserving-expert:** And one line elevating "paid acceleration ≠ ultimate savings" into the Executive Summary. Many programs are sold on paid-LR improvement that does not survive to ultimate.

---

## Round 6 — "What deserves to stay out?"

**General consensus:**
- State-by-state matrices for OON statutes, WC fee schedules, UR timing, PBM rules, MSA thresholds → service-line deliverables, not white-paper material.
- Worked actuarial examples (triangles, GLM detail) → technical appendix.
- Implementation sequencing → engagement-specific, deliberately excluded.
- Vendor RFP scoring methodology → service-line briefing.
- Lien-negotiation playbooks → service-line briefing.

The paper is positioning material. The reviewers agree it should *name* the gates and the disciplines without becoming a methodology handbook.

---

## Closing — single sharpest line from the panel

> *"A program that reports gross savings without ALAE/ULAE attribution and without an ultimate-incurred view is not measuring savings — it is invoicing."* — loss-ratio-analyst, reinforced by actuarial-reserving-expert, payment-integrity-auditor, and stop-loss-reinsurance-analyst.

This becomes the closing sentence of the revised Executive Summary in v3-final.
