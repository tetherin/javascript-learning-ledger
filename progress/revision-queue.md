# Revision Queue

## Priority reviews

| Priority | Topic | Reason | Review date | Interval | Status |
|---|---|---|---|---|---|
| High | Own vs inherited and enumerable properties; Object.keys()/Object.entries() | Session 01 Q1 included inherited and non-enumerable properties incorrectly | 2026-11-12 | Targeted retest | Revisited in Sessions 02–04; independent answer pending |
| High | Safe query normalization and validation | Session 01 Q3 had guard, mutation, numeric-validation, and allowlist issues | 2026-11-12 | Targeted implementation | Revisited in Sessions 03–06; independent implementation pending |
| Medium | Object.hasOwn() vs in vs propertyIsEnumerable() | Q1 second output was correct; newer cases need explanation | 2026-11-12 | Recall check | Revisited in Sessions 03–04; independent answer pending |
| Medium | Object.preventExtensions() / Object.seal() / Object.freeze() | Introduced earlier, not independently assessed | 2026-11-12 | Recall check | Revisited in Sessions 03–04; independent answer pending |
| Medium | map() vs forEach(), including async callback behavior | Introduced earlier, not independently assessed | 2026-11-12 | Recall check | Revisited in Sessions 03–04; independent answer pending |
| Medium | sort() vs toSorted(), comparator and mutation behavior | Introduced earlier, not independently assessed | 2026-11-12 | Recall check | Revisited in Sessions 03–04; independent answer pending |
| High | Descriptor defaults, non-configurable invariants, accessor descriptors | Session 03/04 material; no independent recall | 2026-11-13 | 1-day first review | Retaught in Session 06; still awaiting independent answer |
| High | Object.getOwnPropertyDescriptors() and descriptor-preserving shallow copies | Transfer from shallow-copy learning needs testing | 2026-11-13 | 1-day first review | Retaught in Session 06; still awaiting independent answer |
| High | Object.assign() vs spread: setters, source getters, mutation, return value | Session 04 checkpoint unanswered | 2026-11-13 | 1-day first review | Retaught in Sessions 05–06; still awaiting independent answer |
| High | Prototype pollution, Map, null-prototype dictionaries | Case-based application not demonstrated | 2026-11-13 | 1-day first review | Awaiting independent case solution |
| High | Express req.query validation and TypeScript unknown narrowing | Earlier query validator had multiple bugs | 2026-11-13 | 1-day first review | Retaught in Sessions 05–06; parseLimit implementation pending |
| Medium | Promise.all vs Promise.allSettled and bounded concurrency | No independent failure-policy reasoning | 2026-11-13 | 1-day first review | Worker-pool pattern retaught in Session 06; independent implementation pending |
| Medium | Shallow copy, nested references, and structuredClone() | Learner passed basic prediction and practical shared-headers bug | 2026-11-17 | 7-day spaced review | Scheduled |
| High | Session 02/03 enumeration and getLimit exercises; Session 01 query validation | Earlier exercises remain unanswered; repeated explanations do not count as evidence | 2026-11-12 | Outstanding work | Pending learner response |
| High | Object.assign partial mutation when a later write fails | Production failure mode taught in Session 05 | 2026-11-14 | 1-day first recall | Retaught in Session 06; independent output pending |
| High | Object.assign vs spread with inherited setters and source getters | Session 04 checkpoint unanswered | 2026-11-14 | 1-day first recall | Retaught in Session 06; independent output pending |
| Medium | Shallow nested merge precedence and explicit headers merge | Common request-config failure mode | 2026-11-14 | 1-day first recall | Retaught in Session 06; independent implementation pending |
| Medium | Descriptor-preserving copy: getter retention vs spread getter evaluation | Transfer from descriptor and shallow-copy concepts | 2026-11-14 | 1-day first recall | Retaught in Session 06; independent output pending |
| High | parseLimit(query: unknown): own-property, syntax, safe integer, and range validation | Repeated query-validation weakness | 2026-11-14 | 1-day first recall | Retaught in Session 06; independent implementation and tests pending |
| Medium | Promise.allSettled result ordering and bounded concurrency | Batch-job case not demonstrated | 2026-11-14 | 1-day first recall | Retaught with worker-pool pattern in Session 06; independent implementation pending |
| High | Session 06: Object.assign/spread, partial mutation, nested merge, descriptor copy, parseLimit, bounded worker pool | New session's six review/application topics | 2026-11-15 | 1-day first recall | Retaught in Session 07; independent answers still pending |
| Medium | Session 06: AbortController, fetch response handling, Express 5 errors, node:test | Newly introduced production HTTP/testing concepts | 2026-11-15 | 1-day first recall | Retaught in Session 07; independent answers still pending |

| High | Session 07: Object.assign/spread Symbol and setter semantics; partial mutation; undefined merge overrides; descriptor copies; parseLimit record validation; bounded worker pool; cancellation composition; Fetch body handling; Express 5 returned-Promise handling; async node:test assertions | Fresh first-recall set after Session 07 | 2026-11-16 | 1-day first recall | Scheduled; no answers received |

## Spaced-repetition policy
- First review: about 1 day after teaching.
- After successful recall: schedule the next review about 3 days later, then 7 days, then 14 days.
- If recall is weak or incorrect, record the misconception and review sooner.
- Do not advance an interval merely because an explanation was shown; require an independent answer.
- Retaught-but-unanswered topics remain pending and do not advance their interval.
- Due reviews can occupy some of the 10 daily tips when substantive. Never exceed exactly 10 tips.


## Session 08 review
| Priority | Topic | Reason | Review date | Interval | Status |
|---|---|---|---|---|---|
| High | Session 08: property dimensions, Reflect.ownKeys/key inspection, ownership versus enumerability, defineProperty defaults, non-configurable invariants, integrity levels, prototype-safe dictionaries, Zod strict query schemas, Object.fromEntries "__proto__" behavior | Exactly 10 concepts taught on 2026-11-16; independent recall not yet demonstrated | 2026-11-17 | 1-day first recall | Scheduled; no answers received |

### Session 07 due-review clarification — 2026-11-16
- Related enumeration, descriptor, prototype-safety, and validation themes were revisited in Session 08, but no independent answers were received.
- Session 07's bounded worker pool, AbortSignal composition, Fetch response-body handling, Express 5 detached Promise handling, and node:test assertions remain pending.
- Do not advance any Session 07 interval until the learner supplies independent explanations, predictions, code, or tests.
- Shallow-copy/structuredClone review remains scheduled for 2026-11-17.


## Session 09 first recall — scheduled 2026-11-18

| Priority | Topic | Reason | Review date | Interval | Status |
|---|---|---|---|---|---|
| High | Shallow object/array copies and nested-reference aliasing | Existing Practicing evidence; Session 09 revisited with new example | 2026-11-18 | 1-day recall after retaught example | Scheduled; no new learner answer |
| High | structuredClone supported data versus descriptors/prototypes/functions | New limitation distinctions taught in Session 09 | 2026-11-18 | 1-day first recall | Scheduled |
| Medium | Sparse-array holes versus explicit undefined | New array edge case taught in Session 09 | 2026-11-18 | 1-day first recall | Scheduled |
| Medium | Array.from array-like conversion and dense output | New API usage taught in Session 09 | 2026-11-18 | 1-day first recall | Scheduled |
| Medium | flatMap one-level flattening for nested API data | New API usage taught in Session 09 | 2026-11-18 | 1-day first recall | Scheduled |
| High | forEach async callback versus sequential/parallel iteration | Repeated async iteration weakness; Session 09 retaught failure mode | 2026-11-18 | 1-day recall | Scheduled |
| Medium | sort mutation, toSorted identity, and numeric comparator | Revisited with a fresh numeric example in Session 09 | 2026-11-18 | 1-day recall | Scheduled |
| Medium | Object.entries/fromEntries and own/enumerable/Symbol distinctions | Session 08 due-review theme revisited in Session 09; no answer | 2026-11-18 | Recall pending | Scheduled |
| Medium | Object.freeze shallow behavior and immutable path copying | Session 08 due-review theme revisited in Session 09; no answer | 2026-11-18 | Recall pending | Scheduled |
| High | Map versus object for arbitrary/untrusted keys and serialization | Session 08 due-review theme revisited in Session 09; no answer | 2026-11-18 | Recall pending | Scheduled |

### Due-review status — 2026-11-17
- Session 08 first recall remains due. Session 09 revisited selected Object.entries/fromEntries, freeze, and Map themes, but no independent answer was received. Descriptor invariants and the Zod strict query-schema implementation remain pending.
- Shallow-copy/structuredClone review remains due. The concept was retaught, but no new independent answer was received; do not advance its interval.
- Session 07 bounded concurrency, AbortSignal, Fetch response-body handling, Express 5 detached Promise handling, and node:test assertions remain pending.
- Older Session 01–04 enumeration, descriptors, integrity levels, and query-validation tasks remain outstanding.
- Do not advance any interval merely because a concept was retaught.
