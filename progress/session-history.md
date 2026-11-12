# Session History

## 2026-11-12 — Session 04: Property Semantics, Object Copying, and Reliable Backend Input
- **Status:** In progress — exactly 10 concepts taught; first output-prediction checkpoint pending.
- Read README, dashboard, mastery tracker, revision queue, session history, and Session 03 report before teaching.
- Exactly 10 concepts:
  1. Enumeration API recall: Object.keys, Object.getOwnPropertyNames, Reflect.ownKeys, and for...in.
  2. Object.defineProperty defaults, strict-mode assignment, and return value.
  3. Non-configurable descriptor invariants and the one-way writable transition.
  4. Accessor descriptors; getter/setter invocation versus Object.defineProperty reconfiguration.
  5. Descriptor-preserving shallow copy versus spread and structuredClone.
  6. Object.assign versus object spread: target mutation, return value, inherited setters, and source getters.
  7. preventExtensions/seal/freeze and Object.isExtensible/isSealed/isFrozen.
  8. Map versus Object.create(null) for dynamic dictionaries.
  9. Express req.query as untrusted input and TypeScript unknown/runtime narrowing.
  10. Promise.all versus Promise.allSettled, sequential processing, and bounded-concurrency trade-offs.
- First checkpoint assigned: predict output and explain Object.assign invoking an inherited setter versus object spread creating a new object property. No answer received in this automation run.
- Sessions 01–03 remain in progress with their outstanding exercises unanswered.
- No mastery upgrades made from teaching alone.
- First recall review for descriptor invariants, descriptor copies, assign/spread, safe dictionaries, and query validation scheduled for 2026-11-13.
- Shallow-copy spaced review remains 2026-11-17.
- Monthly assessment remains targeted for approximately 2026-12-09, conditional on sufficient completed material.
- No project milestone yet: four completed formal sessions have not been reached.
- [Session report](../session-reports/2026-11-12-session-04.md)

## 2026-11-11 — Session 03: Property Semantics, Copying, and Safe Request Data
- **Status:** In progress — exactly 10 concepts taught; exercises pending.
- Read README, dashboard, mastery tracker, revision queue, session history, and Session 02 report before teaching.
- Exactly 10 concepts: enumeration APIs; ownership vs enumerability; descriptors; defineProperty defaults/invariants; accessors; descriptor-preserving shallow copies; preventExtensions/seal/freeze; map/forEach async trap; sort/toSorted shallow-copy behavior; prototype pollution and untrusted Express query data.
- Session 03 Exercises A and B assigned; no answers recorded.
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
