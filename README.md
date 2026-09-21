# Digital Experiments — Course Pack

Student-facing practice and assignments for **Business Application of Digital
Experiments** (TAU 1242.3272). This pack is self-contained and designed to be
published to a separate public repository.

The reading — the twelve articles — lives elsewhere and ends each part with a
few **questions to think about**. The *tasks* (what you hand in) live here, on
purpose: reading and doing are two different things.

## What's in here

| Folder | What it holds | Audience |
|--------|---------------|----------|
| [`tasks/`](tasks/) | One task per unit + the final project brief. This is the graded work. | Students |
| [`notebooks/`](notebooks/) | The Colab exercise notebooks a task points to when it needs code. | Students |
| [`solutions/`](solutions/) | Answer keys and the fully-worked demo notebooks. | **Instructor** — see the note below |

> **Before publishing:** decide whether `solutions/` goes public. Answer keys
> and worked notebooks are instructor material. If this pack becomes a public
> student repo, keep `solutions/` in a private repo or a private branch, or
> remove it before publishing. Nothing else in the pack reveals answers.

## How the tasks fit together

Every weekly task produces **one artifact**, and the artifacts stack into the
**final project** — a real digital experiment your group designs across the
term, organised as [eight decisions](tasks/final-project.md). You are not doing
homework *alongside* a project; each task **is** the next decision of your
project.

| Unit | Task | Decision it feeds | Code? |
|------|------|-------------------|-------|
| 01 | Should you even run an experiment? | 1 — Should you experiment at all? | — |
| 02 | Confounding vs. a real effect | 2 — What counts as evidence? | ✅ |
| 03 | Potential outcomes and your estimand | 2 — What counts as evidence? | — |
| 04 | Your OEC and guardrails | 3 — What is the OEC? | ✅ |
| 05 | The design your constraint allows | 4 — What design? | ✅ (optional) |
| 06 | Randomization unit and interference | 5 — What gets randomized? | ✅ |
| 07 | Treatment as delivered | 6 — What exactly is the treatment? | — |
| 08 | Power, MDE, duration | 7 — How much certainty? | ✅ |
| 09 | Trust checks | 8 — Do you trust it? | ✅ |
| 10 | Analysis, decision, ethics | 8 — Do you trust it? | ✅ |
| 11 | (Optional) When the treatment is an AI system | Decisions 5–8, stressed | ✅ |
| — | [Final project](tasks/final-project.md) | All eight decisions | as needed |

Units 01, 03, 07 and 12 are **written / reasoning** tasks with no code — by
design. The course grades reasoning, not code sophistication: a strong task
with simulated data beats a weak one on real traffic.

## Working with the notebooks

Every notebook runs top to bottom in a clean Colab runtime, generates its own
data (no uploads, no keys), and includes a **"Without code"** section so you can
follow the whole argument by reading printed tables and plots if you prefer.

- **Open in Colab:** upload the `.ipynb` (File → Upload notebook), or once this
  pack is on GitHub use `https://colab.research.google.com/github/<owner>/<repo>/blob/main/notebooks/<notebook>.ipynb`.
- **Acceptance test:** Runtime → Restart and run all.
- `notebooks/` holds the **exercise** versions (with `TODO` cells you complete);
  the fully-worked **demo** versions live in `solutions/`.

Full catalog and Colab baseline: [`notebooks/README.md`](notebooks/README.md).

## AI policy (short version)

You may use AI tools; you may not outsource judgment. Any submission that used
AI ends with one line: which tool, and what for. In studio and Q&A you will be
asked **why** you made a decision — own it.

## Grading

- Weekly tasks — **30%** (individual)
- Proposal — **5%** (group)
- Final project — **65%** (group)

Final-project weighting by decision is in
[`tasks/final-project.md`](tasks/final-project.md).
