# Claim Cost Containment

### A Practitioner's Framework for Payers, TPAs, and Self-Insured Employers

*Mahathi Infotech — White Paper · May 2026*

---

## Executive Summary

Medical and indemnity claim spend in the United States continues to outpace wage and premium growth. Self-insured employers, third-party administrators (TPAs), and health plans absorb the difference as either higher trend, eroded margin, or stop-loss premium creep. Yet inside almost every block of claims sits 8–25% of *recoverable* spend — leakage that is structural, repeatable, and addressable without renegotiating a single provider contract.

This paper presents a five-pillar framework — **Network & Repricing, Utilization Management, Payment Integrity, Recovery, and Analytics & AI** — and the operating discipline required to convert each pillar into auditable, CFO-defensible savings. It closes with an implementation roadmap and the measurement contract every program must answer before the first dollar of "savings" is reported.

---

## 1. Why Cost Containment Is a System Problem, Not a Vendor Problem

Most cost-containment programs are bought, not built. A plan layers a PPO network, a bill-review vendor, a utilization-review vendor, a subrogation vendor, and a pharmacy benefit manager — each paid a *percentage of savings* against its own baseline. The aggregate result is a number that looks impressive in a quarterly report and bears no relationship to what the plan actually paid.

The problem is structural:

- **Misaligned incentives.** Percent-of-savings (PoS) fees reward vendors for inflated baselines, not for the lowest defensible paid amount.
- **Overlapping baselines.** The same dollar can be "saved" by the network, the bill-review vendor, and the negotiation vendor in sequence — triple-counted on the way to the CFO.
- **Jurisdictional drift.** Group-health logic gets applied to workers' compensation; commercial logic gets applied to a self-funded ERISA plan; a No Surprises Act (NSA) qualifying-payment-amount workflow gets bolted onto a state out-of-network statute that preempts it.
- **Late detection.** Leakage is caught — if at all — in retrospective audits months after payment, when recovery rates collapse and provider relationships have hardened.

Cost containment, done correctly, is therefore not a vendor stack. It is an **operating system** that aligns levers, baselines, and incentives across the entire claim lifecycle — pre-service, point-of-adjudication, and post-payment.

---

## 2. The Five-Pillar Framework

### Pillar 1 — Network & Repricing

The first dollar of savings comes from paying the right price for in-scope services. The mature program operates a *tiered repricing waterfall*:

1. **Direct contracts** (employer-direct, ACO, Centers of Excellence) — applied first because they carry the strongest unit economics and quality terms.
2. **Primary PPO** — applied where direct contracts do not reach.
3. **Wrap / secondary networks** — applied to leakage outside the primary footprint.
4. **Reference-Based Pricing (RBP)** — typically 140–180% of Medicare for facility claims where no network rate applies, with member-defense and balance-bill protection wrapped around it.
5. **Out-of-network negotiation** — itemized, evidence-based, and capped by either a regulatory benchmark (NSA QPA, state OON statute) or a fee-schedule reference.

Two disciplines separate good waterfalls from leaky ones: **exclusivity** (a bill is repriced by exactly one method, with a documented reason for that method) and **lineage** (every paid claim carries the path it took through the waterfall, so savings can be reconstructed and audited).

### Pillar 2 — Utilization Management (UM)

Repricing reduces the *unit* cost; utilization management reduces the *quantity* of medically unnecessary or low-value services. A modern UM program operates on three horizons:

- **Prospective** — prior authorization on a tightly scoped, evidence-supported list (MCG / InterQual aligned). Over-broad PA lists destroy provider relationships without saving money; under-scoped lists let high-cost low-value procedures through. The right list is short and high-yield.
- **Concurrent** — inpatient length-of-stay review and nurse case management for catastrophic, complex, and high-trajectory claims (NICU, oncology, transplant, polytrauma WC).
- **Retrospective** — medical necessity review on selected post-payment populations, integrated with payment integrity to avoid duplicate work.

The unit of measurement is **avoided cost per case**, validated against a matched comparison group — not the gross dollars on a denial letter.

### Pillar 3 — Payment Integrity

Payment integrity is where the largest near-term recoverable dollars live. The leakage taxonomy is well-understood but under-instrumented:

- Duplicate payments (same bill, different claim number)
- DRG validation (clinical documentation does not support the billed DRG)
- Itemized bill review — unbundling, upcoding, modifier misuse, implant pass-through, never-events
- Eligibility errors (ineligible member, terminated coverage, dependent age-out)
- Coordination of Benefits (COB) — wrong primary payer
- Fee schedule misapplication (wrong year, wrong jurisdiction, wrong locality)
- Contract-term misapplication (carve-outs, lesser-of clauses, stop-loss outliers)

The mature program shifts payment integrity **left** — from a post-payment recovery vendor running 12–24 months in arrears to a pre-payment edit set integrated into the adjudication platform. Pre-pay edits convert 30-cent recovery dollars into 100-cent avoidance dollars and eliminate the provider-abrasion cost of clawbacks.

### Pillar 4 — Recovery

When payment cannot be avoided, it must be recovered. The recovery portfolio includes:

- **Subrogation & third-party liability (TPL)** — auto, premises, product liability, and workers' compensation cross-over
- **Medicare Secondary Payer (MSP) / Section 111** reporting and conditional payment recovery
- **Overpayment recovery** — provider, member, and vendor
- **Stop-loss recovery** — accurate, timely filing against specific and aggregate attachments; lasered-claim management
- **Pharmacy rebates and 340B** reconciliation where applicable

Recovery yield is gated by **trigger detection** (most missed recoveries are missed at the first claim, not at the recovery vendor) and by **statute-of-limitations discipline**, which varies by state and by recovery type.

### Pillar 5 — Analytics & AI

Analytics is not a sixth lever; it is the *connective tissue* across the four above. The high-value applications are:

- **Leakage attribution models** — which dollars are leaking, where, and why, ranked by recoverable potential rather than gross billed.
- **Trajectory models** for catastrophic and creeping claims, surfacing nurse case management candidates 60–90 days earlier than rules-based triggers.
- **Provider profiling** — outlier detection on billing patterns, length of stay, readmission, and complication rates, feeding both network strategy and SIU referral.
- **Fraud, Waste & Abuse (FWA) detection** — network-graph and sequence-based models targeting collusive billing, phantom services, and identity misuse.
- **Member navigation** — steering models that route members toward higher-quality, lower-cost providers *before* the claim is generated, which is the highest-leverage intervention in the entire system.

The discipline that separates production-grade analytics from dashboard theater is **closed-loop measurement**: every model output is linked to a downstream action (auth denial, case-management referral, pre-pay edit, SIU case), and every action is linked back to a measurable outcome (avoided dollar, recovered dollar, member outcome).

---

## 3. The Measurement Contract

No cost-containment program is credible without a written measurement contract that answers, in advance:

| Question | Default Answer |
|---|---|
| What is the baseline? | Billed charges are *not* a defensible baseline. Use the lower of (a) the plan's allowed amount before the lever was applied, or (b) a fixed external benchmark (Medicare × factor, fee schedule year-X). |
| Is savings claimed once or stacked? | Once. Each dollar is attributed to exactly one lever, in waterfall order. |
| How are vendor fees treated? | Reported **net of fees**. Gross savings figures are for vendor marketing, not finance. |
| Who audits the number? | Internal audit or an independent third party, on a sampled-and-extrapolated basis, at least annually. |
| What is the unit of management reporting? | PMPM (group health) or per-claim and per-$100-of-payroll (WC), trended against a matched prior period. |

A program that cannot answer these five questions is not measuring savings — it is reporting vendor invoices.

---

## 4. Implementation Roadmap (12 Months)

**Months 1–3 — Diagnose.** Pull 24 months of paid claims. Run leakage attribution across the five pillars. Rank by recoverable dollars per implementation-month. Map vendor contracts and identify PoS-baseline conflicts.

**Months 3–6 — Shift left.** Move the top three retrospective recoveries into pre-payment edits. Tighten the prior-authorization list to the high-yield short list. Stand up the repricing waterfall with exclusivity and lineage.

**Months 6–9 — Instrument.** Deploy trajectory and leakage-attribution models. Wire model outputs to specific downstream actions. Stand up the measurement contract and the audit trail.

**Months 9–12 — Compound.** Renegotiate vendor contracts on a net-of-fees, audited basis. Retire overlapping vendors. Reinvest a defined share of savings into member navigation and Centers of Excellence steerage — the only lever that bends trend rather than trimming it.

---

## 5. Conclusion

Claim cost containment is not, ultimately, a question of how aggressively a plan denies, reprices, or recovers. It is a question of whether the plan has built an operating system in which the right lever is applied to the right claim at the right time, against a baseline that survives audit, with incentives that point every participant — internal team, vendor, and provider — toward the lowest defensible total cost of care.

The plans that win the next decade of trend will not be the ones with the most vendors. They will be the ones with the clearest measurement contract, the shortest gap between detection and action, and the discipline to shift every recoverable dollar from post-payment recovery to pre-service avoidance.

---

*Prepared by Mahathi Infotech. For engagement enquiries: Krishnan.Narayanan@mahathiinfotech.com.*
