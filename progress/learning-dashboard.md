# Learning Dashboard

**Status:** Session 05 in progress — exactly 10 concepts taught; exercises pending  
**Last updated:** 2026-11-13  
**Completed formal sessions:** 0  
**Current session:** [Session 05 — Object Assignment Semantics and Safe Backend Boundaries](../session-reports/2026-11-13-session-05.md)  
**Previous sessions:** [Session 04](../session-reports/2026-11-12-session-04.md) · [Session 03](../session-reports/2026-11-11-session-03.md) · [Session 02](../session-reports/2026-11-10-session-02.md) · [Session 01](../session-reports/2026-11-09-session-01.md)

## Current focus
1. Complete Session 05's Object.assign/spread output checkpoint, including setter invocation, target identity, and own-property behavior.
2. Complete Session 04's earlier setter checkpoint; it remains unanswered.
3. Implement the safe parseLimit(query) helper using unknown narrowing and own-property presence.
4. Retest enumeration, descriptors, non-configurable invariants, and descriptor-preserving shallow copies from Sessions 01–04.
5. Explain Object.assign partial mutation, nested merge replacement, and source-getter behavior.
6. Apply Promise.allSettled with a real concurrency cap to a batch-job case.
7. Keep shallow-copy review scheduled for 2026-11-17; do not advance intervals without independent recall.

## Progress summary
| Area | Status | Evidence / next action |
|---|---|---|
| Object.keys(), Object.values(), Object.entries() | Introduced; partial understanding | Session 01 Q1 included inherited and non-enumerable properties incorrectly; retaught in Sessions 02–04; independent retest pending |
| Object.getOwnPropertyNames() / Reflect.ownKeys() | Introduced | Differences for non-enumerable and Symbol keys taught in Sessions 03–04; independent output pending |
| Object.hasOwn() vs in vs propertyIsEnumerable() | Practicing | Session 01 second output was correct; later cases taught but independent explanation pending |
| Property descriptors / Object.defineProperty() | Introduced | Descriptor defaults, accessor/data types, and non-configurable invariants taught; independent output and implementation pending |
| Accessor descriptors | Introduced | Getter/setter behavior and assignment-vs-definition semantics taught; independent implementation pending |
| Object.getOwnPropertyDescriptors() | Introduced | Descriptor-preserving shallow-copy pattern taught; compare with spread and structuredClone in code |
| Object.assign() vs object spread | Introduced for semantic differences; shallow copying Practicing | Shared-reference bug independently fixed with structuredClone; setter and getter differences newly taught |
| Object.fromEntries() / filter() | Introduced | Session 01 transformation approach was sound but validation implementation had gaps; safe validator exercise pending |
| Shallow vs deep copying / structuredClone() | Practicing | Correct basic prediction and practical shared-headers bug fix; next spaced review 2026-11-17 |
| Object.preventExtensions() / seal() / freeze() | Introduced; review due | Differences and is* inspection methods taught; independent recall pending |
| Map / Object.create(null) / prototype pollution | Introduced | Safe dictionary trade-offs taught; case-based implementation pending |
| map() vs forEach() | Introduced; review due | Async forEach trap taught; independent explanation pending |
| sort() vs toSorted() | Introduced; review due | Mutation and shallow-copy behavior taught; independent explanation pending |
| Promise.all() vs Promise.allSettled() / concurrency | Introduced | Failure behavior and unbounded concurrency trade-offs taught; independent case analysis pending |
| Backend query validation | Introduced; needs practice | Earlier validator had guard, mutation, numeric-validation, and allowlist gaps; safe own-property and unknown-value validation revisited |
| TypeScript unknown/narrowing | Introduced | Runtime validation boundary taught; no independent type guard yet |
| Functions and scope | Unassessed | Baseline questions later |
| React, Node.js, TypeScript, databases, authentication | Unassessed or introduced only where noted | Assess progressively |

## Learning cadence
- **Session 04 first recall:** 2026-11-13 for descriptor invariants, descriptor-preserving copies, Object.assign/spread semantics, safe dictionaries, and untrusted query values; adjust based on actual answers.
- **Session 01/02/03 outstanding exercises:** remain pending; do not infer success from repeated explanations.
- **Session 05 first recall:** 2026-11-14 for Object.assign partial mutation, nested merge behavior, getter/descriptor copying, parseLimit validation, and bounded concurrency.
- **Shallow-copy spaced review:** 2026-11-17.
- Advance spaced-repetition intervals only after demonstrated recall.
- **Monthly assessment target:** approximately 2026-12-09, if enough material has been covered.
- **Project application:** after 4 completed sessions. No formal session has been completed yet.

## Rules
- Do not mark topics mastered based on exposure alone.
- Record evidence from explanations, code, debugging, and transfer to unfamiliar cases.
- Keep exactly 10 tips per teaching session; follow-up evaluation and targeted retests reinforce those tips.
- Never record an unanswered or misunderstood exercise as correct.
