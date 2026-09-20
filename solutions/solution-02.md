# Answer key — Task 02 (Confounding vs. a real effect)

**Instructor-facing.** Worked notebook: [`unit-02-confounding-demo.ipynb`](unit-02-confounding-demo.ipynb).

## Notebook (Part A)

The demo notebook is the reference. Key results students should reproduce/read:
the naive estimate stays biased as `n` grows (the CI narrows around the wrong
number), and random assignment recovers the true effect. The spoiler cell in the
exercise notebook holds the solution code; every `assert` should pass.

## Model answer (Part B)

A confounder that plausibly drives **both** exposure and outcome, a DAG whose
arrows match the story, and a correct read of the layer (their logs are
association-layer; an experiment moves them to intervention). Example: "Users who
see the new onboarding are disproportionately new-in-app; tenure drives both
seeing it and retention." DAG: tenure → exposure, tenure → retention.

## Common mistakes

- A "confounder" that sits **on the causal path** (a mediator), not a common cause.
- Claiming randomization removes confounding but then proposing to "control for it in a regression" as if equivalent.
- Saying more data would fix the bias — the whole point is that it won't.

## Excellent looks like

The DAG exposes an arrow a teammate could dispute, and the student names one thing
their own design still can't rule out.
