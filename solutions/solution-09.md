# Answer key — Task 09 (Can you trust this result?)

**Instructor-facing.** Worked notebook: [`unit-09-trust-checks-demo.ipynb`](unit-09-trust-checks-demo.ipynb).

## Notebook (Part A)

The demo runs an SRM chi-square check, shows an A/A test producing a "significant"
difference at the expected rate, and plots an effect that fades after week one
(novelty). Students should say what each check catches.

## Model answer (Part B)

Design-specific checks: an SRM/ratio check with a stated stop threshold; one
concrete threat in each validity type for *their* experiment; one internal threat
(e.g. differential attrition) with a detection method; a plan to separate a real
effect from novelty by plotting over time; and a stop-fix-rerun rule set before
seeing results.

## Common mistakes

- A generic validity list not tied to their design.
- Reaching for a **reliability** statistic to diagnose a broken split (wrong
  problem — reliability is a rater concept, SRM is assignment QA).
- Deciding what to do about SRM *after* seeing whether the result is favourable.
- Treating `p < 0.001` as evidence that assignment was fine.

## Excellent looks like

The stop rule is pre-committed, and the student can explain why precision on a
broken comparison isn't wisdom.
