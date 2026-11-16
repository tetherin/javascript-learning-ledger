# Learning Dashboard

**Status:** Session 08 in progress — exactly 10 concepts taught; independent recall pending
**Last updated:** 2026-11-16
**Completed formal sessions:** 0  
**Current session:** [Session 08 — Property Introspection, Descriptors, and Safe Request Schemas](../session-reports/2026-11-16-session-08.md)
**Previous sessions:** [Session 05](../session-reports/2026-11-13-session-05.md) · [Session 04](../session-reports/2026-11-12-session-04.md) · [Session 03](../session-reports/2026-11-11-session-03.md) · [Session 02](../session-reports/2026-11-10-session-02.md) · [Session 01](../session-reports/2026-11-09-session-01.md)

## Current focus
1. Complete Session 08's independent key-enumeration and ownership predictions.
2. Independently inspect descriptors and explain defineProperty defaults and non-configurable transitions.
3. Explain preventExtensions, seal, and freeze, including shallow nested behavior.
4. Solve the prototype-pollution case and choose Map versus Object.create(null) with justification.
5. Implement the strict Zod 4 query schema and Express route without mutating req.query.
6. Complete Session 07's still-pending bounded-concurrency, AbortSignal, Fetch, Express async-error, and node:test checkpoints.
7. Complete outstanding Session 01–04 enumeration, descriptor, integrity-level, and query-validation exercises.
8. Keep shallow-copy/structuredClone review scheduled for 2026-11-17.

## Progress summary
| Area | Status | Evidence / next action |
|---|---|---|
| Object.keys(), Object.values(), Object.entries() | Introduced; partial understanding | Session 01 Q1 incorrectly included inherited/non-enumerable properties; independent retest pending |
| Object.getOwnPropertyNames() / Reflect.ownKeys() | Introduced | Differences taught in Sessions 03–04; independent output pending |
| Object.hasOwn() vs in vs propertyIsEnumerable() | Practicing | Session 01 second output correct; independent explanation of newer cases pending |
| Property descriptors / Object.getOwnPropertyDescriptor() | Introduced | Descriptor types/defaults taught; independent output pending |
| Object.defineProperty() invariants | Introduced | Non-configurable rules taught; independent implementation pending |
| Accessor descriptors | Introduced | Getter/setter and redefinition behavior taught; independent implementation pending |
| Object.getOwnPropertyDescriptors() | Introduced | Descriptor-preserving shallow-copy pattern taught; getter retention versus spread evaluation retaught in Session 06; independent output pending |
| Object.assign() vs object spread | Introduced for semantic differences; shallow copying Practicing | Shared-reference bug independently fixed with structuredClone; setter/getter, partial-mutation, and merge cases retaught; exercises pending |
| Object.fromEntries() and filter() | Introduced | Session 01 transformation approach sound, validator gaps remain; independent safe implementation pending |
| Shallow vs deep copying / structuredClone() | Practicing | Basic prediction and practical shared-headers fix passed; review scheduled 2026-11-17 |
| preventExtensions() / seal() / freeze() | Introduced | Differences taught; independent recall pending |
| Map / Object.create(null) / prototype pollution | Introduced | Safe dictionary trade-offs taught; case-based solution pending |
| map() vs forEach() | Introduced | Async forEach trap taught; independent explanation pending |
| sort() vs toSorted() | Introduced | Mutation and shallow-copy behavior taught; independent explanation pending |
| Promise.all() / Promise.allSettled() / bounded concurrency | Introduced | Outcome handling and worker-pool pattern taught; independent implementation pending |
| AbortController / AbortSignal | Introduced | Cooperative cancellation and fetch signal propagation taught; independent implementation pending |
| Fetch response handling | Introduced | HTTP status versus network rejection and JSON body parsing taught; independent implementation pending |
| Express 5 error handling | Introduced | Async rejection forwarding and error middleware taught; independent route/error case pending |
| Node.js node:test | Introduced | Boundary-test pattern taught; learner has not written tests yet |
| Backend query validation | Introduced; needs practice | Earlier validator gaps remain; Session 06 parseLimit requirements and test cases retaught; independent implementation pending |
| TypeScript unknown/narrowing | Introduced | Used at request boundary; independent type guard pending |
| Functions and scope | Unassessed | Baseline questions later |
| React, PostgreSQL, Drizzle, authentication | Unassessed or introduced only where noted | Assess progressively |

## Learning cadence
- **Session 05/06/07 reviews:** Retaught in later sessions, but independent answers remain pending; intervals do not advance from exposure.
- **Session 07 first recall:** Due 2026-11-16. Session 08 revisited related object-introspection, descriptor, prototype-safety, and validation themes; its concurrency, cancellation, Fetch, Express, and testing checkpoints remain pending.
- **Session 08 first recall:** Scheduled for 2026-11-17.
- **Shallow-copy spaced review:** 2026-11-17.
- Advance spaced-repetition intervals only after demonstrated recall.
- **Monthly assessment target:** approximately 2026-12-09, conditional on sufficient completed material.
- **Project application:** after 4 completed formal sessions. No formal session has been completed yet.

## Rules
- Do not mark topics mastered based on exposure alone.
- Record evidence from explanations, code, debugging, tests, and transfer to unfamiliar cases.
- Keep exactly 10 tips per teaching session; follow-up evaluation and targeted retests reinforce those tips.
- Never record an unanswered or misunderstood exercise as correct.
