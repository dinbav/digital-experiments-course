# Answer key — Task 11 (When the treatment is an AI system) · optional

**Instructor-facing.** Worked notebook: [`v2-ai-eval-demo.ipynb`](v2-ai-eval-demo.ipynb).

## Notebook (Part A)

The demo scores model outputs with two judges and shows verbosity bias inflating
one arm; students complete the decision table for an LLM support treatment.

## Model answer (Part B)

Each decision marked *held / broke / open research* with a reason: non-determinism
framed as a treatment-consistency (SUTVA) problem; the rater's bias direction
named and a calibration plan given if using LLM-as-judge; turn-level assignment
recognised as violating no-interference; cost/latency treated as binding
guardrails; a drift-detection plan for silent vendor updates. Unsupported methods
(e.g. synthetic users) flagged as claims awaiting evidence.

## Common mistakes

- Using non-determinism as an excuse rather than a consistency problem to solve.
- Trusting an LLM judge because "it's AI" without naming or calibrating its bias.
- Ignoring that earlier conversation turns sit in later turns' context.
- Presenting synthetic users as a solution rather than an unproven claim.

## Excellent looks like

Old subject, new object: every "break" maps back to a decision from units 05–10,
and the student demands evidence before spending traffic on a trendy method.
