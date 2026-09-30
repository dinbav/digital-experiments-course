# Notebooks

Colab exercise notebooks for the tasks that need code. Each one has `TODO`
cells you complete, `assert` checks that tell you when you are right, collapsed
hints, and a collapsed full solution at the bottom. The fully-worked **demo**
versions (every output saved) live in [`../solutions/`](../solutions/).

Every notebook runs top to bottom in a clean Colab runtime, generates its own
data (no uploads, no accounts, no API keys, `RANDOM_SEED = 42`), and has a
**Without code** section near the top: you can open the worked demo, read its
saved tables and charts, and answer the questions in plain words.

## Open in Colab

Click the **Open in Colab** badge at the top of any notebook, or use:

`https://colab.research.google.com/github/dinbav/digital-experiments-course/blob/main/notebooks/<notebook>.ipynb`

Then **Runtime → Run all**. If a `TODO` is not done yet, the run stops at that
cell with a message saying what to fix - that is expected.

## Catalog

| Notebook | Task | What you do |
|----------|------|-------------|
| `unit-02-confounding-exercise.ipynb` | 02 | A confounder fakes a lift; stratifying removes it; a bigger sample does not; randomisation does |
| `unit-04-metrics-exercise.ipynb` | 04 | Funnel lifts, a weighted OEC whose weights flip the winner, a guardrail that vetoes the primary-metric winner, two denominators for the same clicks |
| `unit-06-randomization-exercise.ipynb` | 06 | Marketplace interference inflates a user-level A/B result about 3x; a switchback recovers the real effect; an honest, day-level standard error |
| `unit-08-power-mde-exercise.ipynb` | 08 | Sample size from a business MDE, what the calculator default misses, users into weeks, power checked by simulation |
| `unit-09-trust-checks-exercise.ipynb` | 09 | A broken pipeline fakes a win; an SRM check catches it; the A/A false-positive rate; a novelty effect that fades |
| `unit-10-analysis-exercise.ipynb` | 10 | A CI read as a ship range (launch / do not ship / hold), a ratio metric done right, a Simpson's-paradox trap in a ramp-up |
| `v2-did-exercise.ipynb` | 05 (opt) | Difference-in-differences with parallel trends intact and broken, and a placebo test that tells them apart |
| `v2-cuped-exercise.ipynb` | 08 (opt) | CUPED variance reduction from pre-experiment data, and when it stops helping |
| `v2-peeking-sequential-exercise.ipynb` | 08 (opt) | Why "stop when significant" inflates false positives; an always-valid sequential test (mSPRT) |
| `v2-ai-eval-exercise.ipynb` | 11 (opt) | Two AI judges, verbosity bias, a cost guardrail, model drift, and the decision table |
| `v2-bandits-exercise.ipynb` | 10 (opt) | An epsilon-greedy bandit earns more during the test - and knows less about the arm it abandons |
| `v2-ai-eval-real-model.ipynb` | 11 (opt) | **Optional lab:** the same AI checks on real open-source models (Qwen2.5, Apache 2.0) from Hugging Face. Use a free T4 GPU runtime; about 5 minutes; no API key |

## If something breaks

- **An import fails:** remove the `#` in front of `%pip install` in the setup cell and run it again.
- **An `assert` fails:** read its message - it names what to check. The hints are one click away.
- **Different numbers from a classmate:** fine, as long as the asserts pass. Changing `RANDOM_SEED` changes the numbers, never the lesson.

All notebooks except the optional real-model lab use only `numpy`, `pandas`,
`scipy`, `statsmodels` and `matplotlib`, which Colab ships.
