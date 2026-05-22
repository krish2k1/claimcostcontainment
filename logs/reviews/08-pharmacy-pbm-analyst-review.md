# Review — pharmacy-pbm-analyst

**Reviewer:** pharmacy-pbm-analyst
**Artifact:** `whitepaper/claim-cost-containment-v2-draft.md`
**Date:** 2026-05-22
**Verdict:** ACCEPT WITH REVISIONS

## What works

- §2.8 correctly names PBM contract opacity, spread-vs-pass-through, AWP/WAC/NADAC/MAC mechanics.
- Specialty drug strategy, biosimilar substitution, J-code audit, 340B exposure all named.

## Findings

1. **Specialty is too lightly stated.** Specialty drugs are now ~50%+ of total Rx spend on <2% of utilization. The paper says "fastest-growing component of medical trend" — true but understated for the audience. A reader who does not already know this will not learn it from §2.8. Worth a sentence with the magnitude.
2. **Site-of-care steerage is missing from this section.** Site-of-care for infusibles (physician office vs hospital outpatient vs hospital inpatient) is a 20–40% lever on specialty spend and lives between Rx and care management. It is named in §2.11 but not linked to §2.8. Add the cross-link.
3. **Rebate-aggregator opacity should be elevated.** Modern PBM stack increasingly routes rebates through a rebate-aggregator GPO (Zinc, Ascent, Emisar) where margin is harder to audit than at the PBM. The paper names this in the agent spec but only as "rebate-aggregator opacity" in the paper. Worth a clearer line.
4. **MHPAEA Rx parity (NQTL on Rx tiering / step therapy)** — emerging litigation. Not named. Cross-link §2.8 ↔ §2.12.
5. **Effective-rate guarantees are easily gamed by MAC manipulation.** The paper omits this — but it is the single most common audit finding when an independent third party reviews PBM economics.

## Required edits

- Quantify specialty drug magnitude ("~50% of spend on <2% of utilization").
- Cross-link §2.8 ↔ §2.11 on site-of-care.
- One line on rebate aggregator opacity.
- Cross-link §2.8 ↔ §2.12 on Rx parity.
- One line on MAC manipulation as ERG escape.

## Out of scope

Specific PBM RFP scoring methodology; contract clause library.
