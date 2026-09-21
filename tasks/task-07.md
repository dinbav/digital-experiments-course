# Task 07 — Treatment as delivered

**Feeds:** Decision 6 — What exactly is the treatment?
**Type:** Written / reasoning · no code
**Deliverable:** a one-page **treatment specification sheet**.

## Why this task

"Personalised recommendation" is a slide, not a treatment. Experts describe
delivery — which surface, which users, which sessions, through what mechanism,
and what happens when it fails. If the treatment isn't consistent every time,
you're estimating a mixture and reporting its average as if it were one number.

## What to do

Write a spec an engineer could implement without guessing:

1. **Surface** — the interface the user actually meets (layout, message, creative,
   price, social signal).
2. **Audience & sessions** — who receives it, on which sessions.
3. **Delivery mechanism** — server-side vs client-side; feature-flag behaviour;
   staged ramp.
4. **Consistency** — is it the same treatment every time? If a rule, show it's
   stable; if a model, name version, temperature, catalog — and what still drifts
   (stockouts, empty history).
5. **Failure behaviour** — what the user gets if the flag or model fails to load.
6. **Compliance & ethics check** — does the design keep consent symmetric / avoid
   dark patterns? Legal clearance in one jurisdiction is not the whole answer.

Note explicitly: deploying to 100% behind a flag with no held-back group is **not**
an experiment.

## Deliverable & format

One page, structured as the six headings above. Deployable language, not adjectives.

## How it feeds your final project

This is Decision 6: treatment as delivered — surface, mechanism, failure
behaviour, consistency.

## Marked on

- Whether an engineer could build it from your sheet without asking questions.
- Whether treatment consistency is addressed honestly (especially for adaptive/AI treatments).
- Whether the ethics/compliance check is real, not a footnote.
