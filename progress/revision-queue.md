# Revision Queue

## Priority reviews

| Priority | Topic | Reason | Review date | Interval | Status |
|---|---|---|---|---|---|
| High | Own vs inherited and enumerable properties; Object.keys()/Object.entries() | Session 01 Q1 included inherited and non-enumerable properties incorrectly | 2026-11-11 | Targeted retest | Revisited in Sessions 02 and 03; independent answer pending |
| High | Safe query normalization and validation | Session 01 Q3 had guard, mutation, numeric-validation, and allowlist issues; Session 02 Exercise B also pending | 2026-11-11 | Targeted implementation | Revisited in Session 03; implementation pending |
| Medium | Object.hasOwn() vs in vs propertyIsEnumerable() | Q1 second output was correct; new cases need explanation | 2026-11-11 | Recall check | Revisited in Session 03; answer pending |
| Medium | Object.preventExtensions() / Object.seal() / Object.freeze() | Introduced earlier, not independently assessed | 2026-11-11 | Recall check | Revisited in Session 03; answer pending |
| Medium | map() vs forEach(), including async callback behavior | Introduced earlier, not independently assessed | 2026-11-11 | Recall check | Revisited in Session 03; answer pending |
| Medium | sort() vs toSorted(), comparator and mutation behavior | Introduced earlier, not independently assessed | 2026-11-11 | Recall check | Revisited in Session 03; answer pending |
| High | Descriptor defaults, non-configurable invariants, accessor descriptors | New Session 03 material; no independent recall | 2026-11-12 | 1-day first review | Scheduled |
| High | Object.getOwnPropertyDescriptors() and descriptor-preserving shallow copies | New Session 03 material; transfer from shallow-copy learning needs testing | 2026-11-12 | 1-day first review | Scheduled |
| High | Prototype pollution, Map, null-prototype dictionaries | New Session 03 material; case-based application not demonstrated | 2026-11-12 | 1-day first review | Scheduled |
| Medium | Shallow copy, nested references, and structuredClone() | Learner passed basic prediction and practical shared-headers bug fix | 2026-11-17 | 7-day spaced review | Scheduled |

## Spaced-repetition policy
- First review: about 1 day after teaching.
- After successful recall: schedule the next review about 3 days later, then 7 days, then 14 days.
- If recall is weak or incorrect, record the misconception and review sooner.
- Do not advance an interval merely because an explanation was shown; require an independent answer.
- Due reviews can occupy some of the 10 daily tips when substantive. Never exceed exactly 10 tips.
