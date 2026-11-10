# Learning Dashboard

**Status:** Session 02 in progress; Session 01 remains open pending outstanding reviews  
**Last updated:** 2026-11-10  
**Completed formal sessions:** 0  
**Current session:** [Session 02 — Property Descriptors, Safe Object Handling, and Query Validation](../session-reports/2026-11-10-session-02.md)  
**Previous session:** [Session 01 — JavaScript Objects and Safe Data Transformation](../session-reports/2026-11-09-session-01.md)

## Current focus
1. Reassess own vs inherited and enumerable vs non-enumerable properties after the Q1 error.
2. Practice safe query normalization and complete the query-validation implementation after the Q3 gaps.
3. Learn property descriptors and the defaults of Object.defineProperty().
4. Retain the reviewed freeze/seal, map/forEach, and sort/toSorted distinctions.
5. Keep shallow-copy review scheduled for 2026-11-17 after two successful practical examples.

## Progress summary
| Area | Status | Evidence / next action |
|---|---|---|
| Object.keys() / Object.entries() | Introduced; partial understanding | Session 01 Q1 included inherited and non-enumerable properties incorrectly; Session 02 retest pending |
| Object.hasOwn() vs in | Practicing | Session 01 second output was correct; explanation and new case retest pending |
| Property descriptors / Object.defineProperty() | Introduced | Taught in Session 02; independent output-prediction exercise pending |
| Object.fromEntries() / filter() | Introduced | Session 01 approach was sound but validation implementation had gaps; Session 02 practical exercise pending |
| Shallow vs deep copying / structuredClone() | Practicing | Correct basic prediction and practical shared-headers bug fix; next spaced review 2026-11-17 |
| Object.freeze() vs Object.seal() | Introduced; review due | Taught in Session 01 and reviewed in Session 02; recall answer pending |
| map() vs forEach() | Introduced; review due | Reviewed in Session 02; recall answer pending |
| sort() vs toSorted() | Introduced; review due | Reviewed in Session 02; recall answer pending |
| Prototype pollution / safe dictionaries | Introduced | Taught in Session 02; case-based application pending |
| Backend query validation | Introduced; needs practice | Session 01 implementation had guard, mutation, numeric-validation, and allowlist gaps; Session 02 retest pending |
| Functions and scope | Unassessed | Baseline questions later |
| Async JavaScript | Unassessed | Baseline questions later |
| React, Node.js, TypeScript, databases, authentication | Unassessed | Assess progressively |

## Learning cadence
- **Session 02 first recall:** 2026-11-11 for descriptors and safe dictionary concepts, adjusted based on answers.
- **Session 01 targeted reviews:** own/enumerable properties and query validation remain pending.
- **Shallow-copy spaced review:** 2026-11-17.
- Advance spaced-repetition intervals only after demonstrated recall.
- **Monthly assessment target:** approximately 2026-12-09, if enough material has been covered.
- **Project application:** after 4 completed sessions. No formal session has been completed yet.

## Rules
- Do not mark topics mastered based on exposure alone.
- Record evidence from explanations, code, debugging, and transfer to unfamiliar cases.
- Keep exactly 10 tips per teaching session; follow-up evaluation and targeted retests reinforce those tips.
- Never record an unanswered or misunderstood exercise as correct.
