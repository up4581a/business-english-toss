# Product & Learning Spec v1.0

## 1. 제품 정의

토스 미니앱 환경에서 사용하는 **비즈니스 영어 데일리 micro-training 서비스**.

사용자는 매일 실제 직장에서 마주칠 법한 세 가지 상황을 해결한다.

기본 경험은:

> **하루 3문제 → 약 2~3분 → Clear**

제품의 목적은 영어 지식을 많이 제공하는 것이 아니라, 실제 업무에서 **적절한 표현을 빠르게 선택하고 떠올리는 능력**을 반복적으로 훈련하는 것이다.

내부 product promise:

> **실제 업무 상황에서 ‘무슨 말을 해야 할지’뿐 아니라 ‘어떻게 말해야 할지’를 매일 세 번 판단하고, 바로 재사용할 영어 표현을 가져가는 서비스.**

외부적으로 전달할 핵심 가치:

> **읽으면 아는데, 막상 일할 때는 안 나오는 영어를 훈련한다.**

---

# 2. Primary Target

핵심 타겟은:

> **해외 고객, 파트너, 본사, 협력업체 또는 외국인 동료와 업무상 영어를 정기적으로 사용하지만, 영어 자체가 본업은 아니며 상황에 맞는 표현을 즉시 선택하는 데 자신이 없는 한국 직장인.**

대표 행동 특성:

- 일반적인 업무 이메일과 회의 내용을 읽고 이해할 수 있다.
- 간단한 이메일은 직접 작성할 수 있다.
- 요청, 거절, 독촉, 이견, 책임, 문제 대응처럼 뉘앙스가 중요한 순간에는 표현 선택에 시간이 걸린다.
- ChatGPT, 번역기, 이전 이메일 등을 반복적으로 찾아본다.
- 긴 강의나 교재 학습을 꾸준히 하기는 어렵지만 2~3분짜리 학습은 가능하다.
- 목표는 원어민처럼 말하는 것이 아니라 **영어 때문에 업무 흐름이 멈추지 않는 것**이다.

---

# 3. Secondary Target

영어 업무가 매주는 아니지만 정기적으로 발생하는 일반 직장인.

영어를 사용하는 순간의 부담은 크지만 사용 빈도가 낮아 daily retention은 Primary Target보다 약할 수 있다.

기본 콘텐츠는 Primary Target에 맞추되 Secondary Target도 진입할 수 있는 난이도를 유지한다.

---

# 4. 제외 대상

## Too Beginner

다음과 같은 기본 문장 자체를 이해하거나 만드는 데 어려움이 있는 사용자.

> Could you send me the file by Friday?

이 제품은 기본 문법·단어 학습 서비스가 아니다.

## Too Advanced

영어 업무에서 register, tone, commitment level 등을 거의 자동적으로 조절할 수 있고 영어 표현 선택이 업무상의 병목이 아닌 사용자.

---

# 5. Core Jobs-to-be-Done

## Functional Job

상황에 적절한 업무 영어 표현을 빠르게 선택한다.

## Emotional Job

“이 표현이 너무 세지 않을까?”, “괜히 책임을 인정하는 건 아닐까?” 같은 불필요한 불안을 줄인다.

## Social Job

영어 때문에 업무 능력이 부족해 보이지 않도록 한다.

---

# 6. 핵심 학습 목적

이 제품은 단순한 vocabulary trainer가 아니다.

핵심은 **pragmatic competence**다.

> **The product trains not merely what to say, but what is appropriate and effective to say in a given professional context.**

사용자는 다음을 배우게 된다.

- direct해야 할 때와 soften해야 할 때의 차이
- commitment 강도의 차이
- hard constraint와 preference를 다르게 말하는 법
- fact와 assumption을 분리하는 법
- responsibility를 불필요하게 인정하거나 떠넘기지 않는 법
- deadline, scope, ownership을 명확하게 만드는 법
- 회의에서 즉시 사용할 수 있는 response frame
- 상황별로 적절한 tone과 firmness를 선택하는 법

---

# 7. 학습 메커니즘

기본 흐름:

> **Context → Compare → Choose → Explain → Retain**

퀴즈의 목적은 정답률 자체가 아니다.

사용자에게 여러 표현을 비교하게 만들어 차이에 주의를 기울이게 하고, 정답 확인 후 실제 업무에서 재사용할 수 있는 패턴을 남긴다.

신규 문제는 주로 **recognition + judgment**를 훈련한다.

복습은 **retrieval**을 추가한다.

---

# 8. Stage 구조

## Stage 1 — Inbox

정상적인 업무 흐름에서 업무를 처리한다.

예:

- request
- follow-up
- scheduling
- clarification
- confirmation
- status update
- expectation setting
- minor correction
- handoff

주로 비동기 커뮤니케이션.

---

## Stage 2 — Speak Up

통상적인 협업 상황에서 **실시간으로** 의견, 질문, 확인, 조율, 결정을 수행한다.

예:

- asking for clarification
- disagreement
- prioritization
- interrupting
- redirecting
- negotiating
- confirming action items

핵심은 갈등의 강도가 아니라 **실시간 상호작용과 즉각적인 언어 선택**이다.

단, 관계·책임·손실·고객 신뢰 등 중대한 문제 관리가 핵심이면 Handle It으로 분류한다.

---

## Stage 3 — Handle It

관계, 책임, 일정 손실, 비용, 고객 신뢰, 업무 경계 또는 실질적 갈등을 관리한다.

예:

- complaint
- confirmed mistake
- responsibility dispute
- scope creep
- unrealistic demands
- missed commitment
- vendor escalation
- client issue
- recovery

채널은 이메일로 편중하지 않는다.

12개 기준 권장 분포:

- Email 2
- Meeting / Video 6
- Phone 3
- Messenger 1

---

# 9. Stage 분류 우선순위

1. **중대한 문제를 관리하거나 해결해야 하는가?**  
   → Handle It

2. 아니라면 **실시간 상호작용인가?**  
   → Speak Up

3. 아니라면  
   → Inbox

Stage와 channel은 별개의 축이다.

---

# 10. 문제 설계 철학

Best Response는:

> **가장 공손한 답**

이 아니라:

> **주어진 business objective를 가장 효과적으로 달성하는 답**

이다.

평가축은 필요에 따라:

- clarity
- factual accuracy
- appropriate certainty
- commitment
- scope
- actionability
- efficiency
- ownership
- timing
- relationship
- tone

을 사용한다.

Direct, concise, firm, diplomatic, empathetic한 표현 중 어느 것도 그 자체로 우월하지 않다.

---

# 11. English Payoff

모든 핵심 문제에는 업무 판단 외에 명확한 **English payoff**가 있어야 한다.

문제를 푼 사용자는 최소 하나를 가져가야 한다.

예:

- reusable pattern
- collocation
- commitment level의 차이
- useful framing
- live response pattern
- fact/assumption을 나누는 표현

단순히:

> “이 상황에서는 상사에게 물어보면 된다.”

만 남는 문제는 영어 학습 가치가 부족하다.

검수 질문:

> **이 문제를 맞히거나 틀린 뒤, 사용자가 실제 업무 영어에서 무엇을 하나 더 할 수 있게 되는가?**

구체적으로 답할 수 없다면 수정 또는 제외한다.

---

# 12. Daily UX Principle

미니앱의 강점은 **낮은 진입 장벽과 짧은 완료 경험**이다.

따라서 기능을 추가하더라도 기본 흐름을 방해하지 않는다.

기본 mandatory flow:

> Inbox → Speak Up → Handle It → Clear

신규 문제는 하루 3개.

사용자에게 별도의 설정이나 학습 관리 업무를 요구하지 않는다.

앱은 “영어 공부를 관리하는 도구”보다 “잠깐 들어와 오늘의 상황 세 개를 해결하는 곳”처럼 느껴져야 한다.

---

# 13. 결과 화면

결과 화면은 직장생활 survival theme를 유지하되 실패감을 과도하게 주지 않는다.

현재 방향:

- 3/3: 회사의 에이스 계열
- 2/3: 무사 퇴근
- 1/3: 아슬아슬한 퇴근
- 0/3: 가벼운 야근/복습 개그

정확한 copy는 UI 단계에서 최종 확정한다.

복습 여부는 점수나 streak와 연결하지 않는다.

---

# 14. 장기 Product Loop

제품은 다음 구조로 발전한다.

> **Daily quiz**
>
> → 유용한 표현 발견
>
> → 내 표현에 저장
>
> → 짧은 retrieval review
>
> → 실제 업무에서 떠올릴 가능성 증가

따라서 `내 표현에 저장`은 단순 bookmark가 아니라:

> **“이 표현을 내 것으로 만들기”**

기능이다.

---

# 15. 경쟁 관점에서의 포지션

이 제품은 AI role-play 서비스와 같은 깊이의 speaking practice를 제공하지 않는다.

대신:

> **role-play보다 훨씬 가볍고, 단순 영어 콘텐츠보다 훨씬 능동적인 micro-training**

을 지향한다.

핵심 차별점은:

- 2~3분 안에 완료
- 실제 workplace judgment
- 표현 간 차이 비교
- reusable pattern 획득
- optional retrieval review

이다.

---

# 16. Visual Design Backlog

현재 콘텐츠 Work 범위에는 포함하지 않는다.

후속 브랜드/UI 단계에서 반복 등장 인물을 설정하는 방향을 검토한다.

예:

- 김대리
- 최과장
- 이사원
- 외부 고객 / vendor 담당자

각 문제에서:

- 이메일 작성
- 화상회의
- 전화
- 사내 대화

등 상황에 맞는 간단한 이미지 또는 일러스트를 제공할 수 있다.

Visual의 목적은 장식이 아니라:

1. scenario를 즉시 이해하게 하고
2. 반복 등장 인물에 친밀감을 만들고
3. 직장생활 시뮬레이션의 연속성을 강화하는 것

이다.

Visual system은 별도의 Character / Brand / UI 작업 단계에서 설계한다.