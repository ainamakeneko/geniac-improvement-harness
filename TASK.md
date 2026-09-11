# TASK

## Real Pilot 1C — Test the smallest structured-data path

Read `AGENTS.md`, `skills/improvement-run/SKILL.md`, `CONTEXT/facility-profile.md`, `OBSERVATIONS/real-annual-work-type-aggregation-01.md`, `OBSERVATIONS/real-annual-work-type-aggregation-followup-02.md`, `OBSERVATIONS/real-annual-work-type-aggregation-followup-03.md`, `RESULTS/real-pilot-01-next-evidence.md`, and the latest Real Pilot 1B decision record under `RESULTS/` if present.

This is a continuation of a real-facility pilot. Treat only REAL observation files as facility evidence. Earlier simulated experiments may inform method only.

New confirmed evidence: the original monthly Excel files exist and can be reused in future annual aggregation work. The task is expected to recur annually, and the monthly source format is broadly similar across months. The observed roughly two-hour effort is not a clean baseline because it included photographing paper, AI-assisted transcription, and ad-hoc workbook modification.

Your task is to:
1. update the decision now that structured monthly files are known to exist and be reusable;
2. separate OBSERVED, HYPOTHESIS, and UNKNOWN claims;
3. compare at least these options:
   - no change / continue manual annual aggregation from the monthly workbooks;
   - improve only file availability/preservation if that is still the bottleneck;
   - use existing Excel capabilities such as formulas, PivotTable, or Power Query;
   - use a small local script only if it has a clear advantage over Excel;
   - keep OCR/paper transcription only as a fallback, not the default path;
4. determine the smallest safe experiment that can test whether structured-data aggregation materially reduces total annual preparation effort;
5. prefer a prototype using a blank template, sanitized structural sample, or synthetic workbook before any real personal data is handled;
6. if the workbook structure is still insufficiently known, specify the minimum structural facts needed (for example sheet names, column headers, one row's schema, category encoding, and output shape) without requesting personal records;
7. account for full end-to-end cost: locating files, loading/importing, aggregation, exception handling, verification, corrections, maintenance, and hand-off;
8. define how the prototype result will be checked against a known expected result or independently computed synthetic truth;
9. create at most one reversible experiment proposal under `EXPERIMENTS/proposed/` if evidence is sufficient; otherwise create a concise `RESULTS/real-pilot-1c-structure-needed.md` containing only the minimum structural information to request next;
10. stop before using real service-user data, changing official records, changing authoritative storage, or deploying a permanent workflow.

Important constraints:
- Do not build a new application by default. Prefer the smallest existing-tool solution that can be maintained by the organization.
- Do not recommend external cloud OCR/AI for unredacted records.
- Do not infer that Excel automation is worthwhile merely because files exist; the prototype must include verification and maintenance cost.
- Do not treat the prior two-hour effort as the expected saving.
- A local script is justified only if workbook structure or repeated steps make Excel-native approaches materially less reliable or maintainable.
- Any future real-data test requires explicit human approval and locally authorized handling.

At completion, explain:
- why the decision changed after confirming the files exist;
- whether the next step is a prototype experiment or one final structure-only fact check;
- why Excel-native, local-script, file-management, paper/OCR, and no-change options rank as they do;
- the exact evidence threshold for moving from synthetic/blank data to a human-approved real-data trial;
- whether any permanent harness improvement is justified. Do not propose one without repeated or consequential evidence.