# Session History

## 2026-11-09 — Session 01: JavaScript Objects and Safe Data Transformation
- **Status:** In progress; shallow-copy basic retest and practical transfer both passed on 2026-11-10. Other targeted reviews remain.
- Covered exactly 10 tips: object keys/values/entries; entries ownership/enumerability; destructuring entries; filtering and Object.fromEntries; Object.hasOwn vs in; Object.assign; shallow object spread; freeze vs seal; map vs forEach; sort vs toSorted.
- **Q1:** Second output (true false) correct. First and third outputs incorrectly included inherited and non-enumerable properties; key names should be strings, and entries are two-element [key, value] arrays.
- **Q2 basic retest:** After re-teaching, correctly predicted user1.name as "Ansh" and user1.profile.city as "Delhi". Explained that spread copies one level and nested objects remain shared references.
- **Q2 practical transfer:** Correctly predicted all three outputs of the makeRequestConfig shared-headers bug as "Bearer token-B". Explained that defaults.headers, request1.headers, and request2.headers all reference the same nested object. Independently fixed the function using structuredClone(defaults), then assigned the request-specific authorization token.
- Shallow-copy status remains **Practicing** (not Competent yet): basic and practical examples are correct; broader edge cases and alternative strategies have not yet been assessed.
- **Q3:** Learner understood the broad entries/filter/fromEntries approach and correctly stated that allowlisted keys alone do not validate input. Implementation issues: faulty initial guard, input mutation, truthiness-based numeric checks, no sort-value allowlist, and no explicit undefined filtering.
- Explained the separation between input-shape checks, filtering, normalization, required-field checks, and value validation. Provided a corrected illustrative implementation; this is instruction, not evidence of independent mastery.
- Next shallow-copy spaced review scheduled for 2026-11-17.
- [Session report](../session-reports/2026-11-09-session-01.md)

## Ledger initialization — 2026-11-08
- Created the initial learning-ledger structure.
- No formal teaching or assessment session had been recorded at initialization.
- Technical topics were initially unassessed.
