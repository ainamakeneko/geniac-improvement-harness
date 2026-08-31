# Improvement Run Skill

Use this skill when executing `TASK.md`.

## Goal
Turn messy operational observations into a ranked set of evidence-backed improvement opportunities, then design the smallest safe experiment for the best candidate. Do not assume implementation is required.

## Procedure
1. Read `AGENTS.md`, `TASK.md`, and all relevant files under `CONTEXT/` and `OBSERVATIONS/`.
2. Build an evidence table. Every material statement must be marked as:
   - `OBSERVED`: directly supported by supplied material;
   - `HYPOTHESIS`: plausible interpretation needing validation;
   - `UNKNOWN`: important missing information.
3. Identify 3-7 improvement opportunities. For each, record:
   - evidence;
   - hypothesized mechanism of burden;
   - expected benefit;
   - uncertainty;
   - safety/privacy risk;
   - estimated implementation/maintenance burden;
   - smallest reversible test.
4. Rank opportunities using judgment, not false precision. Prefer candidates with strong evidence, low risk, low trial cost, high reversibility, and measurable outcomes.
5. Select at most one candidate for the first experiment. If evidence is too weak, select an observation/measurement experiment instead of building a solution.
6. Create an experiment proposal under `EXPERIMENTS/proposed/` using `EXPERIMENTS/experiment-template.md`.
7. Do not mark the experiment approved. Stop at `Status: PROPOSED` unless a human has explicitly approved it.
8. If a software/document artifact can safely be prototyped before field deployment, it may be created under `ARTIFACTS/`, but label it as unvalidated and do not imply field approval.
9. Complete the post-run review:
   - What assumptions were made?
   - What evidence was missing?
   - Did the agent overproduce a solution when observation would have been better?
   - Was any useful opportunity missed because the harness lacked a rule, schema, or tool?
10. Only if there is evidence for a durable harness improvement, create a proposal under `HARNESS/proposals/` with `Status: PROPOSED`. Do not apply it.

## Success criteria
A successful run is not necessarily one that builds something. It is one that leaves a human with a small number of understandable, evidence-backed options and a safe next experiment whose result can change the next decision.
