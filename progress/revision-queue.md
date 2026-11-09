# Revision Queue

## Due and scheduled reviews

| Priority | Topic | Reason | Review date | Interval | Status |
|---|---|---|---|---|---|
| High | Object.keys(), Object.values(), Object.entries() | Newly introduced; verify ownership/enumerability and ordering | 2026-11-10 | 1 day | Scheduled |
| High | Object.fromEntries() transformation pipeline | Newly introduced; verify independent implementation | 2026-11-10 | 1 day | Scheduled |
| High | Object.hasOwn() vs in | Important for input handling and prototype-chain correctness | 2026-11-10 | 1 day | Scheduled |
| High | Object.assign() and spread | Common mutation and shallow-copy pitfalls | 2026-11-10 | 1 day | Scheduled |
| High | Shallow vs deep copying | Prevent accidental shared-state mutation | 2026-11-10 | 1 day | Scheduled |
| Medium | Object.freeze() vs Object.seal() | Verify property constraints and shallow behavior | 2026-11-10 | 1 day | Scheduled |
| Medium | map() vs forEach() | Verify return values and intended use | 2026-11-10 | 1 day | Scheduled |
| Medium | sort() vs toSorted() | Verify mutation and comparator behavior | 2026-11-10 | 1 day | Scheduled |

## Spaced-repetition policy
- First review: about 1 day after teaching.
- After successful recall: schedule the next review about 3 days later, then 7 days, then 14 days.
- If recall is weak or incorrect: record the misconception and review sooner rather than advancing the interval.
- Reschedule only after observing the learner's answer; do not assume success.
- Due reviews can occupy some of the 10 daily tips when they are substantive concepts. Never exceed exactly 10 tips.
