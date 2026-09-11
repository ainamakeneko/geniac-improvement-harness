# Real Pilot 1C — Structure-only fact check

> **Decision:** Do not prototype yet. The reusable monthly Excel files make structured-data aggregation the leading path, but their structure and the required output are not defined well enough to build a meaningful synthetic test. Obtain the content-free facts below, then choose the smallest Excel-native prototype. This record does not authorize opening or copying real records, using real personal data, changing storage or official records, or conducting a field test.

## Evidence and decision

| Status | Statement | Decision effect |
| --- | --- | --- |
| OBSERVED | The original monthly Excel files exist and can be reused for future annual aggregation. | The previous file-existence branch is resolved; optimizing paper transcription is no longer the default path. |
| OBSERVED | The aggregation is expected to recur annually, and monthly formats are broadly similar. | A reusable structured-data method is plausible, but “broadly similar” does not establish technical compatibility. |
| OBSERVED | About two hours were reported for one operator's partial occurrence, including photography, AI-assisted transcription, and ad-hoc workbook modification. | Effort occurred, but this is neither a clean end-to-end baseline nor an expected saving. |
| HYPOTHESIS | An Excel-native aggregation of reusable monthly files will require less total annual preparation effort than manual aggregation from those files. | This is the next claim to test with synthetic or blank data once the structure is known. |
| UNKNOWN | Exact workbook schema, variations, annual output shape, required checks, retrieval burden, authorized handling rules, and clean end-to-end effort. | Without these facts, a prototype could test the wrong import, calculation, exception, or verification problem. |

## One structure-only fact check

Ask an authorized workbook owner to provide **only** a blank template, sanitized structural sample, or the following content-free description. Do not provide populated rows, screenshots containing records, names, identifiers, or other service-user information.

1. File type and Excel version in normal use; workbook and relevant sheet names; whether one file represents one month.
2. The relevant table/range location and exact column headers, plus one **invented** example row showing data types only (for example, date / invented person key / work-category code).
3. How a day with no work, blanks, multiple categories, corrections, totals, merged cells, formulas, and other non-data rows are encoded; list any month-to-month header, sheet, or layout variations.
4. The allowed work-category values or code pattern, using labels only if they are not sensitive.
5. The annual output's row/column shape, grouping and counting rules, and required totals—again with invented values only.
6. The required verification result (for example, source row counts and category totals) and who performs the check by role, not name.

These are the minimum facts that determine whether formulas, a PivotTable, or Power Query can represent the import, aggregation, exceptions, output, and check. File-location changes are not proposed because reliable retrieval has not been identified as the bottleneck.

## Option ranking

1. **Excel-native prototype after the fact check.** HYPOTHESIS: formulas or a PivotTable may be enough for one consistent table; Power Query may be preferable for repeatable combination of twelve similar files. It uses an existing tool and is likely easier to hand off than code. Start with the least complex option that represents the supplied structure.
2. **No change: manual aggregation from monthly workbooks.** This is the comparison condition and remains preferable if automation's setup, exceptions, checking, corrections, maintenance, and hand-off cost do not produce a material net benefit.
3. **File availability/preservation only.** The files' existence and reuse are OBSERVED, but retrieval reliability is UNKNOWN. Promote this option only if the end-to-end trace shows locating or authorized access—not calculation—is the material bottleneck. Do not change authoritative storage, permissions, retention, or backups in this run.
4. **Small local script.** Consider only if the supplied structures contain bounded variations or repeated transformations that Excel cannot handle as reliably or maintainably. It must show a clear end-to-end advantage after installation, review, exception handling, verification, maintenance, and staff hand-off; no such advantage is currently observed.
5. **Paper transcription/OCR fallback.** Retain only for a future case where structured files cannot be used. External cloud OCR/AI must not receive unredacted records, and any permitted fallback must count capture, correction, and complete verification time.

Building a new application is not ranked because no evidence shows that it is needed.

## Prototype and truth check after the facts arrive

Create one disposable local workbook using the blank/sanitized structure and synthetic monthly inputs that deliberately cover every identified encoding and variation. Before running the prototype, independently write down the expected annual counts and control totals for that synthetic set. A second manual calculation or a simple, reviewable calculation made independently of the prototype may establish this synthetic truth.

Compare the prototype with manual aggregation of the **same synthetic set**. For both paths, record end-to-end staff minutes for locating, loading/importing, aggregation, exceptions, verification, corrections, and hand-off. For the prototype also record initial setup and forecast annual maintenance; record discrepancies, unresolved exceptions, manual steps, and usability concerns. Delete the disposable copies to roll back. This would test implementation behavior only, not operational benefit in the real workflow.

## Threshold for a human-approved real-data trial

Move beyond blank/synthetic data only when all of the following are documented:

- the prototype exactly matches the independently established synthetic truth, including control totals, for every known structural variation and exception;
- the synthetic comparison shows a credible **material** reduction in total recurring preparation effort after verification, correction, hand-off, and forecast maintenance are included, with no unresolved discrepancy;
- an authorized human confirms the real input/output structure, required checking method, approved device/tool, access, copying, retention, and deletion rules, and identifies maintenance and verification roles;
- a separate proposal defines a read-only test on authorized copies, success/failure criteria, rollback, and operational measurement; and
- a human explicitly approves that real-data field test and the locally authorized handling before any real file is used.

No numeric time threshold is invented here. The responsible human should define “material” after seeing measured synthetic times and annual maintenance burden. The reported two hours must not be used as the saving estimate.

## Post-run review

- **Assumptions:** HYPOTHESIS: an authorized owner can supply the six content-free structural facts without disclosing records, and an Excel-native method is maintainable in the organization's existing environment.
- **Missing evidence:** the six structural facts, retrieval effort, clean baseline, authorization and control rules, staff usability, and real-workflow benefit.
- **Overproduction check:** no workbook, script, field experiment, or workflow/storage change was produced because a schema-free prototype would not be informative.
- **Harness review:** no repeated or consequential harness deficiency is evidenced. No permanent harness change or `HARNESS/proposals/` entry is justified.
