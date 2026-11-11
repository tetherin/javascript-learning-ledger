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
| JavaScript objects | Object.keys(), Object.values(), Object.entries() | Introduced | Session 01 Q1 first and third outputs incorrectly included inherited/non-enumerable properties; rule retaught in Sessions 02 and 03 | Complete independent enumeration output retest |
| JavaScript objects | Object.getOwnPropertyNames() / Reflect.ownKeys() | Introduced | Differences taught in Session 03; no independent output yet | Predict own string, non-enumerable, and Symbol key sets |
| JavaScript objects | Object.hasOwn() vs in vs propertyIsEnumerable() | Practicing | Session 01 second output true false was correct; later cases taught but not independently explained | Explain ownership and enumerability separately |
| JavaScript objects | Property descriptors / Object.getOwnPropertyDescriptor() | Introduced | Data/accessor descriptors and own-property behavior taught in Sessions 02 and 03; no answer yet | Predict exact descriptor and return value |
| JavaScript objects | Object.defineProperty() invariants | Introduced | Defaults and non-configurable restrictions taught; no independent implementation | Implement and explain a non-configurable property |
| JavaScript objects | Accessor descriptors | Introduced | Getter/setter behavior and data/accessor mutual exclusion taught in Session 03 | Implement a validating setter and explain side effects |
| JavaScript objects | Object.getOwnPropertyDescriptors() | Introduced | Descriptor-preserving shallow-copy pattern taught in Session 03 | Compare against spread and structuredClone in code |
| JavaScript objects | Object.fromEntries() and filter() | Introduced | Session 01 identified entries → filter → fromEntries approach; validation and mutation issues remained | Implement safe query normalization without mutating input |
| JavaScript objects | Object.assign() and object spread | Practicing | Diagnosed shared nested headers and fixed practical bug with structuredClone(defaults) | Review descriptor and prototype copying trade-offs |
| JavaScript objects | Shallow vs deep copying | Practicing | Passed basic output prediction and practical shared-reference bug; next spaced review 2026-11-17 | Revisit edge cases at scheduled interval |
| JavaScript objects | preventExtensions() / seal() / freeze() | Introduced | Distinctions reviewed in Session 03; no independent recall yet | Explain exactly which changes each blocks |
| JavaScript objects | Prototype chain / prototype pollution / Map / Object.create(null) | Introduced | Safe dictionary and dynamic-key risks taught in Sessions 02 and 03; no independent case solution | Complete safe dictionary/query case |
| JavaScript arrays | map() vs forEach() | Introduced | Async forEach trap reviewed in Session 03; no recall answer yet | Explain why forEach does not await and choose concurrency strategy |
| JavaScript arrays | sort() vs toSorted() | Introduced | Mutation, comparator, and shallow-copy distinctions reviewed in Session 03 | Predict identity and nested-object behavior |
| Backend validation | Query shape, required fields, numeric constraints, allowlists | Introduced; needs practice | Session 01 code had faulty guard, input mutation, truthiness checks, and no sort allowlist; reviewed again in Sessions 02 and 03 | Implement getLimit(query) and full query validation |
| Functions | Scope and closures | Unassessed | No assessment yet | Baseline questions |
| Async JavaScript | Promises and async/await | Unassessed | No independent assessment yet | Baseline questions |

Only advance a level after reviewing the learner's actual explanation or implementation. Do not infer mastery from exposure.
