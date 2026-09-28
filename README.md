# Business English Daily Quiz for Apps-in-Toss

## Project Overview

This project is a business-English daily micro-training service designed for Apps-in-Toss.

The product targets Korean professionals who regularly use English at work but still hesitate when choosing the right wording in real business situations.

The core experience is intentionally lightweight:

> **3 daily workplace situations → 2–3 minutes → Clear**

The goal is not to teach basic grammar or provide long lessons.

The product trains users to make better real-time language choices in professional contexts:

> **Context → Compare → Choose → Explain → Retain**

Users should leave each session with practical, reusable English that is more likely to come to mind in actual work.

---

## Core Product Principle

The service does **not** teach:

> polite = correct  
> direct = wrong

Instead, the best response is the response that most effectively achieves the stated business objective in the given context.

Depending on the situation, the best language may be:

- direct
- concise
- firm
- neutral
- diplomatic
- empathetic

The product focuses on pragmatic competence rather than grammar correctness alone.

---

## Target User

Primary target:

> Korean professionals who regularly communicate in English with overseas clients, partners, headquarters, vendors, or international colleagues, and who can understand ordinary business English but hesitate when choosing wording in real work situations.

Typical pain points:

- wording requests without sounding unclear or unnecessarily weak
- disagreeing in meetings
- responding immediately in live discussions
- rejecting unrealistic requests
- managing deadlines
- handling complaints
- setting boundaries
- reporting problems
- distinguishing facts from assumptions
- deciding how strongly to commit

The product is **not** primarily for:

- beginners who still struggle with basic workplace sentences
- highly fluent professionals for whom English wording is no longer a work bottleneck

---

## Stage Structure

### Stage 1 — Inbox

Routine business communication.

Examples:

- requests
- follow-ups
- scheduling
- clarification
- status updates
- expectation management

Primarily asynchronous communication.

### Stage 2 — Speak Up

Routine **live communication**.

Examples:

- asking questions
- disagreeing
- clarifying
- prioritizing
- redirecting meetings
- confirming decisions

The defining feature is real-time language choice, not conflict intensity.

### Stage 3 — Handle It

Situations involving meaningful risk or friction.

Examples:

- complaints
- confirmed mistakes
- scope creep
- unrealistic demands
- missed commitments
- responsibility disputes
- vendor escalation
- recovery

If the situation involves material relationship, responsibility, cost, schedule, trust, or boundary management, it belongs in Handle It even when the channel is a meeting or phone call.

---

## Daily Learning Flow

Mandatory flow:

> Inbox → Speak Up → Handle It → Clear

Each day contains 3 new questions.

Review is optional and never interrupts the mandatory 3-question flow.

---

## Review System

Review exists to add retrieval practice without making the mini-app feel like a study-management tool.

Review queue entry:

- wrong answer → automatic
- correct answer + user selects **Save to My Expressions** → added to review

Review format:

- compact 1–2 sentence scenario
- no answer choices
- brief mental recall
- reveal answer
- reusable pattern

User choices after review:

- **See again later**
- **I know this now**

Review scheduling is controlled internally by the service.

The user does not manage intervals or memory levels.

Daily automatic review cap:

> **Maximum 2 items per day**

Review does not affect streaks.

---

## Answer Screen

The answer screen is a core learning surface.

It should remain compact.

Recommended structure:

1. Correct / Incorrect
2. Why it works
3. Short contrast when useful
4. Take this with you
5. Save to My Expressions

The objective is for the user to understand the distinction within seconds.

---

## Content Philosophy

Every question should provide an **English payoff**.

A question is weak if the user only learns:

> “Ask your manager which task is more important.”

A stronger question teaches something reusable such as:

> `I'll` vs `I should be able to` vs `I'll do my best`

or:

> `We can't support X without Y.`

or:

> `We haven't confirmed X yet. Let's review Y before we draw a conclusion.`

Each question should answer:

> **After completing this question, what can the user do better in actual business English?**

---

## Question Format

The default objective format is **3 choices**.

- 1 best response
- 2 meaningful distractors

A fourth weak distractor should not be added merely to create a four-choice question.

The two distractors must represent different failure types.

Examples:

- weak commitment
- premature escalation
- unsupported assumption
- vague deadline
- unnecessary concession
- premature admission

Correct-answer position should remain balanced across A / B / C over time.

---

## Repository / Folder Philosophy

Project files should serve as the source of truth.

Do not rely on conversation history as the authoritative project record.

Recommended structure:

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
│   │   ├─ golden-question-set.md
│   │   └─ scenario-bank-v1.md
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
    └─ ...
```

Final product decisions should be written into the relevant files and committed before implementation work begins.

---

## Work / Codex Workflow

### Chat

Use for:

- product judgment
- trade-offs
- content principles
- ambiguous decisions
- revising product rules

### Work

Use for:

- large-scale scenario generation
- coverage analysis
- duplicate audits
- content production
- structured research
- large artifact creation

### Codex

Use for:

- Apps-in-Toss implementation
- data model
- quiz engine
- review engine
- UI
- storage
- ad / login / payment integration
- testing

All three should rely on the repository documents rather than separate conversational memory.

---

## Before Large-Scale Content Production

Work should first produce:

- 120-scenario bank
  - Inbox 40
  - Speak Up 40
  - Handle It 40
- coverage matrix
- duplicate / replacement report
- risk report
- top production candidates

The full question bank should not be mass-produced until the scenario bank is reviewed.

---

## Design Backlog

Visual design is a later phase.

Potential direction:

- recurring workplace characters
- lightweight illustrations for email / meeting / phone situations
- consistent fictional company world
- visual continuity across scenarios

Visuals must support quick comprehension and should never make the mini-app feel heavy.

See `design-backlog.md` for current notes.

---

## Current Status

The following major foundations have been defined:

- target user
- learning purpose
- stage architecture
- question philosophy
- distractor rules
- English-payoff principle
- review system
- answer-screen principle
- scenario-bank expansion process
- visual-design backlog

The next major content step is the structured Scenario Bank 120 expansion.
