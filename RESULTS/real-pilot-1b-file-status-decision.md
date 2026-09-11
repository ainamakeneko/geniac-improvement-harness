# Real Pilot 1B — File-status confirmation decision

> **Decision:** One targeted verbal confirmation is still the safest, lowest-effort next step. This record does not authorize access to records, a field experiment, or any workflow, storage, permission, retention, or technology change.

## Updated evidence

| Status | Statement | Decision relevance |
| --- | --- | --- |
| OBSERVED | The operator expects the aggregation to recur annually. | Recurrence makes prevention of another paper recount more plausible, although the responsible owner has not confirmed the formal schedule. |
| OBSERVED | One person spent about two hours on the observed occurrence, including photographing paper, AI-assisted transcription, and modifying an Excel workbook. | This establishes effort on the occurrence, but **not** a clean paper-only baseline or two hours of potential annual savings; it excludes unobserved upstream/downstream work and mixes processing with ad-hoc tooling. |
| OBSERVED | Monthly source formats were almost the same across months. | Bounded structural variation may support reuse of structured data, but compatibility has not been inspected. |
| OBSERVED | Monthly Excel files existed at some point but were unavailable to the operator during the work. | Upstream prevention remains plausible; unavailability to one operator is not evidence that the files were lost. |
| HYPOTHESIS | If original monthly files can be accessed under existing controls, using or preserving that structured source could avoid future paper recounting with less risk and effort than OCR. | This is the leading improvement mechanism, conditional on the file-status answer and human review. |
| UNKNOWN | Whether the original monthly Excel files or blank templates exist, are safely accessible to authorized staff, and are covered by a reliable approved preservation practice. | This single unknown selects among direct structured-data testing, a temporary availability safeguard, and a paper fallback. |
| UNKNOWN | The required output and checks; end-to-end baseline; authorization for data handling or prior AI use; applicable privacy, retention, document-control, device, and external-tool rules. | These must be resolved before any test involving real records. The prior photo/AI activity does not establish authorization. |

Only the two real observation records are treated as facility evidence. Earlier simulated work is not facility evidence.

## Ranked opportunities

1. **Confirm original-file existence and safe accessibility.** Evidence: the files previously existed and their present status is unknown. Expected benefit: one short answer chooses the next intervention branch. Risk and burden: minimal when answered verbally without opening, copying, or sharing records. Smallest reversible test: the exact factual check below.
2. **Prevent a future paper fallback through temporary, approved file availability.** HYPOTHESIS: if files exist but retrieval or preservation is unreliable, a reversible availability check could reduce future recounting. Expected benefit: avoids re-entry rather than accelerating it. Uncertainty: ownership and controls. Smallest later test: after human approval, trial a temporary checklist or non-authoritative index for one cycle without moving files or changing permissions, retention, official records, or authoritative storage.
3. **Test aggregation from structured monthly files.** HYPOTHESIS: broadly similar monthly structures could support an existing-workbook method or small tool. Expected benefit: fewer manual aggregation steps. Uncertainty: exact structures, output, checks, and net savings. Smallest later test: blank/synthetic structures only, with setup, exception handling, correction, verification, and maintenance time recorded; rollback is deletion of the test copy/tool.
4. **Improve the paper-only fallback.** Evidence: paper was used for this occurrence. HYPOTHESIS: a simple tally/check aid may reduce burden if structured files cannot be used. Uncertainty: the clean manual method, volume, error burden, and required checks are unknown. Smallest later test: first observe or reconstruct category-level steps without record contents; prefer a reversible manual aid before OCR unless full verification and privacy costs support OCR.
5. **Make no operational change.** If recurrence, authority, expected benefit, or safe handling cannot be established, avoiding setup and maintenance may have the best net benefit.

The ranking favors strong evidence, reversibility, low trial cost, privacy, and measurable net benefit rather than technical sophistication.

## Single highest-value confirmation

Ask the **responsible process owner or authorized records/file custodian** this exact question verbally:

> Do the original monthly Excel files for this recurring aggregation still exist, and can authorized staff reliably retrieve and use them under the current approved access, retention, and document-control rules when preparing the next aggregation?

A verbal answer is sufficient. Do **not** request files, screenshots, record contents, names, identifiers, or unredacted service-user data. If the respondent cannot answer both existence and safe accessibility, they may identify the authorized role who can; do not inspect records to answer the question.

## What each answer triggers

| Answer | Next branch (still subject to human approval) |
| --- | --- |
| **Files exist and are safely, reliably accessible** | Prefer upstream use of the existing structured source. Next, confirm the required output and checking rules, then consider one proposal for a blank/synthetic workbook or tool test. Verification cost must include setup, all exceptions, corrections, comparison/checking, and staff review—not only run time. Record who maintains it and the effort needed when monthly formats change. Rollback: delete the test artifact and continue the existing process; do not alter source files. |
| **Files exist, but access or preservation is unreliable** | Prefer upstream prevention before calculation automation. After confirming ownership and controls, consider one proposal for a temporary, reversible retrieval/preservation check (for example, a non-authoritative location/naming checklist tested for one cycle). It must not move or edit authoritative records or change permissions, retention, backup, or official storage. Rollback: remove the temporary aid and leave all official arrangements unchanged. |
| **Files do not exist or cannot be used** | Move to the paper fallback. First gather a content-free workflow trace or category-level reconstruction to identify counting, transcription, or checking burden. Consider a simple tally/check aid before OCR. Any later OCR/tool proposal must use blank/synthetic structure first and include scanning, correction, complete verification, privacy safeguards, maintenance, and rollback costs. Do not assume prior AI transcription was authorized. |
| **Unknown or disputed** | Stop and seek an answer from the authorized owner/custodian. Do not treat uncertainty as file loss and do not begin a field test. |

## Why confirmation beats an immediate experiment

The answer changes the intervention class, not merely its design. A short verbal check can prevent effort spent building OCR, a new application, or a large automation when an approved structured source may already exist. It can also prevent an unsafe file-management recommendation when existing controls do not permit use. Immediate OCR would optimize a fallback before establishing that the fallback is necessary, while a new application or broad automation lacks a defined output, clean baseline, verified input compatibility, authorization, verification method, and maintenance owner.

The roughly two-hour report does not change that conclusion: it is useful evidence that effort occurred, but its mixture of photography, AI transcription, workbook modification, and partial workflow coverage makes it unsuitable as either a manual baseline or a savings claim. A future experiment must measure end-to-end staff minutes, manual steps/hand-offs, exceptions, corrections/rework, verification time, adoption friction, monetary cost, and maintenance burden.

## Decision and post-run review

- **Decision:** do not propose a field experiment yet. Obtain the single verbal factual confirmation above; it has greater expected learning value per staff minute than prototyping.
- **Assumptions made:** HYPOTHESIS: an authorized role can answer the question with little effort and without accessing or disclosing record contents. HYPOTHESIS: avoiding paper recounting would generally be preferable to optimizing OCR, subject to controls and total net benefit.
- **Missing evidence:** file existence/access reliability is the immediate gap. Output/check requirements, clean end-to-end baseline, authorization, controls, structural compatibility, maintenance ownership, and error burden remain unknown for later gates.
- **Overproduction check:** no software, spreadsheet, OCR workflow, field experiment, or storage/process change was created. One factual confirmation is more proportionate than solution-building.
- **Missed-opportunity review:** no useful opportunity appears to be blocked by a missing harness rule, schema, or tool; the existing separation of evidence, hypotheses, unknowns, and human gates supported this decision.
- **Permanent harness change:** none is justified. This follow-up supplies case evidence but not repeated or consequential evidence of a durable harness deficiency, so no `HARNESS/proposals/` entry is created.
