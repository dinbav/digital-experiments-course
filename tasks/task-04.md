# Task 04 — Your OEC and guardrails

**Feeds:** Decision 3 — What is the OEC?
**Type:** Code + written
**Notebook:** [`unit-04-metrics-exercise.ipynb`](../notebooks/unit-04-metrics-exercise.ipynb)
**Deliverable:** completed notebook (or no-code answers) + your project's OEC spec.

## Why this task

The metric on the slide encodes the business model. The same numbers say ship
under an advertising model and don't-ship under a subscription model — nobody
changed the data, only the weights. This task makes you own those weights.

## What to do

**Part A — Notebook.** Complete the exercise: build a weighted OEC from funnel
metrics, set guardrails, and produce a variant that **wins on the primary metric
while failing the composite**. Note the weight flip that reverses the decision.

**Part B — Your project.** Write an OEC spec:

1. **Primary / secondary / guardrail** metrics, named before any test.
2. The **OEC formula** — the two or three metrics and their weights — and one
   sentence on what business model those weights encode.
3. Your **measurement window**, and whether the true reward even fits inside it.
   If not, name the in-window proxy you'll learn from.
4. One **gaming** risk: how the metric gets abused once it's *the* metric.
5. Who **owns** the trade-off (the person accountable if the guardrail breaks).

Bonus (do it if you can): write a *second* OEC whose weights flip your ship
decision, to prove the weights — not the data — carry the verdict.

## Deliverable & format

Completed notebook (or no-code answers) plus the one-page OEC spec.

## How it feeds your final project

Part B is Decision 3 verbatim: weighted composite, guardrails, trade-off,
measurement window.

## Marked on

- Whether the weights are justified by the revenue model, not asserted.
- Whether guardrails were named *before* results (a guardrail added after is an excuse).
- Whether the window/proxy problem is faced honestly.
