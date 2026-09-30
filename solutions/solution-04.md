# Answer key — Task 04 (Your OEC and guardrails)

**Instructor-facing.** Worked notebook: [`unit-04-metrics-demo.ipynb`](unit-04-metrics-demo.ipynb).

## Notebook (Part A)

The demo notebook is the reference (seed 42). Key results:

- Add-to-cart (the primary metric) **+27%**; checkout **-18.5%** (95% CI about -24% to -13%); browsing unchanged.
- Revenue-heavy OEC weights score the treatment **1.14** (treatment wins); conversion-heavy weights score it **0.94** (control wins) - the weight flip.
- The guardrail "checkout may not fall more than 5%" **fails**: the variant wins its primary metric and still cannot ship as is.
- Clicks per user **+38%** vs clicks per session **+8%**: the denominator changes the story.

Strong answers say the next step is diagnosing why full carts stop at checkout, not "ship" or "kill".

## Model answer (Part B)

Primary / secondary / guardrail named up front; an OEC formula whose weights are
justified by the **revenue model**; a measurement window with an honest proxy if
the true reward doesn't fit; a named gaming risk; a named owner. The bonus second
OEC (weights that flip the verdict) is the clearest demonstration of the lesson.

## Common mistakes

- Guardrails invented *after* imagining results (an excuse, not a guardrail).
- Weights asserted with no link to how the business makes money.
- Ignoring the measurement-window problem (a 60-day reward, a 2-week test).
- Letting a model "learn the weights" — that hides who owns the trade-off.

## Excellent looks like

The two-OEC version proves the data is constant and the weights carry the verdict;
the owner of the trade-off is a real role.
