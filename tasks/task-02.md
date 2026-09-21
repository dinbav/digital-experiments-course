# Task 02 — Confounding vs. a real effect

**Feeds:** Decision 2 — What counts as evidence?
**Type:** Code + written
**Notebook:** [`unit-02-confounding-exercise.ipynb`](../notebooks/unit-02-confounding-exercise.ipynb)
**Deliverable:** completed notebook (or its "Without code" answers) + a half-page
confound story for your own project.

## Why this task

More data does not remove bias — a bigger observational sample just tightens the
confidence interval around the *wrong* number. This task is where you feel that
in numbers, then apply it to your project.

## What to do

**Part A — Notebook.** Open the exercise notebook and complete the `TODO` cells.
You will simulate a treatment effect polluted by a confounder, watch a larger
sample shrink the interval around a *biased* estimate, then let random assignment
recover the true effect. If you take the no-code path, answer the same questions
from the printed tables and the precision plot.

**Part B — Your project.** In half a page:

1. Name one **confounder** that could fake the effect you plan to study — a
   variable that moves both your treatment exposure and your outcome.
2. Draw a tiny **DAG** (three or four boxes and arrows) showing it. A photo of a
   hand drawing is fine.
3. State which of Pearl's layers your available data sits on — association,
   intervention, or counterfactual — and what an experiment would move you to.
4. One sentence: what your design still could **not** rule out.

## Deliverable & format

The completed notebook (or no-code answers) plus the half-page story with the DAG.

## How it feeds your final project

Part B is the core of Decision 2: your confound, the evidence hierarchy, and what
remains unresolved.

## Marked on

- Whether the confounder is plausible and actually common to both variables.
- Whether the DAG matches the story (an arrow you can defend).
- Whether you distinguished "more data" from "less bias" in your own words.
