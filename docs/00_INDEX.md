# Documentation Index

> **Start here.**
>
> This file is the navigation map for all product, learning, content, Work, and future implementation documents.
>
> Anyone working on this project — including ChatGPT Work or Codex agents — should read this file before changing product behavior, generating large amounts of content, or implementing app logic.

---

## 1. Document Priority

When documents conflict:

1. the newest explicit product decision wins
2. the newest version of the relevant specification wins
3. Golden examples illustrate the rules but do not override newer written rules
4. do not silently resolve material conflicts — report them

Conversation history is **not** the source of truth once a decision has been captured in the project documents.

---

## 2. Core Product Documents

### `README.md`
**Status:** Available.

**Purpose:** Project overview and repository operating model.

Read when:
- joining the project
- understanding the overall product
- deciding which document to consult next

Contains:
- target user
- core experience
- stage overview
- learning loop
- review summary
- Work / Codex division of responsibilities

---

### `product/product-learning-spec.md`
**Status:** Available.

**Purpose:** Authoritative product and learning definition.

Read before:
- changing target users
- changing the core learning mechanism
- changing Stage definitions
- changing Daily UX
- making positioning decisions
- designing major new product functionality

Contains:
- product definition
- Primary / Secondary target
- exclusion groups
- JTBD
- pragmatic competence goal
- stage structure
- daily learning loop
- English Payoff
- mini-app simplicity principle
- long-term product loop
- product positioning
- visual-design backlog boundary

---

## 3. Content Standards

### `content/editorial-guide.md`
**Status:** Available.

**Purpose:** Authoritative content-production and question-writing rules.

Read before:
- creating questions
- editing questions
- designing distractors
- determining correct answers
- writing explanations
- evaluating ambiguity
- producing content at scale

Key rules include:
- 3-choice default
- Best Response definition
- Directness Neutrality
- Operational Consequence
- Single-Axis Contrast
- Length Parity
- distinct distractor failure types
- Hidden Premise Rule
- One Primary Challenge Rule
- Response Unit Rule
- English Payoff Rule
- answer-position balance
- answer-screen brevity
- review linkage
- QA checklist

This is one of the most important documents in the repository.

---

### `content/scenario-bank-structure.md`
**Status:** Available.

**Purpose:** Defines what counts as a scenario and how the Scenario Bank should be structured.

Read before:
- adding scenarios
- changing scenario metadata
- evaluating Stage coverage
- building storyline groups
- expanding the scenario bank

Contains:
- Scenario vs Question distinction
- Stage classification priority
- Scenario schema
- field definitions
- English Payoff gate
- coverage rules
- channel balance
- counterpart balance
- internal / external balance
- duplicate rules
- storyline rules
- response-style balance
- scenario approval checklist
- representative Golden Scenario Set

---

### `content/golden-question-set.md`
**Status:** Available.

**Purpose:** Reference-quality examples showing how the editorial rules should look in actual questions.

Read before:
- generating questions with AI
- training/reviewing content teams
- evaluating whether new questions match product quality
- interpreting abstract editorial rules

Important:
Golden questions are **examples**, not templates to copy mechanically.

Do not:
- repeat the same sentence structures
- copy distractor patterns too frequently
- infer that the most common answer style in the Golden Set should always be correct

Use them to understand:
- expected level of context
- English payoff
- distractor quality
- explanation length
- directness / politeness balance
- Response Unit handling
- Hidden Premise handling
- A/B/C answer-position balance

---

## 4. Learning / Review Documents

### `learning/answer-review-system.md`
**Status:** Available.

**Purpose:** Defines the answer-screen learning experience and optional review system.

Read before:
- changing answer feedback
- changing Save to My Expressions
- changing review eligibility
- changing review scheduling
- changing daily review volume
- implementing review in the app

Key decisions:
- wrong questions enter review automatically
- correct questions enter review only when saved
- review uses a compact scenario
- review has no multiple-choice options
- user recalls briefly, then reveals the answer
- user chooses:
  - See again later
  - I know this now
- review intervals are automatic
- user does not manage memory levels
- maximum automatic review: **2 per day**
- review is optional after the 3 new questions
- review does not affect streaks
- saved expressions remain saved even after active review ends

---

## 5. Work Instructions

### `work/scenario-bank-120-brief.md`
**Status:** Available.

**Purpose:** Work assignment for the first large-scale content-production phase.

Work should use this brief to produce:

- Inbox 40 scenarios
- Speak Up 40 scenarios
- Handle It 40 scenarios
- Coverage Matrix
- Duplicate / Replacement Report
- Risk Report
- Top 20 Production Candidates

Important:
Work should **not** mass-produce the full question bank during this assignment.

Required process:

1. framework check
2. draft scenarios
3. coverage audit
4. duplicate audit
5. bias audit
6. revision
7. final scenario bank

The Work brief must be used together with:
- `product/product-learning-spec.md`
- `content/editorial-guide.md`
- `content/scenario-bank-structure.md`
- `content/golden-question-set.md`
- `learning/answer-review-system.md`

---

## 6. Work Output Documents

The Scenario Bank and Question Production Pilot outputs completed Work internal QA and product review on 2026-09-28.

### `content/scenario-bank-v1.md`
**Status:** Available — Approved for Question Production.

Approved Scenario Bank containing 120 scenarios and the Top 20 Production Candidates. These are approved scenario designs, not finished questions.

### `content/scenario-coverage-v1.csv`
**Status:** Available — Approved coverage baseline.

Approved row-level coverage data for the 120-scenario bank, suitable for quantitative inspection.

### `content/scenario-audit-v1.md`
**Status:** Available — Product review completed.

Work internal QA record plus duplicate, replacement, bias, risk, targeted-revision, and final product-review outcome.

Product review was completed on 2026-09-28. Scenario Bank v1 is approved for Question Production.

### `content/question-pilot-top20.md`
**Status:** Available — Product Review Passed.

Approved production baseline containing the 20 finished pilot questions, answer screens, and review variants.

### `content/question-pilot-audit.md`
**Status:** Available — Product Review Passed.

Cross-question audit for the approved pilot against Editorial Guide v1.4. The pilot is approved, and production of the remaining 100 questions is authorized.

---

## 7. Design Backlog

### `backlog/design-backlog.md`
**Status:** Available.

**Purpose:** Stores design ideas that should not interfere with the present content-production phase.

Current themes:
- recurring characters
- fictional-company continuity
- question visuals
- email / meeting / phone illustrations
- visual asset reuse
- Stage visual language
- result-screen theme
- review UI
- Save to My Expressions UX
- future illustration-production pipeline

Important:
This document is **not** an implementation specification yet.

Do not treat backlog items as approved product requirements unless they are separately promoted into a current product/design specification.

---

## 8. Codex / Repository Guidance

### `AGENTS.md`
**Status:** Available.

**Purpose:** Repository-level instructions for Codex agents.

Current guidance includes:

- read `docs/00_INDEX.md` before changing product behavior
- read `product-learning-spec.md` before product changes
- read `editorial-guide.md`, `scenario-bank-structure.md`, and `golden-question-set.md` before quiz/content changes
- read `answer-review-system.md` before review changes
- treat `docs/` as authoritative
- do not silently change product rules
- report implementation/spec conflicts first

When application code exists, extend `AGENTS.md` with:
- build commands
- test commands
- lint commands
- Apps-in-Toss integration notes
- repository conventions

---

## 9. Stage Classification Quick Reference

Use this order:

### 1. Is the user managing a material problem?

Examples:
- responsibility
- complaint
- meaningful delay
- scope conflict
- customer trust
- serious vendor issue
- material boundary

→ **Handle It**

### 2. If not, is it routine live interaction?

Examples:
- question
- disagreement
- prioritization
- clarification
- meeting management

→ **Speak Up**

### 3. Otherwise

→ **Inbox**

Channel alone never determines Stage.

---

## 10. Core Content Quality Quick Reference

A good question should satisfy all of the following:

- realistic workplace context
- useful to the Primary Target
- usually 2–3 scenario sentences or fewer
- one clear primary communication challenge
- one best answer
- two distractors with different failure types
- no hidden premise
- no automatic “polite = correct” bias
- no automatic “direct = wrong” bias
- meaningful English payoff
- reusable business-English insight
- concise explanation
- no industry expertise required unless explicitly intended

Ask:

> **After this question, what can the user do better in actual business English?**

If there is no concrete answer, revise or remove the question.

---

## 11. Mini-App Simplicity Rule

Every feature must respect the core experience:

> **3 new questions → about 2–3 minutes → Clear**

Do not turn the service into:
- a settings-heavy SRS tool
- a long course
- a textbook
- a dashboard-heavy learning-management product

Review, saved expressions, visuals, and future monetization must remain subordinate to the fast daily experience.

Review is intentionally lightweight:
- optional
- maximum 2 automatic review items per day
- no user-managed intervals
- no memory-level configuration

---

## 12. Current Repository Structure

Recommended current structure:

```text
business-english-toss/
│
├─ README.md
├─ AGENTS.md
│
├─ docs/
│   ├─ 00_INDEX.md
│   │
│   ├─ product/
│   │   └─ product-learning-spec.md
│   │
│   ├─ content/
│   │   ├─ editorial-guide.md
│   │   ├─ scenario-bank-structure.md
│   │   └─ golden-question-set.md
│   │
│   ├─ learning/
│   │   └─ answer-review-system.md
│   │
│   ├─ work/
│   │   └─ scenario-bank-120-brief.md
│   │
│   └─ backlog/
│       └─ design-backlog.md
│
└─ app/
    └─ (future Apps-in-Toss implementation)
```

---

## 13. Current Next Step

The Question Production Pilot passed Product Review on 2026-09-28. The approved pilot is the production baseline, and production of the remaining 100 questions is authorized.

Recommended sequence:

1. use the approved Pilot v3 as the production baseline
2. produce the remaining 100 questions from the approved Scenario Bank
3. apply the Editorial Guide v1.4 rules and the pilot audit's production guidance during drafting
4. run staged QA for answer-position balance, target-customer distractor plausibility, unique-answer robustness, directness neutrality, explanation brevity, and review suitability
5. resolve any blocking specification conflict before changing authoritative product rules
6. later use the same repository as Codex implementation context

---

## 14. Current Content Boundary

The following are **in scope now**:

- target and learning definition
- content architecture
- Scenario Bank expansion
- English Payoff
- review logic
- answer-screen learning structure

The following are **not part of the current Work assignment**:

- full app implementation
- illustration generation
- character visual design
- UI implementation
- advertising implementation
- monetization implementation

Visual ideas remain in `design-backlog.md` until a later design phase.

---

## 15. Final Operating Principle

Project documents, not chat history, are the shared source of truth for Work and Codex.

Before making a material change:

1. read this index
2. read the relevant authoritative spec
3. make the change
4. update the relevant project document
5. commit the new baseline before parallel implementation or large-scale production
