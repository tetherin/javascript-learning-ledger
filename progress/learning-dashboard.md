# Learning Dashboard

**Status:** Session 01 in progress — shallow-copy concept and practical transfer passed; other targeted reviews remain  
**Last updated:** 2026-11-10  
**Completed formal sessions:** 0  
**Current session:** [Session 01 — JavaScript Objects and Safe Data Transformation](../session-reports/2026-11-09-session-01.md)

## Current focus
1. Retest own-property vs inherited/enumerable-property enumeration.
2. Improve API query validation: input shape, required fields, positive integer constraints, allowed sort values, and avoiding mutation.
3. Continue spaced review of shallow-copy behavior and supported deep-copy strategies.

## Progress summary
| Area | Status | Evidence / next action |
|---|---|---|
| Object.keys() / Object.entries() | Introduced; partial understanding | Q1 incorrectly included inherited and non-enumerable properties; retest |
| Object.hasOwn() vs in | Practicing | Correctly predicted true/false in Q1; verify explanation |
| Object.fromEntries() / filter() | Introduced | Recognized transformation pipeline; implementation needs correction |
| Shallow copying | Practicing | Correctly predicted basic example and diagnosed practical shared-headers bug; independently fixed it with structuredClone() |
| API input validation | Introduced; needs practice | Correctly stated key filtering alone is insufficient; implementation has logic/value-validation gaps |
| Functions and scope | Unassessed | Baseline questions |
| Async JavaScript | Unassessed | Baseline questions |
| React, Node.js, TypeScript, databases, authentication | Unassessed | Assess in later sessions |

## Learning cadence
- **Next targeted review:** 2026-11-10; prioritize own vs inherited/enumerable properties and safe query normalization.
- **Shallow-copy spaced review:** 2026-11-17 after successful basic and practical transfer exercises.
- Advance spaced-repetition intervals only after demonstrated recall.
- **Monthly assessment target:** 2026-12-09, if enough material has been completed.
- **Project application:** after 4 completed sessions. Session 01 is not yet complete.

## Rules
- Do not mark topics mastered based on exposure alone.
- Record evidence from explanations, code, debugging, and transfer to unfamiliar cases.
- Keep exactly 10 tips per teaching session; follow-up evaluation and targeted retests reinforce those tips.
- Never record an unanswered or misunderstood exercise as correct.
