# Answer key — Task 08 (How much certainty can you afford?)

**Instructor-facing.** Worked notebooks: [`unit-08-power-mde-demo.ipynb`](unit-08-power-mde-demo.ipynb),
[`v2-cuped-demo.ipynb`](v2-cuped-demo.ipynb), [`v2-peeking-sequential-demo.ipynb`](v2-peeking-sequential-demo.ipynb).

## Notebook (Part A)

The demo notebooks are the reference (seed 42).

- **Power/MDE:** the 1-point calculator default needs 17,166 users per arm, but has only **29% power** for the 0.5-point lift finance would ship. The business MDE needs **67,493 per arm** (3.9x) - about **7 weeks** at 20,000 users a week. A 1,000-run simulation confirms ~80% power.
- **CUPED (optional):** SE falls from 0.20 to 0.15, a **44% variance reduction**; CUPED reaches 80% power with about half the users. With weak history the reduction is under 1%.
- **Peeking (optional):** daily peeking at a fixed p < 0.05 stops **22%** of A/A tests; one final look 5%; the mSPRT under 1%. With a real effect the mSPRT has less power than one final look (65% vs 90%) but stops around day 9 instead of day 14.

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
