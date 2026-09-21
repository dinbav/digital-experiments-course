# Notebooks

Colab-first exercise notebooks for the tasks that need code. Each is the
**exercise** version — it has `TODO` cells, hints, and a spoiler. The
fully-worked **demo** versions live in [`../solutions/`](../solutions/).

Every notebook: runs top to bottom in a clean runtime, generates its own data
(no uploads, no keys, `RANDOM_SEED = 42`), and includes a **"Without code"**
section near the top so you can follow the whole argument from printed tables and
plots without executing Python.

## Open in Colab

- **Upload:** download the `.ipynb`, go to [colab.research.google.com](https://colab.research.google.com), File → Upload notebook.
- **From GitHub (one click):** `https://colab.research.google.com/github/dinbav/digital-experiments-course/blob/main/notebooks/<notebook>.ipynb` — e.g. the
  [confounding exercise](https://colab.research.google.com/github/dinbav/digital-experiments-course/blob/main/notebooks/unit-02-confounding-exercise.ipynb).
- **Worked demo:** the same name with `-demo`, under `solutions/` — e.g. the
  [confounding demo](https://colab.research.google.com/github/dinbav/digital-experiments-course/blob/main/solutions/unit-02-confounding-demo.ipynb).
- **Acceptance test:** Runtime → Restart and run all.

The first code cell has a **commented-out** `# %pip install -q numpy pandas scipy statsmodels matplotlib`.
Colab ships all of these, so leave it commented unless an import fails.

## Catalog

| Notebook | Task | What you build |
|----------|------|----------------|
| `unit-02-confounding-exercise.ipynb` | 02 | Confounding survives a bigger sample; randomization recovers the true effect |
| `unit-04-metrics-exercise.ipynb` | 04 | A weighted OEC; a variant that wins the primary metric but fails the composite |
| `unit-06-randomization-exercise.ipynb` | 06 | Marketplace interference inflates a user-level effect; a switchback fixes it |
| `unit-08-power-mde-exercise.ipynb` | 08 | Sample size tied to a business MDE, not a calculator default |
| `unit-09-trust-checks-exercise.ipynb` | 09 | SRM check, A/A false positive, an effect that fades after week one |
| `unit-10-analysis-exercise.ipynb` | 10 | CI as a ship range; a Simpson's-paradox aggregation trap |
| `v2-did-exercise.ipynb` | 05 (opt) | Difference-in-differences with parallel trends intact and broken |
| `v2-cuped-exercise.ipynb` | 08 (opt) | CUPED variance reduction using pre-experiment data |
| `v2-peeking-sequential-exercise.ipynb` | 08 (opt) | Why "stop when significant" inflates false positives; sequential fix |
| `v2-ai-eval-exercise.ipynb` | 11 (opt) | Two judges, verbosity bias inflating one arm, a decision table |
| `v2-bandits-exercise.ipynb` | 11 (opt) | Bandits earn while they learn — and what causal clarity they trade away |

Colab updates runtimes without notice; the core notebooks depend only on the
baseline stack above. Re-run once per semester to confirm.
