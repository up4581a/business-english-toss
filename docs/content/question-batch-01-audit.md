# Question Production Batch 01 — Cross-Question Audit

**Status:** Product Review Passed  
**Audit date:** 2026-09-29  
**Batch:** `QB01-001`–`QB01-020`  
**Question source:** `docs/content/question-batch-01.md`

This document preserves the Work internal QA record and the subsequent Product Review outcome. Batch 01's 20 finished questions are approved for the Question Bank. No question from the remaining 80 scenarios was produced here.

## 1. Fixed scenario selection

The following IDs were fixed before question drafting and were not replaced for production convenience:

| Question | Scenario | Stage | Context / counterpart | Channel | Stakes |
|---|---|---|---|---|---|
| `QB01-001` | `IN-004` | Inbox | external / external partner | Email | sensitive |
| `QB01-002` | `IN-008` | Inbox | internal / peer | Email | routine |
| `QB01-003` | `IN-011` | Inbox | internal / junior or team member | Email | routine |
| `QB01-004` | `IN-018` | Inbox | internal / manager | Messenger | routine |
| `QB01-005` | `IN-022` | Inbox | internal / global colleague | Email | routine |
| `QB01-006` | `IN-029` | Inbox | internal / global colleague | Email | routine |
| `QB01-007` | `IN-040` | Inbox | external / vendor | Email | routine |
| `QB01-008` | `SU-005` | Speak Up | internal / manager | Meeting | sensitive |
| `QB01-009` | `SU-006` | Speak Up | external / external partner | Video call | routine |
| `QB01-010` | `SU-009` | Speak Up | internal / global colleague | Video call | routine |
| `QB01-011` | `SU-017` | Speak Up | internal / junior or team member | Video call | routine |
| `QB01-012` | `SU-022` | Speak Up | external / external partner | Video call | routine |
| `QB01-013` | `SU-027` | Speak Up | internal / global colleague | Video call | sensitive |
| `QB01-014` | `SU-040` | Speak Up | internal / peer | Meeting | routine |
| `QB01-015` | `HI-005` | Handle It | external / client | Email | high |
| `QB01-016` | `HI-009` | Handle It | internal / peer | Video call | high |
| `QB01-017` | `HI-016` | Handle It | external / external partner | Phone | high |
| `QB01-018` | `HI-023` | Handle It | internal / junior or team member | Video call | sensitive |
| `QB01-019` | `HI-033` | Handle It | external / client | Video call | high |
| `QB01-020` | `HI-038` | Handle It | external / vendor | Messenger | high |

All 20 IDs are outside the approved Pilot Top 20.

## 2. Production outcome

- Finished questions: **20**
- Blocked — Product Review Required: **0**
- Answer screens: **20**
- Review variants: **20**
- Question blocks with their own `save_target`, `tags`, Answer screen, and Review variant: **20 of 20**
- Best Revision items with `source_utterance` before the prompt: **5 of 5**
- Order the Message items using actual fragment sequencing: **2 of 2**
- `unique_answer_basis` records: **20**
- `target_customer_choice_reason` records: **40**, one for each distractor

All 20 items previously passed Work internal QA. The targeted Product Review revisions in this document supersede the affected parts of that internal result and remain pending final Product Review.

## 3. Distribution

### Stage

| Stage | Count | Share |
|---|---:|---:|
| Inbox | 7 | 35% |
| Speak Up | 7 | 35% |
| Handle It | 6 | 30% |

### Communication mode and context

| Dimension | Value | Count | Share |
|---|---|---:|---:|
| Mode | Async | 9 | 45% |
| Mode | Live | 11 | 55% |
| Context | Internal | 12 | 60% |
| Context | External | 8 | 40% |

Counterparts include manager, peer, junior or team member, client, vendor, external partner, and global colleague. No learner-facing scenario depends on storyline familiarity.

### Question type

| Canonical type | Count | Share |
|---|---:|---:|
| Best Response | 10 | 50% |
| Best Revision | 5 | 25% |
| Tone Check | 2 | 10% |
| Order the Message | 2 | 10% |
| Choose the Follow-up | 1 | 5% |

No ad hoc type was introduced. `QB01-002` and `QB01-014` require ordering actual fragments; neither compares three finished responses under an Order label.

### Difficulty

| Difficulty | Count | Share |
|---|---:|---:|
| 1 | 8 | 40% |
| 2 | 10 | 50% |
| 3 | 2 | 10% |

Difficulty was recalibrated after Product Review. `QB01-002`, `QB01-009`, `QB01-011`, and `QB01-014` are D1 because their decisive cues make the answer relatively immediate; `QB01-013` moved from D3 to D2 after its ambiguous distractor was replaced. `QB01-012` moved from D1 to D2: the learner must distinguish an evidence-producing bounded pilot from indefinite postponement and premature national commitment. `QB01-017` remains D2 because its scenario supplies facts rather than stating the continuation condition. The labels reflect the actual interactions rather than a forced quota.

### Correct-answer position

| Position | Count | Share |
|---|---:|---:|
| A | 6 | 30% |
| B | 7 | 35% |
| C | 7 | 35% |

Sequence: `B–A–C–C–B–A–C–B–A–C–B–B–C–A–B–C–A–C–A–B`. It has no fixed A/B/C rotation.

### Correct-answer length and information density

Whitespace-delimited English tokens were counted for each main option.

| Relative length | Count | Share |
|---|---:|---:|
| Uniquely longest | 1 | 5% |
| Tied for longest | 6 | 30% |
| Middle | 4 | 20% |
| Shortest | 9 | 45% |

The maximum within-item spread is **5 words** and the average is **2.50 words**. One correct answer is uniquely longest. Information-density and answer-leakage checks were rerun after the targeted revisions in section 5.9.

## 4. Individual production-gate summary

| Question | Decisive fact | Tested English / communication function | Result |
|---|---|---|---|
| `QB01-001` | delay unconfirmed; impact known Thursday noon | risk vs confirmed delay + update point | Pass |
| `QB01-002` | `that version` and `After you send it` require antecedents | sequence handoff fragments and ownership | Pass — D1 |
| `QB01-003` | no action is currently required | label FYI vs action request | Pass |
| `QB01-004` | prepare may mean review-first or direct-send | clarify authorization alternatives | Pass |
| `QB01-005` | schedule did not change; prior date was wrong | replacement fact first + brief apology | Pass |
| `QB01-006` | Sales Operations owns approval; speaker knows the context and can connect the approver | warm routing without duplicate context submission | Pass |
| `QB01-007` | review complete; issue resolved; no action remains | explicit closure | Pass |
| `QB01-008` | approved figure is available before a decision | direct factual interruption | Pass |
| `QB01-009` | proposal is viable only after two reviews | conditional agreement with `provided that` | Pass — D1 |
| `QB01-010` | exact figure can be checked in 30 seconds | hold the floor for brief verification | Pass |
| `QB01-011` | Mina knows the findings but did not assess remediation or ownership | targeted expert invitation within known work scope | Pass — D1 |
| `QB01-012` | no operating data; a one-region, four-week pilot can produce needed information | distinguish a bounded evidence path from indefinite postponement or premature commitment | Pass — D2 |
| `QB01-013` | demand is unchanged; channel mix shifted; staffing effect is not yet determined | correct the evidence without inventing a staffing decision | Pass — D2 |
| `QB01-014` | one decision, two open items, one owner/date | order closure fragments with clear references | Pass — D1 |
| `QB01-015` | Friday full delivery impossible; partial Friday capacity and full Tuesday readiness | turn capabilities into a client recovery choice | Pass |
| `QB01-016` | record shows sequence and current owner, not total blame | separate timeline from interpretation | Pass |
| `QB01-017` | three no-shows affect schedule; no named lead or stable cadence exists | derive a measurable continuation boundary from operating facts | Pass — D2 |
| `QB01-018` | three missed notes caused missed follow-ups; 24-hour rule | behavior-impact-expectation feedback | Pass |
| `QB01-019` | cause unconfirmed until joint findings tomorrow | remove unsupported blame; provide interim fact | Pass |
| `QB01-020` | current defect notice is insufficient for a launch decision; immediate call is possible | decision-relevant incident intake before blame | Pass |

## 5. Cross-question QA

### 5.1 Reusable frames and English payoff

- Exact duplicate main-question reusable patterns within Batch 01: **0**.
- Exact reusable-pattern overlap with the approved Pilot 20: **0**.
- The batch covers risk framing, referential ordering, FYI labeling, authorization, factual correction, ownership routing, closure, factual interruption, conditional agreement, thinking time, targeted participation, pilot framing, disagreement, meeting closure, bad-news options, responsibility records, continuation conditions, behavioral feedback, interim investigation wording, and incident intake.
- No two questions require the same core English judgment with nouns merely swapped.

### 5.2 Pilot near-duplicate review

Potential thematic neighbors were checked explicitly:

- `QB01-001` is not Pilot `QP-001`: it revises risk status and a confirmation point rather than refusing a recovery guarantee.
- `QB01-013` is not Pilot `QP-002`: the facts are already known and the skill is explicit disagreement, not testing an unsupported causal assumption.
- `QB01-016` is not Pilot `QP-004` or `QP-013`: it reconstructs an internal record and current ownership without deciding outcome responsibility or correcting a client-facing false cause.
- `QB01-019` is not Pilot `QP-016`: it removes unsupported causal blame and supplies interim investigation wording rather than calibrating result-publication certainty.

Result: no Pilot question was mechanically transformed into a Batch 01 item.

### 5.3 Distractor plausibility and separation

- Every distractor has a one-line `target_customer_choice_reason`.
- Every question has two distinct failure functions.
- No distractor relies on cartoonish rudeness, broken grammar, or obviously impossible workplace behavior.
- `QB01-005` no longer makes correction and apology compete. The correct option leads with the explicit replacement fact and then includes a brief apology; Option A still fails because it never supplies the correct date.
- `QB01-006` Option C remains a realistic ownership redirect, but it now requires the requester to resend context that the speaker can preserve through a direct handoff.
- `QB01-018` Option A now includes the same 24-hour expectation as the correct answer, so the number itself is not the cue; A fails because it retains personality and ownership judgments instead of observable behavior and impact.
- After Product Review, `QB01-011` now states the validator's known work boundary: Mina can explain findings but did not assess remediation or ownership. Option A asks for work outside that boundary, while B requests only the findings.
- After Product Review, `QB01-013` Option B no longer loses because it refers to the colleague personally. It now jumps from a correct channel observation to an unsupported staffing decision, so C wins on evidence discipline rather than social polish.
- In `QB01-001`, `QB01-007`, `QB01-008`, `QB01-012`, `QB01-015`, and `QB01-019`, the distractors now engage the same central scenario facts as the correct answer. Their failure comes from the communication function applied to those facts, not from simply omitting a fact copied from the scenario.

### 5.4 Unique-answer and hidden-premise checks

- Every `unique_answer_basis` names both a decisive scenario fact and a tested English or communication function.
- `QB01-004` states both historical workflows so direct-send authority is not assumed.
- `QB01-001` gives all three options Friday timing and the Thursday checkpoint; B alone names the active risk and commits to confirming the date at that checkpoint.
- `QB01-007` gives all three options completed review and resolution; C alone closes the loop without retaining an open ticket or requesting unnecessary confirmation.
- `QB01-008` gives all three options the approved 8%-versus-18% correction; B alone makes the correction immediately without delaying it or stopping unrelated work.
- `QB01-006` uses the Scenario Bank fact that the speaker knows the background and can connect the actual owner; A preserves that context, while C makes the requester resend it.
- `QB01-011` states both Mina's known findings scope and what she did not assess, so Option A and B are no longer two reasonable versions of the same request.
- `QB01-012` makes all three options engage the one-region, four-week opportunity: B uses it as a bounded evidence path, A rejects it in favor of an undefined wait for broader data, and C commits nationally before its evidence exists.
- `QB01-015` gives all three options the confirmed Friday constraint and Friday/Tuesday recovery capabilities. The Scenario Bank explicitly says the client can receive either schedule, and its Goal and payoff require presenting both choices and asking which works better; B follows that product intent, while C selects split delivery without asking.
- `QB01-013` states the observed demand and channel facts but not a staffing answer; the correct response reports the evidence without adding one.
- `QB01-016` states the recorded transfer and current approval owner without using the record to settle broader blame.
- `QB01-017` now states the missing lead and inconsistent cadence as facts instead of stating the required continuation condition.
- `QB01-019` gives all three options the joint investigation and tomorrow timing; A alone removes unsupported cause attribution while still supplying usable interim wording.
- `QB01-020` states that the current report is insufficient and an immediate call is possible, without listing the exact fact categories used by the correct response.

Result: no hidden premise or unresolved two-good-answer item was found.

### 5.5 Policy, authority, admission, and commitment boundary

- `QB01-004` tests authorization wording rather than asking the learner to infer a company workflow.
- `QB01-006` routes an approval without granting the speaker authority.
- `QB01-009` includes the stated review condition and lack of authority to proceed without it.
- `QB01-016` does not invent shared responsibility or use the record to declare total fault.
- `QB01-019` follows the `HI-033` high-attention guardrail: it tests evidence status only and introduces no legal, contractual, or liability claim.
- `QB01-020` requests facts before blame and does not demand a guarantee as the correct response.

Result: pass.

### 5.6 Politeness, directness, and answer-style balance

- Direct correct answers include `QB01-003`, `QB01-005`, `QB01-008`, `QB01-013`, `QB01-015`, `QB01-017`, and `QB01-020`.
- Firm or bounded correct answers include `QB01-009`, `QB01-016`, `QB01-017`, and `QB01-019`.
- Diplomatic or collaborative answers are correct only when they add a functional path, such as the warm handoff in `QB01-006` or bounded pilot in `QB01-012`.
- Polite-sounding distractors remain wrong for operational reasons, including implied action (`QB01-003`), wrong clarification dimension (`QB01-004`), effort-only attendance language (`QB01-017`), and vague feedback (`QB01-018`).

Result: no `polite = correct` or `direct = wrong` bias was found.

### 5.7 Scenario leakage and storyline dependency

- The targeted scenarios now present facts, constraints, timing, authority, or available capability without supplying a finished response structure.
- `QB01-006` uses the Scenario Bank's observable capability that the speaker knows the request background and can connect the approver; it does not instruct the learner to use a warm handoff.
- `QB01-012`, `QB01-015`, and `QB01-020` do not state the answer action or enumerate the correct response structure.
- For `QB01-001`, `QB01-007`, `QB01-008`, `QB01-012`, `QB01-015`, and `QB01-019`, shared fact coverage across the options prevents the scenario wording from functioning as a simple match-the-fact answer cue.
- Internal storyline names such as Atlas, Nova, Cedar, Delta, and Pulse do not appear in learner-facing text.
- Person names appear only where necessary to make handoff ownership or meeting participation natural, not as storyline prerequisites.

Result: pass.

### 5.8 Answer screens and review variants

- All answer screens retain Correct/Incorrect behavior, a 1–2 sentence Why it works, a concise takeaway, and `save_target`.
- Review variants use changed micro-scenarios, contain no A/B/C options, require no typing, include `[정답 보기]`, and reveal a response plus reusable pattern.
- No review variant copies its main scenario verbatim.
- Assembly validation parsed each `## QB01-xxx` block independently. Every one of the 20 blocks contains exactly one `tags` field, one Answer screen, one Review variant, one review `response`, two `save_target` entries (metadata and Answer screen), and two `reusable_pattern` entries (main question and review).
- The misplaced `QB01-005`, `QB01-010`, and `QB01-015` trailing sections were restored to their original question blocks. `QB01-020` now ends with only its own review variant; no orphaned sections remain after it.

Result: pass.

### 5.9 Targeted Product Review revalidation

| Question | Revalidation focus | Result |
|---|---|---|
| `QB01-001` | risk and checkpoint copied from scenario | All options contain Friday timing and the Thursday checkpoint; B wins by naming the active risk and committing to a date confirmation. |
| `QB01-006` | warm handoff vs realistic redirect | A wins because it uses an available direct connection and preserves known context; C requires duplicate context submission. |
| `QB01-007` | closure facts copied from scenario | All options acknowledge review and resolution; C wins by closing the loop without an unnecessary open state or confirmation request. |
| `QB01-008` | approved number as an answer cue | All options state 8%, not 18%; B wins by correcting the decision-driving fact immediately without deferral or overreaction. |
| `QB01-012` | two-good-answer risk between A and B | A now rejects the available pilot and waits for undefined broader data; B uniquely converts the available scope into a bounded evidence path before commitment. Difficulty remains D2. |
| `QB01-015` | recovery-choice ownership | `HI-005` states that the client can receive either schedule, and its Goal/payoff explicitly require offering both and asking which works better. C now makes the split decision unilaterally; B preserves the intended client choice. |
| `QB01-018` | `24 hours` as an answer cue | A and C both contain 24 hours; C wins through behavior + impact + measurable expectation rather than number matching. |
| `QB01-019` | investigation status copied from scenario | All options mention the joint investigation and tomorrow timing; A removes unsupported blame while preserving usable interim wording. |
| `QB01-020` | prelisted incident inputs | Scenario no longer lists the correct fact categories; B supplies decision-relevant intake and an immediate call. |
| `QB01-014` | unnecessary person names | `Jae` / `Sora` were replaced with `project lead` / `contract owner`; order logic and D1 are unchanged. |
| `QB01-011` | difficulty only | Learner-facing content is unchanged; the explicit expertise boundary supports D1. |

No new authoritative fact, authority, commitment, or error category was added. All revised facts remain within the corresponding Scenario Bank premise and guardrail.

## 6. Issues corrected during Work internal QA and targeted Product Review revision

1. Kept the option-length spread to a maximum of five words; one correct answer is uniquely longest after the targeted revisions.
2. Shortened the non-answer apology in `QB01-005` so the compact correction is not signaled merely by extreme length difference.
3. Rebalanced information density in `QB01-016`, `QB01-017`, and `QB01-018` without changing their failure functions.
4. Reframed `QB01-011` around bounded expertise rather than a politeness-only distinction.
5. Confirmed that both Order the Message items use actual fragments whose references depend on sequence.
6. Kept `QB01-019` at evidence status and interim wording, in line with the Scenario Audit guardrail for `HI-033`.
7. Reworked `QB01-011` so the scenario defines Mina's findings scope and Option A requests remediation and ownership outside that scope.
8. Replaced `QB01-013` Option B's personal framing with an unsupported staffing conclusion; the correct answer now wins by reporting only what the evidence supports.
9. Recalibrated `QB01-002`, `QB01-009`, `QB01-011`, `QB01-012`, `QB01-013`, and `QB01-014` difficulty labels to match answer-hidden Product Review.
10. Removed answer leakage from `QB01-017` by replacing the stated continuation condition with observable operating facts; D2 remains appropriate after the rewrite.
11. Restored the `save_target`, `tags`, Answer screen, and Review variant for `QB01-005`, `QB01-010`, and `QB01-015` to their owning blocks and added block-level assembly validation.
12. Replaced the nonessential person names in `QB01-002` with functional team labels without changing its order logic or D1 label; final learner-facing wording uses `the pricing team` / `the legal team`.
13. Revised `QB01-005` so the correct response leads with the explicit replacement fact and also includes a brief apology, removing the correction-versus-apology false trade-off.
14. Reworked `QB01-006` against the Scenario Bank source so A preserves known context through an available direct connection, while C requires the requester to resend that context.
15. Reframed `QB01-012` as an evidence gap plus available scope/time, then made B construct the bounded test and review point; subsequent Product Review recalibrated it to D2.
16. Reframed `QB01-015` as separate operational capabilities and made B turn them into a customer-facing recovery choice.
17. Added the 24-hour standard to `QB01-018` Option A so the deadline is no longer an answer cue; A still fails through personality judgment and unclear impact.
18. Removed the prelisted fact categories and exact call time from `QB01-020`; B now performs incident intake from an incomplete report.
19. Replaced `Jae` and `Sora` in `QB01-014` with functional owner roles without changing sequence logic or difficulty.
20. Recalibrated `QB01-011` from D2 to D1 without changing learner-facing content.
21. Rebalanced `QB01-001` so every option uses Friday timing and the Thursday checkpoint; the answer now turns on risk status plus a committed confirmation outcome.
22. Rebalanced `QB01-007` so every option includes completed review and resolution; the answer now turns on explicit, unnecessary-action-free closure.
23. Rebalanced `QB01-008` so every option states the approved 8%-versus-18% fact; the answer now turns on immediate proportional correction.
24. Rebalanced `QB01-012` so every option uses the same one-region, four-week scope; the answer now turns on a defined evidence review, and difficulty moved from D1 to D2.
25. Rebalanced `QB01-015` so every option uses the Friday/Tuesday capabilities; the answer now turns on certainty calibration and preserving the client's recovery choice.
26. Rebalanced `QB01-019` so every option uses the investigation and tomorrow timing; the answer now turns on removing unsupported blame while retaining usable interim wording.
27. Replaced `QB01-012` A's reasonable but vague pilot with the Scenario Bank's intended `indefinite postponement` failure, removing the A/B two-good-answer problem.
28. Verified `QB01-015` against `HI-005`: the source explicitly provides two client recovery schedules and requires asking which works better. Revised C so it chooses split delivery unilaterally instead of also functioning as a reasonable offer.

## 7. Blocked items and Product Review issues

Blocked items within the targeted revisions: **none**.

No new authoritative-rule decision is required. All specified answer-leakage, unique-answer, and learner-facing clarity items were addressed against the existing Scenario Bank facts and Editorial Guide v1.4.

## 8. Work internal QA and Product Review outcome

All 20 fixed scenarios were completed as finished questions and passed the recorded Work internal QA against Editorial Guide v1.4. Final Product Review is now complete, including the last learner-facing wording cleanup in `QB01-002`.

**Status: Product Review Passed.**

Batch 01's 20 finished questions, answer screens, and review variants are approved for the Question Bank. Production of the remaining 80 questions is authorized but has not started in this document set.
