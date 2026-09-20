# Answer key — Task 06 (Randomization unit and interference)

**Instructor-facing.** Worked notebook: [`unit-06-randomization-demo.ipynb`](unit-06-randomization-demo.ipynb).

## Notebook (Part A)

The demo shows a user-level split inflating the effect under a shared resource,
and a switchback/block schedule recovering a trustworthy estimate. Students should
note the direction and rough size of the naive bias.

## Model answer (Part B)

A randomization unit tied to the **interference structure** (not the tool
default); the shared resource named, plus *who else* the treatment reaches; an
honest SUTVA judgment with a fix and its cost if it fails; a design-time variance
move (blocking / matched pairs) kept distinct from post-hoc slicing.

## Common mistakes

- Defaulting to cookie/user randomization without checking for a shared resource.
- Confusing user identification with the randomization unit.
- Treating SUTVA as a post-hoc test rather than a design assumption.
- Proposing to "adjust for spillover in the analysis" instead of changing the design.

## Excellent looks like

If SUTVA fails, the fix (switchback, clustering, geo-isolation) is concrete and
its power/complexity cost is acknowledged.
