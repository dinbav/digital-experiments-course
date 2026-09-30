# Answer key — Task 06 (Randomization unit and interference)

**Instructor-facing.** Worked notebook: [`unit-06-randomization-demo.ipynb`](unit-06-randomization-demo.ipynb).

## Notebook (Part A)

The demo notebook is the reference (seed 42). Key results:

- User-level A/B estimate about **+9.5 points**; the real effect of launching (all riders vs none) about **+3.2 points** - the A/B test overstated it about **3x**, in the direction that flatters the treatment.
- Control riders booked **27.8%** during the A/B test, below the 29.1% they get with no test: treated riders took drivers from them.
- The 28-day switchback estimates about **+3.9 points**, close to the truth.
- Treating rider-days as independent understates the switchback SE about **2.7x**; the honest 95% CI is roughly +1.8 to +6.0 points.

Students should name the direction and rough size of the naive bias, and why the wider interval is the honest one.

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
