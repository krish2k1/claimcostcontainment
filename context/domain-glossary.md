# Domain Glossary — Claim Cost Containment

Seed glossary for the `claims-cost-containment-expert` subagent. Extend with care — every term added here is a term the agent can rely on without re-defining in its outputs.

## Lines of Business

- **Group Health** — Employer- or association-sponsored medical/Rx benefit, usually self-funded under ERISA or fully-insured under state law.
- **Workers' Compensation (WC)** — Statutory no-fault employer liability for occupational injury/illness; governed by state-specific fee schedules, UR rules, and causation standards.
- **Auto Medical (PIP / MedPay)** — First-party auto medical coverage; state no-fault statutes drive repricing rules.
- **Property & Casualty (P&C)** — First- and third-party bodily injury claims under GL, premises, product liability policies.

## Pricing & Repricing

- **Billed Charges** — Provider's chargemaster price; not a defensible savings baseline.
- **U&C (Usual & Customary)** — Percentile of a geographic charge distribution (e.g. FAIR Health 80th); historically used for OON, eroded by NSA.
- **Fee Schedule** — Statutory or contracted unit price (Medicare, state WC, Medicaid, network).
- **Reference-Based Pricing (RBP)** — Repricing against a fixed Medicare multiple (typically 140–180%) rather than a network discount.
- **QPA (Qualifying Payment Amount)** — NSA-defined median contracted rate; baseline for OON emergency/ancillary in group health.
- **DRG (Diagnosis-Related Group)** — Inpatient bundled-payment unit (MS-DRG for Medicare; APR-DRG common in commercial/Medicaid).
- **APC (Ambulatory Payment Classification)** — Outpatient prospective payment unit under Medicare OPPS.

## Cost-Containment Levers

- **Bill Review** — Line-by-line audit of facility/professional bills for coding, bundling, and fee-schedule compliance.
- **Utilization Review (UR)** — Medical necessity determination; prospective (prior auth), concurrent (LOS), or retrospective.
- **Case Management (CM)** — Nurse-led coordination for catastrophic / complex / high-trajectory claims.
- **OON Negotiation** — Pre- or post-service negotiation of an OON bill, typically against a benchmark.
- **Centers of Excellence (COE)** — Direct contracts with high-quality, bundled-price providers (e.g. cardiac, orthopedic, transplant).
- **PBM (Pharmacy Benefit Manager)** — Vendor managing Rx network, formulary, rebates; major leakage surface (spread pricing, rebate aggregation).

## Payment Integrity & Recovery

- **Leakage** — Paid dollars that should not have been paid (or should have been paid lower) given plan terms, fee schedule, eligibility, or COB.
- **Pre-Pay Edit** — Adjudication-time rule preventing the leak before payment leaves the plan.
- **Post-Pay Recovery** — Retrospective audit and clawback; lower yield, higher provider abrasion.
- **COB (Coordination of Benefits)** — Determining primary vs. secondary payer order.
- **Subrogation** — Recovery from a liable third party (and their insurer) for paid claims caused by that party.
- **TPL (Third-Party Liability)** — Umbrella term covering subrogation and other third-party recoveries.
- **MSP (Medicare Secondary Payer) / Section 111** — CMS reporting and conditional-payment reconciliation regime.
- **SIU (Special Investigations Unit)** — In-house or vendor function pursuing fraud cases.
- **FWA (Fraud, Waste & Abuse)** — Industry triad covering intentional fraud, unintentional waste, and abusive (but not criminal) billing.

## Regulatory

- **ERISA** — Federal statute governing employer-sponsored benefit plans; preempts most state insurance law for self-funded plans.
- **NSA (No Surprises Act)** — Federal 2022 law on OON emergency, ancillary, air ambulance; introduces IDR process.
- **IDR (Independent Dispute Resolution)** — NSA baseball-style arbitration for OON disputes.
- **ACA (Affordable Care Act)** — EHB, MLR, and market reform rules; affects what can be excluded or limited.
- **HIPAA** — PHI privacy/security; governs data exchange in every workflow described here.
- **NAIC Model Unfair Claims Practices Act** — State-adopted standards for prompt, fair claim handling.
- **MMI (Maximum Medical Improvement)** — WC milestone; post-MMI medical entitlement is narrower and varies by state.
- **MSA (Medicare Set-Aside)** — WC/liability settlement vehicle protecting Medicare's secondary-payer interest.

## Savings Measurement

- **Baseline** — The "would-have-paid" figure against which savings are computed; must be written, defensible, and applied consistently.
- **PoS (Percent of Savings)** — Vendor fee model that pays a share of computed savings; creates structural incentive to inflate baselines.
- **PEPM / PMPM** — Per-employee-per-month / per-member-per-month; standard group-health management-reporting units.
- **Net Savings** — Gross savings minus vendor fees; the only figure that belongs in board reporting.
- **Avoided Cost** — Savings claim from a service that did not occur (e.g. denied auth); requires a matched comparison group to be defensible.
