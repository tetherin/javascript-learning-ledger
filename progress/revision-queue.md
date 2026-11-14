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
| High | Session 06: Object.assign/spread, partial mutation, nested merge, descriptor copy, parseLimit, bounded worker pool | New session's six review/application topics | 2026-11-15 | 1-day first recall | Scheduled; no answers received |
| Medium | Session 06: AbortController, fetch response handling, Express 5 errors, node:test | Newly introduced production HTTP/testing concepts | 2026-11-15 | 1-day first recall | Scheduled; no answers received |

## Spaced-repetition policy
- First review: about 1 day after teaching.
- After successful recall: schedule the next review about 3 days later, then 7 days, then 14 days.
- If recall is weak or incorrect, record the misconception and review sooner.
- Do not advance an interval merely because an explanation was shown; require an independent answer.
- Retaught-but-unanswered topics remain pending and do not advance their interval.
- Due reviews can occupy some of the 10 daily tips when substantive. Never exceed exactly 10 tips.
