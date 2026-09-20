# Final Project — the experiment you've been building all term

**Weight:** 65% (group of three) · **Feeds:** all eight decisions
**Deliverable:** one written report + a live presentation.

The final project is not a new assignment. It is the ten weekly tasks, revised
and assembled into one design and defended out loud. If the weekly tasks felt
like homework *alongside* a project, something went wrong — each task **was** the
next decision. Before writing new prose, collect what you already have.

## The deliverable

**One written report per group**, plus a **live presentation** in the final
sessions. The report and the talk describe the same design; disagreement between
them is a red flag in Q&A.

Organise the report as the **Eight Decisions**. Each maps to the tasks you've
already done:

| Decision | Section must show | Built in |
|----------|-------------------|----------|
| **1** Should you experiment at all? | The business choice, why observational data fails, why an experiment is the practical next step | Task 01 |
| **2** What counts as evidence? | Confound, evidence hierarchy, notation, estimand, what's unresolved | Tasks 02–03 |
| **3** What is the OEC? | Weighted composite, guardrails, trade-off, measurement window | Task 04 |
| **4** What design does the constraint allow? | Chosen design, rejected alternative, principal threat, participant awareness | Task 05 |
| **5** What gets randomized? | Randomization unit, interference, SUTVA, switchback if relevant | Task 06 |
| **6** What exactly is the treatment? | Treatment as delivered: surface, mechanism, failure behaviour, consistency | Task 07 |
| **7** How much certainty can you afford? | Business threshold, MDE, sample size / duration, variance plan | Task 08 |
| **8** Do you trust it, and what next? | Validity threats and checks, analysis plan, ship rule, ethics, consolidated limitations | Tasks 09–10 |

Also include:

- **Results** — from real data if you have it, from simulated data if you don't.
- A **limitations** section naming what the design still doesn't defend, across all eight decisions.
- One sentence per member: the decision they personally argued for (not graded).

**Target length:** 8–15 pages including tables and figures. Shorter is fine if
every criterion is answered; longer usually means repetition.

## What the project is allowed to be

A digital experiment on a **real decision** your group chooses: a product change
(UI, onboarding, pricing, messaging, ranking, notification timing), a growth or
retention intervention, a policy/process change through a digital channel, an
offline decision tested through a digital proxy (survey, fake door, pilot cohort),
or an AI-system treatment if Decision 6 handles consistency honestly.

Data may be **real, simulated, or hybrid**. Simulated data is fully acceptable
and often preferable to a badly designed experiment on real traffic — **the
design is what's assessed.**

## What it must not be

| Not allowed | Why |
|-------------|-----|
| A literature review or market report with no design | The course assesses experimentation |
| An ML model comparison with no randomised assignment | Training splits are not field experiments |
| An A/B proposal with no randomization unit or SUTVA discussion | Decision 5 is non-negotiable |
| A result with no pre-specified OEC, ship rule, or validity checks | That's p-hacking dressed as analysis |
| A design with **no stated limitation** | Can't score top marks on any criterion |
| "Personalisation" / "AI" as a label with no delivery spec | Decision 6 needs deployable language |

Ethical lines: no deceiving participants about harm, no collecting identifiable
sensitive data without a stated privacy plan, no testing dark patterns. Raise
ethics questions at design time, not in a closing apology.

## How the weekly tasks become the report

Don't rewrite from scratch — copy forward, then edit for consistency:

1. Merge individual artifacts into one group voice, organised by decision.
2. Resolve contradictions (if your Task 04 OEC and Task 03 notation disagree, fix it).
3. Run the analysis (or simulation) consistent with your pre-specified Task 10 plan.
4. Write the **results** and a consolidated **limitations** section across all eight decisions.
5. Self-assess each decision against the rubric before submitting.

## Presentation

Presentation quality isn't a separate grade — it's *how* the project is assessed.
The Q&A reveals whether the group owns the design. Be ready to explain, for each
decision, **why** you made it and **what it depends on**. Null results with sound
design score at the top; positive results with no validity plan do not.

## AI disclosure

You may use AI tools; you may not outsource judgment. End any AI-assisted
submission with one line: which tool, and what for. In studio and Q&A you'll be
asked why — own your decisions.

## How it's marked

Eight criteria — the eight decisions. Weights:

| Decision | Weight | | Decision | Weight |
|----------|--------|-|----------|--------|
| 1. Should you experiment? | 10% | | 5. What gets randomized? | 10% |
| 2. What counts as evidence? | 20% | | 6. What is the treatment? | 10% |
| 3. What is the OEC? | 10% | | 7. How much certainty? | 10% |
| 4. What design? | 10% | | 8. Do you trust it? | 20% |

Decisions 2 and 8 carry double weight because each spans two units.
