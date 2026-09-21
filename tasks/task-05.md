# Task 05 — The design your constraint allows

**Feeds:** Decision 4 — What design does the constraint allow?
**Type:** Written / reasoning · optional code
**Notebook (optional):** [`v2-did-exercise.ipynb`](../notebooks/v2-did-exercise.ipynb)
**Deliverable:** a one-page design decision + named principal threat.

## Why this task

"We can't randomize" is where the work starts, not where it stops. Natural, lab,
field, and quasi-experiments each answer a constrained version of the question —
constraints pick the design, not a quality ladder.

## What to do

For your project:

1. State the **constraint** that limits you — whose platform, whether anyone can
   be withheld from treatment, whether the change is already live.
2. Name the **strongest design** that constraint allows: field A/B, lab,
   natural experiment, difference-in-differences, or synthetic control.
3. Name the **rejected alternative** and why it doesn't fit.
4. State the **principal threat** you're signing up to believe (parallel trends
   for DiD, pre-treatment fit for synthetic control, selection for a natural
   experiment) — and how you'd probe it.
5. One line on **participant awareness / ethics**: are people aware they're in a
   study, and is that acceptable here?

**Optional code:** if your honest answer is difference-in-differences, run the
DiD notebook to see parallel trends both intact and broken, and paste which case
your project resembles.

## Deliverable & format

One page: constraint → chosen design → rejected alternative → principal threat →
ethics line. Optional: one figure from the DiD notebook.

## How it feeds your final project

This is Decision 4: chosen design, rejected alternative, principal threat,
participant awareness.

## Marked on

- Whether the design actually follows from the constraint (not chosen first).
- Whether the principal threat is named and probed, not hidden.
- Whether you resisted dressing a natural experiment as an RCT.
