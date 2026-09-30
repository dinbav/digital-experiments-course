# Answer key — Task 09 (Can you trust this result?)

**Instructor-facing.** Worked notebook: [`unit-09-trust-checks-demo.ipynb`](unit-09-trust-checks-demo.ipynb).

## Notebook (Part A)

The demo notebook is the reference (seed 42). Key results:

- The logged data shows a **+2.4-point** lift, p < 0.001, for a page with **no** true effect.
- The SRM check fails decisively (10,012 vs 7,647 logged users; p around 1e-70). The browser breakdown shows the missing old-browser (low-converting) treated users.
- A/A simulations come out significant about **5-6%** of the time.
- Weekly lift falls from about **+3.4** to **+0.4** points (novelty); the lasting effect is +0.5.

Students should say what each check catches, and that a failed SRM means stop - not "analyse the clean segment". The MSN carousel case in the framing cell shows the opposite direction (a broken split hiding a real win).

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
