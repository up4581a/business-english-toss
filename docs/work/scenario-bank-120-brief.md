# Work Brief — Business English Scenario Bank 120

## Role

당신은 비즈니스 영어 학습제품의 **Senior Content Strategist + Business English Curriculum Designer**다.

이 작업은 아이디어 브레인스토밍이 아니라 실제 상용 제품의 콘텐츠 시스템 구축 작업이다.

첨부된 기준 문서를 authoritative source로 사용한다.

반드시 읽고 준수할 문서:

1. Product & Learning Spec v1.0
2. Question Schema & Editorial Guide 최신 버전
3. Scenario Bank Structure v1.0
4. Golden Question Set 최신 버전
5. Answer Screen & Review System Spec v1.0

문서 간 충돌이 있다면 가장 최근 버전을 우선한다.

---

# Objective

정식 콘텐츠 제작의 기반이 될 **120개 Scenario Bank**를 설계한다.

구성:

- Inbox 40
- Speak Up 40
- Handle It 40

이번 작업의 핵심 deliverable은 **scenario bank와 coverage validation**이다.

전체 question bank를 아직 대량 작성하지 않는다.

---

# Target User

다음 사용자를 기준으로 설계한다.

> 업무상 영어를 정기적으로 사용하지만 영어 자체가 본업은 아니며, 일반적인 영어를 이해하고 작성할 수 있으나 실제 업무에서 적절한 표현을 즉시 선택하는 데 어려움을 느끼는 한국 직장인.

사용자는:

- 영어 초급자가 아니다.
- 영어 원어민 수준의 전문가도 아니다.
- 이메일은 시간을 들이면 쓸 수 있다.
- 미팅, 전화, 민감한 요청, 거절, 문제 대응에서는 표현 선택이 늦어진다.
- 실제 업무에서 ChatGPT나 번역기를 반복적으로 사용하는 경우가 있다.
- 긴 학습보다 짧고 실용적인 micro-training에 적합하다.

---

# Product Learning Goal

이 서비스는 단순 vocabulary 또는 grammar trainer가 아니다.

핵심은:

> **pragmatic competence + reusable business English**

다.

Scenario는 최종적으로 사용자가 다음과 같은 것을 배우도록 해야 한다.

- commitment strength
- directness vs hedging
- factual neutrality
- deadline framing
- scope management
- disagreement
- ownership
- escalation
- clarification
- live response
- responsibility
- actionable next steps

모든 scenario에는 영어 학습상의 명확한 payoff가 있어야 한다.

---

# Stage Rules

## Inbox

정상 업무 흐름에서 비동기 중심으로 처리하는 상황.

예:

- request
- follow-up
- scheduling
- clarification
- status update
- expectation setting
- minor correction

## Speak Up

Handle It이 아닌 **통상적 협업의 live communication**.

예:

- immediate clarification
- disagreement
- prioritization
- negotiation
- interruption
- meeting management
- confirming decisions

## Handle It

관계, 책임, 비용, 일정 손실, 고객 신뢰, 업무 경계 또는 실질적 갈등을 관리하는 상황.

Stage classification priority:

1. serious issue management → Handle It
2. otherwise live interaction → Speak Up
3. otherwise routine asynchronous work → Inbox

---

# Handle It Channel Distribution

40개에서 대략 다음 비율을 유지한다.

- Email: 7
- Meeting / Video call: 20
- Phone: 10
- Messenger: 3

정확한 숫자보다 live communication 중심이라는 원칙을 우선한다.

---

# Required Scenario Fields

각 scenario마다 다음 필드를 작성한다.

- `scenario_id`
- `stage`
- `situation_family`
- `channel`
- `communication_mode`
- `context`: internal / external
- `speaker_role`
- `counterpart_role`
- `power_relationship`
- `relationship_status`
- `stakes`
- `scenario_summary`
- `business_goal`
- `primary_communication_challenge`
- `desired_tone_or_style`
- `language_functions`
- `expected_english_payoff`
- `candidate_reusable_pattern`
- `recommended_question_types`
- `target_difficulty`
- `candidate_distractor_types`
- `storyline_id` — optional
- `notes` — optional

---

# Scenario Summary Rule

Scenario 자체는 최종 question이 아니다.

다만 나중에 **가급적 2~3문장 안에 출제 가능한 수준으로 구체적**이어야 한다.

정답을 결정하는 데 필요한:

- relationship
- deadline
- authority
- known facts
- negotiability
- constraint

가 필요한 상황이라면 이를 명확히 정의한다.

문제 제작자가 추후 숨은 전제를 만들어야만 정답을 결정할 수 있는 scenario는 승인하지 않는다.

---

# English Payoff Rule

각 scenario에 대해 반드시 다음 질문에 답한다.

> **이 상황을 영어 문제로 만들어야 할 이유는 무엇인가?**

`expected_english_payoff`에는 구체적인 영어 학습 효과를 쓴다.

나쁜 예:

> Learn how to handle priorities.

좋은 예:

> Distinguish a clear commitment (`I'll`) from hedged commitment (`I should be able to`) and effort-only commitment (`I'll do my best`).

또는:

> Practice the pattern “We can’t support X without Y” for stating a hard constraint without presenting it as a preference.

단순 workplace judgment만 있고 영어 표현상의 payoff가 없는 scenario는 제거한다.

---

# Directness Neutrality

다음 패턴으로 scenario를 설계하지 않는다.

> polite = correct  
> direct = wrong

상황에 따라:

- direct
- concise
- firm
- neutral
- diplomatic
- empathetic

한 표현이 최적일 수 있다.

120개 전체에서 다양한 response style이 정답이 될 수 있도록 scenario를 구성한다.

특히:

- directness가 필요한 상황
- unnecessary hedging이 문제가 되는 상황
- 지나치게 polite한 표현이 commitment를 약화시키는 상황
- firm boundary가 필요한 상황

을 충분히 포함한다.

---

# Coverage Requirements

## Counterparts

다음이 골고루 등장해야 한다.

- manager
- peer
- junior/team member
- client
- external partner
- vendor

`client`에 과도하게 편중하지 않는다.

---

## Internal / External

내부 커뮤니케이션과 외부 커뮤니케이션 모두 충분히 포함한다.

내부 예:

- manager
- peer
- cross-functional team
- global colleague
- junior

외부 예:

- client
- vendor
- partner

---

## Communication Challenges

같은 communication challenge를 대상만 바꿔 반복하지 않는다.

예:

- client reminder
- vendor reminder
- partner reminder

가 모두 같은 `polite reminder`라면 실질적으로 중복이다.

반대로 deadline을 다뤄도:

- hard deadline confirmation
- unrealistic deadline rejection
- deadline escalation
- deadline uncertainty update
- deadline prioritization

처럼 학습 포인트가 다르면 별도 scenario가 될 수 있다.

---

# Storyline Rule

전체 scenario 중 약 20~30%는 느슨한 storyline으로 연결할 수 있다.

예:

request → meeting → vendor issue → client update

단:

- 전날 문제를 알아야 다음 문제를 풀 수 있어서는 안 된다.
- 각각 독립적으로 이해 가능해야 한다.
- storyline 자체가 영어 학습 가치보다 우선해서는 안 된다.

---

# Situation Diversity

일정 변경, 항의, 지연만 반복하지 않는다.

포함해야 할 후보 영역:

- request
- clarification
- approval
- follow-up
- handoff
- delegation
- prioritization
- disagreement
- negotiation
- feedback
- reporting
- workload
- scope
- budget/resource constraint
- delay
- complaint
- vendor quality
- missed commitment
- responsibility
- escalation
- recovery
- correction
- conflicting priorities
- misunderstanding
- expectation management

필요하다면 추가 category를 제안할 수 있다.

---

# Difficulty Potential

Scenario Bank 단계에서는 실제 문제 난이도를 확정하지 않는다.

그러나 각 scenario에:

- Difficulty 1 적합
- Difficulty 2 적합
- Difficulty 3 가능

중 어느 수준이 자연스러운지 표시한다.

전체적으로 Difficulty 2 제작에 적합한 scenario를 중심으로 한다.

---

# Distractor Potential

각 scenario에 대해 실제 문항을 만들었을 때 가능한 **서로 다른 두 distractor failure type**을 제안한다.

예:

- weak commitment
- premature escalation

두 distractor는 같은 오류를 강도만 달리한 것이어서는 안 된다.

---

# Work Process

반드시 다음 순서로 진행한다.

## Phase 1 — Framework Check

기준 문서를 읽고:

- stage boundary
- target persona
- learning goal
- English payoff
- directness neutrality

를 짧게 요약한다.

새로운 규칙을 임의로 만들지 않는다.

기준 문서에서 모순 또는 실제 확장을 방해하는 문제가 발견되면 별도 `Issues to Resolve`에 기록한다.

---

## Phase 2 — Draft 120 Scenarios

- Inbox 40
- Speak Up 40
- Handle It 40

을 생성한다.

---

## Phase 3 — Coverage Audit

다음 기준으로 matrix를 만든다.

- stage
- channel
- internal/external
- counterpart
- situation family
- stakes
- primary communication challenge
- language function
- English payoff category
- expected response style
- difficulty potential

편중을 수치로 확인한다.

---

## Phase 4 — Duplicate Audit

120개를 pairwise 또는 cluster 관점에서 검토한다.

다음과 같은 경우 중복 후보로 표시한다.

- 명사만 바뀐 같은 상황
- 상대만 바뀐 같은 communication challenge
- 같은 reusable pattern을 사실상 반복
- 같은 distractor 구조가 반복
- 결과적으로 동일한 영어 판단을 요구

중복은 교체하거나 명확히 차별화한다.

---

## Phase 5 — Bias Audit

다음 편향을 검사한다.

- polite response가 지나치게 자주 최적이 되는가
- client-facing scenario가 과도한가
- Handle It이 catastrophe 위주인가
- 이메일 비중이 과도한가
- 모든 problem-solving이 apology로 끝나는가
- direct/firm response가 충분히 포함되는가
- workplace judgment만 있고 English payoff가 약한 scenario가 있는가

---

## Phase 6 — Final Revision

Coverage / Duplicate / Bias Audit 결과를 반영해 120개를 수정한다.

초기 draft가 아니라 **수정 완료된 120개만 Final Scenario Bank로 제출**한다.

---

# Required Deliverables

## Deliverable A — Final Scenario Bank 120

구조화된 표 또는 spreadsheet-friendly 형태.

---

## Deliverable B — Coverage Matrix

각 축의 수와 비율을 제공한다.

특히 다음을 명확히 표시한다.

- Stage 40/40/40
- channel
- counterpart
- internal/external
- communication challenge
- English payoff type
- response style

---

## Deliverable C — Duplicate / Replacement Report

초안 과정에서 어떤 유형의 중복이 발견됐고 어떻게 수정했는지 요약한다.

---

## Deliverable D — Risk Report

향후 실제 question 제작 시 품질 문제가 생기기 쉬운 scenario를 표시한다.

예:

- 조직 문화에 따라 정답이 갈릴 위험
- 법률/전문지식 개입 위험
- hidden premise 위험
- pure workplace judgment 위험
- overly subtle answer 위험

---

## Deliverable E — Top 20 Production Candidates

120개 중 실제 Golden Question Set과 가장 유사한 수준의 좋은 문제를 만들 가능성이 높은 scenario 20개를 별도로 추린다.

선정 이유를 짧게 설명한다.

---

# Do Not Do Yet

이번 Work에서는 다음을 하지 않는다.

- 120개 전체의 실제 A/B/C 문제 작성
- 전체 해설 작성
- illustration 생성
- 캐릭터 디자인
- UI 디자인
- 광고/수익화 설계

Scenario Bank가 먼저 승인되어야 한다.

---

# Final Quality Standard

좋은 scenario는 다음 질문에 모두 Yes여야 한다.

1. 실제 직장에서 일어날 법한가?
2. Primary Target에게 유용한가?
3. 기존 scenario와 다른 communication challenge가 있는가?
4. 영어로 학습할 명확한 이유가 있는가?
5. reusable expression 또는 language distinction을 만들 수 있는가?
6. 2~3문장 안에 필요한 context를 제시할 수 있는가?
7. 정답이 단순히 가장 polite한 문장이 되지 않아도 되는 구조인가?
8. 좋은 3지선다 또는 다른 적절한 question type으로 발전할 수 있는가?

하나라도 명백히 No라면 최종 Bank에서 제외하거나 수정한다.