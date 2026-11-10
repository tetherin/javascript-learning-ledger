# Mastery Tracker

Mastery levels:
- **Unassessed** — not yet evaluated.
- **Introduced** — explained, but independent understanding not demonstrated.
- **Practicing** — can solve familiar tasks with some support.
- **Competent** — independently applies the concept and handles common edge cases.
- **Mastered** — explains trade-offs and reliably applies the concept in unfamiliar situations.
- **Needs re-teaching** — learner explicitly reports not understanding or evidence shows a foundational gap.

| Topic | Subtopic / API | Level | Evidence | Next action |
|---|---|---|---|---|
| JavaScript objects | Object.keys(), Object.entries() | Introduced | Session 01 Q1 first and third outputs incorrectly included inherited/non-enumerable properties; Session 02 re-taught the own/enumerable rule | Complete descriptor/enumerability output retest |
| JavaScript objects | Object.hasOwn() vs in | Practicing | Session 01 second output true false was correct; new inherited vs own case taught in Session 02 | Explain and apply to untrusted query input |
| JavaScript objects | Property descriptors | Introduced | Session 02 introduced data/accessor descriptors and getOwnPropertyDescriptor(); no independent answer yet | Predict descriptor output and explain flags |
| JavaScript objects | Object.defineProperty() | Introduced | Session 02 explained false defaults for writable/enumerable/configurable; no independent implementation yet | Create a property with explicit flags |
| JavaScript objects | Object.fromEntries() and filter() | Introduced | Session 01 identified entries → filter → fromEntries approach; validation and mutation issues remained | Implement safe query normalization without mutating input |
| JavaScript objects | Object.assign() and object spread | Practicing | Diagnosed shared nested headers and fixed practical bug with structuredClone(defaults) | Review structuredClone limitations and alternative copying |
| JavaScript objects | Shallow vs deep copying | Practicing | Passed basic output prediction and practical shared-reference bug; next spaced review 2026-11-17 | Revisit edge cases at scheduled interval |
| JavaScript objects | Object.freeze() vs Object.seal() | Introduced | Taught in Session 01 and reviewed in Session 02; no recall answer yet | Distinguish writable from configurable behavior |
| JavaScript objects | Prototype chain / prototype pollution / null-prototype dictionaries | Introduced | Session 02 explained inherited lookup and safe dictionary choices; no independent case solution yet | Analyze unsafe dynamic-key handling |
| JavaScript arrays | map() vs forEach() | Introduced | Reviewed in Session 02; no recall answer yet | Explain return value and async callback trap |
| JavaScript arrays | sort() vs toSorted() | Introduced | Reviewed in Session 02; no recall answer yet | Predict mutation and numeric comparator behavior |
| Backend validation | Query shape, required fields, numeric constraints, allowlists | Introduced; needs practice | Session 01 implementation had faulty guard, input mutation, truthiness checks, and no sort allowlist; Session 02 re-taught validation stages | Complete query validator implementation |
| Functions | Scope and closures | Unassessed | No assessment yet | Baseline questions |
| Async JavaScript | Promises and async/await | Unassessed | No assessment yet | Baseline questions |

Only advance a level after reviewing the learner's actual explanation or implementation. Do not infer mastery from exposure.
