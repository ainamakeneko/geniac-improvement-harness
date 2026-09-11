# TASK

## Real Pilot 1B — Decide the next safe branch from follow-up evidence

Read `AGENTS.md`, `skills/improvement-run/SKILL.md`, `CONTEXT/facility-profile.md`, `OBSERVATIONS/real-annual-work-type-aggregation-01.md`, `OBSERVATIONS/real-annual-work-type-aggregation-followup-02.md`, and `RESULTS/real-pilot-01-next-evidence.md`.

This is a continuation of a real-facility pilot. Treat only the two REAL observation files as facility evidence. Earlier simulated experiments may inform method only.

New operator-reported evidence indicates that the task likely recurs annually, one person spent about two hours on the observed occurrence including photographing paper, AI-assisted transcription, and modifying an Excel workbook, and the monthly source format was broadly similar across months. The existence/access status of the original monthly Excel files remains unknown and can likely be clarified by asking the appropriate person.

Your task is to:
1. update the decision using the new evidence without double-counting the two-hour estimate as a clean manual baseline;
2. separate OBSERVED, HYPOTHESIS, and UNKNOWN claims;
3. identify the single highest-value remaining question or observation that most changes the next intervention choice;
4. decide whether the evidence now justifies a small reversible experiment, or whether one targeted factual confirmation is still better;
5. explicitly compare these branches:
   - original monthly Excel files exist and are safely accessible;
   - original monthly Excel files exist but access/preservation is unreliable;
   - original files do not exist or cannot be used;
6. prefer upstream prevention of future paper recounting over optimization of OCR/paper fallback when evidence supports it;
7. if a spreadsheet/script/tool experiment becomes justified, require blank/synthetic structure first and define verification cost, maintenance burden, and rollback;
8. if a process/file-management experiment becomes justified, keep it temporary/reversible and do not change permissions, retention, official records, or authoritative storage without explicit human approval;
9. do not use or request unredacted service-user data;
10. stop before field deployment or permanent workflow/storage/technology change.

Important constraints:
- Do not infer that the prior photo/AI transcription was authorized merely because it occurred.
- Do not assume the original Excel files are lost.
- Do not infer the exact government program, subsidy, legal basis, or submission format.
- Do not treat the roughly two-hour operator effort as proof of annual savings because it includes ad-hoc tooling and excludes unobserved upstream/downstream work.
- The next step should minimize staff effort. If one verbal factual check can resolve the main branch, prefer that over a larger experiment.

At completion:
- if one targeted confirmation is still the best next step, update or create a concise decision record under `RESULTS/` stating the exact question, who should answer it by role, and what each possible answer triggers;
- if evidence is sufficient for one reversible experiment, create one proposal under `EXPERIMENTS/proposed/` using the template;
- explain why the chosen next step has greater expected learning value than immediately building OCR, a new application, or a large automation;
- state whether any permanent harness change is justified. Do not propose one without repeated or consequential evidence.