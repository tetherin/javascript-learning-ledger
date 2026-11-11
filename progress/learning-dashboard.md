# Learning Dashboard

**Status:** Session 03 in progress — 10 concepts taught; exercises pending  
**Last updated:** 2026-11-11  
**Completed formal sessions:** 0  
**Current session:** [Session 03 — Property Semantics, Copying, and Safe Request Data](../session-reports/2026-11-11-session-03.md)  
**Previous sessions:** [Session 02](../session-reports/2026-11-10-session-02.md) · [Session 01](../session-reports/2026-11-09-session-01.md)

## Current focus
1. Reassess own vs inherited and enumerable vs non-enumerable properties; Session 01 Q1 and Session 02 Exercise A remain unanswered.
2. Complete safe query validation; Session 01 Q3 and Session 02 Exercise B remain unanswered.
3. Demonstrate property descriptor defaults, accessor descriptors, non-configurable invariants, and descriptor-preserving shallow copies.
4. Apply prototype-pollution defenses to dynamic keys and untrusted request data.
5. Retain freeze/seal, map/forEach, and sort/toSorted distinctions with independent recall.
6. Keep shallow-copy review scheduled for 2026-11-17 after two successful practical demonstrations.

## Progress summary
| Area | Status | Evidence / next action |
|---|---|---|
| Object.keys(), Object.values(), Object.entries() | Introduced; partial understanding | Session 01 Q1 included inherited and non-enumerable properties incorrectly; retaught in Sessions 02 and 03; independent retest pending |
| Object.getOwnPropertyNames() / Reflect.ownKeys() | Introduced | Session 03 taught differences for non-enumerable and Symbol keys; output exercise pending |
| Object.hasOwn() vs in vs propertyIsEnumerable() | Practicing | Session 01 second output was correct; retaught with non-enumerable and prototype cases; independent explanation pending |
| Property descriptors / Object.defineProperty() | Introduced | Sessions 02 and 03 taught descriptor types, defaults, and invariants; no independent answer yet |
| Accessor descriptors | Introduced | Session 03 taught getter/setter behavior and descriptor restrictions; no independent implementation yet |
| Object.getOwnPropertyDescriptors() | Introduced | Session 03 taught descriptor-preserving shallow copy; no independent implementation yet |
| Object.fromEntries() / filter() | Introduced | Session 01 transformation approach was sound but validation implementation had gaps; safe validator exercise pending |
| Shallow vs deep copying / structuredClone() | Practicing | Correct basic prediction and practical shared-headers bug fix; next spaced review 2026-11-17 |
| Object.preventExtensions() / seal() / freeze() | Introduced; review due | Revisited in Session 03; independent recall pending |
| map() vs forEach() | Introduced; review due | Revisited async forEach trap in Session 03; independent recall pending |
| sort() vs toSorted() | Introduced; review due | Revisited mutation, comparator, and shallow-copy behavior in Session 03; independent recall pending |
| Prototype pollution / Map / null-prototype dictionaries | Introduced | Taught in Sessions 02 and 03; case-based implementation pending |
| Backend query validation | Introduced; needs practice | Session 01 implementation had guard, mutation, numeric-validation, and allowlist gaps; Sessions 02 and 03 revisited; implementation pending |
| Functions and scope | Unassessed | Baseline questions later |
| Async JavaScript | Unassessed | Baseline questions later |
| React, Node.js, TypeScript, databases, authentication | Unassessed | Assess progressively |

## Learning cadence
- **Session 03 first recall:** 2026-11-12 for descriptor semantics and safe dynamic-key handling, adjusted based on answers.
- **Session 01/02 outstanding exercises:** remain pending; do not infer success from repeated explanations.
- **Shallow-copy spaced review:** 2026-11-17.
- Advance spaced-repetition intervals only after demonstrated recall.
- **Monthly assessment target:** approximately 2026-12-09, if enough material has been covered.
- **Project application:** after 4 completed sessions. No formal session has been completed yet.

## Rules
- Do not mark topics mastered based on exposure alone.
- Record evidence from explanations, code, debugging, and transfer to unfamiliar cases.
- Keep exactly 10 tips per teaching session; follow-up evaluation and targeted retests reinforce those tips.
- Never record an unanswered or misunderstood exercise as correct.
