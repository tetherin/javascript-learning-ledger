# Session History

## 2026-11-09 — Session 01: JavaScript Objects and Safe Data Transformation
- **Status:** In progress; initial answers evaluated on 2026-11-10; shallow-copy retest pending.
- Covered exactly 10 tips: object keys/values/entries; entries ownership/enumerability; destructuring entries; filtering and Object.fromEntries; Object.hasOwn vs in; Object.assign; shallow object spread; freeze vs seal; map vs forEach; sort vs toSorted.
- **Q1:** Second output (true false) correct. First and third outputs incorrectly included inherited and non-enumerable properties; key names should be strings, and entries are two-element [key, value] arrays.
- **Q2:** Learner explicitly said shallow-copy bug was not understood. Re-taught that spread makes a new outer object while nested objects remain shared references. A new independent output-prediction retest is awaiting the learner's response.
- **Q3:** Learner understood the broad entries/filter/fromEntries approach and correctly stated that allowlisted keys alone do not validate input. Implementation issues: faulty initial guard, input mutation, truthiness-based numeric checks, no sort-value allowlist, and no explicit undefined filtering.
- Explained the separation between input-shape checks, filtering, normalization, required-field checks, and value validation. Provided a corrected illustrative implementation; this is instruction, not evidence of independent mastery.
- No mastery claims beyond the evidence above. Shallow copying remains marked **Needs re-teaching**.
- First targeted review due 2026-11-10.
- [Session report](../session-reports/2026-11-09-session-01.md)

## Ledger initialization — 2026-11-08
- Created the initial learning-ledger structure.
- No formal teaching or assessment session had been recorded at initialization.
- Technical topics were initially unassessed.
