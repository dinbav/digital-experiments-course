# Task 10 — Analysis, decision, ethics

**Feeds:** Decision 8 — Do you trust it, and what do you do about it?
**Type:** Code + written
**Notebook:** [`unit-10-analysis-exercise.ipynb`](../notebooks/unit-10-analysis-exercise.ipynb)
**Deliverable:** completed notebook (or no-code answers) + your analysis-and-ship plan.

## Why this task

An experiment can be statistically significant and economically absurd — or work
on the metric and still be the wrong thing to ship. This task turns your result
into a decision, and puts an ethics line in writing *before* the number arrives.

## What to do

**Part A — Notebook.** Complete the exercise: match tests to metric types, read a
confidence interval as a ship range, and walk an aggregation (Simpson's) trap on
simulated data.

**Part B — Your project.** Write an analysis-and-ship plan:

1. **Statistical vs economic significance** — the effect size that is *material*
   for your decision, not just distinguishable from noise.
2. **Pre-specified analysis** — the test(s) you'll run, any pre-specified
   subgroups (not fishing), and a multiple-comparisons plan if you run several.
3. **ITT vs ToT** — which you report by default (ITT, preserving randomisation)
   and when, if ever, you'd look at compliers.
4. **Ship rule** — the confidence-interval range that means launch, hold, or roll
   back, written now.
5. **Ethics** — complete the sentence *"We would not run this experiment if ___,"*
   with a real limitation or ethical line (participant harm, dark-pattern risk,
   a "successful" manipulation).

## Deliverable & format

Completed notebook (or no-code answers) plus the one-page plan.

## How it feeds your final project

Part B completes Decision 8: analysis plan, ship rule, ethics, consolidated
limitations — and sets up the final report assembly.

## Marked on

- Whether the ship rule was written before results (a decision, not a rationalisation).
- Whether subgroups are pre-specified and p-hacking is guarded against.
- Whether the ethics line is a real constraint you'd honour, not a disclaimer.
