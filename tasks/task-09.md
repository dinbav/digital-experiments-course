# Task 09 — Can you trust this result?

**Feeds:** Decision 8 — Do you trust it, and what do you do about it?
**Type:** Code + written
**Notebook:** [`unit-09-trust-checks-exercise.ipynb`](../notebooks/unit-09-trust-checks-exercise.ipynb)
**Deliverable:** completed notebook (or no-code answers) + your trust-check plan.

## Why this task

A significant lift on millions of users can be a broken pipeline in a success
costume — a 200-millisecond load-time gap, differential logging, or an assignment
that arrived 70/30. Significance does not repair broken assignment. Trust checks
are the gate you clear *before* you spend any narrative on effect size.

## What to do

**Part A — Notebook.** Complete the exercise: run an assignment-ratio (SRM) check,
simulate an A/A false positive, and plot an effect that fades after week one.
Note what each check would have caught.

**Part B — Your project.** Write a trust-check plan naming, for your design:

1. **Verifiable assignment** — the SRM / ratio check and covariate-balance check
   you'll run, and what result would make you stop.
2. **Validity** — one concrete threat in each of the four types (construct,
   internal, external, statistical-conclusion) for *your* experiment.
3. One **internal-validity threat** in detail (e.g. differential attrition) and
   how you'd detect it.
4. **Stability over time** — how you'll separate a real effect from novelty /
   primacy (plot over time, not one window).
5. Your rule **if a check fails**: stop, fix the pipeline, re-run — not "analyse
   the clean days."

## Deliverable & format

Completed notebook (or no-code answers) plus the one-page plan.

## How it feeds your final project

Part B is half of Decision 8: validity threats and the checks that gate your analysis.

## Marked on

- Whether the checks are specific to your design, not a generic list.
- Whether you named the stop rule *before* seeing results.
- Whether you kept reliability (a rater concept) separate from SRM (assignment QA).
