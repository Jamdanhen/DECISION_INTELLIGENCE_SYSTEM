# Decision Profile Candidate Use Approval - 2026-07-06

Status: approved for bounded use, not promoted

## Approved Action

The user approved:

```text
APPROVE: Use the 2026-07-06 decision profile candidates in the next bounded decision case before promoting any model changes.
```

## Authority Boundary

This approval applies inside:

```text
C:\DECISION_INTELLIGENCE_SYSTEM
```

It does not authorize modification of:

- `DECISION_MODEL.md`
- the Crucible Registry
- source projects
- Grayline project files
- OneDrive mirrors
- any other project authority folder

## Candidate Source

Use this candidate set as the test basis:

```text
C:\DECISION_INTELLIGENCE_SYSTEM\reports\decision-profile-candidate-updates-2026-07-06.md
```

The candidate fields remain draft/test fields until separately promoted.

## Bounded Use Rule

In the next bounded decision case or next registry-scoped decision scan, apply the candidate fields as an evaluation overlay:

- decision domain
- action risk class
- authority confidence
- promotion state
- source case relationship
- evidence completeness
- human burden / decision surface quality
- missing context handling
- root-cause confidence
- outcome class

The overlay may inform notes, scan records, case records, or recommendations.

It must not silently change the core model, project standards, Registry guidance, or source project authority.

## Test Objective

The next use should answer:

1. Which candidate fields improved the decision?
2. Which fields created process drag?
3. Which fields were redundant with the existing Decision Context Layer Draft?
4. Which fields should remain candidate-only?
5. Which fields are strong enough to propose for promotion?

## Required Output After Test

After the next bounded decision case or registry-scoped scan, create a short test result note inside:

```text
C:\DECISION_INTELLIGENCE_SYSTEM\reports
```

The note should state whether any candidate fields should be promoted, revised, merged, or discarded.

## Current Promotion State

No model promotion has occurred.

`DECISION_MODEL.md` remains unchanged.

`DECISION_CONTEXT_LAYER_DRAFT.md` remains draft guidance.
