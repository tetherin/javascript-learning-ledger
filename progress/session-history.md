# Session History

## 2026-11-10 — Session 02: Property Descriptors, Safe Object Handling, and Query Validation
- **Status:** In progress — exactly 10 concepts taught; exercises pending.
- Read README, dashboard, mastery tracker, revision queue, session history, and Session 01 report before teaching.
- Exactly 10 concepts:
  1. Own/inherited/enumerable/non-enumerable property distinctions and Object.keys/values/entries.
  2. Object.hasOwn vs in and propertyIsEnumerable.
  3. Object.getOwnPropertyDescriptor and data/accessor descriptors.
  4. Object.defineProperty defaults and explicit flags.
  5. Object.seal vs Object.freeze; both shallow.
  6. map vs forEach, including async forEach trap.
  7. sort vs toSorted and comparator correctness.
  8. Prototype chains, prototype pollution, Map, and Object.create(null).
  9. Non-mutating query normalization with entries/filter/map/fromEntries.
  10. Query shape, required fields, numeric syntax/range, and sort allowlist validation.
- Exercises A (output prediction/conceptual) and B (bug-finding/case-based implementation) were assigned; no answers received yet.
- Session 01 remains in progress: shallow-copy concept and practical transfer passed; own/enumerability and query-validation follow-ups remain open.
- No mastery upgrades made from teaching alone.
- [Session report](../session-reports/2026-11-10-session-02.md)

## 2026-11-09 — Session 01: JavaScript Objects and Safe Data Transformation
- **Status:** In progress; shallow-copy basic retest and practical transfer both passed on 2026-11-10. Other targeted reviews remain.
- Covered exactly 10 tips: object keys/values/entries; entries ownership/enumerability; destructuring entries; filtering and Object.fromEntries; Object.hasOwn vs in; Object.assign; shallow object spread; freeze vs seal; map vs forEach; sort vs toSorted.
- **Q1:** Second output (true false) correct. First and third outputs incorrectly included inherited and non-enumerable properties; key names should be strings, and entries are two-element [key, value] arrays.
- **Q2 basic retest:** After re-teaching, correctly predicted user1.name as "Ansh" and user1.profile.city as "Delhi". Explained that spread copies one level and nested objects remain shared references.
- **Q2 practical transfer:** Correctly predicted all three shared-header outputs as "Bearer token-B", explained the shared reference, and independently fixed the function using structuredClone(defaults).
- Shallow-copy status remains **Practicing**; next spaced review 2026-11-17.
- **Q3:** Broad entries/filter/fromEntries approach was sound, but implementation had a faulty guard, mutated input, used truthiness for numeric checks, and lacked a sort allowlist.
- [Session report](../session-reports/2026-11-09-session-01.md)

## Ledger initialization — 2026-11-08
- Created the initial learning-ledger structure.
- No formal teaching or assessment session had been recorded at initialization.
- Technical topics were initially unassessed.
