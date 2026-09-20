# Task 06 — Randomization unit and interference

**Feeds:** Decision 5 — What gets randomized?
**Type:** Code + written
**Notebook:** [`unit-06-randomization-exercise.ipynb`](../notebooks/unit-06-randomization-exercise.ipynb)
**Deliverable:** completed notebook (or no-code answers) + your randomization plan.

## Why this task

If treatment and control share a resource — a driver pool, a feed, inventory, a
model's context, even a visible rating — one unit's treatment leaks into
another's outcome, and your control group stops being a control group. This is
interference, a SUTVA violation, and you fix it in the design, not the analysis.

## What to do

**Part A — Notebook.** Complete the exercise: watch marketplace interference
inflate a user-level effect, then compare a block or switchback-style schedule
where control and treatment periods alternate. Note how much the naive estimate
was off and in which direction.

**Part B — Your project.** Write a randomization plan:

1. Your **randomization unit** — cookie, user, session, account, cluster, or
   time-region block — and why.
2. The **shared resource** (if any) that could cause interference, and who
   *else* your treatment reaches beyond the treated unit.
3. Whether **SUTVA** holds; if not, your fix (switchback, cluster randomization,
   geographic isolation) and its cost (power, complexity, carryover).
4. One design-time variance move you'll use: **blocking or matched pairs** on a
   known covariate (this is principled, unlike post-hoc slicing).

## Deliverable & format

Completed notebook (or no-code answers) plus the one-page plan.

## How it feeds your final project

Part B is Decision 5: randomization unit, interference, SUTVA, switchback if relevant.

## Marked on

- Whether the unit is tied to the interference structure, not a tool default.
- Whether you named who *else* the treatment reaches.
- Whether the SUTVA judgment is honest and, if it fails, actually fixed in design.
