# Decision Context Layer Draft

Status:

```text
Draft candidate model update
```

Source evidence:

```text
reports\registry-decision-scan-2026-07-04.md
reports\registry-decision-scan-note-2026-07-04.md
```

## Purpose

The Decision Context Layer is a candidate addition to the Decision Intelligence
System model.

It does not replace the existing core decision loop:

```text
Observe
Collect Evidence
Score
Compare
Recommend
Monitor
Re-evaluate
```

Instead, it adds evidence-derived context fields that help the system understand
what kind of decision is being made, who owns it, what actions are authorized,
and what must remain unresolved until a real decision boundary is reached.

## Status And Promotion Boundary

This draft is not yet a reusable project standard.

It should not be treated as final governance, a mandatory template, or a change
to `DECISION_MODEL.md` until the user explicitly approves promotion.

This draft may be used as working guidance for future registry-scoped scans,
decision notes, and candidate decision-record formats.

## Why This Layer Exists

The first registry-scoped decision scan found that many important decisions are
not mainly scoring decisions.

They are context decisions about:

- authority
- source protection
- write boundaries
- planning versus execution
- influence versus adoption
- local project rules versus reusable standards
- continuation through approved non-destructive work
- missing rationale or unresolved ownership

Without these fields, the system risks flattening different decision types into
one generic recommendation format.

## Candidate Fields

## `decision_question`

The concrete question being decided.

Use when:

- opening any decision record
- distinguishing a real decision from routine recordkeeping
- identifying what user judgment is actually needed

Example:

```text
Should this source-project pattern become reusable Decision Intelligence
guidance, or remain project-local evidence?
```

## `authority_boundary`

The project, person, system, repository, folder, record set, or governing file
that owns the decision.

Use when:

- a decision affects more than one project
- the system is scanning evidence from another project
- source material may influence a destination project
- a decision could modify project authority, canon, standards, or source files

Candidate values:

- confirmed local project authority
- destination project authority
- Registry relationship authority
- user-only authority
- no authority established
- unclear authority

## `source_authority`

The place where the observed evidence or source material belongs.

Use when:

- another project is providing evidence
- source material may be referenced, extracted, copied, promoted, or adopted
- the system needs to avoid absorbing another project's substance

Example:

```text
C:\REflections remains the source authority for reflection material.
```

## `write_boundary`

The location where this system is allowed to write for the active task.

Use when:

- scans inspect other projects but findings must be recorded locally
- a task touches Registry or source-project evidence
- file modification risk exists

Default for registry-scoped decision discovery:

```text
C:\DECISION_INTELLIGENCE_SYSTEM
```

## `action_risk_class`

The kind of action the decision authorizes or forbids.

Use when:

- a decision involves files, repositories, purchases, standards, canon, source
  material, or project authority
- an approval may cover planning but not execution
- a recommendation could be mistaken for permission to act

Candidate classes:

- observe
- scan
- classify
- plan
- draft
- ask
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
- push
- purchase
- external contact

Rule:

```text
Do not infer a higher-risk action from approval of a lower-risk action.
```

Example:

```text
Approval to create a migration plan does not authorize moving files.
```

## `promotion_state`

The status of material moving from one context to another.

Use when:

- one project informs another
- source material may become local guidance, canon, doctrine, or standards
- a pattern may become reusable Decision Intelligence guidance

Candidate states:

- source
- reference
- evidence
- candidate guidance
- local adoption
- shared standard candidate
- accepted standard
- canon
- rejected
- parked

Rule:

```text
Influence does not equal adoption.
```

## `continuation_rule`

Whether prior approval carries through implied non-destructive work, and where
that permission stops.

Use when:

- work is already inside an approved lane
- the next step is recordkeeping, drafting, scanning, comparison, or analysis
- stopping would create a micro-approval loop

Candidate values:

- continue through non-destructive work
- continue through comparable set
- pause at source modification
- pause at authority change
- pause at final recommendation
- pause at external commitment
- pause at missing user judgment

Rule:

```text
Approval should attach to meaningful boundaries, not routine artifacts.
```

## `authority_confidence`

How settled the authority location or owner is.

Use when:

- registry entries say likely, pending, no authority, or unresolved
- project folders exist but confirmation is missing
- evidence and registry status disagree

Candidate values:

- confirmed
- likely pending confirmation
- no authority established
- conflicting authority
- stale or needs refresh

## `source_case_relationship`

Whether a project is being used as a test case, evidence source, reference, or
owner of reusable methods.

Use when:

- a project provides examples for a broader model
- reusable methods may be generalized from a project
- the system must avoid treating a source case as owned by the method project

Candidate values:

- source case
- test case
- reference case
- implementation owner
- method candidate
- destination adopter

Rule:

```text
A source case can inform a reusable method without transferring ownership.
```

## `observed_rationale`

The reason visible in the source evidence.

Use when:

- a decision record contains enough context to show why the decision was made
- a model note needs to preserve decision logic, not only the outcome

## `accepted_tradeoffs`

The costs, constraints, or losses accepted by the decision.

Use when:

- a decision prioritizes one value over another
- the same future decision may be reconsidered
- the system needs to avoid re-litigating an already accepted tradeoff

## `rejected_options`

The options explicitly or implicitly not chosen.

Use when:

- a future scan might otherwise rediscover rejected paths
- alternatives clarify the shape of the decision

## `missing_context_questions`

Case-specific questions raised by absent rationale, unresolved authority, stale
records, or incomplete decision context.

Use when:

- the scan finds an outcome without enough rationale
- authority is pending or unclear
- a source record is stale against later project evidence
- a model implication is plausible but not yet supported enough to promote

Rule:

```text
Missing context is evidence. Do not fill it with generic assumptions.
```

## `model_implication`

What the decision suggests about the Decision Intelligence System itself.

Use when:

- a scan finding points toward a candidate field, pattern, template, or
  distinction
- evidence suggests a model change but does not yet justify promotion

## Candidate Decision Context Block

Future decision records may include this block:

```markdown
## Decision Context

Authority boundary:

Source authority:

Write boundary:

Action risk class:

Promotion state:

Continuation rule:

Authority confidence:

Source-case relationship:

Observed rationale:

Accepted tradeoffs:

Rejected options:

Missing context questions:

Model implication:
```

Fields may be omitted when irrelevant, but omission should be intentional.

## Relationship To Existing Core Loop

## Observe

The Decision Context Layer mostly belongs in Observe.

It sharpens:

- what is being decided
- who owns the decision
- what authority the system has
- what authority remains outside the system
- which actions are permitted

## Collect Evidence

The layer helps evidence collection distinguish:

- source evidence
- project substance
- decision rationale
- missing context
- candidate model implications

## Score And Compare

The layer does not impose one scoring model.

It can prevent bad scoring by marking:

- unknown authority
- high-risk action classes
- promotion states that are not final
- stale or incomplete evidence

## Recommend

The layer helps recommendations state:

- whether a recommendation is final, draft, or candidate
- whether user approval is required before execution
- which actions remain outside the recommendation

## Monitor And Re-evaluate

The layer gives monitoring better triggers:

- source authority changed
- registry entry became stale
- missing context was answered
- candidate guidance was adopted
- a source case produced repeated evidence

## Initial Use Rules

Until promoted, use this layer as a working aid for:

- registry-scoped decision scans
- scan-derived notes
- candidate model-refinement notes
- high-risk decisions involving files, authority, standards, canon, purchases,
  or cross-project influence

Do not use this draft to:

- overwrite `DECISION_MODEL.md`
- modify Registry entries
- modify source projects
- declare a reusable project standard
- force all decisions into a larger template than they need

## Open Questions

1. Which fields should become required for all decision records?
2. Which fields belong only to registry-scoped scans or cross-project
   decisions?
3. Should `action_risk_class` be mandatory for any decision involving files,
   authority, standards, purchases, or external commitments?
4. Should `promotion_state` be mandatory for any decision involving source
   material, canon, doctrine, local guidance, or standards?
5. Should `Decision / Effect / Boundary` from the File Organization Project
   become the starting durable decision-record format?

## Promotion Criteria

This draft should be promoted into `DECISION_MODEL.md` only after one of these
conditions is met:

- the user explicitly approves promotion
- at least one additional registry-scoped scan supports the same fields
- a second bounded decision case uses the layer successfully
- a model review determines which fields are universal and which are optional

## Recommended Next Step

Use the Decision Context Layer Draft in the next registry-scoped scan or
bounded decision case before promoting it to the core model.
