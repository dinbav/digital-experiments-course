# Answer key — Task 05 (The design your constraint allows)

**Instructor-facing.** Optional worked notebook: [`v2-did-demo.ipynb`](v2-did-demo.ipynb).

## Model answer (shape)

The design **follows from** a stated constraint; the rejected alternative is named
with a reason; the principal threat is the right one for the chosen design
(parallel trends → DiD; pre-treatment fit → synthetic control; selection →
natural experiment) and there's a plan to probe it; the ethics line addresses
participant awareness.

## Notebook (optional)

The DiD demo is the reference (seed 42): after-only **+12.1** and before-after
**+9.4** against a true effect of +5; DiD **+4.9** (95% CI about +4.3 to +5.4)
with a placebo effect near zero. With a treated-only trend, DiD reads **+7.6**
and the placebo test flags it (about +1.3, CI excluding zero). Students who ran
it should say which panel their project resembles and how they would run the
placebo check on their own pre-period data.

## Common mistakes

- Choosing "A/B test" first, then reverse-justifying — design should follow the constraint.
- Treating a natural experiment as an RCT "with extra steps" (it stays observational).
- Naming a design but not its principal threat, or naming a threat with no probe.
- Forgetting that a universal past ship may admit **no** clean design — a valid answer.

## Excellent looks like

The student can say which weaker answer they're *allowed* to write given the
constraint, and defends the single assumption they're choosing to believe.
