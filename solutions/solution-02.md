# Answer key — Task 02 (Confounding vs. a real effect)

**Instructor-facing.** Worked notebook: [`unit-02-confounding-demo.ipynb`](unit-02-confounding-demo.ipynb).

## Notebook (Part A)

The demo notebook is the reference (seed 42). Key results students should reproduce or read:

- Naive effect about **+4.0 points** although the true effect is zero (paid traffic is 43% of the treatment arm vs 19% of control).
- Within-channel (stratified) effect about **-0.4 points** - the fake lift disappears.
- At 100,000 sessions the naive effect is still about +4 points with a 95% CI half-width of only 0.5 points: precision, not correctness.
- With coin-flip assignment the paid share balances (about 35% in each arm) and the naive comparison lands near zero.

Every `assert` in the exercise passes with the spoiler code, and with any correct solution across random seeds.

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
