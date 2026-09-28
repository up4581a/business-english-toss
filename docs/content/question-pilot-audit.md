# Question Production Pilot v3 — Cross-Question Audit

**Status:** Product Review Passed Against Editorial Guide v1.4  
**Audit date:** 2026-09-28  
**Pilot set:** `QP-001`–`QP-020`, using only the approved Top 20 Production Candidates  
**Question source:** `docs/content/question-pilot-top20.md`

This targeted revision passed Work internal QA and Product Review. The pilot is approved, and production of the remaining 100 questions is authorized.

## 1. Revision basis and scope

This pass implements the explicit Product Review decisions for Pilot v2 and audits the result against Editorial Guide v1.4.

Scope controls:

- Exactly the approved Top 20 scenario IDs remain, in the same rank order.
- No Scenario Bank premise, primary communication challenge, English payoff, storyline assignment, or Top 20 selection changed.
- Items marked to remain unchanged kept their question content, options, rationales, answer screens, and review variants; only the required global `save_target` field name changed.
- The remaining 100 questions were not produced.
- No scenario-bank document, product-learning spec, review-system document, or Golden Question Set was modified.

## 2. Internal QA outcome

All 20 questions pass Work internal QA and Product Review against Editorial Guide v1.4.

The targeted revision resolved the Product Review findings:

- `QP-002` Option A now plausibly uses the unsupported price premise as the basis for an actual discount decision; it no longer describes a reasonable experiment.
- `QP-005` now distinguishes actionability rather than politeness: A asks for a priority but omits the known Thursday consequence, while B supplies decision-relevant impact.
- `QP-009`, `QP-012`, and `QP-015` expose a separate `source_utterance` before the prompt.
- `QP-010` uses the idiomatic construction `agree on` consistently.
- `QP-011` states the exact known condition, `one more person today`, and audits B for unnecessarily obscuring it.
- `QP-016` states that inclusion in the joint press release is already decided and that the wording must be finalized in the current meeting. The learner chooses evidence-calibrated wording, not disclosure policy.
- `QP-020` is now Best Response; the former `content_unit` workaround was removed.
- All 20 answer screens use `save_target` metadata with the fixed UI action **[내 표현에 저장]**.
- Question difficulty was reassessed at the finished-question level rather than inherited mechanically.

No blocking conflict was found between the Product Review decisions and the authoritative specifications.

## 3. Distribution audit

### Stage

| Stage | Count | Share |
|---|---:|---:|
| Inbox | 6 | 30% |
| Speak Up | 7 | 35% |
| Handle It | 7 | 35% |

### Question type

| Canonical type | Count | Share |
|---|---:|---:|
| Best Response | 11 | 55% |
| Choose the Follow-up | 4 | 20% |
| Best Revision | 3 | 15% |
| Tone Check | 2 | 10% |
| Order the Message | 0 | 0% |

No ad hoc type was introduced. `QP-020` moved from Order the Message to Best Response because the interaction compares three completed responses rather than ordering fragments.

### Difficulty

| Difficulty | Count | Share |
|---|---:|---:|
| 1 | 3 | 15% |
| 2 | 11 | 55% |
| 3 | 6 | 30% |

`QP-001`, `QP-006`, and `QP-012` changed from D3 to D2 as required. Revised `QP-016` is also D2: inclusion is already decided and the wording must be finalized in the current meeting, removing both the policy-choice ambiguity and the timing hidden premise while leaving a clear certainty distinction. Other difficulties remain unchanged.

### Correct-answer position

| Position | Count | Share |
|---|---:|---:|
| A | 6 | 30% |
| B | 7 | 35% |
| C | 7 | 35% |

Sequence: `B–C–A–C–B–A–C–B–A–B–C–A–C–B–A–C–B–A–B–C`. No option position changed and no fixed rotation is present.

### Correct-answer length rank

Whitespace-delimited English tokens were counted for the three main options of each item.

| Relative length | Count | Share |
|---|---:|---:|
| Longest, including ties | 6 | 30% |
| Middle | 7 | 35% |
| Shortest, including ties | 7 | 35% |

The maximum within-item spread is 8 words and the average spread is 3.65. Correct answers do not show a usable longest-answer cue.

## 4. Canonical interaction-contract audit

### Best Revision

Editorial Guide v1.4 now requires a concrete source message, draft, or previous utterance to exist in the interaction before the prompt.

| Question | `source_utterance` present before prompt | Prompt introduces source for the first time? | Intent-preserving revision |
|---|---|---|---|
| `QP-009` | Yes | No | Replaces an impossible dual commitment with feasible timing and a priority choice. |
| `QP-012` | Yes | No | Replaces an attempt to absorb all comments with a request for one agreed input. |
| `QP-015` | Yes | No | Replaces an unsupported calendar date with a dependency-based turnaround. |

Result: pass.

### Order the Message

Editorial Guide v1.4 now reserves Order the Message for arranging actual message fragments or response parts. Selecting the best of three completed responses is Best Response, and a `content_unit` qualifier cannot change that interaction.

- Pilot Order the Message items: 0.
- `QP-020`: Best Response.
- `content_unit: spoken response` occurrences: 0.

Result: pass. The former `QP-020` taxonomy issue is resolved and is not an open issue.

## 5. Targeted quality findings

### 5.1 Unique-answer robustness

- `QP-002`: A now commits to approving a larger discount because price “looks like the most likely cause,” despite interviews not yet occurring. C uniquely separates the known churn increase from the unconfirmed cause and asks for evidence.
- `QP-011`: C uniquely combines the headline answer with the exact condition `one more person today`. B is plausible but replaces the known condition with nonspecific staffing language.
- `QP-016`: inclusion is already decided, and the wording must be finalized in the current meeting. B leaves a placeholder and postpones that required decision; C alone supplies a usable, evidence-calibrated formulation.

Result: pass. Each correct answer's advantage rests on a scenario fact plus an English/communication function.

### 5.2 Actionability vs Tone

`QP-005` was re-audited on its actual decision value:

- A is natural and direct, but it asks which direction to follow without surfacing the known two-day consequence.
- B states that delivery moves to Thursday and then asks for the priority decision.
- C leaves the already known trade-off unresolved by retaining Tuesday as a soft target.

B wins because it gives the decision-maker material information, not because it is more polite. The `actually` cue and the former personalization rationale were removed.

Across the pilot, direct or firm correct answers remain present in `QP-001`, `QP-004`, `QP-005`, `QP-013`, and `QP-016`. No `polite = correct` or `direct = wrong` pattern was found.

### 5.3 Policy / Organization-Choice Boundary

`QP-016` no longer asks the learner whether an unvalidated result should be published. The scenario states that the joint release will include the initial result and that its wording must be finalized in the current meeting. Option B is wrong because it postpones that required wording decision, not because of a preferred disclosure policy. The tested contrast is `final` versus `preliminary pending validation`, grounded in evidence status.

Result: pass.

### 5.4 Risky Admission / Commitment Language

- `QP-004` remains unchanged from v2; `We own that` was not reintroduced.
- `QP-001` commits only to the known update time, not an unverified recovery time.
- `QP-011` adds the exact staffing condition rather than broadening the promise.
- `QP-016` limits certainty to the available evidence and does not invent publication authority.

Result: pass. No targeted revision invents responsibility, guarantee, contractual right, blame, or authority absent from the scenario.

### 5.5 Target-customer plausibility and distractor separation

- Every item retains two distinct distractor functions.
- `QP-002` A is a recognizable action-bias response, not a cartoonish error.
- `QP-005` A is a plausible manager-facing priority question; its weakness is missing decision-relevant information.
- `QP-016` B is a plausible delay tactic but fails the explicit requirement to finalize the wording in the current meeting.
- The explicitly protected distractors in `QP-004`, `QP-007`, and `QP-018` remain unchanged.

Result: pass. All 60 options remain plausible workplace English, and distractors fail for different reasons.

## 6. Cross-question checks

### English payoff and workplace-judgment boundary

- Every question retains a specific `key_expression` and reusable pattern.
- Exact duplicate main-question reusable patterns: 0.
- No question reduces to pure workplace common sense: decisive contrasts involve certainty, commitment, evidence, scope, ownership, clarification, conditional timing, or discourse structure.

### Answer leakage and hidden premise

- `QP-009`, `QP-012`, and `QP-015` show the source as interaction content without embedding it for the first time in the prompt.
- `QP-016` explicitly states both that inclusion is decided and that the wording must be finalized in the current meeting; no policy or timing hidden premise remains.
- No revised prompt or scenario states the correct option verbatim as an instruction.

### Naturalness

- `QP-010` now uses `agree on` in the main answer, key expression, reusable pattern, answer screen, and review variant.
- All revised English options were checked for idiomatic workplace use.
- Live-response items still warrant a read-aloud pass in the intended voice environment before release.

### Answer screens and save metadata

- Answer screens: 20.
- `save_target` fields: 20.
- Deprecated `내 표현에 저장: 적합 —` metadata lines: 0.
- The learner-facing action remains the fixed label **[내 표현에 저장]**.
- Each screen retains Correct/Incorrect behavior, a 1–2 sentence Why it works, and a concise takeaway; optional Contrast is used only where it adds value.

### Review variants

- Review variants: 20.
- Multiple-choice variants: 0.
- Typing required: 0.
- `[정답 보기]` present: 20.
- Each uses a changed micro-scenario rather than copying the main item.

### Protected-item preservation

`QP-003`, `QP-004`, `QP-007`, `QP-008`, `QP-013`, `QP-014`, `QP-017`, `QP-018`, and `QP-019` retain their v2 question content and options. Their only pilot-file change is the required global rename from the prior save line to `save_target`.

## 7. Remaining cautions

- **Best Response concentration:** 11 of 20. This is acceptable for the showcase pilot but should be monitored during scale production.
- **Difficulty:** D3 is now 30%, closer to the production direction but still above the Editorial Guide's initial 15–20% recommendation. The remaining bank should be calibrated from finished questions, not forced to compensate mechanically.
- **Behavioral validation:** editorial review cannot establish actual target-user option selection rates. Track option choice, response time, ambiguity reports, and expression saves in product testing.
- **Social-risk items:** `QP-004`, `QP-013`, and `QP-019` still merit careful regression review if wording changes later.

## 8. Production guidance for the remaining 100

These are implementation proposals only; they do not alter authoritative rules.

1. Make `source_utterance` required by validation whenever `question_type = Best Revision`.
2. Validate Order the Message as an ordered fragment set rather than three completed response choices.
3. Store `save_target` as metadata and render **[내 표현에 저장]** as fixed UI copy.
4. Record a one-line `target_customer_choice_reason` for each distractor during drafting.
5. Record a `unique_answer_basis` containing both the decisive scenario fact and tested English/communication function.
6. Keep word-count and information-density checks separate; word parity alone cannot detect answer leakage.
7. Reassess difficulty after options and interaction presentation are finished.

## 9. Issues to Resolve

No new blocking product-decision issue was found. The former `QP-020` Order the Message ambiguity was resolved by Product Review and codified in Editorial Guide v1.4.

## 10. Approval status

This targeted revision has passed Work internal QA and Product Review against Editorial Guide v1.4. The pilot is the approved production baseline, and production of the remaining 100 questions is authorized. Scale production must continue to follow the authoritative Editorial Guide and the production guidance recorded in this audit.
