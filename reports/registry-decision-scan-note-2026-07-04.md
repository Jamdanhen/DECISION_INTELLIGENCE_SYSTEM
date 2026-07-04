# Registry Decision Scan Note 2026-07-04

Status:

```text
Scan-derived working note
```

Source scan:

```text
reports\registry-decision-scan-2026-07-04.md
```

## Purpose

Record what the first registry-scoped decision scan means for the Decision
Intelligence System.

The scan record preserves what was inspected and found. This note preserves the
model implications.

## Core Takeaway

The first registry-scoped scan confirms that the Decision Intelligence System
should learn from observed decisions before expanding the model.

The strongest observed decision pattern is not scoring. It is boundary
discipline:

- what is being decided
- who owns the decision
- what kind of action is authorized
- what remains only evidence, reference, candidate guidance, or unresolved
- when continuation is allowed
- when explicit user judgment is required

## Candidate Model Fields

Add these as candidate fields for future decision records:

- `authority_boundary`
- `source_authority`
- `write_boundary`
- `action_risk_class`
- `promotion_state`
- `continuation_rule`
- `authority_confidence`
- `source_case_relationship`
- `missing_context_questions`
- `model_implication`

## Candidate Field Meanings

## `authority_boundary`

The project, person, system, or record set that owns the decision.

Observed reason:

Registry evidence repeatedly separates relationship mapping from project-owned
substance.

## `action_risk_class`

The kind of action the decision authorizes.

Candidate classes:

- observe
- scan
- classify
- plan
- draft
- copy
- write
- move
- delete
- merge
- overwrite
- cleanup
- promote
- adopt
- commit
- purchase

Observed reason:

File Organization decisions repeatedly show that planning approval is different
from execution approval.

## `promotion_state`

The status of material moving from one context to another.

Candidate states:

- source
- reference
- candidate guidance
- local adoption
- shared standard candidate
- accepted standard
- canon

Observed reason:

REflections influence, LENS/MOTU extraction, and ecosystem standards all use
promotion states to prevent accidental authority transfer.

## `continuation_rule`

Whether an approval carries through the next non-destructive steps, and where
it stops.

Observed reason:

The user repeatedly rejects micro-approval when a bounded non-destructive lane
has already been approved.

## `authority_confidence`

How settled an authority location or owner is.

Candidate values:

- confirmed
- likely pending confirmation
- no authority established
- conflicting authority
- stale or needs refresh

Observed reason:

Several Registry entries have likely authority paths while others deliberately
preserve unresolved authority.

## Model Risks

## Risk: Over-Generalizing Project-Local Rules

Campaign Archive and File Organization contain strong decision patterns, but
not all of their rules should become universal.

Mitigation:

Treat scan notes as candidate model evidence. Promote only after either user
approval or repeated cross-project support.

## Risk: Turning Registry Discovery Into Project Review

The scan should find decision evidence, not absorb project substance.

Mitigation:

Keep future scans registry-scoped and write only inside
`C:\DECISION_INTELLIGENCE_SYSTEM`.

## Risk: Treating Missing Context As Failure

Some project files record boundaries but not full rationale.

Mitigation:

Preserve missing context as case-specific questions. Missing rationale is model
evidence.

## Immediate Model-Refinement Candidates

The next model update should not replace the existing decision loop.

It should add an evidence-derived layer to decision records:

```text
Decision Context Layer
```

Candidate sections:

- authority boundary
- source/write boundary
- action risk class
- promotion state
- continuation rule
- authority confidence
- observed rationale
- missing context questions
- model implication

## Questions To Carry Forward

1. Which fields belong in every decision record, and which belong only in
   registry-scoped scans?
2. Should `action_risk_class` become a required field for all decisions or only
   decisions that can modify files, authority, purchases, or governance?
3. Should `promotion_state` be universal, or only used for cross-project,
   canon, standards, and extraction decisions?
4. Should File Organization's explicit `Decision / Effect / Boundary` format
   become the starting model for durable decision records?

## Recommended Next Action

Create a candidate model update that adds the Decision Context Layer without
promoting it to final project standard yet.

This would preserve the scan evidence while keeping the core model open for
revision.
