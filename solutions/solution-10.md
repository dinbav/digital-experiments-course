# Answer key — Task 10 (Analysis, decision, ethics)

**Instructor-facing.** Worked notebook: [`unit-10-analysis-demo.ipynb`](unit-10-analysis-demo.ipynb).

## Notebook (Part A)

The demo notebook is the reference (seed 42). Key results:

- Order value: lift about **$2.1**, 95% CI roughly **$0.9 to $3.3**, p < 0.001 - significant, and the whole interval is below the $5 threshold, so the ship rule says **do not ship**. The bootstrap CI agrees.
- CTR: the ratio of sums gives a gap of about **+0.011**, about twice the mean-of-per-user-ratios gap; the user-level bootstrap CI is roughly +0.009 to +0.014.
- Ramp-up (Simpson's paradox): pooled, the new flow looks like **+3.8 points**; within each day it **loses about 1 point**. The treatment arm is mostly high-converting Saturday traffic.

Students should see how pooling across periods with different allocation reverses the answer, and write a three-way ship rule (launch / do not ship / hold).

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
