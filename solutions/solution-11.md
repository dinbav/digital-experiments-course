# Answer key — Task 11 (When the treatment is an AI system) · optional

**Instructor-facing.** Worked notebook: [`v2-ai-eval-demo.ipynb`](v2-ai-eval-demo.ipynb).

## Notebook (Part A)

The demo notebook is the reference (seed 42). Key results:

- Judge A (an AI judge that rewards length) reports **+0.87**, p < 0.001.
- The assistant's quality variance is about **4x** the templates' (about 2.5x the sample needed).
- Cohen's kappa between the judges is about **0.30** - not interchangeable raters.
- The length-blind judge B sees **+0.07** (true effect +0.10): most of judge A's win was length.
- Cost ratio about **2.0x** fails the 1.5x guardrail.
- Split at the vendor update: about **+0.46** before, **-0.31** after.

Students complete the decision table (held / broke / open) in the exercise's answer cell. The optional real-model notebook shows the same checks on open-source models; its numbers vary by run and hardware, so it is not graded on values.

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
