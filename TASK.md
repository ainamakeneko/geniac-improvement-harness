# TASK

## Experiment 3 — Know when to stop observing and intervene

Read `AGENTS.md`, `skills/improvement-run/SKILL.md`, `CONTEXT/facility-profile.md`, `OBSERVATIONS/interview-notes-01.md`, the Experiment 1 and Experiment 2 proposals under `EXPERIMENTS/proposed/`, `OBSERVATIONS/simulated-daily-record-sample-01.md`, and `OBSERVATIONS/simulated-retrieval-trace-02.md`.

The simulated observation files are harness-test evidence only. Do not present them as real facility evidence.

This run tests whether the improvement process can avoid excessive caution. More observation is not automatically safer or better: delaying a cheap, reversible experiment also has an opportunity cost.

Your task is to:
1. update the causal assessment using all available evidence;
2. separate OBSERVED, HYPOTHESIS, and UNKNOWN claims;
3. explicitly evaluate whether another observation round has enough expected information value to justify delaying intervention;
4. compare at least four next-step options, including:
   - another observation/measurement step,
   - at least one non-software intervention,
   - any software/tool intervention only if justified,
   - doing nothing yet;
5. select at most one next experiment;
6. prefer the smallest intervention capable of testing a causal hypothesis when the evidence is sufficient;
7. do not make a permanent workflow, storage, documentation, or technology change;
8. define baseline, intervention, measures, human effort, success evidence, failure evidence, privacy/safety constraints, rollback, and stop conditions;
9. create a new proposal under `EXPERIMENTS/proposed/` without overwriting earlier experiments;
10. stop before field deployment or permanent harness modification.

Important: do not force an intervention merely because this task mentions excessive caution. If another observation is genuinely preferable, choose it and explain precisely what decision-relevant uncertainty it resolves and why that information is worth the delay and staff effort.

If you choose an intervention involving reference-material staging, indexing, checklists, folders, trays, shortcuts, or similar mechanisms, first account for privacy, access control, document-control requirements, duplication risk, stale-copy risk, and added maintenance work. Prefer temporary/reversible arrangements that leave authoritative records unchanged.

At completion, explain:
- what changed from Experiment 2;
- whether the evidence crossed a threshold from measurement to intervention and why;
- why the selected experiment dominates the strongest alternative on expected learning value, reversibility, risk, staff burden, and measurability;
- what result would cause immediate rollback;
- whether the run reveals a durable weakness in the harness itself. Do not propose a harness change without repeated or consequential evidence.