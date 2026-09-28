# Business English Daily Quiz — Scenario Bank Structure v1.0

## 1. Purpose

Scenario Bank는 실제 문제(question)를 대량 생성하기 전에,
**어떤 업무 상황을 어떤 학습 목적과 커뮤니케이션 판단으로 다룰 것인지 정의하는 설계 레이어**다.

Scenario는 최종 사용자에게 그대로 노출되는 문제 문장이 아니다.

하나의 Scenario는 이후 다음으로 발전할 수 있다.

- Best Response
- Best Revision
- Tone Check
- Choose the Follow-up
- What's Wrong?
- Order the Message
- 기타 적절한 question type

Scenario Bank의 목적은 문제를 많이 만드는 것이 아니라,
**좋은 문제를 안정적으로 만들 수 있는 상황 구조를 충분히 넓고 균형 있게 확보하는 것**이다.

---

## 2. Scenario vs Question

### Scenario

업무 상황과 학습 포인트를 정의하는 설계 단위.

포함:

- 누가 누구에게 말하는가
- 어떤 업무 상황인가
- 무엇을 달성해야 하는가
- 어떤 제약이나 리스크가 있는가
- 어떤 communication challenge가 핵심인가
- 어떤 English payoff가 가능한가

### Question

Scenario를 실제 사용자에게 제시하는 출제 단위.

포함:

- scenario text
- prompt
- 3개 선택지 또는 기타 question format
- correct answer
- distractor rationale
- answer explanation
- reusable pattern

원칙:

> **Scenario Bank 승인 후 Question Bank를 대량 생성한다.**

Scenario 단계에서 이미 학습 가치가 약한 상황은 실제 문제로 만들지 않는다.

---

## 3. Stage Structure

Scenario는 다음 3개 Stage 중 하나에 속한다.

### Stage 1 — Inbox

정상적인 업무 흐름에서 처리하는 비동기 중심 커뮤니케이션.

대표 situation family:

- request
- follow-up
- scheduling
- confirmation
- clarification
- status update
- information sharing
- handoff
- expectation setting
- minor correction
- approval request
- reminder

주요 채널:

- email
- messenger

단, 심각한 문제 관리가 핵심이면 이메일이라도 Handle It이다.

---

### Stage 2 — Speak Up

Handle It에 해당하지 않는 **통상적 협업의 실시간 커뮤니케이션**.

대표 situation family:

- asking for clarification
- giving an opinion
- agreeing
- disagreeing
- interrupting
- redirecting
- prioritizing
- negotiating
- proposing
- confirming action items
- closing a meeting
- checking understanding
- asking for a decision

핵심:

> **실시간 상호작용과 즉각적인 언어 선택**

채널 예:

- meeting
- video call
- phone

---

### Stage 3 — Handle It

관계, 책임, 비용, 일정 손실, 고객 신뢰, 업무 경계 또는 실질적 갈등을 관리하거나 해결해야 하는 상황.

대표 situation family:

- delay
- complaint
- mistake
- bad news
- refusal
- scope creep
- unrealistic demand
- missed commitment
- escalation
- responsibility dispute
- apology / recovery
- vendor issue
- client issue
- boundary setting
- service failure

핵심은 채널이 아니라 **stakes와 problem-management requirement**다.

---

## 4. Stage Classification Priority

항상 다음 순서로 판단한다.

### 1. 중대한 문제를 관리하거나 해결해야 하는가?

예:

- 고객 신뢰
- 책임 소재
- 중대한 지연
- 비용 손실
- scope conflict
- 반복된 vendor 실패
- 실제 업무 경계 침해

→ **Handle It**

### 2. 아니라면 실시간 상호작용인가?

예:

- 회의에서 질문
- 즉시 이견 제시
- 우선순위 확인
- 회의 흐름 조정
- 실시간 negotiation

→ **Speak Up**

### 3. 아니라면

→ **Inbox**

Stage와 channel은 별개의 축이다.

예:

- 전화로 일정 조율 → Speak Up
- 전화로 고객 항의 처리 → Handle It
- 이메일로 일반 요청 → Inbox
- 이메일로 중대한 납기 지연 대응 → Handle It

---

## 5. Scenario Schema

각 Scenario는 다음 필드를 가진다.

### Identity

- `scenario_id`
- `stage`
- `situation_family`
- `storyline_id` — optional

### Communication Context

- `channel`
- `communication_mode`: async / live
- `context`: internal / external
- `speaker_role`
- `counterpart_role`
- `power_relationship`
- `relationship_status`
- `stakes`

### Business Design

- `scenario_summary`
- `business_goal`
- `primary_communication_challenge`
- `desired_tone_or_style`
- `language_functions`

### Learning Design

- `expected_english_payoff`
- `candidate_reusable_pattern`
- `recommended_question_types`
- `target_difficulty`
- `candidate_distractor_types`

### Optional Notes

- `notes`

---

## 6. Field Definitions

### `speaker_role`

예:

- individual contributor
- project manager
- team lead
- account manager
- operations staff
- analyst
- coordinator

직무 전문지식이 문제 해결의 핵심이 되지 않도록 한다.

---

### `counterpart_role`

대표 분류:

- manager
- peer
- junior / team member
- client
- vendor
- external partner
- global colleague

---

### `power_relationship`

대표 값:

- upward
- equal
- downward
- client-facing

필요하다면 external partner / vendor 관계를 notes에 보완할 수 있다.

---

### `relationship_status`

대표 값:

- familiar
- neutral
- formal
- strained

관계 상태는 정답이 달라지는 경우에만 의미 있게 사용한다.

---

### `stakes`

대표 값:

- routine
- sensitive
- high

단순 난이도와 stakes를 혼동하지 않는다.

---

### `business_goal`

그 상황에서 실제로 달성해야 하는 업무 목적.

예:

- obtain a firm deadline
- clarify which data should be used
- preserve required testing time
- obtain a priority decision
- set a scope boundary
- acknowledge a confirmed mistake and start recovery

---

### `primary_communication_challenge`

문항의 핵심 communication judgment.

가능하면 내부적으로 다음 형태로 정리한다.

> **The user needs to ___ without ___.**

예:

- confirm a firm deadline without making it sound optional
- reject an unrealistic date without implying that it may still be possible
- acknowledge a complaint without admitting an unverified cause
- set a boundary without accidentally accepting the work

---

### `expected_english_payoff`

이 Scenario를 **영어 문제로 만들어야 하는 이유**를 구체적으로 적는다.

나쁜 예:

> Learn how to prioritize.

좋은 예:

> Practice converting a capacity problem into an explicit priority question: “Which should take priority—X or Y?”

또는:

> Distinguish a clear commitment (`I'll`) from hedged commitment (`I should be able to`) and effort-only commitment (`I'll do my best`).

Scenario가 workplace judgment만 있고 English payoff가 없다면 승인하지 않는다.

---

### `candidate_reusable_pattern`

정답에서 추출할 가능성이 높은 재사용 표현 또는 frame.

예:

- `Do you mean X or Y?`
- `We can't support X without Y.`
- `Please confirm by [time] that you can meet the deadline.`
- `We haven't confirmed X yet. Let's review Y before we draw a conclusion.`

완성 문장을 미리 강제할 필요는 없지만,
실제 업무에서 재사용 가능한 표현이 나올 가능성이 보여야 한다.

---

### `candidate_distractor_types`

실제 문제 제작 시 사용할 수 있는 **서로 다른 두 failure type**을 제안한다.

예:

- weak commitment
- premature escalation

또는:

- leading assumption
- pseudo-clarification

같은 오류를 강도만 다르게 두 번 쓰지 않는다.

---

## 7. Scenario Summary Rule

Scenario summary는 최종 문제 문구가 아니지만,
나중에 **2~3문장 안에 실제 문제로 발전할 수 있을 정도로 구체적**이어야 한다.

필요한 경우 다음을 명시한다.

- known facts
- deadline
- authority
- negotiability
- hard constraint
- responsibility status
- whether the issue is confirmed or still uncertain

숨은 전제가 있어야 정답을 결정할 수 있는 Scenario는 승인하지 않는다.

---

## 8. Hidden Premise Rule

정답을 결정하는 정보는 Scenario에 명시해야 한다.

예:

직원이 두 업무 중 하나를 선택해야 하는 상황에서
직원이 스스로 우선순위를 정하는 것도 합리적이라면,
“상사에게 물어보는 것이 정답”이라고 강제해서는 안 된다.

상사가 결정해야 한다면 다음과 같은 premise가 필요하다.

> 두 업무의 대외적 중요도는 상사만 알고 있다.

원칙:

> **Scenario에 없는 조직문화, 권한관계, 회사방침을 정답 근거로 사용하지 않는다.**

---

## 9. English Payoff Gate

Scenario 승인 전 반드시 묻는다.

> **이 상황을 영어 문제로 만들어야 할 이유는 무엇인가?**

다음 중 최소 하나가 분명해야 한다.

- commitment strength
- directness vs hedging
- factual neutrality
- assumption vs fact
- deadline framing
- ownership
- responsibility
- scope / boundary
- disagreement
- live response
- clarification
- escalation
- meeting discourse
- actionable next step
- negotiation frame
- useful collocation
- reusable sentence pattern

한국어로 번역해도 사실상 같은 workplace common-sense 문제라면 수정하거나 제외한다.

---

## 10. Coverage Principles

초기 정식 Scenario Bank는:

- Inbox 40
- Speak Up 40
- Handle It 40

총 120개를 기본으로 한다.

Stage 수는 동일하게 맞추되,
각 Stage 내부의 context와 communication challenge는 다양하게 분산한다.

---

## 11. Counterpart Coverage

다음을 충분히 포함한다.

- manager
- peer
- junior / team member
- client
- vendor
- external partner
- global colleague

`client`에 과도하게 편중하지 않는다.

내부 커뮤니케이션도 제품의 중요한 일부다.

---

## 12. Internal / External Coverage

### Internal

예:

- manager
- peer
- cross-functional team
- global colleague
- junior

### External

예:

- client
- vendor
- partner

Scenario Bank 전체에서 어느 한쪽이 압도적으로 많아지지 않도록 한다.

---

## 13. Handle It Channel Balance

Handle It은 특히 이메일 중심이 되지 않도록 한다.

12개 기준 권장 분포:

- Email 2
- Meeting / Video 6
- Phone 3
- Messenger 1

40개로 확장할 경우 대략:

- Email 7
- Meeting / Video 20
- Phone 10
- Messenger 3

을 참고할 수 있다.

정확한 숫자보다 **live response 비중을 충분히 확보하는 것**이 더 중요하다.

---

## 14. Situation Diversity

Scenario Bank는 일정 변경, 납기, 항의만 반복해서는 안 된다.

포함 후보:

- request
- clarification
- approval
- follow-up
- scheduling
- handoff
- delegation
- prioritization
- disagreement
- negotiation
- feedback
- reporting
- workload
- scope
- budget / resource constraint
- expectation management
- correction
- misunderstanding
- delay
- complaint
- vendor quality
- missed commitment
- responsibility
- escalation
- recovery
- conflicting priorities

같은 situation family라도 communication challenge가 다르면 별도 Scenario가 될 수 있다.

예:

- hard deadline confirmation
- unrealistic deadline rejection
- deadline uncertainty update
- deadline escalation
- deadline prioritization

---

## 15. Duplicate Rule

다음은 중복 후보로 본다.

- 명사만 바뀐 같은 상황
- 상대만 client → vendor로 바뀐 같은 문제
- 동일한 communication challenge 반복
- 동일한 reusable pattern 반복
- 동일한 distractor 구조 반복
- 결과적으로 같은 영어 판단을 요구

반대로 표면상 같은 situation family라도
핵심 learning payoff가 다르면 별도 Scenario로 유지할 수 있다.

---

## 16. Storyline Rule

전체 Scenario 중 약 20~30%는 느슨한 storyline으로 연결할 수 있다.

예:

> request → meeting → vendor issue → client update

다만:

- 전날 문제를 알아야 다음 문제를 풀 수 없어야 한다.
- 각각 독립적으로 이해 가능해야 한다.
- storyline 자체가 학습 가치보다 중요해져서는 안 된다.

Storyline은 continuity를 위한 장치이지 prerequisite가 아니다.

---

## 17. Fictional Company / Character Use

콘텐츠 continuity를 위해
광범위한 B2B 프로젝트 환경을 공유하는 가상의 회사와 반복 등장 인물을 사용할 수 있다.

권장 회사 범위:

> 해외 고객·파트너·vendor와 프로젝트를 수행하는 한국 기반 B2B 회사

특정 산업 전문용어가 문제의 핵심이 되지 않도록 한다.

반복 등장 인물은 Scenario 이해를 돕고 continuity를 만들 수 있지만,
현재 Scenario Bank 설계 단계에서는 캐릭터 설정을 과도하게 확정하지 않는다.

Visual/character system은 별도 design backlog에서 다룬다.

---

## 18. Difficulty Potential

Scenario Bank 단계에서 실제 문항 난이도를 완전히 결정하지 않는다.

다만 각 Scenario에 다음 중 하나를 표시한다.

- Difficulty 1 적합
- Difficulty 2 적합
- Difficulty 3 가능

전체적으로 Difficulty 2 제작에 적합한 Scenario를 중심으로 한다.

문제은행의 초기 목표 분포는 별도 Editorial Guide를 따른다.

---

## 19. Response Style Balance

Scenario Bank 자체부터
특정 communication style만 정답이 되도록 편향되지 않게 구성한다.

다음이 모두 최적 response가 될 수 있는 상황을 포함한다.

- direct + clear
- concise
- firm + bounded
- neutral + factual
- diplomatic + collaborative
- empathetic + solution-oriented

특히 충분히 포함할 것:

- unnecessary hedging이 오히려 문제인 상황
- directness가 정확한 상황
- firm boundary가 필요한 상황
- premature apology가 위험한 상황
- 지나친 certainty가 문제인 상황

---

## 20. Scenario Approval Checklist

각 Scenario는 다음 질문에 답한다.

### Realism
- 실제 직장에서 일어날 법한가?
- Primary Target이 경험할 가능성이 있는가?

### Classification
- Stage가 classification priority와 맞는가?
- channel과 Stage를 혼동하지 않았는가?

### Context
- 정답에 필요한 premise가 충분한가?
- hidden premise가 없는가?

### Learning Value
- 명확한 English payoff가 있는가?
- reusable expression 또는 language distinction이 가능한가?
- 단순 workplace common sense 문제로 끝나지 않는가?

### Production Potential
- 2~3문장 내 문제로 만들 수 있는가?
- 서로 다른 두 distractor failure type을 만들 수 있는가?
- 3지선다 또는 다른 적절한 question type으로 발전 가능한가?

하나라도 명백히 No라면 수정 또는 제외한다.

---

## 21. Representative Golden Scenario Set

아래는 Scenario 유형의 기준 예시다.
최종 Question wording이 아니라 **Scenario design quality의 참고점**이다.

### Inbox

1. 고객이 합의된 자료 제출일을 앞두고 있음  
   - Goal: deadline confirmation  
   - Challenge: confirm firmly without reopening negotiation

2. 고객 요청의 “latest numbers”가 잠정치인지 확정치인지 불명확함  
   - Goal: clarify data source  
   - Challenge: resolve ambiguity without making a leading assumption

3. 외부 승인 지연으로 납기가 하루 밀릴 가능성이 있음  
   - Goal: manage expectations  
   - Challenge: communicate uncertainty without overcommitting

4. 상사가 오늘 오후까지 가능한 업무를 요청함  
   - Goal: give clear commitment  
   - Challenge: avoid unnecessary hedging

5. 다른 팀에 자료를 요청해야 함  
   - Goal: obtain input  
   - Challenge: be clear about need and deadline without sounding demanding

6. 고객 follow-up이 필요하지만 지나친 독촉은 원하지 않음  
   - Goal: obtain response  
   - Challenge: create actionability without unnecessary pressure

7. 작은 자료 누락을 발견해 상대에게 알려야 함  
   - Goal: correct issue efficiently  
   - Challenge: flag the problem without making it sound larger than it is

8. 일정 영향 가능성을 미리 알려야 하지만 아직 확정되지 않음  
   - Goal: early warning  
   - Challenge: distinguish risk from confirmed delay

### Speak Up

9. 상사가 현실적으로 불가능한 launch date를 제안함  
   - Goal: protect hard constraint  
   - Challenge: state impossibility clearly without treating it as mere concern

10. 고객이 “move the rollout up”이라고만 말함  
    - Goal: obtain exact target date  
    - Challenge: ask for precise information without guessing

11. 회의 중 잘못된 핵심 수치를 바로잡아야 함  
    - Goal: correct factual error  
    - Challenge: interrupt clearly without unnecessary confrontation

12. 두 업무 중 하나만 오늘 끝낼 수 있고 우선순위 정보는 상사만 알고 있음  
    - Goal: obtain priority decision  
    - Challenge: turn capacity constraint into a clear choice

13. 회의가 산으로 가고 오늘 결정할 안건이 남아 있음  
    - Goal: redirect discussion  
    - Challenge: move on without dismissing the current discussion

14. 제안에 기본적으로 동의하지만 조건 하나가 필요함  
    - Goal: express conditional agreement  
    - Challenge: avoid sounding like full agreement

15. 회의 종료 전 action owner가 정해지지 않음  
    - Goal: establish ownership  
    - Challenge: make responsibility explicit

16. 상대가 제시한 미팅 시간이 어렵지만 대체 시간이 가능함  
    - Goal: reschedule live  
    - Challenge: decline efficiently while offering workable alternatives

### Handle It

17. 고객이 왜 더 일찍 알려주지 않았냐고 항의함  
    - Goal: respond to complaint  
    - Challenge: acknowledge concern without inventing responsibility

18. 고객이 현실적으로 불가능한 deadline을 요구함  
    - Goal: protect delivery quality / feasibility  
    - Challenge: reject clearly while offering workable boundary

19. 장애의 책임 소재가 아직 확인되지 않음  
    - Goal: preserve factual neutrality  
    - Challenge: avoid premature blame or admission

20. 계약 범위 밖 추가 업무를 동일 비용/일정으로 요청받음  
    - Goal: maintain scope boundary  
    - Challenge: refuse current terms while preserving a negotiation path

21. 화난 고객이 전화로 즉시 답을 요구함  
    - Goal: stabilize communication and establish next action  
    - Challenge: respond live without overpromising

22. vendor가 반복적으로 납기를 어기고 있음  
    - Goal: obtain firm commitment  
    - Challenge: be direct without escalating too early

23. 잘못된 파일을 고객에게 보냄  
    - Goal: correct and recover  
    - Challenge: acknowledge confirmed mistake and give next step quickly

24. 동료가 지속적으로 자신의 업무를 떠넘김  
    - Goal: set work boundary  
    - Challenge: be firm without unnecessary hostility

---

## 22. Relationship to Other Documents

Scenario Bank Structure는 다음 문서와 함께 사용한다.

### `product-learning-spec.md`
제품 대상과 학습 목적을 정의한다.

### `editorial-guide.md`
실제 Question 작성, distractor, 정답 판단, 해설 원칙을 정의한다.

### `golden-question-set.md`
Editorial rules가 실제 문제에서 어떻게 구현되는지 보여준다.

### `answer-review-system.md`
정답 화면과 review loop를 정의한다.

### `scenario-bank-120-brief.md`
이 구조를 사용해 실제 120개 Scenario Bank를 생산하도록 Work에 지시한다.

---

## 23. Final Principle

Scenario Bank의 품질 기준은 Scenario 수가 아니다.

핵심 질문은:

> **이 Scenario가 실제 타겟 사용자의 업무 상황을 반영하면서, 영어로만 배울 수 있는 유의미한 판단과 재사용 가능한 표현을 만들어낼 수 있는가?**

그렇지 않다면 Scenario Bank에 포함하지 않는다.
