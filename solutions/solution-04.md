# Answer key — Task 04 (Your OEC and guardrails)

**Instructor-facing.** Worked notebook: [`unit-04-metrics-demo.ipynb`](unit-04-metrics-demo.ipynb).

## Notebook (Part A)

Students should build a weighted composite and exhibit a variant that wins the
primary metric while failing the composite (the news-site reversal). The demo
shows the weight flip that reverses the ship decision.

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
