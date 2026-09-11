# TASK

## Real Pilot 1 — Annual work-type aggregation for government submission

Read `AGENTS.md`, `skills/improvement-run/SKILL.md`, `CONTEXT/facility-profile.md`, and `OBSERVATIONS/real-annual-work-type-aggregation-01.md`.

This is the first real-facility pilot. Treat only statements in the real observation file as current evidence. Earlier simulated experiments may inform the improvement method, but must not be treated as evidence about this facility task.

The human operator entered this work partway through. Monthly records had existed in Excel, but only printed paper was available during the observed annual aggregation. Approximately one year of service-user work-type records was manually aggregated to prepare source material for a government submission. The exact application, recurrence, process ownership, file history, and time burden remain partly unknown.

Your task is to:
1. reconstruct the current evidence without inventing missing process details;
2. separate OBSERVED, HYPOTHESIS, and UNKNOWN claims;
3. identify several plausible improvement opportunities across process, file preservation, spreadsheet automation, OCR/transcription, checking, and doing nothing yet;
4. distinguish prevention of future manual work from acceleration of the already-paper-based fallback path;
5. rank the opportunities using expected benefit, evidence strength, privacy/safety risk, reversibility, staff burden, measurability, and recurrence;
6. determine the minimum additional evidence needed before a useful intervention can be proposed;
7. prefer a short targeted follow-up question set or a small observation/measurement step if key uncertainties block a safe intervention;
8. if evidence is already sufficient for a very small reversible experiment, propose at most one experiment under `EXPERIMENTS/proposed/` using the template;
9. do not build software merely because structured data might once have existed;
10. stop before field deployment, handling real personal data, changing official records, or making a permanent workflow/storage/technology change.

Important constraints:
- Do not infer the exact subsidy, regulation, form, reporting cadence, or legal requirement.
- Do not assume the original Excel files are permanently lost; their existence/location is UNKNOWN.
- Do not recommend uploading unredacted service-user records to an external AI/OCR service.
- Consider whether preserving/exporting structured monthly data could eliminate future annual manual counting before optimizing the paper fallback.
- Account for verification burden: an OCR or automation approach that saves counting time but creates substantial correction/checking work may not be a net improvement.
- The first real pilot should minimize staff effort and should be safe to abandon.

At completion, produce one concise decision artifact under `EXPERIMENTS/proposed/` if an experiment is justified. If the evidence is not yet sufficient, instead create `RESULTS/real-pilot-01-next-evidence.md` containing:
- the strongest current hypotheses;
- the smallest set of concrete questions/observations needed next;
- why each item changes a decision;
- what can already be ruled out;
- the likely decision branches after the answers arrive.

At completion, explain:
- what is known versus still unknown;
- the leading improvement opportunity and why it is not yet necessarily the solution;
- the minimum human effort required for the next step;
- what evidence would justify building a spreadsheet/script/tool;
- what evidence would instead favor a process/file-management change;
- whether any permanent harness improvement is justified. Do not propose one without repeated or consequential evidence.