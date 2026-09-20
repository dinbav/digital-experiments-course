# Task 11 — (Optional) When the treatment is an AI system

**Feeds:** Decisions 5–8, stressed — only if your project's treatment is an AI system
**Type:** Code + written · **optional**
**Notebook:** [`v2-ai-eval-exercise.ipynb`](../notebooks/v2-ai-eval-exercise.ipynb)
**Deliverable:** completed notebook (or no-code answers) + a decision table for an
AI treatment.

## Why this task

When the treatment is a language model, none of the earlier decisions are
replaced — they're stressed. Non-determinism is treatment-inconsistency at scale;
LLM-as-judge is inter-rater reliability with a biased rater; model drift is an
instrumentation threat with no standard fix. New object, old subject.

You do **not** need this task to run an AI project — but if you do, defend
decisions 5 and 6 with the same rigour as any other project.

## What to do

**Part A — Notebook.** Complete the exercise: score model outputs with two judges,
watch verbosity bias inflate one arm, and fill in the decision table for an LLM
support treatment.

**Part B — Your project (if AI-based).** For each decision, mark *held / broke /
open research* and say why:

1. **Treatment consistency (D6):** can you pin version, prompt, temperature,
   catalog? What still drifts?
2. **The rater / metric (D3, D8):** human, user, or model? If LLM-as-judge, name
   the bias direction (verbosity, position, self-preference) and how you calibrate.
3. **Randomization unit (D5):** user / session / conversation / turn — and the
   interference that turn-level assignment creates (earlier turns in later context).
4. **Guardrails (D3, D7):** cost and latency as *binding* constraints, not green
   decoration.
5. **Drift detection (D8):** how you'd notice a silent vendor update mid-experiment.

Flag any method (e.g. synthetic users) you're tempted by, and state the evidence
you'd want before spending traffic on it.

## Deliverable & format

Completed notebook (or no-code answers) plus the decision table.

## How it feeds your final project

If your treatment is an AI system, this strengthens Decisions 5, 6 and 8. If not,
skip it — it is not required.

## Marked on

- Whether non-determinism is treated as a consistency problem, not an excuse.
- Whether the rater's bias is named and calibrated, not assumed away.
- Whether unsupported methods are flagged as claims-awaiting-evidence.
