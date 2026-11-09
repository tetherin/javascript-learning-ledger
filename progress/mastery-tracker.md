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
| JavaScript objects | Object.keys(), Object.entries() | Introduced | Q1 first and third outputs incorrectly included inherited/non-enumerable properties; key names should be strings and entries are [key, value] pairs | Retest ownership, enumerability, and integer-key ordering |
| JavaScript objects | Object.hasOwn() vs in | Practicing | Q1 second output true false was correct; explanation broadly distinguishes prototype-chain lookup from own-property lookup | Explain that hasOwn checks the target object's own properties, not its prototype |
| JavaScript objects | Object.fromEntries() and filter() | Introduced | Q3 identified entries → filter → fromEntries approach; code has validation and omission gaps | Rebuild transformation without mutating input |
| JavaScript objects | Object.assign() and object spread | Practicing | Diagnosed shared nested headers in practical config bug; fixed by cloning defaults before modifying headers | Compare structuredClone(), nested spread, and limitations |
| JavaScript objects | Shallow vs deep copying | Practicing | Correctly predicted user1.name as "Ansh" and user1.profile.city as "Delhi"; then predicted all three shared-header outputs as "Bearer token-B", explained the shared reference, and independently fixed the function with structuredClone(defaults) | Later test deeper nesting, unsupported structured-clone values, and alternative targeted copying |
| JavaScript objects | Object.freeze() vs Object.seal() | Introduced | Taught; no answer submitted | Review later |
| JavaScript arrays | map() vs forEach() | Introduced | Taught; no answer submitted | Review later |
| JavaScript arrays | sort() vs toSorted() | Introduced | Taught; no answer submitted | Review later |
| Backend validation | Query shape, required fields, numeric constraints, allowlists | Introduced; needs practice | Q3: understood filtering alone is insufficient; implementation has faulty guard, mutates input, uses truthiness checks, and lacks sort-value validation | Practice safe normalization and schema validation |
| Functions | Scope and closures | Unassessed | No assessment yet | Baseline questions |
| Async JavaScript | Promises and async/await | Unassessed | No assessment yet | Baseline questions |

Only advance a level after reviewing the learner's actual explanation or implementation. Do not infer mastery from exposure.
