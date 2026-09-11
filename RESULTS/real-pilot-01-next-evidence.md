# Real Pilot 1 — Next-evidence decision

> Decision: evidence is not yet sufficient to select a field intervention. This artifact proposes a short, non-sensitive fact-finding step only; it does not authorize a field test, access to real records, or a permanent workflow, storage, or technology change.

## Current evidence

| Status | Statement | Decision relevance |
| --- | --- | --- |
| OBSERVED | The operator joined partway through a task preparing source data for a government-office submission described as possibly subsidy-related. | The beginning, exact purpose, ownership, and full workflow were not observed and must not be reconstructed as facts. |
| OBSERVED | The source represented each service user's daily work type across approximately one year. | The aggregation spans enough records that prevention or automation could matter, but volume is not known. |
| OBSERVED | Monthly data had existed in Excel at some point, but those files were unavailable to the operator during this work. | Recovering or preserving structured data is a plausible prevention path. It is not evidence that the files are lost. |
| OBSERVED | Printed paper was the available source, and approximately twelve months were manually aggregated; the operator performed part of that work. | A paper-fallback burden occurred, but its duration, counting method, checking, and error burden were not observed in full. |
| HYPOTHESIS | Making existing monthly files reliably available, or exporting a stable non-destructive annual summary, could prevent a future paper recount. | This is the leading opportunity because it acts upstream, but it depends on recurrence, file existence, format stability, authority, and control requirements. |
| HYPOTHESIS | If paper remains the only usable source, a clearer manual tally/checking method may outperform OCR after correction and verification time are counted. | This offers a low-technology fallback, but the current manual method and bottleneck are unknown. |
| UNKNOWN | The exact submission and requirements; recurrence; process owner; file existence, location, history, and format stability; record volume; full time; counting/checking method; final destination; data sensitivity and controls; and related aggregations. | These unknowns prevent a safe, measurable choice among prevention, spreadsheet automation, paper-path assistance, and no change. |

## Ranked opportunities

Ranking uses qualitative judgment rather than invented scores. “Future prevention” avoids another paper fallback; “fallback acceleration” improves work after paper has already become the usable source.

| Rank | Opportunity and scope | Evidence and hypothesized mechanism | Expected benefit / measurability | Risk, burden, uncertainty, and smallest reversible test |
| --- | --- | --- | --- | --- |
| 1 | **Locate and structurally inspect the existing monthly Excel workflow** — future prevention | OBSERVED: monthly Excel data once existed but was unavailable during this task. HYPOTHESIS: availability, preservation, or a routine authorized export could avoid re-entry/counting. | Potentially eliminates much manual annual work; compare end-to-end preparation minutes, manual steps, exceptions, and checking. | Low risk only if the first check asks an authorized owner about existence, formats, and controls without copying or opening personal data. UNKNOWN recurrence and permissions. Smallest test: a 10–15 minute owner/operator conversation plus, only after separate human authorization, inspection of blank templates or structural metadata. |
| 2 | **Measure one recurrence or reconstruct the completed workflow at category level** — observation, both paths | OBSERVED: only part of the work was observed and no duration or detailed method is known. HYPOTHESIS: a coarse trace will identify whether retrieval, counting, transcription, checking, or final entry dominates. | Highest immediate learning value; measure contributor minutes, page/row/category counts, hand-offs, corrections, and checks without record contents. | Very reversible and low cost; must not include personal data or evaluate individual performance. A short retrospective now is weaker than timing a future occurrence but can guide whether waiting is worthwhile. |
| 3 | **Use an existing workbook formula/pivot or a small local script on structured files** — future prevention | HYPOTHESIS only: stable monthly structure may permit automatic aggregation. | Could save counting and checking time; measure total run, exception, correction, and verification minutes against the manual route. | Premature until recurrence, compatible files, required output, permitted environment, and verification rules are known. Maintenance rises if formats vary. Smallest later test: synthetic or blank-template proof, then separately approved use on authorized data. |
| 4 | **Standardize a paper tally and independent check** — fallback acceleration | OBSERVED: paper was manually aggregated. HYPOTHESIS: a category checklist/tally sheet could reduce cognitive load, omissions, or duplicate counts. | Likely modest; compare total minutes, recounts, discrepancies, unresolved exceptions, and staff acceptability. | Low technology and reversible, but may merely add documentation if the existing method is already equivalent. First observe or describe the current method; do not alter official records. |
| 5 | **Local OCR or structured transcription with verification** — fallback acceleration | HYPOTHESIS: machine extraction or keyed transcription could accelerate paper processing. | Potential gross speed benefit on many regular pages, but net benefit must include scanning, correction, checking, setup, and exception handling. | Higher privacy, accuracy, device, and review risk; format/volume/legibility are UNKNOWN. Do not upload unredacted records to external AI/OCR services. Consider only after lower-risk paths fail and local authorization/controls are explicit. |
| 6 | **Do nothing beyond retaining this decision record** | UNKNOWN: the task may be one-off, too small, or governed by constraints that make change uneconomic. | Avoids setup, maintenance, and change burden. | Foregoes learning and possible future savings. Appropriate if no recurrence is expected, burden was immaterial, or answering the minimum questions costs more than the likely benefit. |

## Strongest current hypotheses

1. **HYPOTHESIS — upstream prevention leads:** if the work recurs and compatible monthly files exist or can be retained under approved controls, reliable availability plus an existing-tool summary could avoid more work than optimizing paper counting.
2. **HYPOTHESIS — measurement may change the choice:** if file recovery is infeasible, a category-level workflow trace will show whether a manual tally/check aid, structured transcription, or no intervention has the best net value.
3. **HYPOTHESIS — OCR is not the default:** privacy safeguards and full verification may outweigh extraction savings, particularly at low volume or with irregular pages.

## Minimum next questions and observations

Ask one appropriate process owner/operator these four grouped questions in a **10–15 minute conversation**. Do not request record contents, names, identifiers, or copies.

| Minimum item | Why it changes the decision |
| --- | --- |
| 1. Is another aggregation expected; if so, approximately when, how often, and who owns the process? Is the same information aggregated elsewhere? | Recurrence and ownership decide whether prevention has enough expected benefit and whether waiting to observe a live occurrence is useful. No exact subsidy or legal interpretation is requested. |
| 2. Do any original monthly Excel files or blank templates still exist, where are they normally kept, who is authorized to access them, and are their columns/categories broadly stable across months? A verbal answer is sufficient initially. | Existing, compatible files favor retrieval/preservation and existing spreadsheet functions; absent or incompatible files move attention to the paper fallback. Authorization precedes any inspection. |
| 3. At a coarse level, what were the steps from source retrieval through final hand-off, approximately how many pages/rows/categories were involved, how many total staff-hours were spent, and where did rework or difficulty occur? | Identifies the dominant burden, supplies a baseline, and indicates whether any intervention can create measurable net benefit. Estimates should be labeled estimates. |
| 4. What checking was required or actually performed, what final format received the totals, and what local privacy, retention, document-control, or approved-device rules constrain files, scanning, OCR, and exports? | Verification effort and controls can rule out OCR/automation, alter total-cost estimates, and prevent unsafe handling or changes to official records. |

If answers remain uncertain and the task recurs, the next choice should be an explicitly human-approved, observation-only trace of one naturally occurring aggregation: record only category-level step durations, hand-offs, page/row/category counts, corrections, unresolved exceptions, and checking time. Record no service-user data or contents. This is a candidate next proposal after the conversation, not an approved activity here.

## What can already be ruled out

- Building a new application now: no recurring need, stable input, required output, owner, baseline, or maintenance case is evidenced.
- Treating the Excel files as permanently lost: only their unavailability to this operator during this work is observed.
- Assuming the submission is a particular subsidy, annual legal requirement, or fixed government form.
- Uploading unredacted service-user records to an external AI/OCR service.
- Judging OCR by extraction speed alone; correction and complete verification belong in the end-to-end measure.
- Changing official records, required checks, storage, permissions, retention, or the submission process without explicit human review and approval.
- Treating software tests as evidence of operational benefit.

## Likely decision branches

1. **Recurring + structured files available/compatible + use permitted:** first test a retrieval/preservation or existing-spreadsheet summary path, using blank/synthetic structure before any separately approved handling of real data. Favor a process/file-management change if availability—not calculation—is the bottleneck.
2. **Recurring + structured files available but formats vary:** inspect blank templates or sanitized schemas after approval; consider a small spreadsheet/script only if variation is bounded and forecast savings exceed setup, exception, verification, and maintenance time.
3. **Recurring + structured files unavailable/unusable:** observe the paper workflow. Test a simple tally/check aid before OCR unless volume, regularity, permitted local tooling, and expected net savings support OCR.
4. **One-off, rare, low-burden, or heavily constrained:** make no intervention and record that outcome; preserving this negative decision is useful evidence.
5. **Answers or access controls remain unclear:** stop. Seek the responsible human's review rather than inspect records or propose a field test.

## Evidence thresholds for later action

- **Spreadsheet/script/tool:** justified for a proposal only by evidence of recurrence, stable or bounded input structure, a defined required output, authorized execution/data handling, a material measured or credible baseline burden, and a verification method whose total correction/checking/maintenance cost still leaves worthwhile net benefit. Prototype first with blank or synthetic data; real-data use needs explicit human approval.
- **Process/file-management change:** favored when files already exist and calculation is straightforward, but availability, naming/versioning, authorized retrieval, hand-off, or preservation caused the fallback. Any persistent change still requires a separate proposal and human approval after confirming retention, access, backup, and document-control requirements.

## Decision and post-run review

- **Decision:** no experiment is proposed yet. The four-question conversation is the minimum evidence step; it requires about 10–15 minutes from one appropriate human and no access to service-user records. An observation experiment can be proposed afterward only if needed.
- **Known versus unknown:** the observed annual-scale, paper-based manual aggregation and prior existence/unavailability of Excel data are known. Recurrence, burden, workflow, checks, file status/structure, controls, and required output remain unknown.
- **Leading opportunity:** prevent another paper fallback by making authorized structured monthly data usable. It is not yet the solution because recurrence, file existence, root cause, authority, and format stability are unverified.
- **Assumptions made:** HYPOTHESIS: an appropriate person can answer the grouped questions in 10–15 minutes and category-level answers can be given without exposing sensitive data. The ranking also assumes that eliminating work is generally preferable to accelerating it, subject to local controls and total burden.
- **Missing evidence:** all decision-critical unknowns in the evidence table, especially recurrence, measured burden, structured-file status, checking, and controls.
- **Overproduction check:** no software, template, field intervention, or permanent change was produced. Observation is more informative than solution-building at this stage.
- **Missed-opportunity/harness review:** no repeated or consequential harness deficiency is evidenced by this single real pilot. Existing rules and templates support uncertainty labels, alternatives, privacy gates, net-benefit accounting, and a no-build decision. No permanent harness improvement or `HARNESS/proposals/` entry is justified.
