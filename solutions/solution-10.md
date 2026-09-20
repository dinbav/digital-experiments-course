# Answer key — Task 10 (Analysis, decision, ethics)

**Instructor-facing.** Worked notebook: [`unit-10-analysis-demo.ipynb`](unit-10-analysis-demo.ipynb).

## Notebook (Part A)

The demo matches tests to metric types, reads a CI as a ship range, and walks a
Simpson's-paradox reversal on simulated admissions-style data. Students should see
how an aggregate can reverse within pre-specified subgroups.

## Model answer (Part B)

A material effect size distinct from statistical significance; a pre-specified
analysis with any subgroups named in advance and a multiple-comparisons plan;
ITT reported by default (ToT only for an explicit compliers question); a ship rule
written as CI ranges **before** results; and a real ethics line completing "we
would not run this experiment if ___."

## Common mistakes

- A ship rule written after seeing the estimate (rationalisation, not a rule).
- Subgroups discovered by slicing until something crosses 0.05 (p-hacking).
- Defaulting to ToT because it "looks cleaner" — it breaks randomisation.
- An ethics "line" that's really a disclaimer no one would act on.

## Excellent looks like

The ethics sentence names a limit the group would genuinely honour even at the
cost of a "winning" result; the ship rule could be applied by someone who hasn't
seen the data.
