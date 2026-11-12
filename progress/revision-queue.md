# Revision Queue

## Priority reviews

| Priority | Topic | Reason | Review date | Interval | Status |
|---|---|---|---|---|---|
| High | Own vs inherited and enumerable properties; Object.keys()/Object.entries() | Session 01 Q1 included inherited and non-enumerable properties incorrectly | 2026-11-12 | Targeted retest | Revisited in Sessions 02–04; independent answer pending |
| High | Safe query normalization and validation | Session 01 Q3 had guard, mutation, numeric-validation, and allowlist issues; Session 02/03 implementation exercises remain unanswered | 2026-11-12 | Targeted implementation | Revisited in Sessions 03–04; implementation pending |
| Medium | Object.hasOwn() vs in vs propertyIsEnumerable() | Q1 second output was correct; new cases need explanation | 2026-11-12 | Recall check | Revisited in Sessions 03–04; answer pending |
| Medium | Object.preventExtensions() / Object.seal() / Object.freeze() | Introduced earlier, not independently assessed | 2026-11-12 | Recall check | Revisited in Sessions 03–04; answer pending |
| Medium | map() vs forEach(), including async callback behavior | Introduced earlier, not independently assessed | 2026-11-12 | Recall check | Revisited in Sessions 03–04; answer pending |
| Medium | sort() vs toSorted(), comparator and mutation behavior | Introduced earlier, not independently assessed | 2026-11-12 | Recall check | Revisited in Sessions 03–04; answer pending |
| High | Descriptor defaults, non-configurable invariants, accessor descriptors | Session 03/04 material; no independent recall | 2026-11-13 | 1-day first review | Awaiting first answer |
| High | Object.getOwnPropertyDescriptors() and descriptor-preserving shallow copies | Transfer from shallow-copy learning needs testing | 2026-11-13 | 1-day first review | Awaiting first answer |
| High | Object.assign() vs spread: setters, source getters, mutation, return value | Newly distinguished in Session 04; output checkpoint pending | 2026-11-13 | 1-day first review | Awaiting first answer |
| High | Prototype pollution, Map, null-prototype dictionaries | Case-based application not demonstrated | 2026-11-13 | 1-day first review | Awaiting first answer |
| High | Express req.query validation and TypeScript unknown narrowing | Earlier query validator had multiple bugs; runtime input shape remains untested | 2026-11-13 | 1-day first review | Awaiting implementation |
| Medium | Promise.all vs Promise.allSettled and bounded concurrency | Newly taught; no independent failure-policy reasoning | 2026-11-13 | 1-day first review | Awaiting case analysis |
| Medium | Shallow copy, nested references, and structuredClone() | Learner passed basic prediction and practical shared-headers bug | 2026-11-17 | 7-day spaced review | Scheduled |
| High | Session 02 enumeration and getLimit exercises; Session 03 enumeration and getLimit exercises | Earlier exercises remain unanswered; explanations do not count as evidence | 2026-11-12 | Outstanding work | Pending learner response |

## Spaced-repetition policy
- First review: about 1 day after teaching.
- After successful recall: schedule the next review about 3 days later, then 7 days, then 14 days.
- If recall is weak or incorrect, record the misconception and review sooner.
- Do not advance an interval merely because an explanation was shown; require an independent answer.
- Due reviews can occupy some of the 10 daily tips when substantive. Never exceed exactly 10 tips.
