# Session History

## 2026-11-11 — Session 03: Property Semantics, Copying, and Safe Request Data
- **Status:** In progress — exactly 10 concepts taught; exercises pending.
- Read README, dashboard, mastery tracker, revision queue, session history, and Session 02 report before teaching.
- Exactly 10 concepts:
  1. Enumeration API differences: Object.keys, Object.getOwnPropertyNames, Reflect.ownKeys, and for...in.
  2. Ownership vs enumerability: in, Object.hasOwn, propertyIsEnumerable.
  3. Reading own property descriptors.
  4. Object.defineProperty defaults and non-configurable invariants.
  5. Accessor descriptors and getter/setter behavior.
  6. Descriptor-preserving shallow copies with Object.getOwnPropertyDescriptors and Object.create.
  7. preventExtensions vs seal vs freeze.
  8. map vs forEach, async forEach trap, Promise.all vs sequential iteration.
  9. sort vs toSorted, comparator correctness, and shallow copy behavior.
  10. Prototype pollution defenses, Map/null-prototype dictionaries, and safe Express query input handling.
- Exercise A (enumeration/descriptor output prediction) and Exercise B (getLimit bug hunt and implementation) assigned; no answers received yet.
- Sessions 01 and 02 remain in progress with their outstanding exercises unanswered.
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
