# Experiment 4 — Reference-readiness validation

Status: PROPOSED

> This proposal evaluates simulated harness-test evidence only. It does not report a real facility result, authorize field use, or establish that the simulated pattern applies to any facility.

## Opportunity

OBSERVED IN THE SIMULATION: Temporary reference readiness reduced mean in-session retrieval from 17.7 minutes across three baseline sessions to 5.5 minutes across two intervention sessions. Mean end-to-end time, however, fell only from 54.3 to 49.5 minutes after readiness, refiling, checking, and other work were included.

HYPOTHESIS: The same temporary, controlled readiness method may yield a small repeatable net benefit, but the present two-session intervention sample is too weak to distinguish a stable benefit from day-to-day variation or shifted checking work.

The opportunity is therefore to resolve that narrow adoption-relevant uncertainty with a few more reversible comparisons, not to implement a permanent process.

## Evidence

All values in this table are simulated harness-test observations, not facility facts.

| Status | Statement | Decision implication |
| --- | --- | --- |
| OBSERVED | Baseline totals were 53, 54, and 56 minutes (mean 54.3); intervention totals were 49 and 50 minutes (mean 49.5). | The observed net difference is 4.8 minutes per session, about 9% of the baseline mean. It is modest and based on only two intervention sessions. |
| OBSERVED | Baseline retrieval was 16, 19, and 18 minutes (mean 17.7); intervention retrieval was 6 and 5 minutes (mean 5.5). | The gross in-session retrieval difference is 12.2 minutes, but it is not the net benefit. |
| OBSERVED | Intervention readiness took 4 and 5 minutes and refiling took 3 minutes in each session (7.5 minutes combined on average). | Much of the apparent retrieval reduction reappeared before and after the main work. |
| OBSERVED | Baseline checking was 12, 10, and 11 minutes (mean 11); intervention checking was 14 and 13 minutes (mean 13.5). | Checking was 2.5 minutes higher on average and could further offset the gross retrieval difference. |
| OBSERVED | Direct entry and PC/system waiting were similar across the two conditions. Other/transition time was 5 minutes in each retrieval-trace baseline and 2 minutes in each intervention session. | Components other than readiness may differ between the small samples; attributing the entire net difference to readiness would overclaim. |
| OBSERVED | No privacy, access-control, safety, or document-loss event occurred in the two simulated intervention sessions. | No harm appeared in the simulation, but two event-free sessions do not establish operational safety. |
| HYPOTHESIS | Reference readiness caused some or all of the 4.8-minute mean net difference. | This needs a small contemporaneous validation before any adoption decision. |
| HYPOTHESIS | Higher checking may be random variation, compensation for changed handling, or an early sign of shifted burden. | The next test must retain checking as an explicit measure and must not remove required checks. |
| UNKNOWN | Whether session mix, reference needs, or measurement differences explain the lower intervention totals or lower other/transition time. | Use comparable, naturally occurring sessions and record comparability without sensitive detail. |
| UNKNOWN | Whether the effect persists across days, staff, sites, and reporting periods; whether preparation creates hidden coordination or maintenance; and whether local controls permit staging. | The proposal cannot support broader rollout or permanent change. |

### Result classification

**PROMISING, within the simulation only.** Both intervention sessions had lower end-to-end totals than all three simulated baseline sessions, no adverse event was simulated, and the intervention was cheap and reversible. The classification is not “successful” or evidence for adoption: the net observed difference was only 4–7 minutes relative to individual baseline sessions, most gross retrieval savings shifted into readiness/refiling, checking was higher, and only two intervention sessions exist. It is not currently “failed” or “harmful” because total time did improve and no harm was observed. It is more useful than “inconclusive” because the consistent direction and low-cost reversibility justify one bounded validation that can settle a concrete decision.

## Hypothesis

HYPOTHESIS: Across a short set of comparable daily-record sessions, temporary readiness will usually reduce end-to-end time by at least 5 minutes or 10% relative to usual handling, after counting readiness, retrieval, checking, refiling, maintenance, and measurement effort, without increasing errors, unresolved exceptions, staff burden, or control concerns.

The 5-minute/10% threshold is a prospective decision threshold, not an observed facility requirement. A human reviewer may reject or adjust it before approval if that saving is not operationally meaningful relative to setup and oversight.

## Unknowns

- UNKNOWN: Whether simulated evidence resembles real work at all.
- UNKNOWN: What session characteristics make reference readiness useful or unnecessary.
- UNKNOWN: Whether checking increased because of the intervention.
- UNKNOWN: Whether readiness/refiling effort declines with familiarity or instead becomes recurring maintenance.
- UNKNOWN: Whether preparation falls to the same staff member, is shifted to someone else, or interrupts service-user support.
- UNKNOWN: Whether any error, stale-source, missing-material, access-control, privacy, documentation-quality, or staff-friction effect would occur.
- UNKNOWN: What minimum saving staff and the human approver consider worthwhile.

## Compared next-step options

This ranking uses judgment rather than false numerical precision.

| Rank | Option | Expected learning or benefit | Burden, uncertainty, and decision |
| --- | --- | --- | --- |
| 1 | **Repeat the same temporary intervention in a short alternating comparison.** | Tests whether the modest net effect persists and whether checking rises when readiness is used. Directly informs stop-versus-consider-broader-validation. | Low, reversible effort; retains the known safeguards. **Selected as the one next experiment.** |
| 2 | **Modify readiness to reduce preparation/refiling.** | Could improve net benefit if those steps are reducible. | The evidence does not identify which safe change would reduce them. Changing storage, copies, indexing, or controls could add privacy and maintenance risks and would confound validation. Reject for now; consider only if validation shows a repeatable benefit plus a specific burden mechanism. |
| 3 | **Immediate rollback and stop.** | Eliminates all readiness effort and risk. | Strongest alternative because the measured benefit is modest. It has lower immediate burden but no ability to determine whether the consistent 4–7 minute net difference is repeatable. Choose it immediately if staff do not value the question, the local review finds control risk, or any stop condition occurs. |
| 4 | **Try a different intervention, such as a status prompt or software/configuration change.** | Might address checking or system waiting. | Increased checking has no established cause, and no software bottleneck, configuration authority, safe status convention, or maintenance case is evidenced. A new intervention has lower learning value and higher design risk now. Reject. |
| 5 | **Permanently adopt reference readiness.** | Might retain a modest saving without further study. | Reject. Two simulated sessions do not establish real-world benefit, safety, ownership, representativeness, or sustainable maintenance. Permanent process/storage change also requires explicit human approval and a much higher evidence bar. |

## Smallest reversible intervention

This is a proposal only. After explicit human field approval and confirmation that temporary readiness is permitted, use four naturally occurring sessions that one willing participant and reviewer consider reasonably comparable. Alternate conditions in advance to reduce simple order effects:

1. usual handling;
2. the exact temporary readiness method from Experiment 3;
3. usual handling; and
4. the exact temporary readiness method from Experiment 3.

If operational scheduling makes that sequence unrepresentative, the human reviewer may reverse the starting condition, but must set the sequence before seeing results. Do not select sessions after observing their duration. The two usual-handling sessions are contemporaneous comparators, not a permanent return to an assumed baseline.

For readiness sessions, prepare only normally authorized reference materials immediately before work, create no copies or index, change no storage location or access control, and return everything immediately afterward. Do not modify the method in this experiment. For all four sessions, preserve every required entry and check.

Capture only coarse category durations and event counts. Never record names, identifiers, filenames, dates tied to people, diagnoses, record contents, case details, or other sensitive information. Real field-level results must not be placed in this repository.

## Human effort required

- HYPOTHESIS: Readiness and refiling will add about 7–9 minutes to each of two intervention sessions, based only on the simulation.
- HYPOTHESIS: Coarse timing will add no more than 2 minutes per session, or 8 minutes total.
- HYPOTHESIS: A participant/reviewer comparison will take about 10 minutes.
- UNKNOWN: Actual setup, displaced work, measurement, review, and maintenance burden; measure these rather than assuming them.

## Risks and safeguards

- **Privacy and access control:** A human must confirm local rules before any field test. Keep materials within existing authorized boundaries and supervision; make no copies, lists, labels, shortcuts, screenshots, or changed permissions. Stop on any concern.
- **Rights, care quality, and compliance:** Never omit, shorten, delay, or reorder required documentation or checks. Service-user support and urgent work take priority over measurement.
- **Document integrity:** Confirm materials are current through the normal required method. Return each item to its original controlled location immediately. Stop if anything is stale, missing, misplaced, duplicated, or harder for another authorized worker to find.
- **Shifted burden:** Record who performs readiness/refiling only as “same participant” or “other staff,” plus aggregate minutes. Do not transfer preparation silently to another person or exclude their time from the total.
- **Staff fairness and adoption:** Participation is voluntary. Do not use timings to assess individual performance. Record a simple acceptable/neutral/unacceptable burden rating after each session.
- **Operational continuity:** Use no new software, device, subscription, storage scheme, or permanent routine. The experiment ends after four sessions.
- **Maintenance:** Count all reset, repeated explanation, correction, and extra coordination minutes. A benefit that depends on unmeasured upkeep does not pass.

## Baseline

OBSERVED IN THE SIMULATION: The historical harness-test baseline is 53, 54, and 56 minutes end to end. Because it may differ in session mix or measurement context, the primary comparison in this proposal is the two contemporaneous usual-handling sessions against the two readiness sessions.

UNKNOWN: There is no approved real-facility baseline. No simulated duration or saving may be represented as a local target or fact.

## Measures

For every session, record only aggregate/category-level measures:

- total end-to-end minutes, starting before any readiness and ending after all refiling/reset;
- readiness, retrieval, direct-entry, checking/confirmation, PC/system-waiting, refiling/reset, other/transition, correction/rework, and measurement minutes;
- unresolved-exception and correction/rework counts, without contents;
- whether readiness/refiling was performed by the participant or another staff member, with all contributors' minutes included;
- any extra coordination or maintenance minutes;
- participant burden rating: acceptable, neutral, or unacceptable;
- whether the session was considered comparable before results were reviewed; and
- whether any privacy, access-control, document-control, safety, documentation-quality, care-quality, or operational concern occurred (yes/no only).

Report condition totals and ranges, not only retrieval averages. Do not subtract required checking as if it were waste.

## Success evidence

Evidence would justify one later proposal for broader validation—not permanent adoption—only if:

- both readiness sessions and the combined comparison show at least a 5-minute or 10% net end-to-end improvement against the contemporaneous usual-handling sessions, after including every contributor's readiness, checking, refiling, correction, measurement, coordination, and maintenance time;
- checking, corrections, unresolved exceptions, and staff burden do not show a consistent adverse shift;
- no privacy, access-control, safety, document-control, care-quality, compliance, or operational concern occurs; and
- the participant and human reviewer judge the sessions reasonably comparable and the net saving operationally worthwhile.

These are proportionate directional criteria for a cheap trial, not a claim of statistical proof.

## Evidence threshold before broader rollout or permanent change

Broader rollout must not follow directly from this four-session test. It would require a separate human-approved proposal and, at minimum, de-identified aggregate evidence from representative days and every materially different participating role/site showing:

1. a recurring net saving meeting the locally accepted threshold after **all** readiness, refiling, checking, correction, coordination, training, and maintenance time is counted across staff;
2. no increase in errors, unresolved exceptions, missing/stale materials, required-check failures, privacy/access-control concerns, service-user impact, or unacceptable staff burden;
3. clear local confirmation that the method preserves documentation, access, retention, and operational requirements;
4. named human ownership for preparation and reset, using roles rather than personal names in harness records, with sustainable effort and no hidden transfer of work; and
5. evidence covering enough normal variation to show the result is not confined to two unusually favorable sessions.

Permanent adoption has the higher bar of a human-reviewed total-cost/maintenance assessment, successful reversible use over an agreed representative period, an explicit rollback method, and explicit approval for the persistent workflow change. A large retrieval reduction alone can never satisfy this threshold.

## Failure evidence

Stop and return to usual handling if any privacy, access-control, document-control, safety, rights, care-quality, compliance, or operational concern occurs; required checking is impeded; a material is missing, stale, misplaced, or unavailable to another authorized worker; the participant wants to stop; or measurement materially disrupts work.

Do not continue this intervention direction after the four sessions if the net threshold is missed, checking/corrections or burden consistently increase, total contributor effort cannot be captured, sessions cannot be compared credibly, or staff judge the modest saving not worthwhile. Record a null or negative result rather than modifying the method after seeing results.

## Rollback

At the end of each readiness session, return every material to its original controlled location and discard the category-only temporary tally by the human-approved secure method. After the fourth session, cease readiness and timing. No software, copy, index, label, permission, storage location, or permanent routine remains.

## Decision rationale

HYPOTHESIS: The alternating repeat has better expected learning value than immediate rollback because about four additional low-burden sessions can test the two uncertainties that decide the next action: whether the modest **net** benefit repeats and whether checking burden moves with the intervention. Immediate rollback is the strongest alternative and should win if local staff do not value a possible 5-minute saving or a pre-test review identifies risk. Modifying readiness now might seek a larger effect, but without evidence about the source of preparation, refiling, or checking burden it would add risk and make the existing signal harder to interpret.

No software or permanent artifact is justified. This proposal stops before real deployment, rollout, or persistent workflow/storage/technology change.

## Post-run review

- **Assumptions made:** HYPOTHESIS: four alternating sessions can provide sufficient directional evidence for this cheap decision; sessions can be judged reasonably comparable without sensitive data; coarse timing is tolerable; and 5 minutes/10% is a potentially meaningful threshold. A human must validate these assumptions before approval.
- **Evidence missing:** UNKNOWN: all real-work evidence, representativeness, causal effect on checking, staff/site variation, acceptable local benefit threshold, control requirements, hidden labor, error/rework effects, and long-run maintenance.
- **Overproduction check:** No software, readiness aid, storage redesign, or permanent workflow was produced. Repeating the unchanged test is preferable to optimizing an unvalidated method.
- **Harness weakness review:** No repeated or consequential harness weakness is evidenced. The existing template and rules support net-effect accounting, uncertainty labels, human gates, rollback, and negative-result recording. Therefore no `HARNESS/proposals/` change is created.

## Field approval

Human approver: NOT YET APPROVED  
Date: —
