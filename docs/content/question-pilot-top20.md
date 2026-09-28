# Business English Daily Quiz — Question Production Pilot: Top 20

**Status:** Product Review Passed — Approved Production Baseline  
**Pilot revision:** v3 — targeted revision against Editorial Guide v1.4 on 2026-09-28  
**Source:** Approved Top 20 Production Candidates in `scenario-bank-v1.md`  
**Scope:** 20 finished pilot questions; production of the remaining 100 scenarios is authorized as a separate production phase

Each item preserves its approved Scenario Bank premise, primary communication challenge, and English payoff. Question types use only the canonical Editorial Guide taxonomy.

**Answer screen display rule:** If the learner chose the correct option, show **Correct**; otherwise show **Incorrect** and reveal the correct option. Each item below supplies the explanation and takeaway used in both states. The fixed UI action is **[내 표현에 저장]**; `save_target` stores the expression offered by that action.

---

## QP-001 · Commit to an update, not an unverified recovery time

- **question_id:** `QP-001`
- **scenario_id:** `HI-021`
- **stage:** `Handle It`
- **question_type:** `Best Response`
- **difficulty:** `2`
- **scenario_text:** 서비스 장애를 조사 중입니다. 복구 시각은 아직 추정할 수 없고, 조사팀의 다음 기술 분석 결과는 1시간 안에 나옵니다. 고객은 2시간 안에 복구된다고 보장해 달라고 합니다.
- **prompt:** 고객에게 어떻게 답하는 것이 가장 적절할까요?

- **A.** We'll do everything we can to restore service within two hours, and we'll keep you posted as the investigation moves forward.
- **B.** I can't guarantee a recovery time yet. What I can commit to is a technical update within one hour.
- **C.** We can't commit to any timing or next step until the technical investigation is fully complete and the cause has been verified.

- **correct_option:** `B`
- **distractor_types:** `A = effort-only reassurance`; `C = total refusal to commit`
- **option_A_rationale:** 고객이 요청한 시간을 목표처럼 반복하지만 언제 무엇을 알릴지는 약속하지 않는 `effort-only reassurance`다.
- **option_B_rationale:** 보장할 수 없는 범위를 명확히 거절하면서도 신뢰할 수 있는 다음 commitment를 제공한다.
- **option_C_rationale:** 과도한 약속은 피하지만 제공 가능한 update timing까지 거부하는 `total refusal to commit`이다.
- **answer_explanation:** 복구 시각이 확인되지 않았으므로 추정치를 보장해서는 안 된다. B는 uncertainty를 숨기지 않으면서 실제로 지킬 수 있는 다음 업데이트를 약속한다.
- **key_expression:** `What I can commit to is...`
- **expression_note:** 약속할 수 없는 요구를 거절한 뒤, 대신 확실히 제공할 수 있는 행동을 제시한다.
- **reusable_pattern:** `I can't guarantee X yet. What I can commit to is Y by [time].`
- **tags:** `service-failure`, `commitment`, `certainty`, `client-call`, `factual-neutrality`

### Answer screen

- **Correct / Incorrect:** 정답은 **B**입니다.
- **Why it works:** 복구 시각은 아직 unknown이지만 다음 기술 업데이트는 확정할 수 있습니다. B는 이 둘을 분리해 false promise 없이 commitment를 줍니다.
- **Contrast:** A = effort without a concrete update · C = no useful commitment
- **Take this with you:** `What I can commit to is a technical update within one hour.`
- **save_target:** `What I can commit to is...`

### Review variant

- **review_scenario:** 공급업체 장애의 해결 시각은 아직 모르지만 30분 뒤 진단 결과는 받을 수 있습니다. 상대는 “오늘 오전 안에 끝난다고 확답해 달라”고 합니다.
- **recall_prompt:** 보장할 수 없는 시간을 거절하면서 무엇을 약속할지 떠올려 보세요. **[정답 보기]**
- **response:** `I can't guarantee a fix time yet. What I can commit to is an update in 30 minutes.`
- **reusable_pattern:** `I can't guarantee X yet. What I can commit to is Y by [time].`

---

## QP-002 · Test the evidence behind an assumption

- **question_id:** `QP-002`
- **scenario_id:** `SU-012`
- **stage:** `Speak Up`
- **question_type:** `Best Response`
- **difficulty:** `3`
- **scenario_text:** 프로젝트 팀이 고객 이탈의 원인을 가격이라고 전제하고 할인안을 논의하고 있습니다. 현재 확인된 사실은 이탈률 상승뿐이고, 원인을 확인할 고객 인터뷰는 다음 주에 예정돼 있습니다.
- **prompt:** 회의에서 어떻게 말하는 것이 가장 적절할까요?

- **A.** Price looks like the most likely cause, so let's approve a larger discount for the next campaign.
- **B.** Before we focus on price, could the recent product changes be a more likely cause?
- **C.** What evidence points to price? We know churn rose, but we haven't confirmed the cause.

- **correct_option:** `C`
- **distractor_types:** `A = accepts an unsupported premise`; `B = opposite unsupported assumption`
- **option_A_rationale:** 고객 인터뷰 전인데도 가격을 가장 유력한 원인으로 확정하고, 그 premise를 다음 할인 결정의 근거로 사용하는 `accepts an unsupported premise`다.
- **option_B_rationale:** 가격 가설을 검증하는 대신 근거 없는 다른 원인으로 논의를 옮기는 `opposite unsupported assumption`이다.
- **option_C_rationale:** 확인된 결과와 아직 확인되지 않은 원인을 구분하고, 의사결정 전에 evidence를 묻는다.
- **answer_explanation:** 현재 데이터는 churn이 올랐다는 사실만 보여 준다. C는 가격 가설을 공격하지 않으면서 fact와 hypothesis를 분리한다.
- **key_expression:** `What evidence points to X?`
- **expression_note:** 회의에서 가정을 반박하기보다 근거를 확인하고 known fact의 범위를 명시할 때 쓴다.
- **reusable_pattern:** `What evidence points to X? We know Y, but we haven't confirmed Z.`
- **tags:** `assumption`, `evidence`, `factual-neutrality`, `upward-communication`, `meeting`

### Answer screen

- **Correct / Incorrect:** 정답은 **C**입니다.
- **Why it works:** C는 가격이 원인이라고 동의하거나 반대로 부정하지 않습니다. 현재 확인된 사실과 아직 검증할 가설을 정확히 분리합니다.
- **Contrast:** A = accepts the premise · B = replaces it with another guess
- **Take this with you:** `We know churn rose, but we haven't confirmed the cause.`
- **save_target:** `We know X, but we haven't confirmed Y.`

### Review variant

- **review_scenario:** 회의에서 매출 하락의 원인이 새 웹사이트라고 모두 가정하고 있습니다. 확인된 것은 매출이 줄었다는 사실뿐이며 원인 분석은 아직 시작 전입니다.
- **recall_prompt:** fact와 assumption을 나누어 말해 보세요. **[정답 보기]**
- **response:** `We know sales fell, but we haven't confirmed the cause. What evidence points to the website?`
- **reusable_pattern:** `We know X, but we haven't confirmed Y. What evidence points to Z?`

---

## QP-003 · Clarify whether a suggestion is a request

- **question_id:** `QP-003`
- **scenario_id:** `IN-023`
- **stage:** `Inbox`
- **question_type:** `Choose the Follow-up`
- **difficulty:** `2`
- **scenario_text:** 동료가 오늘 발송할 초안을 보며 메신저로 “It might be useful to add a customer example.”이라고만 말했습니다. 누가 언제 반영해야 하는지는 적혀 있지 않습니다.
- **prompt:** 의도를 가장 잘 확인하는 답은 무엇일까요?

- **A.** Should I add a customer example to this draft, or save the idea for later?
- **B.** I'll add the customer example to this draft and send it today.
- **C.** That could be useful for this draft; I'll keep the idea in mind.

- **correct_option:** `A`
- **distractor_types:** `B = assumes the request`; `C = acknowledgment without clarification`
- **option_A_rationale:** 가능한 두 intent를 구체적으로 제시해 지금 action이 필요한지 확인한다.
- **option_B_rationale:** suggestion을 즉시 실행 요청으로 단정하는 `assumes a request`다.
- **option_C_rationale:** 자연스러운 acknowledgment지만 지금 행동해야 하는지는 확인하지 않는 `acknowledges without clarifying action`이다.
- **answer_explanation:** `It might be useful...`은 suggestion일 수도 request일 수도 있다. A는 상대가 필요한 action scope를 바로 선택할 수 있게 한다.
- **key_expression:** `Should I X, or save it for later?`
- **expression_note:** 간접적인 제안이 현재 요청인지 future idea인지 확인하는 concise intent check다.
- **reusable_pattern:** `Should I [action] in this version, or save the idea for later?`
- **tags:** `intent`, `implied-request`, `messenger`, `clarification`, `action-scope`

### Answer screen

- **Correct / Incorrect:** 정답은 **A**입니다.
- **Why it works:** A는 suggestion을 request로 단정하지 않고, 이번 버전과 future idea라는 실제 ambiguity를 해결합니다.
- **Take this with you:** `Should I add this to the current draft, or save it for later?`
- **save_target:** `Should I X, or save it for later?`

### Review variant

- **review_scenario:** 동료가 문서에 대해 “A comparison chart could help.”라고만 남겼습니다. 지금 문서에 추가하라는 뜻인지 확실하지 않습니다.
- **recall_prompt:** current request인지 future idea인지 확인해 보세요. **[정답 보기]**
- **response:** `Would you like me to add a comparison chart to this version, or keep it as an idea for later?`
- **reusable_pattern:** `Would you like me to X now, or keep it for later?`

---

## QP-004 · Acknowledge the missed date without accepting the wrong cause

- **question_id:** `QP-004`
- **scenario_id:** `HI-037`
- **stage:** `Handle It`
- **question_type:** `Best Response`
- **difficulty:** `2`
- **scenario_text:** 팀이 합의 납기를 놓친 것은 사실입니다. 고객은 팀이 작업을 늦게 시작했다고 말하지만, 실제 원인은 작업 중 늦게 발견된 데이터 오류였습니다.
- **prompt:** 어떻게 답하는 것이 가장 적절할까요?

- **A.** We started on time, so I don't agree that our team missed the commitment.
- **B.** We did miss the date. We'll review our start timing, add more buffer to the next schedule, and move the handoff earlier.
- **C.** We did miss the agreed date. The delay began when we found a data error, not because we started late.

- **correct_option:** `C`
- **distractor_types:** `A = denies a confirmed outcome`; `B = leaves the inaccurate cause uncorrected`
- **option_A_rationale:** 제때 시작했다는 사실을 근거로 확인된 납기 미준수 자체까지 부정하는 `denies a confirmed outcome`이다.
- **option_B_rationale:** 납기 미준수는 인정하지만 잘못 제시된 원인을 교정하지 않고 start timing 개선을 약속하는 `leaves the inaccurate cause uncorrected`다.
- **option_C_rationale:** 확인된 outcome과 확인된 cause를 각각 정확한 강도로 말하며 더 넓은 책임 인정은 추가하지 않는다.
- **answer_explanation:** `We missed the agreed date`는 확인된 사실을 인정한다. C는 여기에 `we own that` 같은 포괄적 책임 표현을 덧붙이지 않고 실제 원인만 정확히 교정한다.
- **key_expression:** `We did miss the agreed date.`
- **expression_note:** 확인된 결과를 명확히 인정하되, 확인되지 않은 책임이나 원인까지 넓혀 말하지 않는 factual acknowledgment다.
- **reusable_pattern:** `We did X. The delay began when Y, not because Z.`
- **tags:** `ownership`, `cause`, `delay`, `client`, `factual-correction`

### Answer screen

- **Correct / Incorrect:** 정답은 **C**입니다.
- **Why it works:** C는 확인된 납기 미준수와 실제 원인을 정확히 구분합니다. 사실보다 넓은 책임 인정이나 보장도 추가하지 않습니다.
- **Contrast:** A = denies the confirmed outcome · B = leaves the wrong cause uncorrected
- **Take this with you:** `We did miss the agreed date. The delay began when...`
- **save_target:** `We did X. The delay began when Y, not because Z.`

### Review variant

- **review_scenario:** 승인 요청을 늦게 보낸 것은 사실이지만, 상대는 이유가 “담당자가 잊었기 때문”이라고 잘못 알고 있습니다. 실제 원인은 마지막 검수에서 발견된 오류였습니다.
- **recall_prompt:** 결과는 인정하고 원인은 바로잡아 보세요. **[정답 보기]**
- **response:** `We did send the request late. The delay began when we found a validation error, not because the task was forgotten.`
- **reusable_pattern:** `We did X. The delay began when Y, not because Z.`

---

## QP-005 · Surface a trade-off between two instructions

- **question_id:** `QP-005`
- **scenario_id:** `SU-031`
- **stage:** `Speak Up`
- **question_type:** `Best Response`
- **difficulty:** `3`
- **scenario_text:** 상사는 회의 초반에 화요일 납기를 최우선으로 하라고 했지만, 지금은 추가 검토 세 단계를 넣으라고 합니다. 현재 일정에는 검토 시간이 없고 세 단계를 완료하려면 이틀이 더 필요합니다.
- **prompt:** 회의에서 어떻게 말하는 것이 가장 적절할까요?

- **A.** The new instruction conflicts with the earlier one. Which direction should we follow?
- **B.** Adding the three reviews moves delivery to Thursday. Should we keep Tuesday or include the reviews?
- **C.** Can we keep Tuesday as the target while we add the reviews, then revisit the date if needed?

- **correct_option:** `B`
- **distractor_types:** `A = asks for a priority choice without surfacing the known consequence`; `C = turns a known trade-off into a vague target`
- **option_A_rationale:** 자연스럽게 priority 선택을 요청하지만 이미 알고 있는 Thursday 일정 영향을 보여 주지 않는 `asks for a priority choice without surfacing the known consequence`다.
- **option_B_rationale:** instruction 자체를 평가하지 않고 schedule consequence를 보여 준 뒤 priority decision을 요청한다.
- **option_C_rationale:** 이미 확인된 이틀의 영향을 decision으로 만들지 않고 Tuesday를 모호한 target으로 남기는 `turns a known trade-off into a vague target`이다.
- **answer_explanation:** 필요한 것은 priority 질문만 던지는 일이 아니라 알려진 trade-off를 decision-ready하게 만드는 것이다. B는 Thursday라는 일정 영향과 선택지를 명확히 제시한다.
- **key_expression:** `Adding X moves Y to Z.`
- **expression_note:** 상충하는 요청을 사람의 일관성 문제가 아니라 operational consequence로 바꿔 말한다.
- **reusable_pattern:** `Adding X would move Y to Z. Should we prioritize A or B?`
- **tags:** `conflicting-priorities`, `trade-off`, `upward-communication`, `meeting`, `deadline`

### Answer screen

- **Correct / Incorrect:** 정답은 **B**입니다.
- **Why it works:** B는 추가 검토가 일정에 미치는 영향을 먼저 밝히고, 상사가 선택해야 할 두 priority를 제시합니다.
- **Contrast:** A = asks without the known consequence · C = leaves the known trade-off unresolved
- **Take this with you:** `Adding the reviews moves delivery to Thursday.`
- **save_target:** `Adding X would move Y to Z.`

### Review variant

- **review_scenario:** 상사는 비용을 늘리지 말라고 했지만 지금은 외부 전문가를 추가하라고 합니다. 전문가를 쓰면 예산이 15% 늘어납니다.
- **recall_prompt:** 두 지시의 consequence를 보여 주고 선택을 요청해 보세요. **[정답 보기]**
- **response:** `Adding the specialist would increase the budget by 15%. Should we keep the current budget or add the specialist?`
- **reusable_pattern:** `Adding X would change Y by Z. Should we prioritize A or B?`

---

## QP-006 · Share preliminary figures with a clear use boundary

- **question_id:** `QP-006`
- **scenario_id:** `IN-025`
- **stage:** `Inbox`
- **question_type:** `Tone Check`
- **difficulty:** `2`
- **scenario_text:** 상사가 내일 내부 인력계획 회의를 준비하려고 오늘 수치를 요청했습니다. 표본 한 건은 아직 검증되지 않았고, 그 결과에 따라 현재 합계가 달라질 수 있습니다.
- **prompt:** 현재 데이터의 status와 사용 범위를 가장 정확하게 전달하는 문장은 무엇일까요?

- **A.** These figures are preliminary. Please use them for planning only until the last sample is verified.
- **B.** Here are the latest figures. I haven't labeled them preliminary because only one sample is still being checked.
- **C.** One sample is unverified, so I don't think we should share any of these figures until the full check is complete.

- **correct_option:** `A`
- **distractor_types:** `B = hides provisional status`; `C = unnecessary withholding`
- **option_A_rationale:** 데이터를 공유하되 `preliminary` status와 `planning only`라는 사용 경계를 함께 명시한다.
- **option_B_rationale:** 변동 가능성이 남아 있는데 `preliminary` 표시를 생략하는 `hides provisional status`다.
- **option_C_rationale:** 사용 가능한 정보까지 막아 버리는 `withholds useful information unnecessarily`다.
- **answer_explanation:** provisional data는 숨기거나 final처럼 제시할 필요가 없다. A는 현재 활용 가능한 범위와 아직 남은 validation을 동시에 보여 준다.
- **key_expression:** `Please use them for planning only.`
- **expression_note:** 공유 가능한 preliminary data의 허용 용도를 짧게 제한하는 표현이다.
- **reusable_pattern:** `These figures are preliminary. Please use them for X only until Y is verified.`
- **tags:** `preliminary-data`, `certainty`, `use-boundary`, `email`, `factual-neutrality`

### Answer screen

- **Correct / Incorrect:** 정답은 **A**입니다.
- **Why it works:** A는 수치를 planning에 활용하게 하면서도 final로 인용해서는 안 된다는 경계를 정확히 표시합니다.
- **Take this with you:** `These figures are preliminary. Please use them for planning only.`
- **save_target:** `Please use X for Y only until Z.`

### Review variant

- **review_scenario:** 다음 분기 forecast에서 한 지역의 수요가 아직 확인되지 않아 합계가 달라질 수 있습니다. 팀은 오늘 내부 계획에 쓸 방향성 수치가 필요합니다.
- **recall_prompt:** 자료를 공유하면서 사용 범위를 제한해 보세요. **[정답 보기]**
- **response:** `This forecast is preliminary. Please use it for internal planning only until the regional demand is confirmed.`
- **reusable_pattern:** `X is preliminary. Please use it for Y only until Z is confirmed.`

---

## QP-007 · Start recovery before assigning the cause

- **question_id:** `QP-007`
- **scenario_id:** `HI-032`
- **stage:** `Handle It`
- **question_type:** `Best Response`
- **difficulty:** `2`
- **scenario_text:** 고객 배송물이 도착하지 않았고 courier와 창고 중 어디서 문제가 생겼는지는 아직 모릅니다. 고객은 내일 물품이 필요하며, 오늘 4시 전에 대체품을 출고하면 내일 도착합니다. 현재 시각은 3시입니다.
- **prompt:** 전화에서 어떻게 답하는 것이 가장 적절할까요?

- **A.** We'll wait for the courier's investigation before deciding what to do next.
- **B.** We should be able to send a replacement tomorrow while we check what happened.
- **C.** We're still confirming what happened, but we'll send a replacement now for delivery tomorrow.

- **correct_option:** `C`
- **distractor_types:** `A = delays recovery pending investigation`; `B = weak recovery commitment`
- **option_A_rationale:** 원인 확인이 끝날 때까지 가능한 recovery도 미루는 `delays recovery pending investigation`이다.
- **option_B_rationale:** 출고 가능 시간과 도착 조건이 확인됐는데도 `should be able to`로 행동을 불필요하게 약하게 만드는 `weak recovery commitment`다.
- **option_C_rationale:** 원인은 미확정으로 남겨 두면서 고객에게 필요한 recovery를 즉시 시작한다.
- **answer_explanation:** 고객 복구와 root-cause 판단은 같은 순서로 기다릴 필요가 없다. C는 책임을 추측하지 않고 통제 가능한 출고 행동을 명확히 약속한다.
- **key_expression:** `We're still confirming what happened, but...`
- **expression_note:** investigation이 진행 중이어도 지금 할 수 있는 recovery action을 이어 말할 때 유용하다.
- **reusable_pattern:** `We're still confirming what happened, but we'll [recovery action] now so you have X by Y.`
- **tags:** `recovery`, `root-cause`, `delivery`, `client-call`, `no-blame`

### Answer screen

- **Correct / Incorrect:** 정답은 **C**입니다.
- **Why it works:** 원인은 아직 unknown이지만 대체 배송은 지금 시작할 수 있습니다. C는 investigation과 customer recovery를 분리합니다.
- **Contrast:** A = waits for investigation · B = weakens a controllable commitment
- **Take this with you:** `We're still confirming what happened, but we'll send a replacement now.`
- **save_target:** `We're still confirming X, but we'll Y now.`

### Review variant

- **review_scenario:** 고객 파일이 전송 과정에서 사라졌지만 어느 시스템 문제인지는 아직 모릅니다. 고객의 회의를 위해 사본을 즉시 다시 보낼 수 있습니다.
- **recall_prompt:** 원인을 단정하지 않고 먼저 복구해 보세요. **[정답 보기]**
- **response:** `We're still confirming where the failure occurred, but we'll resend the file now so you have it before the meeting.`
- **reusable_pattern:** `We're still confirming X, but we'll do Y now so you have Z by [time].`

---

## QP-008 · Clarify who “we” refers to

- **question_id:** `QP-008`
- **scenario_id:** `SU-025`
- **stage:** `Speak Up`
- **question_type:** `Choose the Follow-up`
- **difficulty:** `2`
- **scenario_text:** 파트너가 화상회의에서 “We’ll finalize it Friday.”라고 말했습니다. 양사 모두 편집 담당자가 있지만, 이 파일의 최종 담당자는 아직 정하지 않았습니다.
- **prompt:** 바로 이어서 무엇을 묻는 것이 가장 좋을까요?

- **A.** Great, we'll send you our final version on Friday as well, then move straight into the next phase.
- **B.** When you say “we,” will your team finalize the file on Friday, or should ours?
- **C.** Okay, so the final version will be ready on Friday, and we'll plan our next steps around that deadline.

- **correct_option:** `B`
- **distractor_types:** `A = assumes ownership`; `C = preserves collective ambiguity`
- **option_A_rationale:** 상대 팀의 의미를 확인하지 않고 자기 팀도 같은 작업을 하겠다고 가정하는 `assumes ownership`이다.
- **option_B_rationale:** ambiguous `we`를 양사의 명확한 ownership choice로 바꾼다.
- **option_C_rationale:** 날짜만 반복하고 누가 final file을 만드는지는 그대로 두는 `preserves collective ambiguity`다.
- **answer_explanation:** `we`는 여러 조직이 함께 있는 회의에서 ownership을 숨길 수 있다. B는 상대를 탓하지 않고 바로 실행 가능한 두 owner를 명시한다.
- **key_expression:** `When you say “we,” do you mean...?`
- **expression_note:** 집단 주어가 누구를 가리키는지 자연스럽게 확인하는 live clarification frame이다.
- **reusable_pattern:** `When you say “we,” do you mean your team will X, or should ours?`
- **tags:** `ownership`, `ambiguous-we`, `partner`, `video-call`, `clarification`

### Answer screen

- **Correct / Incorrect:** 정답은 **B**입니다.
- **Why it works:** B는 `we`를 양쪽 team으로 풀어 말해 owner를 확정합니다. 날짜 확인만으로는 업무 중복 위험이 남습니다.
- **Take this with you:** `When you say “we,” do you mean your team or ours?`
- **save_target:** `When you say “we,” do you mean...?`

### Review variant

- **review_scenario:** 외부 파트너가 “We’ll send the client update on Monday.”라고 말했습니다. 어느 회사가 발송하는지 정해지지 않았습니다.
- **recall_prompt:** `we`의 owner를 확인해 보세요. **[정답 보기]**
- **response:** `When you say “we,” do you mean your team will send the update, or should ours?`
- **reusable_pattern:** `When you say “we,” do you mean your team will X, or should ours?`

---

## QP-009 · Revise an impossible “ASAP” commitment

- **question_id:** `QP-009`
- **scenario_id:** `IN-034`
- **stage:** `Inbox`
- **question_type:** `Best Revision`
- **difficulty:** `3`
- **scenario_text:** 상사가 새 분석을 “ASAP” 요청했습니다. 정기 보고서를 내일로 옮기면 분석을 오늘 끝낼 수 있고, 보고서를 예정대로 하면 분석은 내일 오후에 가능합니다. 메시지에는 두 결과물 중 어느 것이 더 중요한지 적혀 있지 않습니다.
- **source_utterance:** `Sure, I'll finish the analysis and the weekly report today.`
- **prompt:** 이 답장을 가장 적절하게 고친 것은 무엇일까요?

- **A.** The analysis can be ready today if the report moves to tomorrow; otherwise, it will be ready tomorrow afternoon. Which takes priority?
- **B.** I'll move the weekly report to tomorrow, finish the new analysis today, and send the report tomorrow afternoon, since you need this ASAP.
- **C.** I'll work on both today and send an update when I know which one will be ready first.

- **correct_option:** `A`
- **distractor_types:** `B = assumes urgency`; `C = avoids the priority decision`
- **option_A_rationale:** 두 feasible option과 trade-off를 보여 주고 `ASAP`의 실제 priority를 상사에게 확인한다.
- **option_B_rationale:** `ASAP`를 오늘로 해석해 정기 보고서 이동을 임의로 결정하는 `assumes urgency level`이다.
- **option_C_rationale:** 두 작업을 병행하며 나중에 알리겠다고 해 현재 필요한 priority decision을 피하는 `avoids the priority decision`이다.
- **answer_explanation:** `ASAP`는 정확한 deadline도 priority decision도 아니다. A는 가능한 timing을 제시하고 무엇을 우선할지 결정하게 한다.
- **key_expression:** `Which takes priority?`
- **expression_note:** vague urgency를 구체적인 resource trade-off와 priority question으로 바꾼다.
- **reusable_pattern:** `X can be ready today if Y moves; otherwise, X will be ready by Z. Which takes priority?`
- **tags:** `asap`, `priority`, `capacity`, `messenger`, `best-revision`

### Answer screen

- **Correct / Incorrect:** 정답은 **A**입니다.
- **Why it works:** A는 가능한 두 일정과 그 trade-off를 투명하게 보여 줍니다. 상사가 `ASAP`의 실제 의미를 결정할 수 있습니다.
- **Contrast:** B = assumes the priority · C = postpones the priority decision
- **Take this with you:** `Which takes priority?`
- **save_target:** `X can be ready today if Y moves; otherwise...`

### Review variant

- **review_scenario:** 팀장이 새 deck을 빨리 달라고 합니다. 오늘 만들려면 예정된 data check를 내일로 옮겨야 하고, 그렇지 않으면 deck은 내일 준비됩니다.
- **recall_prompt:** feasible options를 보여 주고 priority를 물어보세요. **[정답 보기]**
- **response:** `The deck can be ready today if the data check moves to tomorrow; otherwise, it will be ready tomorrow. Which takes priority?`
- **reusable_pattern:** `X can be ready today if Y moves; otherwise, X will be ready by Z. Which takes priority?`

---

## QP-010 · Compare the briefs before agreeing rework scope

- **question_id:** `QP-010`
- **scenario_id:** `HI-013`
- **stage:** `Handle It`
- **question_type:** `Best Response`
- **difficulty:** `3`
- **scenario_text:** 고객은 결과물이 brief와 다르다며 무료 재작업을 요구합니다. 양측이 보관한 brief 버전이 달라, 어떤 변경이 언제 들어갔는지는 두 문서를 비교해야 확인할 수 있습니다.
- **prompt:** 화상회의에서 어떻게 답하는 것이 가장 적절할까요?

- **A.** I can ask our commercial team whether no-charge rework is possible now, then compare the two brief versions with you afterward.
- **B.** I understand the concern. Before we agree on the rework scope, let's compare both brief versions to confirm what changed.
- **C.** We can't discuss any rework until your team sends the version you believe we should have used.

- **correct_option:** `B`
- **distractor_types:** `A = premature concession escalation`; `C = unnecessarily rigid evidence demand`
- **option_A_rationale:** 사실관계 확인 전에 no-charge option부터 내부에 올리는 `premature concession escalation`이다.
- **option_B_rationale:** concern은 인정하지만 rework scope 결정은 evidence comparison 이후로 정확히 보류한다.
- **option_C_rationale:** 양측 기록을 함께 비교할 수 있는데 고객에게만 증거 제출 부담을 넘기고 대화를 중단하는 `unnecessarily rigid evidence demand`다.
- **answer_explanation:** 현재 필요한 것은 즉시 양보하거나 반박하는 일이 아니라 두 brief의 차이를 확인하는 것이다. B는 관계를 유지하면서 scope 결정을 위한 evidence를 먼저 확보한다.
- **key_expression:** `Before we agree on X, let's compare Y.`
- **expression_note:** 책임이나 범위를 확정하기 전에 확인해야 할 evidence를 제시하는 collaborative boundary다.
- **reusable_pattern:** `Before we agree on X, let's compare Y and Z to confirm what changed.`
- **tags:** `rework`, `scope`, `evidence`, `client`, `conditional-boundary`

### Answer screen

- **Correct / Incorrect:** 정답은 **B**입니다.
- **Why it works:** B는 고객 concern을 무시하지 않으면서도 free rework를 성급히 약속하지 않습니다. 두 brief를 먼저 비교해 scope를 판단합니다.
- **Contrast:** A = concession before evidence · C = one-sided process block
- **Take this with you:** `Before we agree on the rework scope, let's compare both versions.`
- **save_target:** `Before we agree on X, let's compare Y.`

### Review variant

- **review_scenario:** 고객은 추가 화면이 원래 요청에 포함됐다고 주장하며 무료 작업을 요구합니다. 양측의 회의록 내용이 다르고 어느 기록도 최종 합의를 명확히 보여 주지 않습니다.
- **recall_prompt:** concern을 인정하면서 scope 결정을 보류해 보세요. **[정답 보기]**
- **response:** `I understand the concern. Before we agree on the additional scope, let's compare both meeting records to confirm what was included.`
- **reusable_pattern:** `Before we agree on X, let's compare Y to confirm Z.`

---

## QP-011 · Give the headline answer with its condition

- **question_id:** `QP-011`
- **scenario_id:** `SU-026`
- **stage:** `Speak Up`
- **question_type:** `Best Response`
- **difficulty:** `1`
- **scenario_text:** 임원이 “이번 달 안에 끝낼 수 있나요?”라고 묻습니다. 현재 인력으로는 다음 달 첫째 주에 끝나지만, 추가 담당자 한 명이 오늘 배정되면 이번 달 안에 끝납니다.
- **prompt:** 가장 효과적인 첫 답변은 무엇일까요?

- **A.** There are a few dependencies to explain before I can say whether this month is realistic.
- **B.** Yes, if the staffing plan works out and we can add the support we need.
- **C.** The short answer is yes, provided that we add one more person today.

- **correct_option:** `C`
- **distractor_types:** `A = buries the answer`; `B = gives a vague condition`
- **option_A_rationale:** background를 먼저 예고해 yes/no answer를 뒤로 미루는 `buries the answer`다.
- **option_B_rationale:** 이미 확인된 exact condition인 `one more person today`를 `if the staffing plan works out`과 `the support we need`라는 vague language로 불필요하게 흐리는 `gives a vague condition`이다.
- **option_C_rationale:** headline answer와 `one more person today`라는 exact condition을 한 turn에 먼저 전달한다.
- **answer_explanation:** 임원의 질문에는 먼저 결론이 필요하다. C는 `yes`를 명확히 주면서 오늘 한 명을 추가해야 한다는 정확한 조건도 숨기지 않는다.
- **key_expression:** `The short answer is yes, provided that...`
- **expression_note:** 빠른 답이 필요한 live setting에서 conclusion과 조건을 먼저 제시하는 frame이다.
- **reusable_pattern:** `The short answer is yes, provided that X.`
- **tags:** `headline-answer`, `condition`, `executive`, `meeting`, `concise`

### Answer screen

- **Correct / Incorrect:** 정답은 **C**입니다.
- **Why it works:** C는 결론부터 말하고, 가능 여부를 바꾸는 핵심 조건을 바로 붙입니다. 상세 배경은 필요할 때 이어갈 수 있습니다.
- **Take this with you:** `The short answer is yes, provided that we add one more person today.`
- **save_target:** `The short answer is yes, provided that...`

### Review variant

- **review_scenario:** 임원이 “금요일까지 가능합니까?”라고 묻습니다. 시스템 접근 권한을 오늘 받으면 가능합니다.
- **recall_prompt:** 결론과 조건을 먼저 말해 보세요. **[정답 보기]**
- **response:** `The short answer is yes, provided that we receive system access today.`
- **reusable_pattern:** `The short answer is yes, provided that X.`

---

## QP-012 · Request one agreed set of client comments

- **question_id:** `QP-012`
- **scenario_id:** `IN-021`
- **stage:** `Inbox`
- **question_type:** `Best Revision`
- **difficulty:** `2`
- **scenario_text:** 고객 조직의 세 명이 서로 함께 적용할 수 없는 수정 의견을 따로 보내고 있습니다. 우리 팀에는 고객의 사업 우선순위 중 하나를 대신 선택할 권한이 없으며, 금요일에 다음 버전 작업을 시작할 예정입니다.
- **source_utterance:** `We'll try to incorporate everyone's comments.`
- **prompt:** 이 답장을 가장 적절하게 고친 것은 무엇일까요?

- **A.** Could you send one agreed set of comments by Thursday? We need consolidated direction for the next version.
- **B.** Could you identify by Thursday which comments all three reviewers agree should go into the next version?
- **C.** Could each of you confirm by Thursday which comments should take priority for the next version?

- **correct_option:** `A`
- **distractor_types:** `B = requests only the consensus subset`; `C = requests separate priority decisions`
- **option_A_rationale:** 고객 의견을 거부하지 않으면서 하나의 agreed direction과 필요한 시점을 명확히 요청한다.
- **option_B_rationale:** 모두가 동의한 부분만 찾고 실제로 충돌하는 결정은 남겨 두는 `requests only the consensus subset`이다.
- **option_C_rationale:** 세 이해관계자에게 다시 개별 priority 답변을 요청해 같은 충돌을 반복할 수 있는 `requests separate priority decisions`다.
- **answer_explanation:** 다음 버전에는 고객이 합의한 한 방향이 필요하다. A는 process boundary를 분명히 하면서도 협업 경로를 유지한다.
- **key_expression:** `one agreed set of comments`
- **expression_note:** 여러 이해관계자의 충돌하는 feedback을 하나의 승인된 direction으로 요청할 때 쓴다.
- **reusable_pattern:** `Could you send one agreed set of X by [time]? We need consolidated direction for Y.`
- **tags:** `conflicting-feedback`, `client`, `process-boundary`, `email`, `consolidation`

### Answer screen

- **Correct / Incorrect:** 정답은 **A**입니다.
- **Why it works:** A는 세 의견을 무시하지 않고 고객 측의 합의된 우선순위를 요청합니다. 누가 conflict를 해결해야 하는지도 분명합니다.
- **Contrast:** B = leaves the conflicts undecided · C = asks for more separate answers
- **Take this with you:** `Could you send one agreed set of comments?`
- **save_target:** `one agreed set of comments`

### Review variant

- **review_scenario:** 고객의 법무팀과 마케팅팀이 함께 적용할 수 없는 문구를 요구합니다. 우리 팀은 어느 고객 우선순위를 선택할 권한이 없습니다.
- **recall_prompt:** 하나의 consolidated direction을 요청해 보세요. **[정답 보기]**
- **response:** `Could you send one agreed set of wording changes? We need consolidated direction before preparing the next draft.`
- **reusable_pattern:** `Could you send one agreed set of X? We need consolidated direction before Y.`

---

## QP-013 · Correct the record without a public counter-attack

- **question_id:** `QP-013`
- **scenario_id:** `HI-018`
- **stage:** `Handle It`
- **question_type:** `Best Response`
- **difficulty:** `3`
- **scenario_text:** 고객 회의에서 동료가 지연 원인을 당신 팀의 늦은 검토라고 말했습니다. 기록상 검토는 화요일에 끝났고 지연은 이후 승인 단계에서 시작됐습니다. 회의는 5분 남았고 고객은 오늘 recovery plan을 결정해야 합니다.
- **prompt:** 회의에서 어떻게 대응하는 것이 가장 적절할까요?

- **A.** Our review finished Tuesday, and the delay began during approval. Could the approval team explain what happened there?
- **B.** Let's not spend time on the cause now. We can review the full timeline internally after the client meeting and follow up separately.
- **C.** I need to clarify one point: our review finished Tuesday, and the delay began during approval. Let's focus on recovery.

- **correct_option:** `C`
- **distractor_types:** `A = uses recovery time for root-cause questioning`; `B = allows a material false record`
- **option_A_rationale:** 사실은 바로잡지만 남은 시간을 public root-cause questioning에 사용해 오늘 필요한 recovery decision을 밀어내는 `uses recovery time for root-cause questioning`이다.
- **option_B_rationale:** 갈등은 피하지만 고객 의사결정에 중요한 false record를 남기는 `allows a material false record`다.
- **option_C_rationale:** 사실을 즉시 교정하되 사람을 탓하지 않고 recovery discussion으로 이동한다.
- **answer_explanation:** 침묵하면 잘못된 원인이 공식 기록처럼 남을 수 있고, 원인 공방을 길게 열면 오늘 필요한 recovery decision을 놓친다. C는 timeline을 교정한 뒤 남은 회의 목적을 지킨다.
- **key_expression:** `I need to clarify one point...`
- **expression_note:** socially risky한 상황에서 핵심 사실을 직접 교정하되 대화를 사람 간 blame으로 만들지 않는 시작 표현이다.
- **reusable_pattern:** `I need to clarify one point: X was completed on [date], and the delay began at Y. Let's focus on Z.`
- **tags:** `public-correction`, `responsibility`, `client-meeting`, `timeline`, `recovery`

### Answer screen

- **Correct / Incorrect:** 정답은 **C**입니다.
- **Why it works:** C는 고객에게 중요한 timeline을 즉시 바로잡고, 특정 팀을 공격하는 대신 recovery로 대화를 이동합니다.
- **Contrast:** A = reopens root-cause discussion · B = leaves the false record uncorrected
- **Take this with you:** `I need to clarify one point: our review finished Tuesday.`
- **save_target:** `I need to clarify one point...`

### Review variant

- **review_scenario:** 파트너 회의에서 동료가 파일을 당신 팀이 늦게 보냈다고 말합니다. 기록상 파일은 월요일에 전송됐고 지연은 수신 후 검토 단계에서 발생했습니다. 회의 종료 전 다음 행동을 정해야 합니다.
- **recall_prompt:** 공개적인 blame 없이 기록을 바로잡아 보세요. **[정답 보기]**
- **response:** `I need to clarify one point: our team sent the file Monday, and the delay began during the review stage. Let's focus on the next step.`
- **reusable_pattern:** `I need to clarify one point: X happened on [date], and Y began at Z.`

---

## QP-014 · Name the missing criterion before recommending

- **question_id:** `QP-014`
- **scenario_id:** `SU-029`
- **stage:** `Speak Up`
- **question_type:** `Best Response`
- **difficulty:** `2`
- **scenario_text:** 고객이 두 공급업체 중 하나를 바로 추천해 달라고 합니다. 한 업체는 더 저렴하고 다른 업체는 더 빠르지만, 고객은 예산과 속도 중 무엇이 중요한지 말하지 않았습니다.
- **prompt:** 통화에서 어떻게 답하는 것이 가장 적절할까요?

- **A.** The faster vendor seems like the better choice, so I'd recommend them for now.
- **B.** I can recommend one once I know the priority: staying under budget or delivering sooner. Which matters more?
- **C.** Both vendors meet the requirements, so I don't see a meaningful basis to recommend one over the other.

- **correct_option:** `B`
- **distractor_types:** `A = unsupported recommendation`; `C = ignores a decision-relevant trade-off`
- **option_A_rationale:** decision criterion 없이 속도를 임의로 우선하는 `unsupported recommendation`이다.
- **option_B_rationale:** 추천을 회피하지 않고, 추천을 가능하게 하는 missing criterion을 구체적인 선택지로 요청한다.
- **option_C_rationale:** price와 speed라는 실제 차이가 있는데도 recommendation basis가 없다고 닫는 `ignores a decision-relevant trade-off`다.
- **answer_explanation:** 어느 vendor가 더 좋은지는 고객의 우선순위에 달려 있다. B는 recommendation을 위한 criterion을 명확히 얻는다.
- **key_expression:** `Which matters more?`
- **expression_note:** 두 선택지의 강점이 다를 때 recommendation 전에 decision criterion을 확인하는 질문이다.
- **reusable_pattern:** `I can recommend one once I know whether X or Y is the priority. Which matters more?`
- **tags:** `recommendation`, `decision-criterion`, `client-call`, `trade-off`, `clarification`

### Answer screen

- **Correct / Incorrect:** 정답은 **B**입니다.
- **Why it works:** B는 추천에 필요한 기준을 budget과 speed로 구체화합니다. 정보를 얻은 뒤에는 실제 recommendation을 줄 수 있습니다.
- **Contrast:** A = guesses the priority · C = dismisses the available criterion
- **Take this with you:** `Which matters more: staying under budget or delivering sooner?`
- **save_target:** `I can recommend one once I know whether...`

### Review variant

- **review_scenario:** 고객이 두 software plan 중 하나를 추천해 달라고 합니다. 하나는 저렴하고 다른 하나는 지원 범위가 넓지만 고객의 기준은 모릅니다.
- **recall_prompt:** 추천 전에 missing criterion을 확인해 보세요. **[정답 보기]**
- **response:** `I can recommend one once I know whether price or support coverage is the priority. Which matters more?`
- **reusable_pattern:** `I can recommend one once I know whether X or Y is the priority.`

---

## QP-015 · Tie the delivery time to the missing dependency

- **question_id:** `QP-015`
- **scenario_id:** `IN-032`
- **stage:** `Inbox`
- **question_type:** `Best Revision`
- **difficulty:** `2`
- **scenario_text:** 디자인 파일을 받으면 최종 문서를 하루 안에 만들 수 있지만 파일 도착일은 아직 정해지지 않았습니다. 동료가 최종 문서가 언제 준비되는지 묻습니다.
- **source_utterance:** `The final document should be ready Wednesday.`
- **prompt:** 이 답장을 가장 적절하게 고친 것은 무엇일까요?

- **A.** Once we receive the design file, we can deliver the final document within one business day.
- **B.** We can confirm the delivery date once the design file arrival is scheduled and then share an updated project timeline.
- **C.** The final document will be ready soon after the design file comes in, and we'll keep you updated on timing.

- **correct_option:** `A`
- **distractor_types:** `B = avoids a conditional commitment`; `C = vague timing`
- **option_A_rationale:** 통제할 수 없는 start point와 통제할 수 있는 one-day turnaround를 분리한다.
- **option_B_rationale:** 파일 수신 후 하루라는 알려진 turnaround까지 말하지 않고 모든 timing 답변을 미루는 `avoids a conditional commitment`다.
- **option_C_rationale:** dependency는 말하지만 `soon`으로 turnaround를 모호하게 만드는 `vague timing`이다.
- **answer_explanation:** calendar date를 약속할 근거는 없지만 파일 수신 후 소요 시간은 약속할 수 있다. A는 dependency와 controllable timing을 정확히 연결한다.
- **key_expression:** `Once we receive X, we can deliver Y within Z.`
- **expression_note:** 시작 시점은 외부 dependency에 달려 있지만 turnaround는 통제할 수 있을 때 쓰는 conditional timeline이다.
- **reusable_pattern:** `Once we receive X, we can deliver Y within Z.`
- **tags:** `dependency`, `conditional-timeline`, `messenger`, `commitment`, `best-revision`

### Answer screen

- **Correct / Incorrect:** 정답은 **A**입니다.
- **Why it works:** A는 알 수 없는 도착일을 지어내지 않고, 파일을 받은 뒤 하루라는 확실한 turnaround를 약속합니다.
- **Take this with you:** `Once we receive the design file, we can deliver within one business day.`
- **save_target:** `Once we receive X, we can deliver Y within Z.`

### Review variant

- **review_scenario:** 번역 원고가 언제 올지는 모르지만, 원고를 받으면 검수본을 이틀 안에 보낼 수 있습니다.
- **recall_prompt:** dependency와 controllable turnaround를 연결해 보세요. **[정답 보기]**
- **response:** `Once we receive the translated copy, we can send the reviewed version within two business days.`
- **reusable_pattern:** `Once we receive X, we can deliver Y within Z.`

---

## QP-016 · Refuse “final” while preserving a preliminary option

- **question_id:** `QP-016`
- **scenario_id:** `HI-031`
- **stage:** `Handle It`
- **question_type:** `Tone Check`
- **difficulty:** `2`
- **scenario_text:** 파트너와 공동 보도자료에 초기 결과를 포함하기로 이미 결정했고, 이번 회의에서 해당 결과의 문구를 확정해야 합니다. 파트너는 이를 `final result`로 쓰자고 하지만 표본 검증이 끝나지 않았고, 남은 결과에 따라 수치가 달라질 수 있습니다.
- **prompt:** certainty와 publication boundary를 가장 정확히 표현한 문장은 무엇일까요?

- **A.** We can describe the result now and mention the remaining validation only if someone asks.
- **B.** Let's leave a placeholder for the result and decide on the wording after sample validation is complete.
- **C.** We can't present the result as final, but we can label it preliminary pending sample validation.

- **correct_option:** `C`
- **distractor_types:** `A = hides a material qualification`; `B = postpones the required wording decision`
- **option_A_rationale:** 결과를 공개하면서 현재 validation status를 기본 문구에서 숨기는 `hides a material qualification`이다.
- **option_B_rationale:** 결과 포함은 이미 결정됐고 이번 회의에서 문구를 확정해야 하는데도 placeholder를 두고 결정을 미루는 `postpones the required wording decision`이다.
- **option_C_rationale:** final claim에는 firm boundary를 세우면서 허용 가능한 preliminary disclosure를 제시한다.
- **answer_explanation:** 결과 포함은 이미 결정됐고 이번 회의에서 certainty level에 맞는 문구를 확정해야 한다. C는 `final`을 거절하고 evidence status에 맞는 `preliminary pending validation`을 제공한다.
- **key_expression:** `preliminary pending validation`
- **expression_note:** 결과를 숨기지 않되 검증 상태보다 강하게 주장하지 않도록 certainty를 제한한다.
- **reusable_pattern:** `We can't present X as final, but we can label it preliminary pending Y.`
- **tags:** `publication`, `certainty`, `preliminary`, `boundary`, `partner-meeting`

### Answer screen

- **Correct / Incorrect:** 정답은 **C**입니다.
- **Why it works:** C는 evidence보다 강한 final claim을 거절하면서도 허용 가능한 preliminary communication을 남깁니다.
- **Contrast:** A = hides the qualification · B = postpones the required wording decision
- **Take this with you:** `We can label it preliminary pending validation.`
- **save_target:** `preliminary pending validation`

### Review variant

- **review_scenario:** 성과 수치의 audit이 끝나지 않았고 남은 검증에 따라 값이 달라질 수 있습니다. 팀은 이 수치를 보도자료에서 어떻게 표현할지 결정하고 있습니다.
- **recall_prompt:** final claim은 막고 qualified alternative를 제시해 보세요. **[정답 보기]**
- **response:** `We can't present the figure as final, but we can label it preliminary pending the audit.`
- **reusable_pattern:** `We can't present X as final, but we can label it preliminary pending Y.`

---

## QP-017 · Confirm a multi-part decision without reopening it

- **question_id:** `QP-017`
- **scenario_id:** `SU-014`
- **stage:** `Speak Up`
- **question_type:** `Best Response`
- **difficulty:** `2`
- **scenario_text:** 긴 논의에서 참석자들은 1단계 두 지역 출시와 초기 결과 검토 후 나머지 지역 결정에 대체로 동의했습니다. 다만 서로 다른 표현을 사용했고, 회의 종료 전 의장이 결론을 요약해 달라고 합니다.
- **prompt:** 어떻게 정리하는 것이 가장 적절할까요?

- **A.** So the only decision today is to launch in two regions; nothing else has been agreed.
- **B.** Let me confirm: we launch in two regions first and review the others after the results. Is that our decision?
- **C.** It sounds as though we may start with two regions. Should we go through the options again?

- **correct_option:** `B`
- **distractor_types:** `A = erases the deferred agreement`; `C = reopens a settled discussion`
- **option_A_rationale:** 나머지 지역을 초기 결과 후 다시 검토한다는 합의까지 없었던 것으로 만드는 `erases the deferred agreement`다.
- **option_B_rationale:** now/deferred/review point를 요약하고 참석자에게 explicit confirmation을 요청한다.
- **option_C_rationale:** 합의를 확인하기보다 전체 option discussion을 다시 여는 `reopens settled discussion`이다.
- **answer_explanation:** B는 현재 결정과 나중에 검토할 범위를 분리하고, 한 번의 confirmation question으로 alignment를 확인한다.
- **key_expression:** `Let me confirm... Is that our decision?`
- **expression_note:** 긴 논의 후 decision과 deferred item을 짧게 요약해 final alignment를 얻는 live frame이다.
- **reusable_pattern:** `Let me confirm: X now, and Y after Z. Is that our decision?`
- **tags:** `decision-summary`, `alignment`, `video-call`, `scope`, `meeting-close`

### Answer screen

- **Correct / Incorrect:** 정답은 **B**입니다.
- **Why it works:** B는 두 지역 launch와 나머지 지역 review를 구분해 요약합니다. 합의를 과장하거나 논의를 처음부터 다시 열지 않습니다.
- **Contrast:** A = erases the deferred decision · C = reopens the debate
- **Take this with you:** `Let me confirm: X now, and Y after Z.`
- **save_target:** `Let me confirm... Is that our decision?`

### Review variant

- **review_scenario:** 팀은 세 기능 중 두 개만 이번 release에 넣고, 세 번째 기능은 사용자 feedback 후 다시 보기로 한 듯합니다. 회의 종료 전에 확인해야 합니다.
- **recall_prompt:** current decision과 deferred item을 요약해 보세요. **[정답 보기]**
- **response:** `Let me confirm: we include features A and B now, and revisit C after user feedback. Is that our decision?`
- **reusable_pattern:** `Let me confirm: X now, and Y after Z. Is that our decision?`

---

## QP-018 · Turn “review” into concrete work

- **question_id:** `QP-018`
- **scenario_id:** `IN-001`
- **stage:** `Inbox`
- **question_type:** `Choose the Follow-up`
- **difficulty:** `1`
- **scenario_text:** 다른 팀이 수치 표, 설명 문구, 승인란이 모두 있는 보고서를 보내며 “Could you review this today?”라고만 썼습니다. 세 작업은 담당자와 소요 시간이 서로 다릅니다.
- **prompt:** 가장 유용한 clarification은 무엇일까요?

- **A.** Would you like me to check the figures, revise the wording, or approve the report?
- **B.** Before I begin, would you like a quick review or a detailed review of the report?
- **C.** I'll revise the report and send an updated version today to keep the project moving.

- **correct_option:** `A`
- **distractor_types:** `B = pseudo-clarification`; `C = unnecessary assumption`
- **option_A_rationale:** broad verb `review`를 실제로 다른 세 action category로 분해한다.
- **option_B_rationale:** task type이 아니라 검토 깊이만 물어 broad verb `review`를 그대로 두는 `pseudo-clarification`이다.
- **option_C_rationale:** 필요한 work unit을 확인하지 않고 revision을 선택하는 `unnecessary assumption`이다.
- **answer_explanation:** `review`는 check, revise, approve를 모두 뜻할 수 있다. A는 상대가 action scope를 바로 선택하게 한다.
- **key_expression:** `Would you like me to check X, revise Y, or approve Z?`
- **expression_note:** broad work verb를 deliverable이 다른 구체적인 action으로 바꾸는 clarification frame이다.
- **reusable_pattern:** `Would you like me to check X, revise Y, or approve Z?`
- **tags:** `review`, `scope-clarification`, `email`, `work-unit`, `atlas`

### Answer screen

- **Correct / Incorrect:** 정답은 **A**입니다.
- **Why it works:** A는 `review`가 의미할 수 있는 실제 작업을 구분합니다. 상대는 추가 설명을 길게 쓰지 않고 필요한 범위를 선택할 수 있습니다.
- **Take this with you:** `Would you like me to check, revise, or approve it?`
- **save_target:** `Would you like me to check X, revise Y, or approve Z?`

### Review variant

- **review_scenario:** 동료가 계약서를 “look over”해 달라고 합니다. 숫자 확인인지, 문구 수정인지, 승인 요청인지 알 수 없습니다.
- **recall_prompt:** broad request를 action categories로 나눠 보세요. **[정답 보기]**
- **response:** `Would you like me to check the figures, suggest wording changes, or approve the draft?`
- **reusable_pattern:** `Would you like me to check X, revise Y, or approve Z?`

---

## QP-019 · Respond to a cancellation threat without conceding blindly

- **question_id:** `QP-019`
- **scenario_id:** `HI-025`
- **stage:** `Handle It`
- **question_type:** `Choose the Follow-up`
- **prompt_scope:** `first question`
- **difficulty:** `3`
- **scenario_text:** 반복된 응답 지연에 화난 고객이 계약 취소를 언급합니다. 구체적으로 무엇이 해결돼야 계약을 유지할지는 아직 말하지 않았습니다. 당신은 상업 조건을 확정하는 담당자는 아니지만 운영 recovery plan은 오늘 제안할 수 있습니다.
- **prompt:** 고객에게 가장 먼저 물을 질문은 무엇일까요?

- **A.** Would it help if I asked our commercial team to consider a service credit?
- **B.** What would we need to address first for a recovery plan to be credible to you?
- **C.** Don't you think cancellation is premature before we've discussed what we can change?

- **correct_option:** `B`
- **distractor_types:** `A = premature concession framing`; `C = defensive minimization`
- **option_A_rationale:** 권한을 주장하거나 credit을 약속하지는 않지만, 실제 recovery need를 듣기 전에 대화를 금전 양보로 고정하는 `premature concession framing`이다.
- **option_B_rationale:** 관계 위험을 진지하게 받아들이면서 고객이 가장 먼저 해결돼야 한다고 보는 조건을 확인한다.
- **option_C_rationale:** 고객 판단을 성급하다고 평가해 complaint의 seriousness를 낮추는 `defensive minimization`이다.
- **answer_explanation:** 첫 단계는 concession 가능성을 먼저 띄우거나 고객 판단을 방어하는 일이 아니라 credible recovery의 조건을 듣는 것이다. B는 당일 제안에 필요한 정보를 얻는다.
- **key_expression:** `What would we need to address first...?`
- **expression_note:** 상대가 관계 종료를 언급했을 때 concession 전에 recovery priority를 확인하는 empathetic question이다.
- **reusable_pattern:** `What would we need to address first for X to be credible to you?`
- **tags:** `cancellation-risk`, `recovery`, `first-question`, `client-call`, `authority`

### Answer screen

- **Correct / Incorrect:** 정답은 **B**입니다.
- **Why it works:** B는 cancellation threat를 가볍게 보지 않으면서 concession framing 전에 고객의 recovery condition을 구체화합니다.
- **Contrast:** A = frames a concession too early · C = minimizes the concern
- **Take this with you:** `What would we need to address first for a recovery plan to be credible?`
- **save_target:** `What would we need to address first...?`

### Review variant

- **review_scenario:** 고객이 반복된 일정 변경 때문에 다른 업체를 검토하겠다고 합니다. 구체적인 유지 조건은 아직 듣지 못했으며, 운영 recovery plan은 오늘 제안할 수 있습니다.
- **recall_prompt:** 첫 질문으로 recovery priority를 확인해 보세요. **[정답 보기]**
- **response:** `What would we need to address first for a recovery plan to be credible to you?`
- **reusable_pattern:** `What would we need to address first for X to be credible to you?`

---

## QP-020 · Structure a two-part live answer

- **question_id:** `QP-020`
- **scenario_id:** `SU-038`
- **stage:** `Speak Up`
- **question_type:** `Best Response`
- **difficulty:** `1`
- **scenario_text:** 고객이 “왜 support response가 늦었고, 지금 무엇을 하고 있나요?”라고 묻습니다. 원인은 불완전한 handoff였고, 현재는 두 번째 reviewer를 추가했습니다.
- **prompt:** 두 질문에 가장 명확하게 답하는 response는 무엇일까요?

- **A.** The delay came from an incomplete handoff, and we've identified where the process broke down.
- **B.** The handoff was incomplete, which created a backlog; we're working to improve response times across the remaining requests now.
- **C.** There are two parts to that. First, the handoff was incomplete. Second, we've added another reviewer.

- **correct_option:** `C`
- **distractor_types:** `A = answers only one part`; `B = gives a vague current action`
- **option_A_rationale:** 원인은 설명하지만 현재 action에는 답하지 않는 `answers only one part`다.
- **option_B_rationale:** 원인은 말하지만 현재 조치인 second reviewer를 `working to improve`로 흐리는 `gives a vague current action`이다.
- **option_C_rationale:** signposting으로 cause와 current action을 분리해 두 질문에 바로 답한다.
- **answer_explanation:** 고객은 원인과 현재 행동이라는 두 답을 요구했다. C는 `First / Second` 구조로 빠르게 구분해 전달한다.
- **key_expression:** `There are two parts to that.`
- **expression_note:** 복수 질문을 받았을 때 답의 구조를 먼저 알리고 각 부분을 짧게 처리하는 live response frame이다.
- **reusable_pattern:** `There are two parts to that. First, X. Second, Y.`
- **tags:** `signposting`, `two-part-answer`, `client-call`, `concise`, `spoken-response`

### Answer screen

- **Correct / Incorrect:** 정답은 **C**입니다.
- **Why it works:** C는 cause와 current action을 명시적으로 나눠 고객의 두 질문에 모두 답합니다.
- **Take this with you:** `There are two parts to that. First, X. Second, Y.`
- **save_target:** `There are two parts to that.`

### Review variant

- **review_scenario:** 상사가 “무엇이 잘못됐고, 재발 방지를 위해 무엇을 바꿨나요?”라고 묻습니다. 원인은 누락된 승인이고, 현재는 자동 알림을 추가했습니다.
- **recall_prompt:** 두 부분을 signpost해서 답해 보세요. **[정답 보기]**
- **response:** `There are two parts to that. First, the approval was missed. Second, we've added an automatic reminder.`
- **reusable_pattern:** `There are two parts to that. First, X. Second, Y.`

