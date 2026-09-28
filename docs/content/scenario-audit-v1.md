# Business English Daily Quiz — Candidate Scenario Bank v1 Work Internal Audit

## 1. Audit status

This audit covers the 120 candidate scenarios in `scenario-bank-v1.md` and the row-level coverage matrix in `scenario-coverage-v1.csv`.

Checks completed:

- framework and Stage-boundary check
- required-field and ID check
- quantitative coverage audit
- semantic duplicate / replacement audit
- directness, channel, counterpart, apology, and English-payoff bias audit
- production-risk review
- Work revision and re-count

Result: **120 unique scenarios completed Work internal QA.** This did not itself constitute final product approval. At the Work handoff, the Candidate Scenario Bank was **Pending Product Review**, and no full A/B/C questions were produced. The later product-review decision is recorded in Section 8.

---

## 2. Coverage audit

### 2.1 Stage and mode

| Dimension | Value | Count | Share |
|---|---|---:|---:|
| Stage | Inbox | 40 | 33.3% |
| Stage | Speak Up | 40 | 33.3% |
| Stage | Handle It | 40 | 33.3% |
| Communication mode | Async | 50 | 41.7% |
| Communication mode | Live | 70 | 58.3% |

Stage classification was checked using the required priority: material problem management → Handle It; otherwise live interaction → Speak Up; otherwise routine async work → Inbox.

### 2.2 Channel

| Channel | Overall | Inbox | Speak Up | Handle It |
|---|---:|---:|---:|---:|
| Email | 35 | 28 | 0 | 7 |
| Messenger | 15 | 12 | 0 | 3 |
| Meeting | 32 | 0 | 20 | 12 |
| Video call | 19 | 0 | 11 | 8 |
| Phone | 19 | 0 | 9 | 10 |
| **Total** | **120** | **40** | **40** | **40** |

Handle It matches the brief exactly at Email 7 / Meeting·Video 20 / Phone 10 / Messenger 3. Overall email share is 29.2%, while live communication is 58.3%; the bank is not email-dominant.

### 2.3 Internal / external

| Stage | Internal | External |
|---|---:|---:|
| Inbox | 26 | 14 |
| Speak Up | 26 | 14 |
| Handle It | 13 | 27 |
| **Total** | **65 (54.2%)** | **55 (45.8%)** |

Routine stages intentionally carry more internal collaboration; Handle It contains more external relationship and service risk. Neither side dominates the full bank.

### 2.4 Counterpart coverage

| Counterpart | Count | Share |
|---|---:|---:|
| Client | 30 | 25.0% |
| Manager | 23 | 19.2% |
| Peer | 23 | 19.2% |
| External partner | 14 | 11.7% |
| Global colleague | 11 | 9.2% |
| Junior / team member | 10 | 8.3% |
| Vendor | 9 | 7.5% |

Client scenarios are the largest single group but remain at one quarter of the bank. Internal roles collectively exceed client-facing scenarios, and all required counterpart groups are represented.

### 2.5 Expected response style

| Response style | Count | Share |
|---|---:|---:|
| Concise | 23 | 19.2% |
| Neutral + factual | 21 | 17.5% |
| Direct + clear | 20 | 16.7% |
| Diplomatic + collaborative | 19 | 15.8% |
| Firm + bounded | 19 | 15.8% |
| Empathetic + solution-oriented | 18 | 15.0% |

The largest-to-smallest gap is five scenarios. Direct + clear and firm + bounded together account for 39 scenarios (32.5%), so directness is not treated as an error by default.

### 2.6 English payoff categories

| Payoff category | Count | Share |
|---|---:|---:|
| Actionability / next step | 16 | 13.3% |
| Clarification precision | 13 | 10.8% |
| Factual neutrality | 13 | 10.8% |
| Scope / boundary | 13 | 10.8% |
| Ownership / responsibility | 12 | 10.0% |
| Negotiation / conditionality | 10 | 8.3% |
| Commitment / certainty | 8 | 6.7% |
| Meeting discourse | 8 | 6.7% |
| Tone / relationship recovery | 8 | 6.7% |
| Deadline / time framing | 7 | 5.8% |
| Concise information structure | 6 | 5.0% |
| Disagreement / alignment | 6 | 5.0% |

No payoff category exceeds 13.3%. Every scenario has a named payoff category plus a specific reusable pattern or language distinction in the bank.

### 2.7 Handle It stakes review

| Handle It stakes | Count | Share within Handle It |
|---|---:|---:|
| High | 30 | 75.0% |
| Sensitive | 10 | 25.0% |

The first Work draft marked 35 Handle It scenarios as high. Targeted review changed `HI-010`, `HI-014`, `HI-026`, `HI-028`, and `HI-036` to sensitive because their stated downstream impact is limited, promptly correctable, or primarily relationship-sensitive. Existing sensitive scenarios `HI-008`, `HI-017`, `HI-023`, `HI-024`, and `HI-035` remain sensitive. No quota was imposed; all other high classifications retain a stated material delivery, cost, customer, quality, responsibility, or relationship consequence.

Across the full bank, stakes are routine 67 (55.8%), sensitive 23 (19.2%), and high 30 (25.0%).

### 2.8 Difficulty potential

| Difficulty potential | Count | Share |
|---|---:|---:|
| Difficulty 1 적합 | 30 | 25.0% |
| Difficulty 2 적합 | 72 | 60.0% |
| Difficulty 3 가능 | 18 | 15.0% |

This is Scenario-level production potential, not a fixed final-question label. It matches the Editorial Guide’s starting range and centers the bank on Difficulty 2.

### 2.9 Storyline coverage

| Storyline | Shared thread | Episode IDs | Count |
|---|---|---|---:|
| `SL-NOVA-ROLLOUT` | Project Nova client rollout | `IN-009`, `IN-024`, `SU-001`, `SU-002`, `HI-006`, `HI-029` | 6 |
| `SL-ATLAS-REPORT` | Atlas market-analysis report | `IN-001`, `IN-013`, `SU-005`, `SU-012`, `SU-023`, `HI-031` | 6 |
| `SL-CEDAR-PARTNERSHIP` | Cedar joint webinar partnership | `IN-006`, `IN-010`, `IN-020`, `IN-038`, `SU-006`, `HI-016` | 6 |
| `SL-DELTA-SUPPLY` | Delta supplier relationship | `IN-026`, `SU-033`, `HI-012`, `HI-001`, `HI-038`, `HI-040` | 6 |
| `SL-PULSE-ACCOUNT` | Pulse client account and renewal | `IN-002`, `IN-033`, `SU-018`, `SU-038`, `HI-019`, `HI-025` | 6 |
| No storyline | — | — | 90 |

Thirty scenarios (25.0%) belong to five actual loose storylines, within the requested 20–30% range. Premises now name the shared project, client account, vendor, or initiative. Every scenario remains independently understandable and keeps its original Stage and English payoff.

### 2.10 Question type taxonomy

Work production recommendations now use only canonical Editorial Guide types:

| Canonical type | Count |
|---|---:|
| Best Response | 75 |
| Best Revision | 14 |
| Choose the Follow-up | 13 |
| Tone Check | 10 |
| Order the Message | 8 |
| What's Wrong? | 0 |
| Fill the Expression | 0 |

The absence of the two optional types does not create a coverage requirement; they remain available for later production when appropriate.

Normalized former ad hoc labels:

- `Best First Question` → `Choose the Follow-up` + `prompt_scope: first question`
- `Best First Response` → `Best Response` + `prompt_scope: first response`
- `Tone / Position Check` → `Tone Check`
- `Order the Response` → `Order the Message` + `content_unit: spoken response`
- `Order the Update` → `Order the Message` + `content_unit: spoken update`

`prompt_scope` and `content_unit` are production qualifiers, not new question types and not changes to the authoritative Question Schema.

---

## 3. Duplicate / replacement report

### 3.1 Method

Scenarios were compared by:

- primary communication challenge
- operational consequence
- candidate reusable pattern
- candidate distractor pair
- required premise
- Stage and stakes

Sharing a topic such as deadlines or clarification was not treated as duplication by itself. A pair was considered duplicate when it would ultimately test the same English judgment with nouns or counterpart labels changed.

### 3.2 Revisions made during drafting

| Draft cluster | Duplicate risk found | Revision made in the candidate bank |
|---|---|---|
| Priority choice | An async “which task first?” scenario duplicated the live priority decision in `SU-004`. | Replaced the async version with `IN-018`, which tests authorization hidden in the verb `prepare` (`draft for review` vs `send directly`). |
| Generic reminders | Client, vendor, and partner reminders initially converged on “please respond by X.” | Retained only distinct judgments: `IN-006` asks for a decision point, `HI-001` requires a firm commitment after repeated failure, and `HI-040` communicates an authorized consequence. |
| Delay updates | Several candidates differed only by the object being delayed. | Split by epistemic and operational function: `IN-004` is an unconfirmed risk, `IN-015` requests a replacement commitment, `HI-005` announces a confirmed material delay with options, and `HI-037` owns the missed outcome while correcting the claimed cause. |
| Complaint responses | Early candidates overused acknowledgment + apology + update. | Differentiated confirmed failure (`HI-019`), unverified conduct (`HI-036`), unknown recovery time (`HI-007`), cancellation threat (`HI-025`), and immediate physical recovery despite unknown cause (`HI-032`). |
| Ownership | Handoff, action owner, and ambiguous pronoun scenarios initially risked the same “Who owns this?” payoff. | Separated transfer conditions (`IN-008`), meeting assignment (`SU-007`), ambiguous `we` (`SU-025`), action recap (`SU-033`), and outcome-versus-cause ownership (`HI-037`). |
| Scope / boundary | Multiple drafts were generic refusals. | Differentiated commercial scope renegotiation (`HI-002`), recurring peer work (`HI-008`), quality gate (`HI-015`), resource trade-off (`HI-027`), evidence-integrity boundary (`HI-031`), and recurring cross-functional support (`HI-035`). |
| Binary clarification | Several candidates used the identical `Do you mean X or Y?` pattern. | Varied the English function: categorized task scope (`IN-001`), named data choice (`IN-009`), absolute deadline confirmation (`IN-024`), authorization alternatives (`IN-018`), and live hearing check (`SU-024`). |

### 3.3 Post-revision near-neighbor check

The following clusters remain intentionally because their primary judgments differ:

- `IN-002` vs `HI-001`: confirm an already agreed routine deadline vs secure a new, time-bounded commitment after repeated failure.
- `SU-012` vs `SU-013`: challenge the evidence for a planning assumption vs label an observed result and an interpretation correctly.
- `HI-003` vs `HI-033`: run a joint root-cause investigation vs refuse an externally requested blame statement.
- Scheduling set `IN-012`, `IN-016`, `IN-036`, `SU-008`: time-zone options, replacing a meeting with async resolution, canceling one recurrence, and live rescheduling are distinct language acts.

Work internal QA found no unresolved semantic duplicate in the candidate bank. Product review may still identify additional overlaps.

---

## 4. Bias audit

### 4.1 Polite = correct / direct = wrong

**Work internal audit: no blocking bias found.**

- Direct + clear: 20 scenarios
- Firm + bounded: 19 scenarios
- Diplomatic + collaborative: 19 scenarios
- Empathetic + solution-oriented: 18 scenarios
- Neutral + factual or concise: 44 scenarios

The bank explicitly includes situations where hedging is the failure mode (`IN-003`, `IN-002`, `SU-002`, `HI-006`), where direct interruption is necessary (`SU-005`), and where a firm boundary is the productive response (`HI-002`, `HI-015`, `HI-027`, `HI-031`). Directness is marked wrong only when it creates a specific operational or relationship cost.

### 4.2 Client-facing concentration

**Work internal audit: no blocking concentration found.** Clients account for 25.0%. Manager, peer, junior/team-member, global-colleague, vendor, and external-partner situations collectively make up 75.0%.

### 4.3 Channel concentration

**Work internal audit: no blocking concentration found.** Email is 29.2% overall. Speak Up is fully live, and Handle It contains 30 live scenarios. Handle It matches the requested live-channel mix.

### 4.4 Handle It catastrophe bias

**Work internal audit: no blocking catastrophe bias found, with a production caution.** Handle It covers material stakes by definition, but the situations vary across boundaries, performance feedback, scope, quality, billing, vendor recovery, responsibility, resource conflict, conduct, and relationship repair. Not every scenario is a service outage or angry-client emergency. Stakes were reclassified according to the actual stated impact rather than forced distribution.

Production caution: question wording should not add dramatic language beyond the recorded facts merely to make Handle It feel difficult.

### 4.5 Apology bias

**Work internal audit: no blocking apology bias found.** No scenario requires apology alone as the productive endpoint. Confirmed mistakes require ownership plus action (`HI-004`, `HI-028`); uncertain complaints use acknowledgment plus verification (`HI-036`); known communication failure uses acknowledgment plus process repair (`HI-019`).

### 4.6 Pure workplace-common-sense risk

**Work internal audit: no blocking Scenario-level issue found.** Every scenario records a concrete English distinction or reusable frame. During Question Bank production, a scenario fails this gate if its options remove that language distinction and leave only an obvious business decision.

---

## 5. Risk report

These scenarios remain valid but need extra care during question production.

### 5.1 High-attention scenarios

| Scenario | Main risk | Production guardrail |
|---|---|---|
| `HI-013` | Scope and free-rework answers can depend on contract wording. | Keep the two conflicting brief versions and the need to compare them explicit; do not invent contractual rights. |
| `HI-018` | Public correction can become a tone-preference question. | Make the false causal claim material to the client’s planning; compare factual correction against silence and counter-attack. |
| `HI-025` | Cancellation-threat responses vary by commercial authority and account strategy. | Preserve the explicit lack of concession authority and make the first goal requirement discovery, not retention at any cost. |
| `HI-031` | Data-publication scenarios can drift into legal or compliance advice. | Test certainty language only; do not introduce securities, regulatory, or legal obligations. |
| `HI-033` | A blame statement can become politically or legally sensitive. | Keep the answer at evidence status and interim factual wording; avoid liability conclusions. |
| `HI-034` | Contract-remedy language can become legal interpretation. | Quote only the explicit agreed remedy in the scenario and test operational escalation, not legal enforceability. |
| `HI-036` | Acknowledgment can accidentally sound dismissive or like an admission. | Use acknowledgment of concern plus a specific investigation time; avoid `if you felt` language and factual admissions before review. |
| `HI-037` | Outcome ownership and cause correction are a subtle two-axis distinction. | Keep all options similar in length and make neither apology nor defensiveness an obvious cue. |

### 5.2 Medium-attention scenarios

| Scenario | Main risk | Production guardrail |
|---|---|---|
| `IN-021` | Some organizations let the supplier reconcile client comments. | Preserve the premise that the client must provide one agreed direction before the next version. |
| `IN-025` | “Preliminary” use rules may depend on organization policy. | State explicitly that the figures may support preparation but may not be cited as final. |
| `IN-034` | Priority decisions may depend on employee autonomy. | Keep both feasible options and the manager’s requested urgency visible; test trade-off language, not deference. |
| `SU-012` | Asking for evidence can sound adversarial depending on wording. | Compare factual inquiry with accepting or reversing the assumption; do not make politeness the sole axis. |
| `SU-015` | Upward disagreement may become a hierarchy-culture question. | Keep the written vendor confirmation as decisive evidence and the deadline as operationally material. |
| `SU-023` | Option framing can bias the decision through unequal detail. | Give speed and accuracy options parallel structure and equivalent information density. |
| `SU-031` | The “conflict” can be interpreted as criticism of the manager. | Phrase the options through schedule impact and a priority question, not accusation. |
| `HI-021` | `can’t guarantee` can look less helpful than a speculative estimate. | Make the next verified update a concrete commitment and keep the recovery time genuinely unknown. |

### 5.3 Cross-bank production risks

- **Length cue:** many strong patterns naturally contain constraint + alternative + next step. Distractors must receive comparable information density so the longest answer does not become a shortcut.
- **Pattern overuse:** reusable frames such as `We can’t X without Y` and `Please confirm by...` should not be copied mechanically across the final Question Bank.
- **Native naturalness:** candidate patterns are production anchors, not frozen final copy. Final options require naturalness review while preserving the recorded judgment.
- **Review conversion:** retrieval prompts should use a changed compact context rather than repeating the eventual multiple-choice wording.

---

## 6. Issues to Resolve

**No blocking product-decision conflict was found.** The authoritative documents agree on the target, Stage priority, English Payoff gate, directness neutrality, Scenario-vs-Question boundary, and review constraints.

Non-blocking production notes:

1. The specs require balance but do not prescribe exact quotas for counterpart, payoff category, or response style. The distributions in this audit are quality-control results for v1, not newly introduced product rules.
2. Exact wording, answer-position balance, and final difficulty remain Question Bank decisions. Scenario-level difficulty labels indicate production potential only.
3. The mixed Korean-context / English-pattern documentation style follows the current source documents; a future content-operations style guide may normalize authoring language without changing product behavior.

---

## 7. Work internal QA checklist

Completion of this checklist does not constitute product approval.

- [x] 120 unique IDs
- [x] Inbox / Speak Up / Handle It = 40 / 40 / 40
- [x] Document status at Work handoff was Candidate Scenario Bank v1 / Pending Product Review
- [x] Required metadata present for every scenario
- [x] English payoff and reusable pattern present for every scenario
- [x] Two distinct distractor failure types proposed for every scenario
- [x] Hidden-premise requirements recorded in each scenario premise
- [x] Storyline coverage within 20–30%
- [x] Five storyline groups have real shared-project continuity and remain independently understandable
- [x] Handle It channel target met
- [x] Handle It stakes rechecked against stated downstream impact
- [x] Question type recommendations normalized to Editorial Guide taxonomy
- [x] Duplicate candidates revised or differentiated
- [x] Directness and politeness bias audited
- [x] Risk scenarios identified with production guardrails
- [x] Top 20 Production Candidates included in `scenario-bank-v1.md`
- [x] No illustrations, character design, UI design, or full Question Bank produced

---

## 8. Product Review Outcome

The targeted revision was reviewed separately from Work internal QA. Product review was completed on **2026-09-28**, and Scenario Bank v1 was **Approved for Question Production**.

This approval applies to the 120 scenarios, their metadata, storyline assignments, coverage matrix, audit record, and Top 20 selection. These remain approved scenario designs, not finished questions; Question Bank production is a separate subsequent phase.
