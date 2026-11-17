## 2026-11-17 — Session 09: Array Semantics, Copy Boundaries, and Safe Collections
- **Status:** In progress — exactly 10 concepts taught; independent exercises pending.
- Read README, dashboard, mastery tracker, revision queue, session history, and Session 08 report before teaching.
- Prioritized the due shallow-copy/structuredClone review and selected Session 08 object/collection themes, then progressed into array semantics and API-data transformations.
- Exactly 10 concepts:
  1. Object/array spread creates shallow copies; nested references remain shared.
  2. structuredClone deep-clones supported data graphs and preserves cycles, but does not preserve functions, custom prototype behavior, or property descriptors/accessors.
  3. Sparse-array holes differ from explicit undefined; map/filter/forEach skip holes while spread materializes undefined.
  4. Array.from converts iterables and array-like objects into a new dense array and can map during construction.
  5. flatMap maps and flattens exactly one level for nested API data.
  6. forEach does not await async callbacks; choose sequential for...of or parallel Promise.all deliberately.
  7. sort mutates and defaults to string ordering; toSorted returns a new shallow array and numeric sorting needs a comparator.
  8. Object.entries only returns own enumerable string keys; Object.fromEntries can create Symbol keys and later duplicate keys win.
  9. Object.freeze is shallow; immutable updates copy the changed path.
  10. Map supports arbitrary keys and insertion order; object/Map serialization trade-offs matter.
- Assigned five checkpoints: output prediction, async forEach bug fix, flatMap implementation, Array.from conversion, and safe dynamic permissions dictionary case.
- No learner answers received; no mastery upgrades made.
- Session 08 descriptor invariants and Zod implementation remain pending; selected Object.entries/fromEntries, freeze, and Map themes were revisited without independent answers.
- Session 07 bounded concurrency, cancellation, Fetch, Express async-error, and node:test checkpoints remain pending.
- Shallow-copy/structuredClone review remains due 2026-11-17 because no new independent answer was received.
- Session 09 first recall scheduled for 2026-11-18.
- Monthly assessment remains targeted for approximately 2026-12-09, conditional on sufficient completed material.
- No project milestone: four completed formal sessions have not been reached.
- [Session report](../session-reports/2026-11-17-session-09.md)

## 2026-11-16 — Session 08: Property Introspection, Descriptors, and Safe Request Schemas
- **Status:** In progress — exactly 10 concepts taught; independent recall pending.
- Read README, dashboard, mastery tracker, revision queue, session history, and Session 07 report before teaching.
- Prioritized older high-priority enumeration, descriptor, integrity-level, prototype-safety, and query-validation gaps while revisiting related Session 07 first-recall material.
- Exactly 10 concepts:
  1. Property dimensions: own/inherited, enumerable/non-enumerable, string/Symbol.
  2. Object.keys, getOwnPropertyNames, getOwnPropertySymbols, and Reflect.ownKeys.
  3. for...in traverses enumerable string properties through the prototype chain; own-property guard.
  4. Object.hasOwn versus in versus propertyIsEnumerable.
  5. Object.defineProperty defaults, return value, and no inherited setter invocation.
  6. Non-configurable data-property transitions, including writable true to false.
  7. preventExtensions, seal, freeze, and shallow immutability.
  8. Prototype-pollution risks in dynamic dictionaries and safer Map/null-prototype/allowlist choices.
  9. Zod 4 strict runtime query schemas, transformations, defaults, and safeParse in Express.
  10. Object.fromEntries duplicate keys and own "__proto__" data-property behavior, including downstream merge risk.
- Assigned five independent checkpoints covering exact enumeration outputs, descriptor invariants, prototype-safe dictionaries, Zod query implementation, and shallow immutability.
- No learner answers received; no mastery upgrades made.
- Session 07's concurrency, cancellation, Fetch, Express error, and node:test checkpoints remain pending.
- Session 08 first recall scheduled for 2026-11-17.
- Shallow-copy/structuredClone review remains scheduled for 2026-11-17.
- Monthly assessment remains targeted for approximately 2026-12-09, conditional on sufficient completed material.
- No project milestone: four completed formal sessions have not been reached.
- [Session report](../session-reports/2026-11-16-session-08.md)

## 2026-11-15 — Session 07: Reliable JavaScript Boundaries — Recall and Failure Modes
- **Status:** In progress — exactly 10 review/application concepts taught; independent recall pending.
- Read README.md, dashboard, mastery tracker, revision queue, session history, and Session 06 report before teaching.
- Session 06 first-recall set was due today. All ten topics were revisited with fresh edge cases; no learner answers were received, so no interval advanced.
- Exactly 10 concepts:
  1. Object.assign source enumeration, Symbol keys, source Get, target Set, and target identity.
  2. Object.assign partial mutation and lack of rollback after a later write fails.
  3. Shallow override precedence, including explicit undefined replacing a default and nested-object replacement.
  4. Descriptor-preserving copies: getter capture without execution, prototype retention, and shallow nested aliases.
  5. Strict query-boundary validation: record shape, own-property presence, decimal-string syntax, safe integer, and range.
  6. Bounded worker-pool invariants, input-order preservation, and measuring the active-task cap.
  7. AbortSignal one-shot behavior, AbortSignal.timeout(), and AbortSignal.any().
  8. Fetch response status, content-type/body parsing, and one-shot response-body consumption.
  9. Express 5 returned-Promise forwarding versus unreturned/detached asynchronous work.
  10. node:test asynchronous test functions and assert.rejects versus synchronous assert.throws.
- Assigned fresh output prediction, bug analysis, parseLimit implementation/tests, worker-pool concurrency proof, cancellation/fetch reasoning, Express route correction, and asynchronous test-writing exercises.
- No learner answers were received; no mastery upgrades or interval advances were made.
- Session 07 first recall scheduled for 2026-11-16.
- Shallow-copy/structuredClone review remains scheduled for 2026-11-17.
- Monthly assessment remains targeted for approximately 2026-12-09, conditional on sufficient completed material.
- No project milestone: four completed formal sessions have not been reached.
- [Session report](../session-reports/2026-11-15-session-07.md)

# Session History

## 2026-11-14 — Session 06: Reliable Object Boundaries, Cancellation, and Backend Testing
- **Status:** In progress — exactly 10 concepts taught; practice checkpoints pending.
- Read README, dashboard, mastery tracker, revision queue, session history, and Session 05 report before teaching.
- Exactly 10 concepts:
  1. Object.assign versus spread: target setters, target identity, and own-property behavior.
  2. Source getter evaluation versus descriptor-preserving accessor copies.
  3. Object.assign partial mutation when a later property write throws.
  4. Shallow nested merge precedence and explicit headers merging.
  5. Safe parseLimit(query: unknown) with own-property presence, syntax, safe integer, and range checks.
  6. Bounded worker-pool design preserving input order and collecting partial outcomes.
  7. AbortController/AbortSignal cooperative cancellation.
  8. Fetch HTTP status handling, network rejection, and JSON body parsing.
  9. Express 5 async route rejection forwarding and safe error middleware.
  10. Node built-in node:test and node:assert/strict boundary testing.
- Assigned output prediction, bug analysis, parseLimit implementation, bounded worker-pool reasoning, cancellation/fetch analysis, and validator tests; no learner answers received in this run.
- Session 05 first-recall topics were retaught but remain pending independent answers; intervals do not advance.
- Sessions 01–04 retain outstanding exercises.
- No mastery upgrades made from teaching alone.
- Session 06 first recall scheduled for 2026-11-15.
- Shallow-copy review remains scheduled for 2026-11-17.
- Monthly assessment remains targeted for approximately 2026-12-09, conditional on sufficient completed material.
- No project milestone: four completed formal sessions have not been reached.
- [Session report](../session-reports/2026-11-14-session-06.md)

## 2026-11-13 — Session 05: Object Assignment Semantics and Safe Backend Boundaries
- **Status:** In progress — exactly 10 concepts taught; exercises pending.
- Exactly 10 concepts: Object.assign source Get/target Set; spread data-property creation; source getter behavior; partial mutation on failure; nested merge precedence; descriptor-preserving shallow copies; non-configurable writable transition; hasOwn presence including undefined; Express/TypeScript unknown query validation; Promise.allSettled ordering and bounded concurrency.
- No learner answers received in the scheduled run.
- No mastery upgrades made from teaching alone.
- [Session report](../session-reports/2026-11-13-session-05.md)

## 2026-11-12 — Session 04: Property Semantics, Object Copying, and Reliable Backend Input
- **Status:** In progress — exactly 10 concepts taught; first output-prediction checkpoint pending.
- Exactly 10 concepts: enumeration APIs; defineProperty defaults; non-configurable invariants; accessor redefinition; descriptor-preserving shallow copy; assign versus spread; integrity levels; Map versus null-prototype dictionary; Express unknown query values; Promise.all versus allSettled and bounded concurrency.
- No learner answers received in that scheduled run.
- No mastery upgrades made from teaching alone.
- [Session report](../session-reports/2026-11-12-session-04.md)

## 2026-11-11 — Session 03: Property Semantics, Copying, and Safe Request Data
- **Status:** In progress — exactly 10 concepts taught; exercises pending.
- Exactly 10 concepts: enumeration APIs; ownership vs enumerability; descriptors; defineProperty defaults/invariants; accessors; descriptor-preserving shallow copies; preventExtensions/seal/freeze; map/forEach async trap; sort/toSorted shallow-copy behavior; prototype pollution and untrusted Express query data.
- Session 03 Exercises A and B assigned; no answers received.
- No mastery upgrades made from teaching alone.
- [Session report](../session-reports/2026-11-11-session-03.md)

## 2026-11-10 — Session 02: Property Descriptors, Safe Object Handling, and Query Validation
- **Status:** In progress — exactly 10 concepts taught; Exercises A and B unanswered.
- Exactly 10 concepts: enumeration; hasOwn/in/propertyIsEnumerable; descriptor types; defineProperty defaults; seal/freeze; map/forEach async trap; sort/toSorted; prototypes and safe dictionaries; non-mutating query normalization; production query validation.
- No mastery upgrades justified by teaching alone.
- [Session report](../session-reports/2026-11-10-session-02.md)

## 2026-11-09 — Session 01: JavaScript Objects and Safe Data Transformation
- **Status:** In progress; shallow-copy basic retest and practical transfer both passed on 2026-11-10. Own/enumerability and query-validation follow-ups remain unanswered.
- Covered exactly 10 tips: object keys/values/entries; entries ownership/enumerability; destructuring entries; filtering and Object.fromEntries; Object.hasOwn vs in; Object.assign; shallow object spread; freeze vs seal; map vs forEach; sort vs toSorted.
- Shallow-copy concept remains Practicing after successful basic prediction and practical structuredClone() fix.
- Query-validation implementation had a faulty guard, input mutation, truthiness-based numeric checks, and no sort allowlist.
- [Session report](../session-reports/2026-11-09-session-01.md)

## Ledger initialization — 2026-11-08
- Created the initial learning-ledger structure.
- No formal teaching or assessment session had been recorded at initialization.
- Technical topics were initially unassessed.
