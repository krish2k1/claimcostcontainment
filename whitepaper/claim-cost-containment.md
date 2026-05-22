# Claim Cost Containment

### A Financial and Operating Framework for Payers, TPAs, Carriers, and Self-Insured Employers

*Mahathi Infotech — White Paper · May 2026 · v3 (panel-reviewed final)*

---

## Executive Summary

In every block of U.S. claim spend — group health, workers' compensation, auto medical, and property & casualty — between 8% and 25% of paid dollars are structurally recoverable. They do not require a single renegotiated provider contract to address; they require an *operating system* that aligns pricing, utilization, integrity, recovery, clinical management, pharmacy, and regulatory posture against a single set of financial metrics.

This paper presents that operating system. It is organized around the financial reality of the buyer — the loss-ratio family that drives every CFO conversation — and around the twelve service lines that, taken together, constitute a credible cost-containment capability.

A warning that sets the tone for everything that follows: **accelerating or deferring paid losses is not the same as reducing ultimate incurred losses.** Many cost-containment programs are sold on paid-loss-ratio improvements that vanish when the same losses are restated to ultimate. The only number that represents real economic savings is the difference at *ultimate* — and the only program that survives audit is the one designed against that number.

This paper deliberately does not prescribe an implementation sequence; sequencing is engagement-specific. What is universal is the diagnostic discipline, the service catalog, the measurement contract, and the regulatory floor described below.

---

## 1. The Financial Lens: Loss Ratios and What Moves Them

Cost containment is ultimately an exercise in moving ratios. The vocabulary matters because the same word means different things in different contexts, and misquoting them is the single most common analytical failure in this space.

### 1.1 The Loss-Ratio Family

| Ratio | Formula | What It Measures |
|---|---|---|
| **Loss Ratio (LR)** | Incurred Losses ÷ Earned Premium | Headline underwriting performance |
| **Medical Loss Ratio (MLR), ACA** | (Incurred Claims + Quality Activities) ÷ (Premium − Taxes/Fees), 3-yr credibility-adjusted | Triggers rebates below 85% (large group) / 80% (small group, individual). The federal formula adds a credibility adjustment; small blocks (under ~1,000 life-years) fall below the rebate-triggering threshold entirely. |
| **Pure Loss Ratio** | Incurred Losses ÷ Earned Premium, *excluding* LAE | Strips out claim-handling cost |
| **LAE Ratio** | Loss Adjustment Expenses ÷ Earned Premium | Cost of *managing* claims — split into **ALAE** (claim-tied: bill review, UR, case management, defense) and **ULAE** (claims-department overhead). Cost-containment vendor fees are almost entirely ALAE. |
| **Expense Ratio** | Underwriting Expenses ÷ Premium | Commission, admin, premium tax |
| **Combined Ratio** | LR + LAE + Expense | < 100% = underwriting profit |
| **Operating Ratio** | Combined − Net Investment Income Ratio | True economic profitability |
| **Burning Cost** | Ceded Losses ÷ Subject Premium | Used to price excess layers |
| **Pure Premium** | Losses ÷ Exposure Unit | PMPM (group health, per member-month); per-$100-of-payroll (workers' comp). The trend's natural unit. |

**Self-insured employers do not have premium.** They have a *budget rate* or *premium-equivalent*. The ratios above can be computed against budget-equivalent for management reporting, but the ACA MLR rebate framework does not apply, and "loss ratio against budget" is a budget-vs-actual story, not a regulatory one. Mixing these up is a recurring source of board-level confusion.

Two distinctions that are routinely blurred:

- **Calendar-Year (CY) vs Accident-Year (AY).** CY mixes accident periods and reserve development; AY restates losses to the year of injury / onset. A cost-containment program is judged on AY ratios; CY ratios are accounting artefacts.
- **Paid vs Incurred vs Ultimate.** Programs that accelerate or defer payment can flatter the paid view without touching the *ultimate* incurred — which is the only view that represents real economic savings.

### 1.2 Where Cost-Containment Activities Show Up

Cost-containment levers reduce **losses** (the numerator) but typically raise **LAE** (operating cost of running the lever). The CFO view is therefore not gross savings — it is the *net* movement across LR and LAE together.

A program that reduces losses by $10M while raising LAE by $4M is a $6M win. A program that reports $10M of gross savings while quietly running $7M of vendor fees in LAE is a $3M win. Gross-savings dashboards mask this; the loss-ratio family, properly attributed between ALAE and ULAE, does not.

### 1.3 Trend Decomposition

"Trend is up 8%" is not actionable. The only useful trend statement decomposes into components:

> Total Trend ≈ Unit-Cost Trend × Utilization Trend × Mix Shift × Buy-Down/Buy-Up × Provider-Contract Step-Up

Industry-survey ranges in the current cycle (Mercer, KFF, Milliman MGTR) typically resolve to roughly: unit cost in the +3 to +4% range, utilization +1 to +2%, specialty Rx mix +2 to +4%, contract step-up around +1%. Workers' comp severity trend has frequently outpaced declining frequency, producing rising per-claim severity even as injury counts fall. Specific numbers should always be cited to a current survey rather than asserted.

Decomposition determines which lever to pull. A unit-cost-driven block needs network and repricing work; a utilization-driven block needs UM and steerage; a mix-driven block needs pharmacy and site-of-care strategy.

### 1.4 Reserving and the Savings Baseline

Every savings claim ultimately rests on a reserve view. The mature program:

- Triangulates *ultimate* incurred losses using chain-ladder (paid and incurred), Bornhuetter-Ferguson, or Cape Cod methods, with **on-leveling** (restating historical losses to current benefit and rate level so that triangles compare apples to apples) and **credibility weighting** against a complement (manual or industry baseline) for mid- and small-size blocks.
- Distinguishes **pure IBNR** (events not yet reported) from **IBNER** (development on known claims); IBNER often dominates in mature blocks and is where cost-containment-induced reserve change actually shows up.
- Increasingly applies **GLM-based trend** modeling, now common in WC and large-group health, alongside classical triangulation.
- Treats every program launch as a **process change** that breaks the prior development pattern, requiring a documented method adjustment in the launch cohort.
- Reports savings against *ultimate*, not paid — because that is the only number a credentialed actuary can sign.
- Coordinates with stop-loss attachment sizing so that catastrophic-claim handling and recovery are scoped consistently.

---

## 2. The Service Catalog

A credible cost-containment capability is twelve service lines, not five "pillars" and a vendor stack. Each is summarized below with its highest-leverage moves and the coordination points where it must connect to others.

### 2.1 Loss-Ratio & Financial Performance

The financial intelligence layer. Decomposes loss ratios, LAE, combined ratio, trend, and rate adequacy. Translates every other service line's activity into AY-restated, ALAE/ULAE-attributed, PMPM/PEPM, CFO-facing language. Without this layer, savings are anecdotes; with it, they are reconcilable line items.

### 2.2 Actuarial & Reserving

The reserve and trend layer. Produces the ultimate-incurred view (chain-ladder, BF, Cape Cod, GLM), selects trend, manages credibility-weighted blends, and quantifies the reserve sensitivity of any proposed intervention. Sizes specific and aggregate stop-loss attachments. Without this layer, "savings" is computed against an unstable baseline.

### 2.3 Stop-Loss & Reinsurance

The catastrophic-loss layer. Manages **specific (ISL)** and **aggregate (ASL)** attachment design — ASL is the rarely-paid "sleep insurance" cap while ISL carries the meaningful catastrophic protection. Manages lasers, run-in/run-out alignment, and timely recovery filing.

The single most expensive failure mode in cost containment is the missed 50%-of-attachment notification — a denied stop-loss claim on a six- or seven-figure catastrophic case erases a year of small-claim discipline. The second most expensive is **non-disclosure** at renewal: most denied stop-loss claims are denied on disclosure grounds, not coverage grounds.

A subtler interaction: **stop-loss carriers may not recognize savings produced by RBP or aggressive OON negotiation as a "paid amount"** for reimbursement purposes. A plan that reprices a catastrophic claim down can find its stop-loss reimbursement basis quietly cut. Lever choice (§2.4, §2.6) must be coordinated with the savings-clause definition in the stop-loss policy.

### 2.4 Network & Repricing

The unit-price layer. Operates the repricing waterfall — direct contracts and Centers of Excellence first as the *strategic* lever, then primary PPO as the *coverage-of-leakage* lever, then wrap networks for residual leakage, then Reference-Based Pricing (RBP), then OON negotiation, then plan default — with two non-negotiable disciplines: **exclusivity** (one method per claim, never stacked) and **lineage** (every paid claim carries the path it took, for audit).

A "55% PPO discount" tells you nothing without the Medicare-multiple context: two networks both quoting 55% can produce paid amounts that differ by 80%+ on the same service. Direct contracts and COE typically outperform PPO by 15–35% on unit price *and* materially on quality (volume thresholds, accreditation, complication rate); they are the strategic lever, not a niche move. Direct contracting and COE design must, however, be structured around **Anti-Kickback Statute and Stark Law safe harbors** — a counsel-reviewed compliance gate that is not optional.

RBP requires **member balance-bill defense** (legal-defense fund, provider-education program, member advocacy) as a non-negotiable component, not an optional enhancement; absent it, RBP produces complaint volume, employer reputation damage, and litigation.

For OON disputes under the **No Surprises Act**, the IDR outcome is determined almost entirely by the quality of the QPA derivation file — methodology, sample, locality, year, status indicator. The dispute is usually won or lost on documentation, not on price. State OON statutes still apply to fully-insured plans where not preempted; ERISA preempts most for self-funded.

### 2.5 Utilization Management

The medical-necessity layer. Operates prospective (prior authorization), concurrent (length-of-stay, discharge planning), and retrospective review against MCG, InterQual, ODG (WC), or plan-specific medical policy.

The PA list is the central design choice — short, high-yield, evidence-graded, with annual sunset reviews retiring services with >95% approval rates. **Gold-carding** — waiving PA for providers with strong historical approval rates — reduces provider abrasion at zero savings cost and is now mandated in several states. Denial defensibility is procedural: criteria version, clinical rationale, peer-to-peer offer, member rights, jurisdictional deadlines.

UM denial is the *wrong tool* when clinical steerage is the *right tool*. Denying a $40K elective surgery produces the same surgery six months later, with worse outcomes; steering the same case to a COE under a waived-deductible benefit produces a 25–40% unit-price reduction and a measurably better outcome. UM and Care Management & Steerage (§2.11) must be designed together, not in parallel.

**Avoided-cost measurement must be matched-cohort validated** — raw "denied dollars × 100%" is vendor-marketing math (see §3). Provider abrasion is a measurable cost: turnover in PA-heavy specialties, network defection, member complaint volume. And the PA list itself is the most-scrutinized MHPAEA NQTL parity surface in commercial health (§2.12).

### 2.6 Payment Integrity

The "did we pay this correctly" layer. Covers duplicate detection, COB, eligibility, fee-schedule and contract-term application, DRG validation, itemized bill review (unbundling, modifier abuse, never-events), and specialty / J-code adjudication.

The mature program **shifts left** — converting every recurring post-pay recovery into a pre-pay edit, because pre-pay dollars recover at ~100% with minimal provider abrasion while post-pay recovers at 25–60% with high abrasion and potential state prompt-pay exposure on late clawbacks. A plan that leaves a known recurring leak in post-pay because the recovery vendor is paid on a percent-of-savings basis is structurally betraying the plan: the vendor's economic incentive points away from the pre-pay shift.

Two operational disciplines: pre-pay edits require **governance** (false-positive tracking, provider-appeal volume, documented escape hatch for legitimate exceptions) or they generate provider rebellion. DRG validation denials require **physician reviewer** documentation — nurse-only review is a defensibility weakness that loses appeals.

### 2.7 Subrogation, TPL & Recovery

The third-party-money layer. Pursues subrogation, third-party liability, Medicare Secondary Payer / Section 111, COB, overpayment, and stop-loss recovery. Yield is gated by **trigger detection** (ICD-10 mechanism-of-injury V/W/X/Y codes, place-of-service patterns, pharmacy-trauma scans) and by **statute-of-limitations discipline** — a barred claim is $0 regardless of merit; any inventory inside 90 days of SoL is P0.

For ERISA self-funded plans, recovery depends on plan-document language strength against the **made-whole** and **common-fund** doctrines (the *McCutchen* / *Sereboff* line of cases). Weak SPD language loses recovery cases that should win.

**MSP / Section 111** carries the highest single-event dollar exposure in this service line: under **42 USC §1395y(b)(3)(A), missed primary-payer obligations are subject to double damages** by CMS demand. For self-funded employers, this is the single most expensive recovery-program failure mode.

Workers' comp third-party recovery is a *distinct discipline*, not a sub-bullet of subro: carrier intervention rights, statutory lien rules, and made-whole interaction with statutory benefits all behave differently than group-health subro.

Vendor structure matters: subrogation vendors run percent-of-savings, which creates a structural incentive to under-invest in trigger detection (high-effort, low per-case yield) and over-invest in chasing known high-dollar files. Most missed recoveries are missed at the *first claim* — never flagged for follow-up — not at the vendor.

### 2.8 Pharmacy & PBM

The Rx layer — the fastest-growing component of medical trend in most blocks. **Specialty drugs now account for roughly 50% of total Rx spend on under 2% of utilization.** That single asymmetry reshapes the cost-containment center of gravity.

Diagnoses PBM contract structure (spread vs. pass-through; AWP / WAC / NADAC / MAC mechanics; rebate guarantee vs. pass-through; rebate-aggregator opacity via Zinc / Ascent / Emisar), specialty drug strategy, J-code / medical-benefit Rx audit, and 340B exposure. **Effective-rate guarantees are routinely gamed via MAC manipulation** — silent updates to the PBM's maximum-allowable-cost list reset the achieved discount without breaching the contract on paper. Audit-rights and effective-rate clauses are where the real economics live.

**Site-of-care steerage** for infusibles — physician office < hospital outpatient < hospital inpatient — is a 20–40% lever on specialty spend and lives at the boundary with Care Management & Steerage (§2.11). MHPAEA NQTL parity on Rx tiering and step-therapy (§2.12) is an emerging litigation surface; PBM design must pass parity audit *before* deployment.

### 2.9 Fraud, Waste & Abuse / SIU

The intent layer. Triages patterns into fraud, abuse, waste, and error using provider outlier profiling, network-graph signals, sequence patterns, and geospatial / velocity signals. Builds defensible cases — specific allegation, pattern evidence, intent or recklessness inference, chain of custody — and discharges NAIC-required state DOI referral obligations.

For Medicare Advantage and Medicaid MCO plans, **False Claims Act and qui tam exposure** is the largest dollar-risk in the entire FWA universe: failing to detect or report fraud is itself an FCA exposure, and whistleblower actions carry treble damages plus per-claim penalties.

**Pre-pay suspension** on a flagged provider requires due-process scaffolding under state UR / claims statutes; absent it, the carrier faces bad-faith and prompt-pay exposure (coordinate with §2.12).

### 2.10 Workers' Compensation Specialty

The WC-specific layer. WC is not group health with a different fee schedule. It is a no-fault statutory scheme with state-specific compensability, causation, MMI scope, indemnity layer, return-to-work obligations, MSA / Medicare exposure, and a settlement architecture (Compromise & Release, stipulated awards) that group health does not have.

**Indemnity** — TTD (Temporary Total), TPD (Temporary Partial), PPD (Permanent Partial), PTD (Permanent Total) — is a service line in its own right, not a footnote to medical. On lost-time claims, indemnity frequently exceeds medical in total severity. The medical-only-versus-lost-time triage is therefore the highest-leverage operational decision in WC: a medical-only claim that becomes lost-time is almost always a preventable medical-management failure.

**First-touch latency to medical care** — the 4-to-24-hour window after injury report, with telephonic nurse triage and designated-provider routing — drives downstream outcome more than any other intervention in the WC stack.

State **Medical Provider Networks (MPNs)** apply where NSA does not; certified networks in CA, TX, FL, PA carry their own OON penalty structures. **Presumption statutes** — firefighter cancer, COVID for healthcare workers, others — override standard causation analysis in many states and reshape compensability.

Every other lever — network, UM, PI, recovery, pharmacy — applies *differently* in WC, and the cost of getting it wrong is bad-faith litigation, not just leakage.

### 2.11 Care Management & Steerage

The positive-clinical-action layer. Nurse case management (telephonic, field, catastrophic), disease management, behavioral health integration, maternity / NICU diversion, Centers of Excellence steerage, member navigation, site-of-care optimization. A single NICU diversion can be $100K–$500K+; for a small or mid-size self-funded employer, this is the largest single-event lever in the entire stack.

The highest-leverage intervention is *upstream of the claim* — getting the right member to the right provider before the high-cost event. It requires benefit-design support (waived cost-share, travel benefits) that ordinary in-network terms do not provide; absent that support, COE utilization stays trivially low (under 2% of eligible episodes).

**Every model output must connect to a defined clinical action.** A trajectory model whose output sits in a dashboard with no downstream NCM assignment, second-opinion referral, BH outreach, or COE steerage is *cost*, not *capability*. **Matched-cohort validation** is mandatory for any care-management ROI claim — "engaged member vs unengaged member" is confounded by selection. And **member experience is a measurable hard constraint, not a vibe** — programs that reduce dollars while generating complaint volume and disenrollment are not wins.

### 2.12 Regulatory & Compliance

The regulatory floor under everything else. Compliance is designed in, not audited in.

**Federal surface:** ERISA fiduciary duty and SPD adequacy. ACA — MLR rebates and EHB and preventive coverage. **MHPAEA** — financial parity and **NQTL (non-quantitative treatment limitations) parity**, which now requires a documented **comparative analysis** demonstrating that BH / SUD treatment limitations are no more restrictive in design *or application* than medical / surgical; plans without that document on the shelf are exposed at first DOL / HHS audit request. NSA — QPA methodology and IDR readiness. HIPAA — and the BAA (Business Associate Agreement) obligation that attaches to *every* cost-containment vendor handling PHI, routinely missed for bill-review and subro vendors. CMS MSP / Section 111. AKS / Stark / FCA. CAA 2021 transparency, including the annual **gag-clause prohibition attestation** that requires plans to certify their vendor contracts do not contain price/quality data gag clauses.

**ERISA preemption** is misunderstood more than any other doctrine in this space. The *insurance saving clause* lets states regulate the business of insurance, so fully-insured plans take both state and federal layers. The *deemer clause* means self-funded plans are not deemed insurance, so state insurance regulation does not reach them. But generally-applicable laws (taxation, criminal), and the federal floor (HIPAA, ACA, NSA, MHPAEA, COBRA, ADA, GINA) reach self-funded plans regardless.

**State surface:** DOI prompt-pay statutes. State balance-bill statutes (apply to fully-insured where not preempted by NSA). State PBM regulation — rapidly evolving, with 30+ states changing copay-accumulator, MAC-transparency, and PBM-licensing rules in the last 24 months. State WC fee schedules, UR statutes, MPN rules, and formularies.

**Service-line × compliance-gate matrix:**

| Service line | Dominant compliance gates |
|---|---|
| §2.4 Network & Repricing | NSA / QPA / IDR; ERISA SPD; AKS / Stark for direct contracts & COE; state OON (fully-insured) |
| §2.5 UM | MHPAEA NQTL; ERISA appeal & external review; state UR timing (WC especially) |
| §2.6 Payment Integrity | State prompt-pay (clawback windows); ERISA fiduciary; provider-appeal due process |
| §2.7 Subrogation | MSP / Section 111 (treble); ERISA reimbursement language; state SoL |
| §2.8 Pharmacy | MHPAEA Rx-tier NQTL; state PBM (rapidly evolving); 340B; white-bagging restrictions |
| §2.9 FWA | NAIC anti-fraud / state DOI referral; FCA / qui tam (MA, Medicaid); due process on pre-pay suspension |
| §2.10 WC | State WC fee schedule / UR / MPN / formulary; presumption statutes; MSA / Section 111 |
| §2.11 Care Management | Member-experience / network-adequacy; benefit-design discrimination (parity); transparency rule |
| All | HIPAA + BAA; CAA gag-clause attestation; CAA broker-compensation disclosure |

---

## 3. The Measurement Contract

No cost-containment program is credible without a written measurement contract that answers, in advance, the following questions. The default answers below are the audit-defensible defaults; deviations require documented rationale.

| Question | Default Answer |
|---|---|
| **What is the baseline?** | Billed charges are *not* a defensible baseline. Use the lower of (a) the plan's allowed amount before the lever applied, or (b) a fixed external benchmark (Medicare × factor, current-year fee schedule, prior-paid). |
| **Paid, incurred, or ultimate?** | Ultimate. Paid-savings views are quarterly comfort; only ultimate-incurred movement is real economic savings. |
| **Stacked or attributed once?** | Attributed once. Every dollar belongs to exactly one lever in the waterfall, with documented exclusivity. |
| **How are vendor fees treated?** | Reported **net of fees**, with ALAE attribution. Gross figures are vendor marketing; net-of-fees, ALAE-attributed figures belong in board reporting. |
| **What is the reporting unit?** | PMPM / PEPM (group health), per-claim and per-$100-of-payroll (WC), AY-restated, against matched prior period. |
| **How is UM avoided-cost validated?** | Matched-cohort comparison; raw "denied dollars × 100%" is vendor-marketing math. |
| **How is CM ROI validated?** | Matched-cohort comparison; engagement bias is real and "engaged vs unengaged" is confounded by selection. |
| **Who audits?** | Internal audit or independent third party; sampled-and-extrapolated; at least annually. |

A program that cannot answer these questions in writing is not measuring savings — it is invoicing.

---

## 4. Structural Failure Modes to Design Against

Six failure modes recur across nearly every program, regardless of vendor stack:

1. **Misaligned incentives.** Percent-of-savings (PoS) vendor fees reward inflated baselines, not the lowest defensible paid amount. PoS contracts must be audited annually, with the baseline computation reproduced in-house — never accepted from vendor reporting. Worst form: subrogation and bill-review vendors paid on PoS where post-pay leak persists *because* the vendor's economics oppose the pre-pay shift.
2. **Overlapping baselines.** The same dollar gets claimed by the network, the bill-review vendor, and the negotiation vendor in sequence. Exclusivity and lineage eliminate this; absent them, gross savings figures are arithmetically incoherent.
3. **Jurisdictional drift.** Group-health logic applied to WC; commercial logic applied to self-funded ERISA; NSA workflows bolted onto preempted state OON statutes. Every lever should carry a jurisdictional gate at design time.
4. **Late detection.** Leakage caught months after payment recovers at 25–60%; the same leakage caught at adjudication recovers at ~100%. The pre-pay shift is the single highest-ROI architectural move in the entire stack.
5. **Compliance retrofit.** Programs designed against financial KPIs alone fail MHPAEA NQTL audits, fail NSA IDR challenges, miss CAA gag-clause attestations, neglect BAA paperwork, and trigger DOL / HHS / state DOI enforcement. Compliance is a design constraint, not a post-launch reconciliation.
6. **Investigative language that defames.** FWA and PI artefacts must use conditional language ("consistent with", "warrants further inquiry") rather than conclusory accusations. Discoverable defamatory artefacts produce provider litigation that erases the underlying recovery, sometimes by orders of magnitude.

---

## 5. The Operating-Model Principle

Claim cost containment is not, ultimately, a question of how aggressively a plan denies, reprices, or recovers. It is a question of whether the plan has built an operating model in which the right service line is applied to the right claim at the right time, against a baseline that survives audit, under incentives that point every participant — internal team, vendor, provider, and member — toward the lowest defensible total cost of care.

The blocks of business that will outperform on trend over the next decade share three traits:

- A **financial lens** that speaks in loss-ratio, ALAE-attributed, AY-restated, ultimate-incurred language — not in vendor savings reports.
- A **service catalog** that covers all twelve lines with explicit coordination contracts between them — so that UM denial and clinical steerage do not contradict on the same case; so that the network discount, the bill-review audit, and the OON negotiation do not double-count the same dollar; so that stop-loss reimbursement bases survive the repricing waterfall; and so that every clinical model output connects to a defined downstream action.
- A **measurement contract** signed off by finance, actuarial, and counsel — *before* the first dollar of "savings" is reported. Without it, what is being reported is invoices, not savings.

Implementation sequencing is engagement-specific and is therefore not prescribed here. What is universal is the diagnostic discipline, the service catalog, the measurement contract, and the regulatory floor above.

---

*Prepared by Mahathi Infotech. For engagement enquiries: Krishnan.Narayanan@mahathiinfotech.com.*

*This document is v3-final, the result of panel review by twelve specialist domain experts whose individual reviews, panel discussion, and disposition log are preserved in `logs/reviews/`, `logs/discussion-transcript.md`, and `logs/revision-log.md`. The session timeline is in `logs/sessions.jsonl`.*
