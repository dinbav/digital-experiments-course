# Task 08 — How much certainty can you afford?

**Feeds:** Decision 7 — How much certainty can you afford?
**Type:** Code + written
**Notebook:** [`unit-08-power-mde-exercise.ipynb`](../notebooks/unit-08-power-mde-exercise.ipynb)
**Optional extensions:** [`v2-cuped-exercise.ipynb`](../notebooks/v2-cuped-exercise.ipynb),
[`v2-peeking-sequential-exercise.ipynb`](../notebooks/v2-peeking-sequential-exercise.ipynb)
**Deliverable:** completed notebook (or no-code answers) + your power plan.

## Why this task

The sample-size formula is the easy part; every calculator hands you
`n = f(alpha, beta, effect size)`. The hard part is upstream: the smallest lift
that would actually change your build decision. Alpha is a price you set against
the stakes, not a law of nature.

## What to do

**Part A — Notebook.** Complete the exercise: tie sample size to a stated
business threshold, and see how the calculator's default MDE differs from the one
the business would act on. Optionally run CUPED (variance reduction) and the
peeking/sequential notebook (why "stop when significant" manufactures results).

**Part B — Your project.** Write a power plan:

1. Your **MDE** — the smallest effect worth acting on — stated *before* sizing,
   with the business reason.
2. Your **alpha and power**, and why those levels given the stakes (looser for a
   reversible low-stakes change, stricter for billing/compliance).
3. **Sample size and duration**: the `n` you need, whether your traffic can reach
   it, and the weeks required (weekly seasonality floor, novelty decay).
4. Your **variance plan**: CUPED / covariates, balanced allocation — buying power
   with statistics instead of calendar time.
5. **Monitoring**: fixed horizon vs a sequential method — and your honest answer
   to "someone *will* peek."

## Deliverable & format

Completed notebook (or no-code answers) plus the one-page plan.

## How it feeds your final project

Part B is Decision 7: business threshold, MDE, sample size / duration, variance plan.

## Marked on

- Whether the MDE comes from the business, not the calculator.
- Whether alpha is justified by stakes, not defaulted to 0.05.
- Whether the monitoring plan survives real human behaviour (peeking).
