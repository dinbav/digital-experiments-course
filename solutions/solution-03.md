# Answer key — Task 03 (Potential outcomes and your estimand)

**Instructor-facing.** No code.

## Model answer (shape)

`Y_i(1)` and `Y_i(0)` describe two genuinely different worlds for the same unit;
the identity `Y_i = D_i·Y_i(1) + (1−D_i)·Y_i(0)` is written with the unobserved
half marked; the estimand is the **ATE** unless a subgroup effect is defended.
The crossover critique names carryover / learning / time-as-treatment. The
heterogeneity note is pre-specified.

## Common mistakes

- `Y_i(1)` and `Y_i(0)` that differ only in wording — a sign the control isn't
  defined ("status quo" hand-wave).
- Claiming to estimate an **individual** effect from a standard A/B (it's
  unobservable in principle).
- A subgroup "hope" that's really a licence to slice later — should be pre-specified or dropped.

## Excellent looks like

The estimand matches what the design can identify, and the student can say in one
sentence why "does it work for me?" is harder than "does it work on average?"
