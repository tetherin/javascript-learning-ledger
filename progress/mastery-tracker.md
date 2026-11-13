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
| JavaScript objects | Object.keys(), Object.values(), Object.entries() | Introduced | Session 01 Q1 first and third outputs incorrectly included inherited/non-enumerable properties; rule retaught in Sessions 02–04 | Complete independent enumeration output retest |
| JavaScript objects | Object.getOwnPropertyNames() / Reflect.ownKeys() | Introduced | Differences taught in Sessions 03 and 04; no independent output yet | Predict own string, non-enumerable, and Symbol key sets |
| JavaScript objects | Object.hasOwn() vs in vs propertyIsEnumerable() | Practicing | Session 01 second output true false was correct; later cases taught but not independently explained | Explain ownership and enumerability separately |
| JavaScript objects | Property descriptors / Object.getOwnPropertyDescriptor() | Introduced | Data/accessor descriptors and defaults taught in Sessions 02–04; no independent answer yet | Predict exact descriptor and return value |
| JavaScript objects | Object.defineProperty() invariants | Introduced | Defaults and non-configurable restrictions taught; no independent implementation | Implement and explain a non-configurable property |
| JavaScript objects | Accessor descriptors | Introduced | Getter/setter behavior and assignment-vs-definition semantics taught | Implement a validating setter and explain side effects |
| JavaScript objects | Object.getOwnPropertyDescriptors() | Introduced | Descriptor-preserving shallow-copy pattern taught; compare with spread and structuredClone not independently demonstrated | Implement and explain copy behavior |
| JavaScript objects | Object.assign() vs object spread | Introduced for semantic differences | Shared nested headers bug diagnosed and fixed with structuredClone; setter/source-getter, partial-mutation, and merge-order cases taught in Sessions 04–05; Session 05 checkpoint unanswered | Complete output prediction and explain target mutation/setter behavior |
| JavaScript objects | Object.fromEntries() and filter() | Introduced | Session 01 identified entries → filter → fromEntries approach; validation and mutation issues remained | Implement safe query normalization without mutating input |
| JavaScript objects | Shallow vs deep copying | Practicing | Passed basic output prediction and practical shared-reference bug; next spaced review 2026-11-17 | Revisit edge cases at scheduled interval |
| JavaScript objects | preventExtensions() / seal() / freeze() | Introduced | Differences reviewed in Sessions 03–04; no independent recall yet | Explain exactly which changes each blocks |
| JavaScript objects | Prototype chain / prototype pollution / Map / Object.create(null) | Introduced | Safe dictionary and dynamic-key risks taught in Sessions 02–04; no independent case solution | Complete safe dictionary/query case |
| JavaScript arrays | map() vs forEach() | Introduced | Async forEach trap reviewed; no recall answer yet | Explain why forEach does not await and choose concurrency strategy |
| JavaScript arrays | sort() vs toSorted() | Introduced | Mutation, comparator, and shallow-copy distinctions reviewed | Predict identity and nested-object behavior |
| Async JavaScript | Promise.all() vs Promise.allSettled() / concurrency | Introduced | Failure semantics and unbounded concurrency trade-offs taught in Session 04; no independent case answer | Choose failure and concurrency strategy for a batch job |
| Backend validation | Query shape, required fields, numeric constraints, allowlists | Introduced; needs practice | Earlier code had faulty guard, input mutation, truthiness checks, and no sort allowlist; Session 05 parseLimit(query: unknown) validation order taught; no independent implementation yet | Implement parseLimit(query: unknown) and full query validation |
| TypeScript | unknown and runtime narrowing | Introduced | Taught as boundary for untrusted Express query values; no independent type guard | Write a type guard and validate runtime shape |
| Functions | Scope and closures | Unassessed | No assessment yet | Baseline questions |
| Async JavaScript | Promises and async/await | Introduced; not independently assessed | Async iteration patterns taught, but no learner implementation yet | Assess with a practical task |

Only advance a level after reviewing the learner's actual explanation or implementation. Do not infer mastery from exposure.
