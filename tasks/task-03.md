# Task 03 — Potential outcomes and your estimand

**Feeds:** Decision 2 — What counts as evidence?
**Type:** Written / reasoning · no code (paper is enough)
**Deliverable:** a one-page estimand statement for your project.

## Why this task

Every unit has two potential outcomes and you only ever see one — so the
individual effect is unobservable in principle, and the average is the honest
default. Writing your estimand down forces the questions a dashboard hides.

## What to do

For your project's outcome, on paper:

1. Define `Y_i(1)` and `Y_i(0)` in words — what happens to unit *i* **under
   treatment** and **under control**. If those two sentences differ only in
   wording, your control isn't defined yet.
2. Write the observed-outcome identity for your setting:
   `Y_i = D_i·Y_i(1) + (1 − D_i)·Y_i(0)`, and say which half you never observe.
3. State your **estimand**: do you need the ATE, a pre-specified subgroup effect,
   or something individual (much harder — say why if so)?
4. Name one reason a crossover / before-after "fix" would **not** rescue an
   individual effect here (carryover, learning, time as treatment).
5. Preview one heterogeneity worry: a subgroup for whom the effect might point the
   other way, and whether you'd pre-specify it.

## Deliverable & format

One page. The two potential-outcome sentences, the identity with the unobserved
half marked, your estimand, and the two short reasoning points.

## How it feeds your final project

This becomes the notation-and-estimand half of Decision 2, and it locks the
outcome you'll defend before any data arrives.

## Marked on

- Whether `Y_i(1)` and `Y_i(0)` describe genuinely different worlds.
- Whether the estimand matches what your design can actually identify.
- Whether the heterogeneity note is pre-specified, not fishing.
