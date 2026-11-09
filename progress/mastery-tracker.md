# Mastery Tracker

Mastery levels:
- **Unassessed** — not yet evaluated.
- **Introduced** — explained, but independent understanding not demonstrated.
- **Practicing** — can solve familiar tasks with some support.
- **Competent** — independently applies the concept and handles common edge cases.
- **Mastered** — explains trade-offs and reliably applies the concept in unfamiliar situations.
- **Needs re-teaching** — learner explicitly reports not understanding or evidence shows a foundational gap.

| Topic | Subtopic / API | Level | Evidence from Session 01 | Next action |
|---|---|---|---|---|
| JavaScript objects | Object.keys(), Object.entries() | Introduced | Q1 first and third outputs incorrectly included inherited/non-enumerable properties; key strings and exact array structure missed | Retest ownership, enumerability, and integer-key ordering |
| JavaScript objects | Object.hasOwn() vs in | Practicing | Q1 second output true false was correct | Explain why and transfer to another prototype example |
| JavaScript objects | Object.fromEntries() and filter() | Introduced | Q3 identified entries → filter → fromEntries approach; code has validation and omission gaps | Rebuild transformation without mutating input |
| JavaScript objects | Object.assign() and object spread | Introduced | Q2 not understood; learner explicitly requested explanation | Re-teach reference sharing and shallow copy |
| JavaScript objects | Shallow vs deep copying | Needs re-teaching | Learner explicitly said they did not understand Q2 | Use reference diagrams and nested-object exercise |
| JavaScript objects | Object.freeze() vs Object.seal() | Introduced | Taught; no answer submitted | Review later |
| JavaScript arrays | map() vs forEach() | Introduced | Taught; no answer submitted | Review later |
| JavaScript arrays | sort() vs toSorted() | Introduced | Taught; no answer submitted | Review later |
| Backend validation | Query shape, required fields, numeric constraints, allowlists | Introduced; needs practice | Q3: understood filtering alone is insufficient; implementation has faulty guard, mutates input, and lacks sort-value validation | Practice safe normalization and schema validation |
| Functions | Scope and closures | Unassessed | No assessment yet | Baseline questions |
| Async JavaScript | Promises and async/await | Unassessed | No assessment yet | Baseline questions |

Only advance a level after reviewing the learner's actual explanation or implementation. Do not infer mastery from exposure.
