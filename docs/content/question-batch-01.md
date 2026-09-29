# Business English Daily Quiz — Question Production Batch 01

**Status:** Product Review Passed  
**Production date:** 2026-09-29  
**Source:** 20 fixed scenarios from the approved Scenario Bank v1, excluding the approved Pilot 20  
**Scope:** First production batch only; the remaining 80 scenarios are not produced here

The fixed UI action is **[내 표현에 저장]**. Each `save_target` is internal metadata for that action. `unique_answer_basis` and `target_customer_choice_reason` are internal production metadata, not learner-facing copy.

---

## QB01-001 · Warn about a risk without declaring a delay

- **question_id:** `QB01-001`
- **scenario_id:** `IN-004`
- **stage:** `Inbox`
- **question_type:** `Best Revision`
- **difficulty:** `2`
- **scenario_text:** 외부 승인이 아직 나오지 않아 금요일 납품이 하루 밀릴 가능성이 있습니다. 지연은 확정되지 않았고 목요일 정오에는 실제 영향을 확인할 수 있습니다. 현재 작성한 업데이트는 다음과 같습니다.
- **source_utterance:** `The delivery will be one day late because approval is still pending. We'll keep you posted.`
- **prompt:** 이 업데이트를 가장 적절하게 고친 것은 무엇일까요?

- **A.** Friday delivery remains on track. If approval is still pending at noon Thursday, we'll reassess and update you.
- **B.** Friday delivery is still possible, but the pending approval puts it at risk. We'll confirm the date by noon Thursday.
- **C.** Friday delivery may move by one day. We'll review the approval status at noon Thursday and update you when the timing is final.

- **correct_option:** `B`
- **distractor_types:** `A = downplays a known risk`; `C = defers the confirmation outcome`
- **option_A_rationale:** 이미 알려진 delivery risk를 `remains on track`으로 축소하고 update도 approval이 계속 pending일 때만 하겠다는 `downplays a known risk`다.
- **option_B_rationale:** 확정되지 않은 risk와 구체적인 confirmation point를 분리해 정확히 전달한다.
- **option_C_rationale:** 목요일 정오에 status를 보겠다고 하지만 그때 delivery date를 확정하지 않고 final timing까지 update를 미루는 `defers the confirmation outcome`이다.
- **option_A_target_customer_choice_reason:** 아직 금요일 가능성이 있으므로 active risk를 강조하지 않는 편이 불필요한 우려를 줄인다고 생각할 수 있다.
- **option_C_target_customer_choice_reason:** 승인 상태를 먼저 검토한 뒤 최종 timing이 정해질 때만 확정적으로 알리는 편이 안전하다고 느낄 수 있다.
- **unique_answer_basis:** decisive fact = delay is unconfirmed and impact will be known by noon Thursday; tested function = distinguish a delivery risk from a confirmed delay while setting a concrete confirmation point.
- **answer_explanation:** B는 금요일 가능성을 닫지 않으면서도 pending approval이 만드는 risk를 숨기지 않는다. 목요일 정오라는 다음 확정 시점도 제공한다.
- **key_expression:** `X is still possible, but Y puts it at risk.`
- **expression_note:** 가능성과 위험을 동시에 전달하되, 어느 쪽도 확정 사실처럼 말하지 않는 frame이다.
- **reusable_pattern:** `X is still possible, but Y puts it at risk. We'll confirm Z by [time].`
- **save_target:** `X is still possible, but Y puts it at risk.`
- **tags:** `delivery-risk`, `uncertainty`, `external-email`, `confirmation-point`, `best-revision`

### Answer screen

- **Correct / Incorrect:** 정답은 **B**입니다.
- **Why it works:** 지연은 아직 확정되지 않았지만 목요일 정오에는 판단할 수 있습니다. B는 risk와 confirmed delay를 구분하고 다음 update point를 줍니다.
- **Contrast:** A = hides the active risk · C = does not confirm the date at the stated checkpoint
- **Take this with you:** `Friday is still possible, but the pending approval puts it at risk.`
- **save_target:** `X is still possible, but Y puts it at risk.`

### Review variant

- **review_scenario:** 보안 승인이 늦어져 월요일 시작 일정에 위험이 생겼지만, 실제 영향은 금요일 오후에 확인됩니다.
- **recall_prompt:** risk와 confirmed change를 구분하고 다음 확인 시점을 말해 보세요. **[정답 보기]**
- **response:** `Monday is still possible, but the pending security approval puts it at risk. We'll confirm the start date by Friday afternoon.`
- **reusable_pattern:** `X is still possible, but Y puts it at risk. We'll confirm Z by [time].`

---

## QB01-002 · Sequence a handoff with follow-up ownership

- **question_id:** `QB01-002`
- **scenario_id:** `IN-008`
- **stage:** `Inbox`
- **question_type:** `Order the Message`
- **difficulty:** `1`
- **scenario_text:** 다음 주 휴가 동안 동료가 고객 주간 보고서를 대신 보냅니다. 최종 초안은 공유 폴더에 있고 금요일 오전 10시에 발송해야 합니다. 발송 후 수치 질문은 동료가 답하고 가격 질문은 pricing team으로 넘겨야 합니다.
- **prompt:** 다음 세 message fragment를 가장 자연스럽고 명확한 순서로 배열한 것은 무엇일까요?

1. `The final draft is in the shared folder.`
2. `Please send that version to the client by 10 a.m. Friday.`
3. `After you send it, please handle questions about the figures and route pricing questions to the pricing team.`

- **A.** `1 → 2 → 3`
- **B.** `2 → 3 → 1`
- **C.** `3 → 1 → 2`

- **correct_option:** `A`
- **distractor_types:** `B = refers to the version before identifying it`; `C = gives post-send ownership before the send action`
- **option_A_rationale:** file location, required action and deadline, post-send ownership 순으로 reference와 시간 관계가 모두 명확하다.
- **option_B_rationale:** `that version`이 어떤 파일인지 밝히기 전에 발송을 지시하는 순서다.
- **option_C_rationale:** `After you send it`이 가리키는 발송 action을 아직 제시하지 않은 채 후속 ownership부터 시작한다.
- **option_B_target_customer_choice_reason:** deadline과 핵심 action을 먼저 쓰는 것이 더 직접적이라고 생각할 수 있다.
- **option_C_target_customer_choice_reason:** 고객 질문 대응이 가장 복잡해 보여 그 지시를 먼저 강조하고 싶을 수 있다.
- **unique_answer_basis:** decisive fact = the file must be identified before `that version`, and the send action must precede `After you send it`; tested function = order message parts so references and handoff ownership resolve in sequence.
- **answer_explanation:** A만 `that version`과 `After you send it`의 선행 내용을 먼저 제시한다. 업무 인계도 file → send → follow-up ownership 순으로 완결된다.
- **key_expression:** `After you send it, please...`
- **expression_note:** main handoff action 뒤의 후속 책임을 별도 단계로 연결한다.
- **reusable_pattern:** `X is in [location]. Please do Y by [time]. After Y, handle Z and route A to B.`
- **save_target:** `After you send it, please...`
- **tags:** `handoff`, `ownership`, `message-order`, `email`, `reference-clarity`

### Answer screen

- **Correct / Incorrect:** 정답은 **A**입니다.
- **Why it works:** 먼저 파일을 특정해야 `that version`이 명확하고, 발송을 말한 뒤에야 `After you send it`이 자연스럽게 이어집니다.
- **Take this with you:** `After you send it, please handle X and route Y to Z.`
- **save_target:** `After you send it, please...`

### Review variant

- **review_scenario:** 동료가 휴가 중인 당신 대신 월요일에 승인 요청을 보내고, 이후 법무 질문은 legal team으로 넘겨야 합니다.
- **recall_prompt:** 자료 위치 → 발송 action → 후속 ownership 순서로 떠올려 보세요. **[정답 보기]**
- **response:** `The approved request is in the project folder. Please send it Monday morning. After you send it, handle schedule questions and route legal questions to the legal team.`
- **reusable_pattern:** `X is in [location]. Please do Y by [time]. After Y, handle Z and route A to B.`

---

## QB01-003 · Make “FYI” operationally clear

- **question_id:** `QB01-003`
- **scenario_id:** `IN-011`
- **stage:** `Inbox`
- **question_type:** `Best Response`
- **difficulty:** `1`
- **scenario_text:** 팀원에게 다음 분기 일정이 바뀔 수 있다는 사실을 미리 공유하려고 합니다. 아직 팀원이 해야 할 일은 없으며, 이전 FYI 메일은 요청으로 오해돼 불필요한 작업이 생겼습니다.
- **prompt:** 어떤 메시지가 목적을 가장 정확히 전달할까요?

- **A.** Please review the possible schedule change and let me know how you plan to adjust next quarter.
- **B.** The schedule may change next quarter, so please keep it in mind as you plan your work.
- **C.** For your awareness, next quarter's schedule may change. No action is needed at this stage.

- **correct_option:** `C`
- **distractor_types:** `A = invents a current action request`; `B = creates an implied planning task`
- **option_A_rationale:** 아직 필요하지 않은 review와 adjustment plan을 요구하는 `invents a current action request`다.
- **option_B_rationale:** 명시적 task는 아니지만 지금 계획을 조정해야 한다는 기대를 만드는 `creates an implied planning task`다.
- **option_C_rationale:** 정보 공유 목적과 현재 action이 없다는 점을 모두 명시한다.
- **option_A_target_customer_choice_reason:** 단순 공유보다 확인과 준비를 함께 요청하는 편이 책임감 있어 보일 수 있다.
- **option_B_target_customer_choice_reason:** 별도 action을 강하게 요구하지 않으면서도 미리 대비하게 하고 싶을 수 있다.
- **unique_answer_basis:** decisive fact = the recipient has no action at this stage and prior FYI messages triggered unnecessary work; tested function = distinguish information sharing from an action request explicitly.
- **answer_explanation:** C는 변화 가능성을 숨기지 않으면서 `No action is needed`로 현재 기대 행동을 닫는다.
- **key_expression:** `No action is needed at this stage.`
- **expression_note:** FYI 메시지가 task로 해석될 가능성을 줄이는 명시적 no-action label이다.
- **reusable_pattern:** `For your awareness, X. No action is needed at this stage.`
- **save_target:** `No action is needed at this stage.`
- **tags:** `fyi`, `action-expectation`, `internal-email`, `information-sharing`, `concise`

### Answer screen

- **Correct / Incorrect:** 정답은 **C**입니다.
- **Why it works:** 지금 필요한 것은 정보 공유뿐입니다. C는 uncertainty를 전달하면서 불필요한 작업을 시작하지 않아도 된다고 명확히 합니다.
- **Contrast:** A = creates a task · B = implies planning action
- **Take this with you:** `No action is needed at this stage.`
- **save_target:** `No action is needed at this stage.`

### Review variant

- **review_scenario:** 조직 개편안이 검토 중이지만 아직 확정된 변경도, 팀이 준비할 일도 없습니다. 팀원에게 가능성만 알려야 합니다.
- **recall_prompt:** 정보 공유와 action request를 분리해 보세요. **[정답 보기]**
- **response:** `For your awareness, the team structure may change. No action is needed at this stage.`
- **reusable_pattern:** `For your awareness, X. No action is needed at this stage.`

---

## QB01-004 · Clarify whether “prepare” includes sending

- **question_id:** `QB01-004`
- **scenario_id:** `IN-018`
- **stage:** `Inbox`
- **question_type:** `Choose the Follow-up`
- **difficulty:** `2`
- **scenario_text:** 상사가 메신저로 “Please prepare the customer update.”라고 요청했습니다. 과거에는 상사 검토 후 발송한 경우와 담당자가 직접 발송한 경우가 모두 있어, 이번 메시지만으로는 발송 권한까지 포함하는지 알 수 없습니다.
- **prompt:** 가장 유용한 확인 질문은 무엇일까요?

- **A.** I'll prepare the customer update and send it directly unless you'd prefer to review it first.
- **B.** Could you clarify whether you want a quick draft or a detailed customer update?
- **C.** Would you like me to draft the customer update for your review, or send it directly?

- **correct_option:** `C`
- **distractor_types:** `A = defaults to acting beyond confirmed authority`; `B = clarifies detail instead of authorization`
- **option_A_rationale:** 상사가 별도로 멈추지 않으면 직접 발송하겠다는 default를 만드는 `acts beyond confirmed authority`다.
- **option_B_rationale:** draft의 상세 수준만 묻고 핵심 ambiguity인 review-before-send 여부를 남기는 `clarifies the wrong dimension`이다.
- **option_C_rationale:** `prepare`가 draft 작성인지 직접 발송까지인지 두 실제 next action으로 구분한다.
- **option_A_target_customer_choice_reason:** 빠르게 진행하면서 상사가 원하면 수정할 기회를 주는 효율적 방식으로 보일 수 있다.
- **option_B_target_customer_choice_reason:** `prepare`의 범위를 문서 완성도 문제로 해석할 수 있다.
- **unique_answer_basis:** decisive fact = both review-first and direct-send workflows have occurred before; tested function = turn a broad action verb into explicit authorization alternatives.
- **answer_explanation:** C는 vague한 `prepare`를 권한이 다른 두 행동으로 풀어 묻는다. 어느 workflow인지 확인하기 전에는 고객 발송을 default로 둘 수 없다.
- **key_expression:** `for your review, or send it directly`
- **expression_note:** draft 권한과 external-send 권한을 한 질문에서 구분한다.
- **reusable_pattern:** `Would you like me to draft X for your review, or send it directly to Y?`
- **save_target:** `Would you like me to draft X for your review, or send it directly?`
- **tags:** `authority`, `prepare`, `messenger`, `upward-communication`, `clarification`

### Answer screen

- **Correct / Incorrect:** 정답은 **C**입니다.
- **Why it works:** `prepare`는 초안 작성과 직접 발송을 모두 뜻할 수 있습니다. C는 권한이 다른 두 next action을 명확히 구분합니다.
- **Contrast:** A = defaults to sending · B = asks about detail, not authority
- **Take this with you:** `Would you like me to draft it for your review, or send it directly?`
- **save_target:** `for your review, or send it directly`

### Review variant

- **review_scenario:** 팀장이 “Please put together the partner note.”라고 했습니다. 팀장 검토용 초안인지 파트너에게 직접 보내는 메시지인지 알 수 없습니다.
- **recall_prompt:** 작성과 발송 권한을 나누어 확인해 보세요. **[정답 보기]**
- **response:** `Would you like me to draft the note for your review, or send it directly to the partner?`
- **reusable_pattern:** `Would you like me to draft X for your review, or send it directly to Y?`

---

## QB01-005 · Correct a date without burying the correction

- **question_id:** `QB01-005`
- **scenario_id:** `IN-022`
- **stage:** `Inbox`
- **question_type:** `Best Revision`
- **difficulty:** `1`
- **scenario_text:** 방금 보낸 메일에 회의 날짜를 화요일이라고 썼지만 실제 일정은 수요일입니다. 상대가 아직 행동하기 전이고 다른 내용은 모두 맞습니다. 이전 메일의 문장은 다음과 같습니다.
- **source_utterance:** `The meeting is Tuesday.`
- **prompt:** 정정 메시지로 가장 적절하게 고친 것은 무엇일까요?

- **A.** Sorry for the confusion in my earlier email about the meeting date.
- **B.** Correction: the meeting is Wednesday, not Tuesday. Sorry for the mix-up.
- **C.** Just to clarify, the meeting schedule has been updated to Wednesday.

- **correct_option:** `B`
- **distractor_types:** `A = apology without the corrected fact`; `C = falsely implies a schedule change`
- **option_A_rationale:** 사과는 하지만 상대가 사용해야 할 정확한 날짜를 주지 않는 `apology without the corrected fact`다.
- **option_B_rationale:** replacement fact를 먼저 명시하고 짧은 apology를 덧붙여, 정정과 관계 관리를 함께 수행한다.
- **option_C_rationale:** 작성자의 오류를 정정하는 상황을 실제 일정이 변경된 것처럼 표현하는 `falsely implies a schedule change`다.
- **option_A_target_customer_choice_reason:** 실수를 했으므로 먼저 충분히 사과하는 것이 관계에 안전하다고 느낄 수 있다.
- **option_C_target_customer_choice_reason:** 자신의 오류를 직접 강조하지 않고 부드럽게 날짜를 바로잡고 싶을 수 있다.
- **unique_answer_basis:** decisive fact = the schedule did not change; only the sender's previous date was wrong; tested function = put an explicit old/new replacement fact first while allowing a brief apology after it.
- **answer_explanation:** B는 replacement fact를 먼저 보여 주고 짧게 사과한다. 사과를 배제하는 것이 아니라, 정확한 날짜가 apology에 묻히지 않게 한다.
- **key_expression:** `Correction: X is Y, not Z.`
- **expression_note:** 작은 factual error에서는 replacement information을 전면에 두고, 필요하면 짧은 apology를 뒤에 붙인다.
- **reusable_pattern:** `Correction: X is Y, not Z.`
- **save_target:** `Correction: X is Y, not Z.`
- **tags:** `self-correction`, `date`, `email`, `concise`, `best-revision`

### Answer screen

- **Correct / Incorrect:** 정답은 **B**입니다.
- **Why it works:** 일정 자체가 바뀐 것이 아니라 이전 날짜가 틀렸습니다. B는 정확한 replacement fact를 먼저 전달한 뒤 짧게 사과합니다.
- **Take this with you:** `Correction: the meeting is Wednesday, not Tuesday. Sorry for the mix-up.`
- **save_target:** `Correction: X is Y, not Z.`

### Review variant

- **review_scenario:** 방금 보낸 메일에 제출 시각을 오후 3시라고 썼지만 실제 시각은 오후 2시입니다. 다른 내용은 맞습니다.
- **recall_prompt:** 정확한 시각을 먼저 정정하고 짧게 사과해 보세요. **[정답 보기]**
- **response:** `Correction: the submission time is 2 p.m., not 3 p.m. Sorry for the mix-up.`
- **reusable_pattern:** `Correction: X is Y, not Z.`

---

## QB01-006 · Route an approval request without losing context

- **question_id:** `QB01-006`
- **scenario_id:** `IN-029`
- **stage:** `Inbox`
- **question_type:** `Best Response`
- **difficulty:** `2`
- **scenario_text:** 해외 동료가 가격표 승인을 요청했습니다. 결정권은 Sales Operations에 있고, 당신은 요청 배경을 알고 있으며 그 팀의 승인 담당자를 바로 연결할 수 있습니다.
- **prompt:** 어떻게 답하는 것이 가장 적절할까요?

- **A.** Sales Operations owns this approval, so I'm looping in the approver with the request and background below.
- **B.** I can approve the price list after I review the supporting figures and confirm that everything is complete.
- **C.** This sits with Sales Operations rather than my team. Please contact the approver directly and resend the request background.

- **correct_option:** `A`
- **distractor_types:** `B = promises outside authority`; `C = deflects without routing or context`
- **option_A_rationale:** 실제 owner를 명시하고 담당자를 context와 함께 대화에 연결한다.
- **option_B_rationale:** 자신에게 없는 승인 권한을 행사하겠다는 `promises outside authority`다.
- **option_C_rationale:** owner는 알려 주지만 발신자가 보존할 수 있는 context를 요청자에게 다시 보내게 하는 `deflects without routing or context`다.
- **option_B_target_customer_choice_reason:** 자료 내용을 잘 알고 있으므로 실질적으로 승인까지 처리할 수 있다고 생각할 수 있다.
- **option_C_target_customer_choice_reason:** 잘못 온 요청은 담당 부서로 안내하면 역할이 끝난다고 볼 수 있다.
- **unique_answer_basis:** decisive fact = Sales Operations owns approval, and the speaker both knows the request context and can connect its approver directly; tested function = preserve that context through a warm handoff rather than overstepping or making the requester resend it.
- **answer_explanation:** A는 권한을 넘지 않으면서도 요청자를 혼자 다시 시작하게 하지 않는다. `owns this approval`과 `looping in`이 owner와 handoff를 동시에 보여 준다.
- **key_expression:** `X owns this approval, so I'm looping in Y.`
- **expression_note:** 결정권을 명확히 하면서 context가 이어지는 warm handoff를 만든다.
- **reusable_pattern:** `X owns this decision, so I'm looping in Y with the context below.`
- **save_target:** `X owns this decision, so I'm looping in Y.`
- **tags:** `ownership-routing`, `authority`, `global-colleague`, `email`, `warm-handoff`

### Answer screen

- **Correct / Incorrect:** 정답은 **A**입니다.
- **Why it works:** A는 승인 권한을 넘지 않으면서 담당자를 바로 연결하고 기존 context를 함께 보냅니다. 요청자가 배경을 다시 제출할 필요가 없습니다.
- **Contrast:** B = exceeds authority · C = sends the requester away
- **Take this with you:** `Sales Operations owns this approval, so I'm looping in the approver.`
- **save_target:** `X owns this decision, so I'm looping in Y.`

### Review variant

- **review_scenario:** 동료가 당신에게 채용 인원 승인을 요청했습니다. People Operations가 결정권자이며, 당신은 요청 사유를 알고 있고 승인 담당자를 바로 연결할 수 있습니다.
- **recall_prompt:** 권한을 넘지 않으면서 담당자에게 context와 함께 연결해 보세요. **[정답 보기]**
- **response:** `People Operations owns this approval, so I'm looping in the approver with the context below.`
- **reusable_pattern:** `X owns this decision, so I'm looping in Y with the context below.`

---

## QB01-007 · Close a resolved vendor loop

- **question_id:** `QB01-007`
- **scenario_id:** `IN-040`
- **stage:** `Inbox`
- **question_type:** `Best Revision`
- **difficulty:** `1`
- **scenario_text:** vendor가 수정 파일을 보냈고 내부 검토 결과 문제가 해결됐습니다. 추가 작업이나 회신은 필요 없으며 ticket을 닫을 수 있습니다. 현재 작성한 답장은 다음과 같습니다.
- **source_utterance:** `Thanks, we received the revised file.`
- **prompt:** 이 답장을 가장 적절하게 고친 것은 무엇일까요?

- **A.** Thanks—we've reviewed the revised file, and the issue appears resolved. We'll keep the ticket open for now.
- **B.** We've reviewed the revised file, and the issue is resolved. Please confirm that no further action is needed.
- **C.** We've reviewed the revised file, and the issue is resolved. No further action is needed.

- **correct_option:** `C`
- **distractor_types:** `A = keeps a resolved ticket open`; `B = requests unnecessary confirmation`
- **option_A_rationale:** review와 resolution을 언급하지만 `appears`로 약화하고 닫을 수 있는 ticket을 계속 열어 두는 `keeps a resolved ticket open`이다.
- **option_B_rationale:** speaker가 이미 no-action status를 알고 있는데 vendor에게 다시 확인을 요구하는 `requests unnecessary confirmation`이다.
- **option_C_rationale:** review 완료, resolution, no-action status를 짧게 닫는다.
- **option_A_target_customer_choice_reason:** 예상하지 못한 문제가 다시 생길 수 있으므로 ticket을 잠시 더 열어 두는 편이 신중해 보일 수 있다.
- **option_B_target_customer_choice_reason:** 양쪽이 no-action status를 확인해야 closure가 확실해진다고 생각할 수 있다.
- **unique_answer_basis:** decisive fact = review is complete, the issue is resolved, and the vendor has no remaining action; tested function = close an action loop explicitly rather than acknowledge receipt only.
- **answer_explanation:** 세 선택지 모두 review와 resolution을 언급하지만, C만 불필요한 open status나 확인 요청 없이 action loop를 닫는다.
- **key_expression:** `No further action is needed.`
- **expression_note:** ticket이나 요청이 완전히 종료됐음을 상대가 추측하지 않게 한다.
- **reusable_pattern:** `We've reviewed X, and the issue is resolved. No further action is needed.`
- **save_target:** `No further action is needed.`
- **tags:** `closure`, `vendor`, `email`, `resolution`, `best-revision`

### Answer screen

- **Correct / Incorrect:** 정답은 **C**입니다.
- **Why it works:** 파일을 받았다는 말만으로는 ticket이 끝났는지 알 수 없습니다. C는 해결과 no-action status를 명시합니다.
- **Take this with you:** `The issue is resolved. No further action is needed.`
- **save_target:** `No further action is needed.`

### Review variant

- **review_scenario:** 파트너가 수정한 참석자 명단을 보냈고 검토 결과 모든 오류가 해결됐습니다. 더 요청할 사항은 없습니다.
- **recall_prompt:** 해결과 closure를 분명하게 알려 보세요. **[정답 보기]**
- **response:** `We've reviewed the updated list, and the issue is resolved. No further action is needed.`
- **reusable_pattern:** `We've reviewed X, and the issue is resolved. No further action is needed.`

---

## QB01-008 · Correct a decision-driving number immediately

- **question_id:** `QB01-008`
- **scenario_id:** `SU-005`
- **stage:** `Speak Up`
- **question_type:** `Best Response`
- **difficulty:** `2`
- **scenario_text:** 회의에서 발표자가 비용 증가율을 18%라고 말했지만 승인된 최종 표에는 8%로 기록돼 있습니다. 참석자들은 지금 그 수치를 기준으로 예산 결정을 하려 하며, 당신은 최종 표를 바로 보여 줄 수 있습니다.
- **prompt:** 회의에서 어떻게 말하는 것이 가장 적절할까요?

- **A.** The approved table shows 8%, not 18%, but we can correct the budget after the meeting.
- **B.** Can I correct one number? The approved table shows 8%, not 18%.
- **C.** The approved table shows 8%, not 18%, so let's stop and fix the presentation before continuing.

- **correct_option:** `B`
- **distractor_types:** `A = delays a material correction`; `C = derails the decision unnecessarily`
- **option_A_rationale:** 정확한 source와 number를 알고도 budget correction을 회의 후로 미루는 `delays a material correction`이다.
- **option_B_rationale:** 필요한 순간에 정확한 수치와 authoritative source를 짧고 직접적으로 제시한다.
- **option_C_rationale:** 정확한 수치를 제시하지만 presentation 수정이 끝날 때까지 필요한 budget discussion까지 멈추는 `derails the decision unnecessarily`다.
- **option_A_target_customer_choice_reason:** 수치는 지금 밝혀도 실제 budget correction은 회의 후 처리하는 편이 흐름을 덜 방해한다고 생각할 수 있다.
- **option_C_target_customer_choice_reason:** 잘못된 자료를 사용한 회의는 즉시 중단해야 한다고 판단할 수 있다.
- **unique_answer_basis:** decisive fact = the approved figure is available and the meeting is about to use the wrong number; tested function = make a concise factual interruption with the authoritative figure.
- **answer_explanation:** B는 사람을 평가하지 않고 decision-driving fact만 바로잡는다. 근거가 바로 있으므로 회의 후로 미룰 이유도, 전체 논의를 중단할 이유도 없다.
- **key_expression:** `Can I correct one number?`
- **expression_note:** 회의 흐름을 최소한으로 끊으면서 material fact를 즉시 교정한다.
- **reusable_pattern:** `Can I correct one number? The approved figure is X, not Y.`
- **save_target:** `Can I correct one number?`
- **tags:** `factual-correction`, `meeting`, `upward-communication`, `evidence`, `directness`

### Answer screen

- **Correct / Incorrect:** 정답은 **B**입니다.
- **Why it works:** 예산 결정 전에 8%라는 승인 수치를 바로잡아야 합니다. B는 공격 없이 정확한 source와 number를 즉시 제시합니다.
- **Contrast:** A = waits too long · C = stops more work than necessary
- **Take this with you:** `Can I correct one number? The approved figure is 8%, not 18%.`
- **save_target:** `Can I correct one number?`

### Review variant

- **review_scenario:** 회의에서 예상 사용자 수를 50,000명이라고 말했지만 승인된 forecast는 15,000명입니다. 이 수치로 서버 용량을 정하려 합니다.
- **recall_prompt:** 사람을 공격하지 않고 핵심 수치를 즉시 바로잡아 보세요. **[정답 보기]**
- **response:** `Can I correct one number? The approved forecast is 15,000 users, not 50,000.`
- **reusable_pattern:** `Can I correct one number? The approved figure is X, not Y.`

---

## QB01-009 · Agree with a condition still visible

- **question_id:** `QB01-009`
- **scenario_id:** `SU-006`
- **stage:** `Speak Up`
- **question_type:** `Tone Check`
- **difficulty:** `1`
- **scenario_text:** 외부 파트너가 공동 발표를 제안했습니다. 방향에는 동의하지만 발표 전에 양사의 법무 검토가 완료돼야 하며, 검토 없이는 진행할 권한이 없습니다.
- **prompt:** 현재 입장과 조건을 가장 정확히 표현한 문장은 무엇일까요?

- **A.** I'm on board, provided that both legal reviews are completed before the presentation.
- **B.** I'm on board with the joint presentation, and we can sort out the legal review afterward.
- **C.** I can't agree to the joint presentation because the legal reviews aren't complete yet.

- **correct_option:** `A`
- **distractor_types:** `B = sounds like unconditional agreement`; `C = rejects a viable conditional proposal`
- **option_A_rationale:** support를 분명히 하면서 진행 권한의 선행 조건을 `provided that`으로 유지한다.
- **option_B_rationale:** agreement를 먼저 확정하고 필수 검토를 발표 후로 미루는 `sounds like unconditional agreement`다.
- **option_C_rationale:** 검토 완료 후 가능한 제안을 현재 불가능하다는 이유로 전면 거절하는 `rejects a viable conditional proposal`다.
- **option_B_target_customer_choice_reason:** 관계를 위해 먼저 동의하고 세부 절차는 나중에 처리하는 편이 협력적으로 보일 수 있다.
- **option_C_target_customer_choice_reason:** 권한 조건이 충족되지 않았으므로 지금은 동의하면 안 된다고 생각할 수 있다.
- **unique_answer_basis:** decisive fact = the proposal is acceptable only after both legal reviews; tested function = express support and a true condition in the same turn with `provided that`.
- **answer_explanation:** A는 방향에 동의한다는 점과 반드시 먼저 끝나야 할 조건을 동시에 보존한다. full yes도 blanket no도 아니다.
- **key_expression:** `I'm on board, provided that...`
- **expression_note:** 지지와 선행 조건을 한 문장에 결합하는 conditional alignment 표현이다.
- **reusable_pattern:** `I'm on board, provided that X is completed before Y.`
- **save_target:** `I'm on board, provided that...`
- **tags:** `conditional-agreement`, `partner`, `video-call`, `authority`, `alignment`

### Answer screen

- **Correct / Incorrect:** 정답은 **A**입니다.
- **Why it works:** 공동 발표에는 동의할 수 있지만 법무 검토는 선행 조건입니다. A는 support와 condition을 어느 쪽도 흐리지 않습니다.
- **Contrast:** B = full agreement · C = unnecessary rejection
- **Take this with you:** `I'm on board, provided that both reviews are completed first.`
- **save_target:** `I'm on board, provided that...`

### Review variant

- **review_scenario:** 파트너의 공동 설문 제안에는 동의하지만, 발송 전에 양사의 개인정보 문구 승인이 필요합니다.
- **recall_prompt:** 방향을 지지하면서 선행 조건을 붙여 보세요. **[정답 보기]**
- **response:** `I'm on board, provided that both privacy notices are approved before the survey goes out.`
- **reusable_pattern:** `I'm on board, provided that X is completed before Y.`

---

## QB01-010 · Take thirty seconds instead of guessing

- **question_id:** `QB01-010`
- **scenario_id:** `SU-009`
- **stage:** `Speak Up`
- **question_type:** `Best Response`
- **difficulty:** `1`
- **scenario_text:** 화상회의에서 예상하지 못한 비용 추정 질문을 받았습니다. 정확한 수치는 메모를 확인하면 30초 안에 답할 수 있지만 지금 기억만으로 말하면 틀릴 수 있습니다.
- **prompt:** 어떻게 답하는 것이 가장 적절할까요?

- **A.** I don't have the figure right now, so I'll come back to that after the meeting.
- **B.** It's roughly 15%, although I'd need to check my notes to confirm the exact number.
- **C.** Give me a moment to check my notes—I want to give you the right figure.

- **correct_option:** `C`
- **distractor_types:** `A = unnecessary long deferral`; `B = guesses before verification`
- **option_A_rationale:** 회의 중 30초면 확인할 수 있는 답을 회의 후로 넘기는 `unnecessary long deferral`이다.
- **option_B_rationale:** 확인이 필요한 숫자를 먼저 quote하는 `guesses before verification`이다.
- **option_C_rationale:** 짧은 pause의 이유를 알리고 정확한 답을 위해 발언권을 유지한다.
- **option_A_target_customer_choice_reason:** 모르는 숫자를 즉석에서 다루기보다 회의 후 정확히 답하는 편이 안전해 보일 수 있다.
- **option_B_target_customer_choice_reason:** 대략적인 방향이라도 즉시 답하면 회의 흐름에 도움이 된다고 느낄 수 있다.
- **unique_answer_basis:** decisive fact = the exact figure is available within 30 seconds; tested function = hold the floor for a brief verification instead of guessing or deferring the question.
- **answer_explanation:** C는 질문을 피하지 않고 정확한 답을 위해 필요한 짧은 시간을 확보한다. `Give me a moment`는 회의 후 follow-up과 다른 즉시 확인 신호다.
- **key_expression:** `Give me a moment to check that.`
- **expression_note:** live setting에서 짧은 확인 시간을 자연스럽게 확보한다.
- **reusable_pattern:** `Give me a moment to check X—I want to give you the right Y.`
- **save_target:** `Give me a moment to check that.`
- **tags:** `thinking-time`, `live-response`, `video-call`, `accuracy`, `concise`

### Answer screen

- **Correct / Incorrect:** 정답은 **C**입니다.
- **Why it works:** 정확한 수치는 30초 안에 확인할 수 있습니다. C는 추측하지 않으면서 질문에도 바로 대응합니다.
- **Take this with you:** `Give me a moment to check that—I want to give you the right figure.`
- **save_target:** `Give me a moment to check that.`

### Review variant

- **review_scenario:** 회의에서 지난달 전환율을 묻습니다. dashboard를 열면 바로 확인되지만 기억만으로는 확실하지 않습니다.
- **recall_prompt:** 짧은 확인 시간을 확보해 보세요. **[정답 보기]**
- **response:** `Give me a moment to check the dashboard—I want to give you the right figure.`
- **reusable_pattern:** `Give me a moment to check X—I want to give you the right Y.`

---

## QB01-011 · Invite the expert through a specific entry point

- **question_id:** `QB01-011`
- **scenario_id:** `SU-017`
- **stage:** `Speak Up`
- **question_type:** `Best Response`
- **difficulty:** `1`
- **scenario_text:** 회의에서 데이터 품질 질문이 나왔습니다. 조용히 있던 미나는 검증을 직접 수행해 발견된 오류를 설명할 수 있는 유일한 참석자지만, 수정 방안이나 담당 팀은 검토하지 않았습니다.
- **prompt:** 미나에게 어떻게 발언을 요청하는 것이 가장 적절할까요?

- **A.** Mina, you ran the validation. What is the fix, and who owns it?
- **B.** Mina, could you walk us through what you found in the validation?
- **C.** Does anyone have anything to add about the data-quality question?

- **correct_option:** `B`
- **distractor_types:** `A = asks beyond the known work scope`; `C = generic invitation with no clear entry point`
- **option_A_rationale:** 미나가 검토하지 않은 수정안과 담당 팀을 이미 아는 것처럼 답하게 하는 `asks beyond the known work scope`다.
- **option_B_rationale:** 미나의 실제 경험을 근거로 구체적으로 설명할 범위를 제시한다.
- **option_C_rationale:** 누구에게 어떤 내용을 요청하는지 없어 실제 expert가 발언하지 않을 수 있는 `generic invitation`이다.
- **option_A_target_customer_choice_reason:** 검증을 수행한 사람이 오류의 해결책과 적절한 owner도 가장 잘 알 것이라고 생각할 수 있다.
- **option_C_target_customer_choice_reason:** 특정인을 지목하지 않는 편이 덜 부담스럽고 포용적으로 보일 수 있다.
- **unique_answer_basis:** decisive fact = Mina can explain the validation findings but did not assess remediation or ownership; tested function = invite contribution within the person's known work scope and give a specific entry point.
- **answer_explanation:** B는 미나가 직접 확인한 findings로 요청 범위를 한정한다. A처럼 검토하지 않은 수정안과 ownership까지 맡기지 않고, C처럼 expert의 진입점을 놓치지도 않는다.
- **key_expression:** `Could you walk us through what you found?`
- **expression_note:** 전문성을 존중하면서 설명 범위를 자연스럽게 제시한다.
- **reusable_pattern:** `[Name], could you walk us through what you found in X?`
- **save_target:** `Could you walk us through what you found?`
- **tags:** `participation`, `expertise`, `meeting`, `team-member`, `targeted-invitation`

### Answer screen

- **Correct / Incorrect:** 정답은 **B**입니다.
- **Why it works:** 미나는 검증 결과는 설명할 수 있지만 수정안과 owner는 검토하지 않았습니다. B는 요청을 확인된 업무 범위에 맞춥니다.
- **Contrast:** A = asks outside her work scope · C = gives no entry point
- **Take this with you:** `Could you walk us through what you found in the validation?`
- **save_target:** `Could you walk us through what you found?`

### Review variant

- **review_scenario:** 보안 검토 질문이 나왔고 준호는 해당 테스트의 발견 사항은 설명할 수 있지만 remediation plan은 검토하지 않았습니다. 회의에서 아직 발언하지 않았습니다.
- **recall_prompt:** 전문성과 구체적인 설명 범위를 연결해 발언을 요청해 보세요. **[정답 보기]**
- **response:** `Junho, could you walk us through what you found in the security test?`
- **reusable_pattern:** `[Name], could you walk us through what you found in X?`

---

## QB01-012 · Turn uncertainty into a bounded pilot

- **question_id:** `QB01-012`
- **scenario_id:** `SU-022`
- **stage:** `Speak Up`
- **question_type:** `Best Response`
- **difficulty:** `2`
- **scenario_text:** 외부 파트너와 새로운 협업 방식을 전국에 적용할지 논의하고 있지만 실제 운영 데이터가 없습니다. 앞으로 4주 동안 실제로 운영해 볼 수 있는 범위는 한 지역뿐입니다.
- **prompt:** 화상회의에서 무엇을 제안하는 것이 가장 적절할까요?

- **A.** One region for four weeks won't give us enough evidence, so let's postpone the rollout discussion until broader operating data is available.
- **B.** Could we test this in one region for four weeks, then review the evidence before a national rollout?
- **C.** Let's approve the national rollout now and use the first region's four-week results to adjust the model as we go.

- **correct_option:** `B`
- **distractor_types:** `A = indefinite postponement despite an available pilot`; `C = unsupported full commitment`
- **option_A_rationale:** 실행 가능한 한 지역·4주 pilot을 evidence source로 쓰지 않고, 범위나 시점이 없는 broader data를 기다리자는 `indefinite postponement despite an available pilot`이다.
- **option_B_rationale:** 이용 가능한 범위와 기간을 bounded experiment로 전환하고 national decision 전 review point를 만든다.
- **option_C_rationale:** 첫 지역의 evidence를 보기 전에 national rollout부터 승인하는 `unsupported full commitment`다.
- **option_A_target_customer_choice_reason:** 한 지역만으로는 national rollout을 판단하기에 표본이 좁다고 보고 broader data를 기다리는 편이 안전하다고 생각할 수 있다.
- **option_C_target_customer_choice_reason:** 실제 환경에서 빨리 실행해야 유용한 데이터를 얻을 수 있다고 생각할 수 있다.
- **unique_answer_basis:** decisive fact = no operating data exists, while the next four weeks permit operation in only one region; tested function = turn those constraints into a bounded test and evidence review before a national commitment.
- **answer_explanation:** B는 지금 가능한 한 지역·4주 운영을 evidence-producing pilot으로 사용하고 national commitment 전에 review point를 둔다. A는 실행 가능한 학습 경로를 버린 채 기한 없는 broader data를 기다리고, C는 evidence를 보기 전에 전국 적용을 승인한다.
- **key_expression:** `Could we test X in Y for [period], then review the evidence?`
- **expression_note:** 큰 결정을 즉시 확정하지 않으면서도 학습 가능한 next step을 제안한다.
- **reusable_pattern:** `Could we test X in Y for [period], then review the evidence before Z?`
- **save_target:** `Could we test X, then review the evidence before Y?`
- **tags:** `pilot`, `uncertainty`, `partner`, `video-call`, `proposal`

### Answer screen

- **Correct / Incorrect:** 정답은 **B**입니다.
- **Why it works:** 필요한 것은 즉시 전국 적용하거나 무기한 미루는 일이 아닙니다. B는 제한된 범위와 기간을 evidence review가 있는 test로 바꿉니다.
- **Contrast:** A = indefinite postponement · C = commits before evidence
- **Take this with you:** `Could we test this in one region for four weeks, then review the evidence?`
- **save_target:** `Could we test X, then review the evidence before Y?`

### Review variant

- **review_scenario:** 새 고객 onboarding 방식을 전 부서에 적용할지 논의 중이지만 효과 데이터가 없습니다. 앞으로 한 달 동안 실제로 운영할 수 있는 범위는 한 팀뿐입니다.
- **recall_prompt:** 큰 commitment 대신 범위와 review point가 있는 pilot을 제안해 보세요. **[정답 보기]**
- **response:** `Could we test this with one team for a month, then review the evidence before a company-wide rollout?`
- **reusable_pattern:** `Could we test X in Y for [period], then review the evidence before Z?`

---

## QB01-013 · Disagree without hiding behind agreement

- **question_id:** `QB01-013`
- **scenario_id:** `SU-027`
- **stage:** `Speak Up`
- **question_type:** `Tone Check`
- **difficulty:** `2`
- **scenario_text:** 동료는 support 문의가 줄었다고 말하지만, 데이터상 전체 문의량은 같습니다. 문의가 email에서 chat으로 이동했을 뿐이며, 다음 달 staffing 결정에 필요한 채널별 업무량은 아직 비교하지 않았습니다.
- **prompt:** 회의에서 데이터에 근거한 이견을 가장 정확히 표현한 문장은 무엇일까요?

- **A.** I agree that demand looks lower, although chat volume may be worth watching before we reduce staffing.
- **B.** Email volume is down and chat volume is up, so we should keep staffing exactly as it is.
- **C.** I see it differently. The total hasn't fallen; it has shifted from email to chat.

- **correct_option:** `C`
- **distractor_types:** `A = agreement language obscures the disagreement`; `B = draws an unsupported staffing conclusion`
- **option_A_rationale:** 실제로는 전체 demand 감소에 동의하지 않으면서 `I agree`로 핵심 position을 흐리는 `agreement language obscures the disagreement`다.
- **option_B_rationale:** channel별 workload를 평가하지 않은 채 현재 staffing을 그대로 유지하자는 결론으로 뛰는 `draws an unsupported staffing conclusion`이다.
- **option_C_rationale:** 이견을 명시하고 total과 channel shift라는 두 확인 사실을 짧게 제시한다.
- **option_A_target_customer_choice_reason:** 먼저 동의하면 이견이 덜 공격적으로 들릴 것이라고 생각할 수 있다.
- **option_B_target_customer_choice_reason:** 전체 문의량이 같으므로 staffing도 그대로 유지하는 것이 가장 안전하다고 생각할 수 있다.
- **unique_answer_basis:** decisive fact = total demand is unchanged and only the channel mix shifted, while the staffing effect has not yet been determined; tested function = signal real disagreement and correct the evidence without adding an unsupported staffing decision.
- **answer_explanation:** C는 실제 이견과 확인된 channel shift만 정확히 말한다. 현재 데이터만으로 staffing을 유지하자는 결론까지 만들지 않는다.
- **key_expression:** `I see it differently.`
- **expression_note:** 거짓 agreement 없이 이견을 열고 바로 evidence로 이동한다.
- **reusable_pattern:** `I see it differently. X hasn't changed; it has shifted from Y to Z.`
- **save_target:** `I see it differently.`
- **tags:** `disagreement`, `evidence`, `staffing`, `video-call`, `directness`

### Answer screen

- **Correct / Incorrect:** 정답은 **C**입니다.
- **Why it works:** 전체 문의는 줄지 않았습니다. C는 이견을 분명히 밝힌 뒤 email에서 chat으로 이동한 사실을 정확히 제시합니다.
- **Contrast:** A = sounds like agreement · B = adds an unsupported staffing decision
- **Take this with you:** `I see it differently. The total hasn't fallen; it has shifted.`
- **save_target:** `I see it differently.`

### Review variant

- **review_scenario:** 동료는 매출이 줄었다고 말하지만 총매출은 같고 판매가 retail에서 online으로 이동했습니다. 채널 예산 결정 전에 바로잡아야 합니다.
- **recall_prompt:** 거짓 동의 없이 evidence로 이견을 말해 보세요. **[정답 보기]**
- **response:** `I see it differently. Total sales haven't fallen; they've shifted from retail to online.`
- **reusable_pattern:** `I see it differently. X hasn't changed; it has shifted from Y to Z.`

---

## QB01-014 · Close with decisions before open items

- **question_id:** `QB01-014`
- **scenario_id:** `SU-040`
- **stage:** `Speak Up`
- **question_type:** `Order the Message`
- **difficulty:** `1`
- **scenario_text:** 회의에서 출시일을 5월 15일로 옮기기로 결정했습니다. 가격 정보와 support estimate는 아직 미확인이며 project lead가 내일 정오까지 두 항목을 확인합니다. 그 전에는 전체 계획이 완전히 확정된 것이 아닙니다.
- **prompt:** 다음 closing fragments를 가장 명확한 순서로 배열한 것은 무엇일까요?

1. `We've decided to move the launch to 15 May.`
2. `Two items remain open before that plan is fully confirmed: the pricing input and support estimate.`
3. `The project lead will confirm both by noon tomorrow.`

- **A.** `1 → 2 → 3`
- **B.** `2 → 1 → 3`
- **C.** `1 → 3 → 2`

- **correct_option:** `A`
- **distractor_types:** `B = uses an unclear backward reference`; `C = references both before naming the two items`
- **option_A_rationale:** decided item을 먼저 제시한 뒤 `that plan`, 두 open item, `both`가 순서대로 명확한 referent를 갖는다.
- **option_B_rationale:** `that plan`이 아직 소개되지 않아 무엇이 완전히 확정되지 않았는지 처음에 모호하다.
- **option_C_rationale:** `both`가 가리키는 두 항목을 말하기 전에 owner와 deadline을 제시한다.
- **option_B_target_customer_choice_reason:** unresolved risk를 먼저 말하면 회의 종료 시 주의사항이 더 강조된다고 생각할 수 있다.
- **option_C_target_customer_choice_reason:** decision 직후 owner와 deadline을 바로 붙이는 편이 action-oriented로 보일 수 있다.
- **unique_answer_basis:** decisive fact = one decision is settled, two named items remain open, and one owner/date applies to both; tested function = sequence closure so backward references and status hierarchy are unambiguous.
- **answer_explanation:** A만 decision → open items → owner/deadline 순으로 `that plan`과 `both`의 referent를 먼저 제공합니다.
- **key_expression:** `Two items remain open before that plan is fully confirmed.`
- **expression_note:** 결정된 것과 아직 열린 것을 같은 status처럼 섞지 않고 구분한다.
- **reusable_pattern:** `We've decided X. Y remains open before the plan is final. Z will confirm it by [time].`
- **save_target:** `X remains open before the plan is final.`
- **tags:** `meeting-close`, `open-items`, `message-order`, `ownership`, `alignment`

### Answer screen

- **Correct / Incorrect:** 정답은 **A**입니다.
- **Why it works:** 결정 사항을 먼저 말한 뒤 open items와 owner를 연결해야 status와 reference가 모두 명확합니다.
- **Take this with you:** `We've decided X. Two items remain open before the plan is final.`
- **save_target:** `X remains open before the plan is final.`

### Review variant

- **review_scenario:** 회의에서 공급업체 A를 선택했습니다. 계약 시작일은 아직 열려 있고 contract owner가 금요일까지 확인합니다.
- **recall_prompt:** decision → open item → owner/date 순서로 정리해 보세요. **[정답 보기]**
- **response:** `We've decided to use vendor A. The contract start date remains open before the plan is final. The contract owner will confirm it by Friday.`
- **reusable_pattern:** `We've decided X. Y remains open before the plan is final. Z will confirm it by [time].`

---

## QB01-015 · Announce a confirmed delay with real choices

- **question_id:** `QB01-015`
- **scenario_id:** `HI-005`
- **stage:** `Handle It`
- **question_type:** `Best Response`
- **difficulty:** `2`
- **scenario_text:** 핵심 부품 수급 실패로 금요일 전체 납품은 불가능해졌습니다. 금요일에는 일부 물량만 출고할 수 있고, 나머지까지 모두 준비되는 가장 빠른 날은 다음 화요일입니다.
- **prompt:** 고객에게 어떻게 알리는 것이 가장 적절할까요?

- **A.** Friday delivery may still be possible. If not, we'll send part Friday and the rest Tuesday.
- **B.** The full order won't be ready Friday. Would you prefer part Friday and the rest Tuesday, or everything together Tuesday?
- **C.** The full order won't be ready Friday, so we'll split the shipment between Friday and Tuesday rather than wait for everything.

- **correct_option:** `B`
- **distractor_types:** `A = understates a confirmed delay`; `C = chooses a recovery option for the client`
- **option_A_rationale:** 이미 불가능한 Friday full delivery를 여전히 가능하다고 말해 confirmed delay를 risk처럼 약화하는 `understates a confirmed delay`다.
- **option_B_rationale:** confirmed bad news를 직접 전달하고 operational capabilities를 고객이 선택할 수 있는 두 recovery option으로 구성한다.
- **option_C_rationale:** 두 feasible schedule을 이해하고도 고객 선호를 확인하지 않은 채 split delivery를 확정하는 `chooses a recovery option for the client`다.
- **option_A_target_customer_choice_reason:** 일부 물량을 금요일 보낼 수 있으므로 original Friday commitment도 아직 살릴 수 있다고 표현하고 싶을 수 있다.
- **option_C_target_customer_choice_reason:** 일부라도 금요일에 받는 편이 고객에게 당연히 더 유리하다고 보고 빠른 split delivery를 먼저 확정하고 싶을 수 있다.
- **unique_answer_basis:** decisive fact = full Friday delivery is impossible and two feasible recovery options exist; tested function = state confirmed bad news without hedging and present the client's actual choice.
- **answer_explanation:** 세 선택지 모두 Friday/Tuesday recovery를 다루지만, B만 full-Friday impossibility를 정확히 말하고 어느 feasible option도 고객 대신 선택하지 않는다.
- **key_expression:** `We won't be able to deliver X by Y.`
- **expression_note:** confirmed impossibility를 모호한 risk처럼 표현하지 않는 bad-news opener다.
- **reusable_pattern:** `X won't be ready by Y. Would you prefer A or B?`
- **save_target:** `Would you prefer A or B?`
- **tags:** `material-delay`, `client-email`, `bad-news`, `recovery-options`, `certainty`

### Answer screen

- **Correct / Incorrect:** 정답은 **B**입니다.
- **Why it works:** 금요일 전체 납품은 이미 불가능합니다. B는 이를 숨기지 않고 가능한 출고 조건을 고객의 실제 선택으로 구성합니다.
- **Contrast:** A = treats a fact as a risk · C = decides for the client
- **Take this with you:** `The full order won't be ready Friday. Would you prefer part Friday and the rest Tuesday, or everything Tuesday?`
- **save_target:** `Would you prefer A or B?`

### Review variant

- **review_scenario:** 시스템 이전은 이번 주말에 모두 끝낼 수 없습니다. 이번 주말에는 핵심 계정만 옮길 수 있고, 나머지까지 완료되는 가장 빠른 날은 다음 수요일입니다.
- **recall_prompt:** 확정된 delay와 두 recovery option을 전달해 보세요. **[정답 보기]**
- **response:** `The full migration won't be complete this weekend. Would you prefer the key accounts this weekend and the rest Wednesday, or everything Wednesday?`
- **reusable_pattern:** `X won't be ready by Y. Would you prefer A or B?`

---

## QB01-016 · Move a responsibility dispute back to the record

- **question_id:** `QB01-016`
- **scenario_id:** `HI-009`
- **stage:** `Handle It`
- **question_type:** `Best Response`
- **difficulty:** `3`
- **scenario_text:** 두 팀이 승인 지연의 책임을 서로에게 돌리고 있습니다. 기록상 요청은 월요일에 접수됐고 담당은 화요일에 승인팀으로 이관됐습니다. 고객 업데이트 전에 현재 승인 owner를 분명히 해야 합니다.
- **prompt:** 화상회의에서 어떻게 말하는 것이 가장 적절할까요?

- **A.** The record proves the delay sits with the approval team, not us, so they need to explain the timeline and next step.
- **B.** Both teams contributed to the delay, so let's share responsibility equally, name a joint owner, and focus on the client update.
- **C.** Let's separate the timeline from the interpretation. The request was logged Monday, transferred Tuesday, and the approval team owns the next step.

- **correct_option:** `C`
- **distractor_types:** `A = defensive counter-blame`; `B = invents shared responsibility`
- **option_A_rationale:** 기록을 자기 팀의 무죄 주장과 상대 팀 blame에 사용하는 `defensive counter-blame`이다.
- **option_B_rationale:** 기록이 보여 주지 않는 공동 책임을 합의된 사실처럼 만드는 `invents shared responsibility`다.
- **option_C_rationale:** timeline과 interpretation을 분리하고 기록에 근거해 현재 next owner를 확정한다.
- **option_A_target_customer_choice_reason:** 고객 업데이트 전에 자기 팀에 잘못된 책임이 남지 않도록 강하게 정리하고 싶을 수 있다.
- **option_B_target_customer_choice_reason:** 내부 공방을 빨리 끝내려면 책임을 나누는 것이 실용적이라고 느낄 수 있다.
- **unique_answer_basis:** decisive fact = the record shows when the request was logged and transferred and identifies the current approval owner; tested function = separate timeline from blame and state current ownership without inventing responsibility.
- **answer_explanation:** C는 누가 잘못했는지를 성급히 결론내리지 않고 확인된 sequence와 현재 owner만 정리한다. 고객 업데이트에 필요한 next ownership도 확보된다.
- **key_expression:** `Let's separate the timeline from the interpretation.`
- **expression_note:** 책임 공방에서 observable record와 평가를 분리하는 factual reset이다.
- **reusable_pattern:** `Let's separate the timeline from the interpretation. The record shows X, then Y, and Z owns the next step.`
- **save_target:** `Let's separate the timeline from the interpretation.`
- **tags:** `responsibility-dispute`, `timeline`, `ownership`, `internal-video`, `factual-neutrality`

### Answer screen

- **Correct / Incorrect:** 정답은 **C**입니다.
- **Why it works:** 기록은 sequence와 현재 owner를 보여 주지만 전체 blame을 확정하지는 않습니다. C는 해석을 추가하지 않고 다음 행동의 책임을 명확히 합니다.
- **Contrast:** A = counter-blame · B = unsupported shared blame
- **Take this with you:** `Let's separate the timeline from the interpretation.`
- **save_target:** `Let's separate the timeline from the interpretation.`

### Review variant

- **review_scenario:** 두 부서가 계약 검토 지연을 서로 탓합니다. 기록상 초안은 수요일 법무팀으로 넘어갔고 현재 최종 확인은 법무팀 차례입니다.
- **recall_prompt:** timeline과 blame을 분리하고 현재 owner를 말해 보세요. **[정답 보기]**
- **response:** `Let's separate the timeline from the interpretation. The draft moved to Legal on Wednesday, and Legal owns the next review step.`
- **reusable_pattern:** `Let's separate the timeline from the interpretation. The record shows X, then Y, and Z owns the next step.`

---

## QB01-017 · Set a working condition after repeated no-shows

- **question_id:** `QB01-017`
- **scenario_id:** `HI-016`
- **stage:** `Handle It`
- **question_type:** `Best Response`
- **difficulty:** `2`
- **scenario_text:** 외부 파트너가 세 차례 핵심 planning call에 참석하지 않아 공동 일정이 지연됐습니다. 현재 파트너 측 고정 담당자가 없고 planning call 일정도 매주 달라집니다.
- **prompt:** 전화에서 어떻게 말하는 것이 가장 적절할까요?

- **A.** This is the third missed call, and the schedule is slipping. To continue, we need a named lead and a weekly check-in.
- **B.** We understand schedules are busy, but please make every effort to attend future planning calls and keep the project moving.
- **C.** After three missed calls, we need to pause the partnership until your team can guarantee full attendance at every future planning session.

- **correct_option:** `A`
- **distractor_types:** `B = minimizes a repeated pattern`; `C = premature relationship suspension`
- **option_A_rationale:** 반복 횟수와 일정 영향을 명시하고 협업 지속에 필요한 measurable operating condition을 제시한다.
- **option_B_rationale:** 세 차례의 pattern과 필요한 운영 변화를 effort request로 약화하는 `minimizes a repeated pattern`이다.
- **option_C_rationale:** 고정 담당자와 cadence를 먼저 요구할 수 있는데 협업 중단과 attendance guarantee로 뛰는 `premature relationship suspension`이다.
- **option_B_target_customer_choice_reason:** 관계를 악화시키지 않으면서 참석 노력을 요청하는 편이 현실적이라고 느낄 수 있다.
- **option_C_target_customer_choice_reason:** 세 번 반복됐으므로 강한 consequence가 없으면 행동이 바뀌지 않을 것이라고 생각할 수 있다.
- **unique_answer_basis:** decisive fact = three missed calls are delaying the schedule, with no named partner lead and no consistent meeting cadence; tested function = turn a repeated pattern into a measurable continuation condition without a premature threat.
- **answer_explanation:** A는 한 번의 실수처럼 말하지 않고 실제 impact와 필요한 operating change를 연결한다. 협업 종료를 먼저 위협하지도 않는다.
- **key_expression:** `To continue, we need...`
- **expression_note:** 반복 문제 뒤에 관계 위협 대신 구체적인 continuation condition을 둔다.
- **reusable_pattern:** `This is the [number] time X has happened, and it is affecting Y. To continue, we need Z.`
- **save_target:** `To continue, we need...`
- **tags:** `partner-reliability`, `boundary`, `phone`, `repeated-pattern`, `working-condition`

### Answer screen

- **Correct / Incorrect:** 정답은 **A**입니다.
- **Why it works:** 세 번의 no-show가 실제 일정에 영향을 줬습니다. A는 pattern과 impact를 말하고 named lead와 weekly check-in이라는 실행 조건을 제시합니다.
- **Contrast:** B = effort request only · C = jumps to suspension
- **Take this with you:** `To continue, we need a named lead and a weekly check-in.`
- **save_target:** `To continue, we need...`

### Review variant

- **review_scenario:** 파트너가 네 차례 자료 승인 시점을 넘겨 공동 캠페인이 지연됐습니다. 계속 진행하려면 승인 담당자와 고정 검토일이 필요합니다.
- **recall_prompt:** 반복 pattern과 continuation condition을 연결해 보세요. **[정답 보기]**
- **response:** `This is the fourth missed approval date, and the campaign is slipping. To continue, we need a named approver and a fixed review day.`
- **reusable_pattern:** `This is the [number] time X has happened, and it is affecting Y. To continue, we need Z.`

---

## QB01-018 · Revise feedback into behavior, impact, and expectation

- **question_id:** `QB01-018`
- **scenario_id:** `HI-023`
- **stage:** `Handle It`
- **question_type:** `Best Revision`
- **difficulty:** `2`
- **scenario_text:** 팀원이 최근 세 번의 고객 회의 후 action notes를 보내지 않아 후속 업무가 누락됐습니다. notes 발송은 그 팀원의 역할이며 다음 회의부터 24시간 안에 공유해야 합니다. 현재 준비한 feedback은 다음과 같습니다.
- **source_utterance:** `You've been careless about follow-up notes lately. Please be more responsible.`
- **prompt:** 이 feedback을 가장 적절하게 고친 것은 무엇일까요?

- **A.** After the last three client meetings, your careless follow-up caused problems. Show more ownership by sending the notes within 24 hours.
- **B.** The team has missed some follow-up work recently. Please try to send clear action notes more consistently within a reasonable time after client meetings.
- **C.** After the last three client meetings, action notes weren't sent and follow-ups were missed. From now on, please send them within 24 hours.

- **correct_option:** `C`
- **distractor_types:** `A = personality judgment despite a measurable deadline`; `B = vague behavioral expectation`
- **option_A_rationale:** 24시간 기준은 포함하지만 observable behavior와 구체적 impact 대신 `careless`와 ownership 평가를 유지하는 `personality judgment`다.
- **option_B_rationale:** impact는 말하지만 `try`, `more consistently`로 필요한 24시간 expectation을 흐리는 `vague behavioral expectation`이다.
- **option_C_rationale:** 세 번의 observable behavior, follow-up impact, 앞으로의 24시간 expectation을 명확히 연결한다.
- **option_A_target_customer_choice_reason:** 문제의 seriousness와 책임감을 분명히 해야 행동이 바뀐다고 생각할 수 있다.
- **option_B_target_customer_choice_reason:** 관계를 보호하면서 개선을 요청하려면 부드러운 표현이 낫다고 느낄 수 있다.
- **unique_answer_basis:** decisive fact = notes were missed three times, follow-up work was lost, and the role requires notes within 24 hours; tested function = replace character judgment with behavior, impact, and a measurable expectation.
- **answer_explanation:** C는 사람의 성격이나 태도를 평가하지 않고 확인된 행동과 업무 영향, 다음부터 지켜야 할 기준을 말한다.
- **key_expression:** `From now on, please... within...`
- **expression_note:** corrective feedback를 measurable future behavior로 끝낸다.
- **reusable_pattern:** `In the last X cases, Y happened, which caused Z. From now on, please A by B.`
- **save_target:** `From now on, please A by B.`
- **tags:** `performance-feedback`, `behavior-impact`, `team-member`, `video-call`, `best-revision`

### Answer screen

- **Correct / Incorrect:** 정답은 **C**입니다.
- **Why it works:** C는 `careless` 같은 personality label 대신 반복된 행동과 실제 impact를 제시하고 24시간 기준을 명확히 합니다.
- **Contrast:** A = keeps personality judgment · B = leaves the standard vague
- **Take this with you:** `From now on, please send the notes within 24 hours.`
- **save_target:** `From now on, please A by B.`

### Review variant

- **review_scenario:** 팀원이 최근 두 번 expense report를 늦게 제출해 월말 마감이 지연됐습니다. 앞으로는 매월 25일까지 제출해야 합니다.
- **recall_prompt:** behavior, impact, future expectation으로 feedback을 구성해 보세요. **[정답 보기]**
- **response:** `The last two expense reports arrived after the cutoff, which delayed month-end closing. From now on, please submit them by the 25th.`
- **reusable_pattern:** `In the last X cases, Y happened, which caused Z. From now on, please A by B.`

---

## QB01-019 · Replace an unsupported blame statement with interim facts

- **question_id:** `QB01-019`
- **scenario_id:** `HI-033`
- **stage:** `Handle It`
- **question_type:** `Best Revision`
- **difficulty:** `3`
- **scenario_text:** 고객은 경영진 보고에 넣을 장애 원인 문장을 지금 확정해 달라고 요청합니다. 공동 조사 결과는 내일 나오며 현재 evidence로는 원인을 특정할 수 없습니다. 현재 문안은 다음과 같습니다.
- **source_utterance:** `The vendor system caused the outage.`
- **prompt:** 현재 evidence status에 맞게 문안을 고친 것은 무엇일까요?

- **A.** The cause has not been confirmed. The outage is under joint investigation, with findings due tomorrow.
- **B.** The vendor system is the leading explanation, but the cause remains under joint investigation, with findings due tomorrow.
- **C.** We can't confirm the cause until the joint investigation finishes tomorrow, so no interim wording should be included today.

- **correct_option:** `A`
- **distractor_types:** `B = preserves unsupported blame through hedging`; `C = refuses factual interim communication`
- **option_A_rationale:** 원인 미확정, joint investigation, 다음 findings 시점을 사실 수준에 맞게 제공한다.
- **option_B_rationale:** investigation status와 timing을 정확히 말해도 `leading explanation`으로 evidence에 없는 vendor blame을 유지하는 `preserves unsupported blame`이다.
- **option_C_rationale:** evidence limit와 investigation timing은 정확하지만 사용할 수 있는 interim wording 자체를 막는 `refuses factual interim communication`이다.
- **option_B_target_customer_choice_reason:** 고객이 원인 방향을 요구하므로 certainty를 낮춰 잠정 가설이라도 제공하고 싶을 수 있다.
- **option_C_target_customer_choice_reason:** 조사 완료 전에는 원인과 관련된 어떤 interim wording도 보고서에서 빼는 것이 가장 안전하다고 느낄 수 있다.
- **unique_answer_basis:** decisive fact = no cause can be identified until tomorrow's joint findings; tested function = reject unsupported blame while offering a factual interim statement about investigation status.
- **answer_explanation:** 세 선택지 모두 investigation과 내일 timing을 언급하지만, A만 unsupported cause를 넣지 않으면서 오늘 사용할 factual interim wording을 제공합니다.
- **key_expression:** `X is under joint investigation.`
- **expression_note:** 책임 결론 없이 investigation status를 공식적인 interim wording으로 제시한다.
- **reusable_pattern:** `X has not been confirmed. Y is under joint investigation, with findings due Z.`
- **save_target:** `X is under joint investigation.`
- **tags:** `blame`, `investigation`, `interim-wording`, `client-video`, `best-revision`

### Answer screen

- **Correct / Incorrect:** 정답은 **A**입니다.
- **Why it works:** 현재 evidence는 vendor 원인을 지지하지 않습니다. A는 blame을 빼면서 조사 상태와 내일 결과라는 usable fact를 남깁니다.
- **Contrast:** B = hedged blame · C = no usable interim statement
- **Take this with you:** `The cause has not been confirmed. The outage is under joint investigation.`
- **save_target:** `X is under joint investigation.`

### Review variant

- **review_scenario:** 배송 손상의 원인이 창고인지 courier인지 아직 확인되지 않았고 조사 결과는 금요일에 나옵니다. 보고서 초안은 창고 책임으로 단정합니다.
- **recall_prompt:** blame 결론 대신 factual interim wording을 떠올려 보세요. **[정답 보기]**
- **response:** `The source of the damage has not been confirmed. The incident is under joint investigation, with findings due Friday.`
- **reusable_pattern:** `X has not been confirmed. Y is under joint investigation, with findings due Z.`

---

## QB01-020 · Ask for incident facts before assigning blame

- **question_id:** `QB01-020`
- **scenario_id:** `HI-038`
- **stage:** `Handle It`
- **question_type:** `Best Response`
- **prompt_scope:** `first response`
- **difficulty:** `2`
- **scenario_text:** vendor가 생산 시작 두 시간 전에 critical defect를 발견했다고 메신저로 알렸습니다. 현재 알림만으로는 launch 여부를 판단할 수 없으며 vendor와 즉시 통화할 수 있습니다.
- **prompt:** 첫 답변으로 무엇이 가장 적절할까요?

- **A.** This is unacceptable so close to launch. Explain how this happened and confirm that it won't happen again.
- **B.** Please send the affected quantity, current containment status, and likely scope of the defect, then join an immediate call.
- **C.** Please fix the defect ASAP and update us once the launch risk has been fully resolved.

- **correct_option:** `B`
- **distractor_types:** `A = blame before fact collection`; `C = vague urgency without decision inputs`
- **option_A_rationale:** launch decision에 필요한 facts보다 원인 설명과 재발 보장을 먼저 요구하는 `blame before fact collection`이다.
- **option_B_rationale:** launch 판단에 필요한 영향 규모, containment, defect scope와 live escalation을 구체적으로 요청한다.
- **option_C_rationale:** `ASAP`와 `fully resolved`만 제시해 현재 판단에 필요한 정보와 시점을 주지 않는 `vague urgency request`다.
- **option_A_target_customer_choice_reason:** launch 직전 critical defect이므로 seriousness와 vendor accountability를 즉시 강조하고 싶을 수 있다.
- **option_C_target_customer_choice_reason:** 가장 중요한 것은 빠른 수정이므로 세부 정보보다 해결을 먼저 요구하고 싶을 수 있다.
- **unique_answer_basis:** decisive fact = the defect report is too incomplete for a launch decision and an immediate call is possible; tested function = request concrete decision-relevant facts and initiate a live escalation before blame or generic urgency.
- **answer_explanation:** B는 감정이나 원인 공방보다 launch decision에 필요한 impact, containment, scope를 먼저 모으고 즉시 통화로 escalation합니다.
- **key_expression:** `Please send the affected quantity, containment status, and likely defect scope.`
- **expression_note:** incident first response에서 decision inputs를 category로 명시한다.
- **reusable_pattern:** `Please send X, Y, and Z, then join an immediate call.`
- **save_target:** `Please send X, Y, and Z.`
- **tags:** `vendor-incident`, `first-response`, `messenger`, `fact-collection`, `escalation`

### Answer screen

- **Correct / Incorrect:** 정답은 **B**입니다.
- **Why it works:** 현재 알림만으로는 launch 여부를 판단할 수 없습니다. B는 blame보다 decision-relevant facts를 먼저 요청하고 즉시 통화로 연결합니다.
- **Contrast:** A = starts with blame · C = urgency without inputs
- **Take this with you:** `Please send the affected quantity, containment status, and likely defect scope.`
- **save_target:** `Please send X, Y, and Z.`

### Review variant

- **review_scenario:** 배포 한 시간 전 외부 개발사가 critical error를 발견했습니다. 현재 알림만으로는 go/no-go를 결정할 수 없으며 개발사와 즉시 통화할 수 있습니다.
- **recall_prompt:** blame보다 decision inputs와 즉시 통화를 먼저 요청해 보세요. **[정답 보기]**
- **response:** `Please send the affected user count, rollback status, and available workaround, then join an immediate call.`
- **reusable_pattern:** `Please send X, Y, and Z, then join an immediate call.`
