# Answer key — Task 08 (How much certainty can you afford?)

**Instructor-facing.** Worked notebooks: [`unit-08-power-mde-demo.ipynb`](unit-08-power-mde-demo.ipynb),
[`v2-cuped-demo.ipynb`](v2-cuped-demo.ipynb), [`v2-peeking-sequential-demo.ipynb`](v2-peeking-sequential-demo.ipynb).

## Notebook (Part A)

Sample size is tied to a stated business MDE, which differs from the calculator's
default. CUPED demo shows variance reduction from pre-experiment data; the
peeking/sequential demo shows repeated looks inflating the false-positive rate far
above the labelled alpha, and a sequential method fixing it.

## Model answer (Part B)

MDE stated **before** sizing with a business reason; alpha/power justified by
stakes (looser for reversible low-stakes, stricter for billing/compliance);
sample size and duration with a traffic-feasibility check and a weekly-seasonality
floor; a variance plan (CUPED/covariates); a monitoring plan that survives "someone
will peek."

## Common mistakes

- MDE read off the calculator instead of the business ("we can detect 0.5%, so that's our MDE").
- Alpha defaulted to 0.05 with no stakes reasoning.
- Stopping at two weeks for cost, ignoring novelty distortion.
- "We'll just tell people not to peek" instead of a sequential method.

## Excellent looks like

The whole plan flows from the smallest lift that would change the build decision;
buying power with statistics (CUPED) is preferred to buying it with calendar time.
