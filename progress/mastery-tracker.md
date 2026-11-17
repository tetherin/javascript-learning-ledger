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
| JavaScript arrays | map() vs forEach() | Introduced | Session 09 retaught sparse-slot skipping and that forEach discards async callback Promises; no independent answer | Explain async iteration policy and sparse-array behavior |
| JavaScript arrays | sort() vs toSorted() | Introduced | Session 09 retaught mutation, default string ordering, numeric comparator, and shallow result identity; independent prediction pending | Predict identity and nested-object behavior |
| Async JavaScript | Promise.all() / Promise.allSettled() / bounded concurrency | Introduced | Failure semantics, ordering, and worker-pool pattern taught; no independent implementation | Implement capped worker pool preserving result order |
| Async JavaScript | AbortController / AbortSignal | Introduced | Cooperative cancellation and fetch signal propagation taught in Session 06; no learner implementation | Implement cancellation and distinguish abort from ordinary failure |
| Backend HTTP | Fetch status and body handling | Introduced | HTTP error response versus network rejection and JSON parsing taught in Session 06 | Implement robust getJSON and error handling |
| Backend HTTP | Express 5 async error propagation | Introduced | Async rejected route handling and four-argument error middleware taught in Session 06 | Explain Express 5 versus Express 4 behavior and safe error responses |
| Node.js testing | node:test and node:assert/strict | Introduced | Boundary-testing examples taught in Session 06; no learner tests | Write and run validator tests |
| Backend validation | Query shape, own-property presence, numeric syntax, safe integer, allowlists | Introduced; needs practice | Earlier validator had faulty guard, mutation, truthiness, and allowlist gaps; parseLimit requirements retaught in Sessions 05–06; no independent implementation | Implement parseLimit and comprehensive edge-case tests |
| TypeScript | unknown and runtime narrowing | Introduced | Used as boundary for untrusted Express query values; no independent type guard | Write a type guard and validate runtime shape |
| Functions | Scope and closures | Unassessed | No assessment yet | Baseline questions |
| Async JavaScript | Promises and async/await | Introduced; not independently assessed | Async iteration, settlement, worker pools, and cancellation taught; no learner implementation yet | Assess with a practical task |

| JavaScript arrays | Sparse arrays: holes vs explicit undefined | Introduced | Session 09 explained how map/filter/forEach skip holes while spread materializes undefined; no independent prediction | Demonstrate hole checks and method behavior |
| JavaScript arrays | Array.from() | Introduced | Session 09 explained iterable/array-like input, dense output, and mapping callback; no implementation | Normalize an array-like object and test missing indices |
| JavaScript arrays | flatMap() | Introduced | Session 09 explained map plus one-level flattening for nested API data; no implementation | Flatten user-role records without mutating input |
| Async JavaScript | forEach async callback vs sequential/parallel iteration | Introduced | Session 09 retaught that forEach returns undefined and ignores callback Promises; no learner implementation | Implement sequential and parallel policies and explain failure behavior |
| JavaScript collections | Map vs ordinary object dictionary | Introduced | Session 09 revisited arbitrary keys, insertion order, and JSON serialization; no case solution | Choose and serialize a safe permissions dictionary |

Only advance a level after reviewing the learner's actual explanation, implementation, or tests. Do not infer mastery from exposure.

 
## Session 07 evidence note — 2026-11-15
- Session 06's ten concepts were revisited with fresh edge cases and production failure modes.
- No learner answers or code were received in this scheduled run.
- No mastery level was upgraded. Retaught concepts remain at their existing levels until independent evidence is reviewed.


## Session 08 evidence note — 2026-11-16
- Exactly 10 concepts were taught: property dimensions; own-key inspection APIs; for...in prototype traversal; ownership versus enumerability checks; defineProperty defaults and setter behavior; non-configurable transitions; preventExtensions/seal/freeze; prototype-pollution defenses; Zod 4 strict query schemas; Object.fromEntries duplicate-key and "__proto__" behavior.
- No learner answers or code were received in this scheduled run.
- No mastery level was upgraded. Existing levels and the prior shallow-copy evidence remain unchanged.
- Zod strict schema usage, Reflect.ownKeys, descriptor invariants, integrity levels, and safe dynamic dictionaries remain introduced until independently demonstrated.


## Session 09 evidence note — 2026-11-17
- Exactly 10 concepts were taught: shallow copies; structuredClone boundaries; sparse-array holes; Array.from; flatMap; async forEach versus sequential/parallel iteration; sort versus toSorted; Object.entries/fromEntries and ownership; shallow freeze with immutable path copying; Map versus object dictionaries.
- The due shallow-copy review and selected Session 08 themes were retaught, but no independent answers were received.
- No learner answers or code were received in this scheduled run.
- No mastery level or spaced-repetition interval was advanced.
- Earlier shallow-copy prediction and shared-headers structuredClone fix remain the only independent evidence for that topic.
