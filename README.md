# Claim Cost Containment

A specialist-agent framework and white paper on U.S. claim cost containment — covering group health, workers' compensation, auto medical, and property & casualty.

This repository was built using a **12-agent expert panel methodology**: thirteen Claude Code subagents (twelve specialists plus an umbrella orchestrator) were defined first, then used as virtual reviewers to draft, critique, revise, and tighten a positioning white paper over multiple rounds. The repository preserves every intermediate version, every individual review, every panel discussion transcript, and an append-only event log — so a reader can audit not just the final paper but every editorial decision that shaped it.

---

## Repository structure

```
.
├── README.md                                ← this file
│
├── .claude/agents/                          ← 13 specialist subagents (Claude Code format)
│   ├── claims-cost-containment-expert.md      umbrella orchestrator
│   ├── loss-ratio-analyst.md                  MLR, LR, LAE, combined/operating ratio, trend
│   ├── actuarial-reserving-expert.md          IBNR, LDF, chain-ladder, BF, Cape Cod, GLM
│   ├── stop-loss-reinsurance-analyst.md       ISL/ASL, lasers, run-in/out, recovery filing
│   ├── network-repricing-strategist.md        PPO/wrap/RBP/COE waterfall, NSA QPA/IDR
│   ├── utilization-management-reviewer.md     prospective/concurrent/retro UR, gold-carding
│   ├── payment-integrity-auditor.md           leakage taxonomy, DRG validation, pre-pay shift
│   ├── subrogation-recovery-specialist.md     TPL, MSP / Section 111, ERISA recovery
│   ├── pharmacy-pbm-analyst.md                PBM economics, specialty, 340B, rebate aggregators
│   ├── fwa-siu-investigator.md                fraud taxonomy, FCA exposure, NAIC anti-fraud
│   ├── workers-comp-specialist.md             compensability, MMI, indemnity, MSA, RTW
│   ├── care-management-steerage-strategist.md NCM, COE, trajectory triggers, navigation, VBC
│   └── regulatory-compliance-watchdog.md      ERISA / ACA / MHPAEA / NSA / HIPAA / MSP / state
│
├── whitepaper/                              ← the white paper, all versions preserved
│   ├── claim-cost-containment.md              v4 — current, 3 pages, panel-tightened
│   ├── claim-cost-containment-v3.md           v3 — 5 pages, full panel-reviewed final
│   ├── claim-cost-containment-v2-draft.md     v2 — pre-panel draft (no implementation roadmap)
│   └── claim-cost-containment-v1.md           v1 — original 3-page baseline
│
├── context/
│   └── domain-glossary.md                   ← curated terminology the agents draw from
│
└── logs/                                    ← full audit trail of the writing process
    ├── sessions.jsonl                         append-only event log (every action timestamped)
    ├── reviews/                               12 individual expert reviews of v2-draft
    │   ├── 01-loss-ratio-analyst-review.md
    │   ├── 02-actuarial-reserving-expert-review.md
    │   ├── ...
    │   └── 12-regulatory-compliance-watchdog-review.md
    ├── discussion-transcript.md               panel discussion that produced v3 (6 rounds)
    ├── discussion-transcript-v4.md            editorial-panel discussion that produced v4
    └── revision-log.md                        finding-by-finding disposition table (50+ edits)
```

---

## The 12-agent panel methodology

The white paper was written not as a single draft but as the output of a structured multi-round review process. The same twelve specialist agents that constitute the cost-containment capability *in the paper* were used as reviewers *of the paper* — each looking at the draft from the seat they sit in operationally.

### Stage 1 — Build the specialists

Twelve specialist subagents were defined first, each as a `.claude/agents/<name>.md` file with YAML frontmatter (`model`, `token_budget`, `thinking_budget`, `cache_priority`, `on_budget_exceeded`) and a structured body covering:

- The agent's specific value (the questions a generalist would not ask)
- Domain depth (loss-ratio anatomy, reserving methods, repricing waterfalls, NSA mechanics, MSP exposure, PBM economics, WC statutory framework, MHPAEA NQTL, etc.)
- Required output format
- Boundaries (what the agent will not do)
- Escalation rules (when to defer to credentialed counsel / actuary)

The roster covers every meaningful service line in U.S. claim cost containment. A thirteenth agent — `claims-cost-containment-expert` — sits above as an umbrella orchestrator that routes ambiguous questions to the right specialist.

### Stage 2 — Draft the paper

`whitepaper/claim-cost-containment-v1.md` — original 3-page positioning paper. Acceptable but light; specifically thin on financial detail (loss ratios) and on the full service catalog.

`whitepaper/claim-cost-containment-v2-draft.md` — revised draft. Implementation-roadmap section removed (engagement-specific, not appropriate for positioning material). New §1 introducing the full loss-ratio family. New §2 enumerating all twelve service lines.

### Stage 3 — Panel review

Each of the twelve specialist agents reviewed v2-draft from the seat of their service line. Reviews live in [logs/reviews/](logs/reviews/) and follow a common format:

- **Verdict** (ACCEPT / ACCEPT WITH REVISIONS / REJECT)
- **What works** — explicit positive findings
- **Findings** — ranked by importance, with concrete edit recommendations
- **Required edits** — the actionable list
- **Out of scope** — what belongs in a service-line briefing rather than this paper

Verdict tally: 12 / 12 ACCEPT WITH REVISIONS. No full rejections; no APPROVE-AS-IS.

### Stage 4 — Panel discussion

The single-reviewer format catches issues inside one section but not interactions between sections. [logs/discussion-transcript.md](logs/discussion-transcript.md) captures the cross-expert debate — six rounds covering:

1. The biggest gap in v2-draft from each expert's seat.
2. Where two service lines collide (UM vs. care management, payment integrity vs. retrospective UR, subrogation vs. stop-loss recovery).
3. Recovery-ownership ambiguity.
4. Regulatory-ownership consolidation (which led to the §2.12 compliance-gate matrix replacing twelve individual cross-references).
5. Omissions across the paper (WC indemnity layer, first-touch latency, trend-range citations).
6. What stays deferred to service-line briefings rather than being forced into the paper.

The closing line of v3 — *"A program that cannot answer the measurement contract in writing is not measuring savings — it is invoicing"* — was elevated into the paper from this panel discussion.

### Stage 5 — Revision

[logs/revision-log.md](logs/revision-log.md) records every finding from every review as a row with **Source → Disposition** (Accept / Accept-and-strengthen / Defer / Reject). Fifty-plus targeted edits were applied; five major items were explicitly deferred (state-by-state matrices, GLM worked examples, implementation roadmap, vendor RFP scoring, lien-negotiation playbook) — each appropriate for a service-line deliverable rather than a positioning paper.

Output: `whitepaper/claim-cost-containment-v3.md`, ~5 pages, ~2,500 words.

### Stage 6 — Editorial tightening to 3 pages

A second panel session was run with a different mandate: shorten v3 to exactly 3 pages while preserving all twelve services and the loss-ratio depth, and read cleanly cold. [logs/discussion-transcript-v4.md](logs/discussion-transcript-v4.md) records the editorial debate. Each specialist stated the *irreducible core* of their section vs. what they could surrender, against a ~1,450-word budget.

Editor's standing rules for the rewrite:
1. **No orphan sentences.** Every paragraph carries at least two related thoughts.
2. **Each section opens with a thesis line.** The reader knows what it's about by the end of the first sentence.
3. **Every acronym defined on first use.** ALAE, IBNR, MHPAEA, NQTL, QPA, MSP, DRG, COB all expand inline.

Output: `whitepaper/claim-cost-containment.md`, ~1,800 words, 3 dense pages, three tables, all twelve service paragraphs preserved at irreducible core.

### Stage 7 — Logging

Every action is timestamped in [logs/sessions.jsonl](logs/sessions.jsonl) — an append-only JSONL event log. Sample event types:

- `session.start` / `session.close`
- `agent.create` (one per agent file)
- `artifact.preserve` (every version checkpoint)
- `review` (one per expert review)
- `panel.complete` / `discussion.transcript` / `revision.log`
- `editorial.cut` (one per expert in the v4 tightening — documenting what was surrendered)
- `artifact.publish`

A reader can reconstruct the full editorial timeline from this single file.

---

## Reading order

For someone arriving at this repo cold:

1. **Start here:** [whitepaper/claim-cost-containment.md](whitepaper/claim-cost-containment.md) — the 3-page final.
2. **If you want depth instead of brevity:** [whitepaper/claim-cost-containment-v3.md](whitepaper/claim-cost-containment-v3.md) — the same content at 5 pages.
3. **To see what the experts argued about:** [logs/discussion-transcript.md](logs/discussion-transcript.md) (v3 panel) and [logs/discussion-transcript-v4.md](logs/discussion-transcript-v4.md) (v4 tightening panel).
4. **To audit a specific expert's view:** the individual review files in [logs/reviews/](logs/reviews/).
5. **To see what was changed and why:** [logs/revision-log.md](logs/revision-log.md).
6. **To trace the timeline of every action:** [logs/sessions.jsonl](logs/sessions.jsonl).
7. **To use one of the specialists as a working agent in your own Claude Code session:** copy the relevant file from [.claude/agents/](.claude/agents/) into your project's `.claude/agents/` directory. The format is standard Claude Code subagent.

---

## Using the agents

Each agent in `.claude/agents/` is a standard Claude Code subagent. To invoke one in your own session, place it in your project's `.claude/agents/` folder and the agent becomes available for delegation. The umbrella agent (`claims-cost-containment-expert`) is designed to route ambiguous cost-containment questions to the right specialist; the twelve specialists handle service-line-specific depth.

Each agent's frontmatter documents its budget (token, thinking depth), its cache priority, and its escalation rules — when to defer to credentialed counsel, actuary, or licensed adjuster rather than producing an answer.

---

## Acknowledgements

The repository structure (specialist subagents, append-only event logs, decision logs, glossary-as-context) is adapted from the **krish-claudestarter** spec-driven development framework (https://github.com/krish2k1/krish-claudestarter), which provides the underlying conventions for `.claude/`, `context/`, and `logs/`.

---

## Contact

Prepared by **Mahathi Infotech**.
Engagement enquiries: **Krishnan.Narayanan@mahathiinfotech.com**.
