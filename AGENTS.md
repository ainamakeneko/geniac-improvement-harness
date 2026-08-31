# AGENTS.md

## Mission
Help a resource-constrained welfare organization discover and test small operational improvements without requiring a dedicated DX team, software engineer, or large budget.

## Non-negotiable rules
1. Separate `OBSERVED`, `HYPOTHESIS`, and `UNKNOWN` statements. Never present a hypothesis as a facility fact.
2. Do not include names, diagnoses, addresses, contact details, IDs, case notes, or other personally identifying/sensitive service-user data in this repository.
3. Do not optimize for building software. Consider process changes, existing tools, spreadsheets, templates, checklists, physical devices, scripts, documentation, or further observation.
4. Prefer the smallest reversible experiment that can produce useful evidence.
5. Do not deploy or recommend a field experiment that could materially affect safety, rights, privacy, benefits, care quality, medication, money handling, or legal compliance without explicit human review.
6. Human approval is required before a proposed experiment becomes `APPROVED_FOR_FIELD_TEST`.
7. Software verification proves implementation behavior only. Operational improvement must be measured in the real workflow.
8. Do not permanently modify this harness merely because one run was imperfect. Durable changes require evidence and a proposal under `HARNESS/proposals/`.
9. Prefer fewer questions. Ask for additional information only when uncertainty blocks a safe, informative experiment or would materially change the choice of experiment.
10. Record negative results. A failed experiment is useful evidence if it is cheap, reversible, and measured.

## Improvement objective
Optimize for practical net benefit, not technical sophistication.

Consider at minimum:
- human time saved;
- cognitive/coordination burden reduced;
- error reduction;
- adoption/friction;
- privacy and safety risk;
- maintenance burden;
- monetary cost;
- reversibility;
- effect on service users and staff.

## Human gates
A human must approve:
- any field experiment;
- any handling of real sensitive or personally identifying data;
- any persistent harness change.
