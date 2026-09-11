# TASK

## Real Pilot 1D — Resolve the category encoding, then prototype only if justified

Read `AGENTS.md`, `skills/improvement-run/SKILL.md`, `CONTEXT/facility-profile.md`, all Real Pilot 1 observation files including `OBSERVATIONS/real-annual-work-type-aggregation-followup-04.md`, `RESULTS/real-pilot-01-next-evidence.md`, the Real Pilot 1B decision record, and `RESULTS/real-pilot-1c-structure-needed.md`.

This is a continuation of a real-facility pilot. Treat only REAL observation files as facility evidence. Earlier simulated experiments may inform method only.

Current confirmed facts include:
- one workbook per month;
- relevant sheet described as `作業記録`;
- a recurring annual aggregation;
- reusable original monthly Excel files exist;
- intended annual output is counts by 利用者 × 作業種類;
- blank means no work;
- monthly and annual totals should reconcile;
- the operator also reports that one person/day can have multiple `○` cells when multiple work types occur.

There is one important structural ambiguity: the description `C: 作業種類` is not yet sufficient to explain how multiple `○` cells encode multiple work types. Do not guess the workbook schema.

Your task is to:
1. separate OBSERVED, HYPOTHESIS, and UNKNOWN claims;
2. identify the minimum single structural clarification needed to distinguish among likely encodings of multiple work types;
3. prefer that one clarification over building the wrong prototype;
4. if the encoding can be represented safely from the supplied evidence without guessing, create at most one synthetic/blank-data experiment proposal under `EXPERIMENTS/proposed/`;
5. otherwise create or update a concise result artifact specifying exactly what to inspect or ask, using only content-free structure;
6. if a prototype becomes justified, prefer the least complex Excel-native approach that can:
   - combine 12 monthly files;
   - count annual occurrences by synthetic person key × work category;
   - handle multiple work categories on one day correctly;
   - preserve blanks/no-work semantics;
   - produce monthly and annual control totals;
   - surface exceptions rather than silently dropping them;
7. compare formulas/PivotTable/Power Query with a small local script and justify the simplest maintainable choice;
8. create synthetic truth before running the prototype and require exact agreement on counts and control totals;
9. measure setup, import, aggregation, exceptions, verification, correction, maintenance, and hand-off effort;
10. stop before any real service-user data is used or any permanent workflow/storage/technology change is made.

Important constraints:
- Do not request names, identifiers, populated rows, screenshots containing real records, or real workbook contents.
- A content-free screenshot or sketch of only headers/blank structure is acceptable only if the human operator confirms it contains no personal or sensitive data.
- Do not interpret `C: 作業種類` and `multiple ○ cells` as compatible without evidence.
- Do not build a new application.
- Do not use the prior roughly two-hour effort as the expected saving.

At completion, explain:
- the one remaining structural ambiguity;
- the smallest way to resolve it;
- whether a synthetic prototype is now justified;
- if so, what exact prototype and truth-check should be used;
- whether any permanent harness improvement is justified. Do not propose one without repeated or consequential evidence.