# Scan-Derived Note - Registry Decision Pattern Sweep - 2026-07-06

Status: scan-derived project note

## Core Finding

The Decision Intelligence System should model decisions as authority-bounded, context-bearing acts, not as simple recommendations.

The strongest reusable pattern across the Registry is:

```text
Useful evidence is not authority.
Clear structure is not completeness.
Uncertainty is not always a user decision.
Safe continuation should continue.
Promotion, source modification, cleanup, and ownership changes require explicit decision.
```

## What This Means For The Profile

The decision profile should expand beyond procurement into a general decision context model with these recurring dimensions:

- authority boundary
- evidence completeness
- promotion state
- source/destination relationship
- action risk
- human burden
- reversibility
- missing context
- fragile detail preservation
- root-cause confidence
- next real decision boundary

## Non-Procurement Importance

The sweep confirms the user's correction: the system should not be framed as mainly about buying technology.

Procurement is only one case type. The same decision intelligence work applies to:

- project authority
- source-of-truth selection
- promotion from candidate to canon/current truth
- interface design
- workflow continuation
- data extraction confidence
- cross-project adoption
- public/private separation
- cleanup and migration risk
- pause/reset decisions

## Candidate Model Direction

The current `DECISION_CONTEXT_LAYER_DRAFT.md` is directionally useful, but the next candidate update should add a stronger matrix/profile section for:

1. action risk ladder
2. authority confidence
3. evidence completeness
4. promotion/adoption state
5. human burden and decision-surface quality
6. source-case relationship
7. missing-context handling
8. stop/reset/continue outcome class

## Do Not Promote Yet

This note does not recommend immediately changing `DECISION_MODEL.md`.

The better next step is to use the candidate update file from this sweep in one more bounded decision case, then decide whether to promote selected fields into the stable model.
