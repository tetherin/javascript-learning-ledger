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
| JavaScript objects | Object.keys(), Object.values(), Object.entries() | Introduced | Session 01 Q1 first and third outputs incorrectly included inherited/non-enumerable properties; repeatedly retaught, still no independent retest | Complete enumeration output retest |
| JavaScript objects | Object.getOwnPropertyNames() / Reflect.ownKeys() | Introduced | Differences taught in Sessions 03–04; no independent output | Predict own string, non-enumerable, and Symbol key sets |
| JavaScript objects | Object.hasOwn() vs in vs propertyIsEnumerable() | Practicing | Session 01 second output true/false was correct; newer cases not independently explained | Explain ownership and enumerability separately |
| JavaScript objects | Property descriptors / Object.getOwnPropertyDescriptor() | Introduced | Data/accessor descriptors and defaults taught in Sessions 02–04; no independent answer | Predict exact descriptor and return value |
| JavaScript objects | Object.defineProperty() invariants | Introduced | Defaults and non-configurable restrictions taught; no independent implementation | Implement and explain a non-configurable property |
| JavaScript objects | Accessor descriptors | Introduced | Getter/setter behavior and assignment-vs-definition semantics taught | Implement a validating setter and explain side effects |
| JavaScript objects | Object.getOwnPropertyDescriptors() | Introduced | Descriptor-preserving shallow-copy pattern taught; getter retention versus spread evaluation retaught in Session 06; independent output pending | Demonstrate getter behavior and shallow nested references |
| JavaScript objects | Object.assign() vs object spread | Introduced for semantic differences | Shared nested headers bug independently fixed with structuredClone; setter/source-getter, partial mutation, and nested merge cases taught in Sessions 04–06; checkpoints unanswered | Predict output and explain target mutation, setter invocation, and partial failure |
| JavaScript objects | Object.fromEntries() and filter() | Introduced | Session 01 identified entries → filter → fromEntries approach; validation and mutation issues remained | Implement safe query normalization without mutating input |
| JavaScript objects | Shallow vs deep copying | Practicing | Passed basic output prediction and practical shared-headers bug; review remains scheduled 2026-11-17 | Revisit edge cases at scheduled interval |
| JavaScript objects | preventExtensions() / seal() / freeze() | Introduced | Differences reviewed in Sessions 03–04; no independent recall | Explain exactly which changes each blocks |
| JavaScript objects | Prototype chain / prototype pollution / Map / Object.create(null) | Introduced | Safe dictionary and dynamic-key risks taught; no independent case solution | Complete safe dictionary/query case |
| JavaScript arrays | map() vs forEach() | Introduced | Async forEach trap reviewed; no recall answer | Explain why forEach does not await and choose iteration strategy |
| JavaScript arrays | sort() vs toSorted() | Introduced | Mutation, comparator, and shallow-copy distinctions reviewed | Predict identity and nested-object behavior |
| Async JavaScript | Promise.all() / Promise.allSettled() / bounded concurrency | Introduced | Failure semantics, ordering, and worker-pool pattern taught; no independent implementation | Implement capped worker pool preserving result order |
| Async JavaScript | AbortController / AbortSignal | Introduced | Cooperative cancellation and fetch signal propagation taught in Session 06; no learner implementation | Implement cancellation and distinguish abort from ordinary failure |
| Backend HTTP | Fetch status and body handling | Introduced | HTTP error response versus network rejection and JSON parsing taught in Session 06 | Implement robust getJSON and error handling |
| Backend HTTP | Express 5 async error propagation | Introduced | Async rejected route handling and four-argument error middleware taught in Session 06 | Explain Express 5 versus Express 4 behavior and safe error responses |
| Node.js testing | node:test and node:assert/strict | Introduced | Boundary-testing examples taught in Session 06; no learner tests | Write and run validator tests |
| Backend validation | Query shape, own-property presence, numeric syntax, safe integer, allowlists | Introduced; needs practice | Earlier validator had faulty guard, mutation, truthiness, and allowlist gaps; parseLimit requirements retaught in Sessions 05–06; no independent implementation | Implement parseLimit and comprehensive edge-case tests |
| TypeScript | unknown and runtime narrowing | Introduced | Used as boundary for untrusted Express query values; no independent type guard | Write a type guard and validate runtime shape |
| Functions | Scope and closures | Unassessed | No assessment yet | Baseline questions |
| Async JavaScript | Promises and async/await | Introduced; not independently assessed | Async iteration, settlement, worker pools, and cancellation taught; no learner implementation yet | Assess with a practical task |

Only advance a level after reviewing the learner's actual explanation, implementation, or tests. Do not infer mastery from exposure.
