# Business English Daily Quiz — Editorial Guide v1.2

## 1. 학습 목표

이 제품은 문법적으로 맞는 영어를 고르는 시험이 아니다.

핵심 목표는 다음과 같다.

> **The product trains not merely what to say, but what is appropriate and effective to say in a given professional context.**

기본 학습 과정은:

**Context → Compare → Choose → Explain → Retain**

이다.

사용자는 실제 업무 상황에서 여러 가능한 대응을 비교하고, 그중 해당 상황의 업무 목적을 가장 효과적으로 달성하는 표현을 선택한다.

---

## 2. Stage 구조

### Stage 1 — Inbox

정상적인 업무 흐름에서 요청, 확인, 일정 조율, 업데이트, 후속 연락 등을 처리한다.

대표 기능:

- request
- follow-up
- scheduling
- confirmation
- clarification
- update
- handoff
- information sharing
- expectation setting
- minor correction

주요 채널은 이메일과 메신저다.

---

### Stage 2 — Speak Up

통상적인 업무 협업 과정에서 **실시간으로** 의견을 제시하고, 질문하고, 확인하고, 조율하고, 결정을 이끌어내는 상황을 다룬다.

핵심은 갈등의 강도가 아니라:

> **실시간 상호작용과 즉각적인 언어 선택**

이다.

다만 관계, 책임, 손실, 고객 신뢰 등 중대한 문제를 관리해야 하는 경우에는 채널이 미팅이나 전화이더라도 Handle It으로 분류한다.

---

### Stage 3 — Handle It

관계, 책임, 비용, 일정 손실, 고객 신뢰, 업무 경계 또는 실질적인 갈등을 관리하거나 해결해야 하는 상황이다.

Stage 분류 우선순위:

1. 중대한 문제를 관리해야 하는가? → **Handle It**
2. 아니라면 실시간 상호작용인가? → **Speak Up**
3. 아니라면 → **Inbox**

Handle It은 이메일 중심으로 만들지 않는다.

12개 기준 권장 채널 구성:

- Email 2
- Meeting / Video call 6
- Phone 3
- Messenger 1

---

## 3. Question Schema

각 문제는 다음 필드를 가진다.

### Identity
- `question_id`
- `status`
- `version`

### Scenario
- `stage`
- `situation_family`
- `scenario_id`
- `storyline_id` — optional

### Context
- `channel`
- `communication_mode`
- `context`
- `speaker_role`
- `counterpart_role`
- `power_relationship`
- `relationship_status`
- `stakes`

### Learning Design
- `business_goal`
- `primary_communication_challenge`
- `desired_tone`
- `language_function`
- `difficulty`
- `question_type`

### Question
- `scenario_text`
- `prompt`
- `option_1`
- `option_2`
- `option_3`
- `correct_option`

### Explanation
- `option_rationale_1`
- `option_rationale_2`
- `option_rationale_3`
- `distractor_type_1`
- `distractor_type_2`
- `answer_explanation`

### Learning Asset
- `key_expression` — optional
- `expression_note` — optional
- `tags`

---

## 4. 기본 객관식 구조

기본은 **3지선다**다.

- Best answer 1개
- 의미 있는 distractor 2개

4번째 선택지를 채우기 위해 질이 낮은 오답을 추가하지 않는다.

Best Response형에서 나머지 두 표현은 현실에서 절대로 쓸 수 없는 문장일 필요는 없다.

문항에 따라 다음이 섞일 수 있다.

- clearly inappropriate
- acceptable but suboptimal
- plausible but risky

---

## 5. Best Response의 정의

Best Response는:

> **해당 scenario에 명시된 business objective를 가장 효과적으로 달성하는 response**

다.

가장 공손한 문장, 가장 길고 친절한 문장, 가장 완곡한 문장을 의미하지 않는다.

다음 요소를 필요에 따라 평가한다.

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

**Politeness는 여러 평가축 중 하나일 뿐이다.**

---

## 6. Directness Neutrality Rule

Direct, concise, firm, diplomatic, empathetic한 표현 중 어느 것도 그 자체로 우월하지 않다.

상황에 따라 가장 직접적인 답이 정답일 수 있다.

예:

- 이미 합의된 deadline을 다시 확인할 때
- 반복적으로 납기를 어긴 vendor에게 확정적인 행동을 요구할 때
- 지킬 수 없는 일정 요구를 거절할 때
- 잘못된 사실관계를 바로잡을 때
- 명확한 책임·담당자를 정할 때

반대로 directness가 오답 사유가 되려면:

> **그 직접성 때문에 현재 업무 목적에 불필요한 비용이나 위험이 생긴다는 이유**

가 있어야 한다.

단순히 “너무 direct하다”만으로는 충분한 오답 근거가 아니다.

---

## 7. Operational Consequence Rule

가능한 경우 tone 차이보다 **업무 결과에 실제로 영향을 미치는 차이**를 우선한다.

좋은 비교축:

- deadline이 명확한가
- 실제로 이행 가능한 commitment인가
- 책임을 성급하게 인정하는가
- 상대가 다음 행동을 알 수 있는가
- scope를 불필요하게 포기하는가
- 사실보다 강하게 단정하는가
- 결정해야 할 사항이 결정되는가
- ownership이 명확한가

Tone 관련 판단 역시 사용할 수 있지만 문제은행 전체를 지배해서는 안 된다.

---

## 8. Single-Axis Contrast Rule

가능한 경우 세 선택지는:

- 비슷한 길이
- 비슷한 정보량
- 모두 자연스러운 영어

를 유지한다.

정답에만 acknowledgment + reason + alternative + next step + question을 모두 몰아넣고 오답은 짧게 만드는 구조를 피한다.

문항의 핵심 communication challenge와 관련된 **한두 가지 주요 차이**로 선택지를 구분한다.

---

## 9. Length Parity Rule

정답이 반복적으로 가장 길어서는 안 된다.

정답이 가장 짧아도 되고, 중간 길이여도 되고, 가장 길 수도 있다.

사용자가 “제일 긴 답을 고르면 된다”는 패턴을 학습할 수 없어야 한다.

---

## 10. Distractor Rule

### 10.1 서로 다른 실패 유형

두 distractor는 반드시 서로 다른 실패 유형을 가진다.

예:

- vague deadline
- unsupported commitment

처럼 서로 다른 판단 오류를 구성한다.

### 10.2 선택 이유가 있어야 한다

각 distractor에 대해 다음 질문에 답할 수 있어야 한다.

> **왜 어떤 사용자는 이 선택지를 고를 수 있는가?**

답을 설명할 수 없다면 좋은 distractor가 아니다.

### 10.3 명백한 오답도 사용할 수 있다

모든 distractor를 미묘하게 만들 필요는 없다.

일부 Difficulty 1 또는 비교적 쉬운 문제에서는:

- 지나치게 공격적인 표현
- 무조건적 수용
- 지나친 사과
- 명백한 회피

가 포함될 수 있다.

다만 단순 우스운 문장이나 맥락 없는 “나쁜 영어”가 아니라 **실제 잘못된 업무 판단으로 나올 수 있는 표현**이어야 한다.

---

## 11. 주요 Distractor Categories

### Clarity / Action
- too vague
- unclear deadline
- unclear ownership
- no actionable next step

### Commitment
- overcommitment
- weak commitment
- ambiguous commitment
- avoids commitment

### Factual Position
- unsupported assumption
- premature admission
- premature blame
- excessive certainty

### Scope / Authority
- unnecessary concession
- promises outside authority
- unnecessarily rigid boundary
- unclear boundary

### Process
- acts before confirming
- postpones a decision unnecessarily
- fails to escalate when required
- escalates before necessary

### Tone / Relationship
- unnecessarily confrontational
- unnecessarily apologetic
- too weak for the situation
- unnecessarily indirect
- dismissive

---

## 12. Scenario 작성

Scenario는 **가급적 2~3문장 이내**로 작성한다.

4문장은 특별한 이유가 없으면 사용하지 않는다.

정답 판단에 필요한 정보만 넣는다.

특히 다음 정보 중 필요한 것을 명확히 한다.

- 상대방
- 목표
- 현재 알려진 사실
- deadline 또는 constraint
- 관계 및 권한
- 어느 정도까지 협상 가능한지

이 정보가 없으면 조직 문화나 개인 스타일에 따라 정답이 달라질 수 있는 문항은 출제하지 않는다.

---

## 13. Hidden Premise Rule

정답을 결정하는 업무상 전제는 문제 제작자의 머릿속에만 존재해서는 안 된다.

예를 들어 직원이 직접 우선순위를 정하는 것도 충분히 좋은 업무 방식일 수 있다.

따라서 상사가 직접 우선순위를 정해야 하는 것이 정답의 근거라면:

> 두 업무의 대외적 중요도는 상사만 알고 있다.

등의 조건을 scenario에 명시한다.

**Scenario에 제시되지 않은 조직문화, 권한관계, 회사방침을 정답 근거로 사용하지 않는다.**

---

## 14. One Primary Challenge Rule

한 문제는 하나의 핵심 판단을 중심으로 설계한다.

내부적으로 다음 문장을 완성하는 것을 권장한다.

> **The user needs to ______ without ______.**

예:

- confirm a firm deadline without making it sound optional
- reject an unrealistic date without implying it might still be possible
- acknowledge a complaint without admitting an unverified cause
- set a boundary without accidentally accepting the work

---

## 15. Response Unit Rule

Live communication 문제에서 평가 단위는 원칙적으로 **하나의 자연스러운 conversational turn**이다.

`What should you say next?`는 반드시 한 문장만 의미하지 않는다. 필요하다면 자연스럽게 이어지는 두 문장까지 하나의 response로 볼 수 있다.

따라서 어떤 distractor에 간단한 후속 문장 하나만 덧붙이면 정답과 사실상 동등한 대응이 되는 경우, 단순히 그 후속 문장이 생략되어 있다는 이유만으로 오답 처리하지 않는다.

특정한 **첫 질문 / 첫 반응 / 첫 문장**만 평가하려는 경우에는 prompt에서 명확히 한정한다.

예:

- What would be the best first question?
- What should you say first?

---

## 16. English Payoff Rule

모든 핵심 문항에는 업무 판단 외에 **명확한 영어 학습 보상**이 있어야 한다.

좋은 문제를 푼 사용자는 최소한 하나를 가져갈 수 있어야 한다.

- reusable sentence pattern
- collocation
- commitment 강도의 차이
- directness / hedging의 효과
- fact / assumption을 구분하는 표현
- deadline / ownership / boundary 설정 방식
- 실제 회의에서 바로 쓸 수 있는 response frame

단순히:

> “이 상황에서는 상사에게 물어보는 게 좋다.”

만 남는 문제는 영어 학습 문제로서 약하다.

좋은 결과는:

> “확답이 가능한 상황에서는 `I should be able to`보다 `I’ll…`이 더 정확한 commitment구나.”

처럼 **업무 판단과 영어 표현상의 발견이 함께 남는 것**이다.

---

## 17. Question Types

주력:

- Best Response
- Best Revision
- Tone Check
- Choose the Follow-up

보조:

- What's Wrong?
- Order the Message
- Fill the Expression

Fill the Expression 등 전통적인 영어 퀴즈형은 제품의 핵심 차별성이 약하므로 제한적으로 사용한다.

---

## 18. Difficulty

### Difficulty 1

비교적 명확한 문제.

한두 선택지는 쉽게 제거할 수 있으나, 표현이나 communication pattern에 학습 가치가 있어야 한다.

### Difficulty 2

제품의 기본 난이도.

두 distractor도 합리적인 선택 이유가 있으나, scenario를 제대로 읽으면 하나가 업무 목적을 더 정확히 달성한다.

### Difficulty 3

책임, certainty, hierarchy, commitment 등 미묘한 차이를 판단한다.

세 문장이 모두 plausible할 수 있으나 조직 문화나 개인 취향만으로 답이 달라질 정도라면 출제하지 않는다.

초기 권장 분포:

- Difficulty 1: 20~25%
- Difficulty 2: 약 60%
- Difficulty 3: 15~20%

실제 서비스 데이터에서는 문항별 **약 70~85% 정답률**을 중심 범위로 가정하되, 데이터에 따라 조정한다.

---

## 19. Response Style Balance

문제은행에서 정답이 특정 스타일에 편중되지 않도록 한다.

정답으로 모두 등장해야 하는 스타일:

- direct + clear
- concise
- firm + bounded
- neutral + factual
- diplomatic + collaborative
- empathetic + solution-oriented

특히 Golden Set에는:

- 가장 direct한 선택지가 정답인 문제
- 가장 짧은 선택지가 정답인 문제
- 가장 polite한 선택지가 오답인 문제

를 의도적으로 포함한다.

---

## 20. Answer Position Balance

정답 위치가 패턴화되지 않도록 관리한다.

Golden Set에서는 A/B/C를 동일하게 배분한다.

대규모 문제은행에서도 장기적으로 각각 약 1/3이 되도록 관리하되, 사용자가 예측할 수 있는 규칙적인 순환 패턴은 만들지 않는다.

---

## 21. Result Explanation Structure

정답 화면은 가능하면 두 층으로 구성한다.

### Why it works

이 상황에서 왜 이 response가 업무 목적을 잘 달성하는지 설명한다.

### Take this with you

다른 업무 상황에서도 재사용 가능한 영어 표현 또는 pattern을 짧게 제시한다.

`Take this with you`의 내용은 **[내 표현에 저장]** 대상이 될 수 있다.

모든 문제에서 반드시 한 문장을 저장하게 할 필요는 없지만, 주력 문항에서는 가능한 한 명확한 reusable payoff를 설계한다.

---

## 22. Answer Screen Length Principle

정답 화면이 문제보다 훨씬 길어져서는 안 된다.

목표는 사용자가:

> “아, 차이가 이거구나.”

를 수 초 안에 이해하는 것이다.

긴 문법 설명, 여러 예문, 어원, 유사 표현 목록은 기본 화면에서 제공하지 않는다.

---

## 23. Workplace Judgment Check

문항 검수 시 다음 질문을 추가한다.

> **선택지를 한국어로 번역해도 사실상 같은 문제가 되는가?**

그렇다면 순수한 직장생활 상식 문제가 아닌지 점검한다.

업무 상황 판단 자체는 필요하지만, 문제의 학습 가치에는 영어 표현상의 차이가 포함되어야 한다.

---

## 24. 복습 연계 원칙

틀린 문제는 자동으로 복습 큐에 들어간다.

맞힌 문제는 사용자가 **[내 표현에 저장]**한 경우 복습 대상이 된다.

복습은:

- 짧은 scenario
- 선택지 없음
- 잠깐 생각
- `[정답 보기]`
- reusable pattern 확인

형식으로 진행한다.

복습 후에는:

- `[다음에 다시 보기]`
- `[이제 알겠어요]`

중 하나를 선택한다.

사용자에게 복습 간격이나 4단계 기억도 설정을 노출하지 않는다.

하루 자동 복습 출제는 **최대 2개**다.

복습은 신규 3문제 완료 후 optional이며 streak에 영향을 주지 않는다.

---

## 25. 최종 QA Checklist

### Scenario
- 실제 업무 상황인가?
- Primary Persona에게 유용한가?
- 가급적 2~3문장 안에 필요한 context가 들어가는가?
- 정답이 조직 취향만으로 갈리지 않도록 조건이 충분한가?
- hidden premise가 없는가?

### Answer
- 가장 polite해서가 아니라 business objective를 가장 잘 달성하는가?
- 더 직접적인 답이 더 좋을 가능성을 검토했는가?
- 더 짧은 답이 더 효율적일 가능성을 검토했는가?

### Options
- 두 distractor는 서로 다른 실패 유형인가?
- 각 distractor를 사용자가 고를 이유가 있는가?
- 정답만 유난히 길거나 정보가 많지 않은가?
- 세 선택지 모두 충분히 자연스러운 영어인가?

### Learning Value
- 문법 정오 이상의 판단을 요구하는가?
- 사용자가 다음 업무에서 재사용할 원칙 또는 표현을 얻는가?
- 명확한 English payoff가 있는가?

### Bias Check
- “더 공손한 답 = 정답” 패턴이 아닌가?
- directness를 이유 없이 감점하지 않았는가?
- 과도한 hedging을 무조건 좋은 영어로 취급하지 않았는가?

### Final Value Test
- 이 문제를 맞히거나 틀린 뒤, 사용자가 실제 업무 영어에서 무엇을 하나 더 할 수 있게 되는가?

구체적인 답이 없다면 문제를 수정하거나 제외한다.

---

## 26. 최종 Editorial Principle

우선순위는 다음과 같다.

1. 실제 업무상 효과
2. 정답의 명확성
3. 학습 가치
4. 자연스러운 영어
5. 난이도
6. 재미

최종 목표는:

> **가장 예의 바른 영어를 고르는 문제가 아니라, 이 상황에서 실제로 일을 가장 잘 되게 하는 영어를 고르는 문제**

를 만드는 것이다.
