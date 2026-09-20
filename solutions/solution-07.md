# Answer key — Task 07 (Treatment as delivered)

**Instructor-facing.** No code.

## Model answer (shape)

A spec an engineer could implement without questions: surface, audience, sessions,
delivery mechanism (server/client, flag behaviour, ramp), **consistency**
(a stable rule shown stable, or a model with version/temperature/catalog pinned
and remaining drift named), failure behaviour, and a real compliance/ethics check.
Explicitly notes that 100%-behind-a-flag with no holdout is not an experiment.

## Common mistakes

- Adjectives instead of delivery ("a better, personalised flow").
- Ignoring failure behaviour (what loads when the flag/model fails).
- For adaptive/AI treatments, hand-waving consistency — the mixture problem.
- Treating one jurisdiction's legal clearance as the whole ethics answer.

## Excellent looks like

The consistency section is honest about what still varies for a meaningful slice
of users, and the ethics check is a design input, not a closing disclaimer.
