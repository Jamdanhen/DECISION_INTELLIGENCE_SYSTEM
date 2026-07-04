# Registry-Scoped Decision Scan Record Template

Status:

```text
Working template
```

Purpose:

```text
Record one read-only Decision Intelligence System scan of the Crucible Registry
for decisions, decision context, and missing rationale.
```

## Scan Header

Scan date:

```text
YYYY-MM-DD
```

Scan label:

```text
registry-decision-scan-YYYY-MM-DD
```

Scan type:

```text
Registry-scoped decision discovery
```

Scan authority boundary:

```text
C:\CRUCIBLE_REGISTRY
```

Write boundary:

```text
C:\DECISION_INTELLIGENCE_SYSTEM
```

Source modification status:

```text
Read-only. No registry files or source project files modified.
```

Last scan baseline:

```text
No prior scan baseline exists.
```

or:

```text
Compare against: [previous scan record path]
Previous scan timestamp: [timestamp]
```

## Active Objective

```text
Identify decisions, decision-making context, and missing rationale from
registry-scoped project updates so the Decision Intelligence model can be
refined from observed evidence.
```

## Registry Scope Inspected

Registry files inspected:

| File | Reason Inspected | Notes |
| --- | --- | --- |
|  |  |  |

Registry entries inspected:

| Entry | Entry Type | Authority Location | Included In Scan | Reason |
| --- | --- | --- | --- | --- |
|  |  |  | Yes/No |  |

Registry-approved project references inspected:

| Project | Authority Location | Files Considered | Updated Since Baseline | Notes |
| --- | --- | --- | --- | --- |
|  |  |  | Yes/No/Unknown |  |

## Scan Method

File selection rule:

```text
Inspect registry entries and registry-approved project authority references.
When a prior scan record exists, prioritize files updated since that scan.
When no baseline exists, perform an initial baseline scan and mark coverage
limits clearly.
```

Decision evidence searched for:

- explicit decision
- implied decision
- decision rationale
- criteria or values used
- tradeoff accepted
- option rejected
- authority or boundary decision
- unresolved decision
- missing decision context

Exclusions:

- no source project modification
- no registry modification
- no file movement, copying, renaming, deletion, cleanup, merge, or restructure
- no extraction of project substance unrelated to decision-making
- no conversion of findings into final governance

## Decision Findings

| ID | Project / Entry | Source File | Finding Type | Decision Area | Summary | Evidence Strength |
| --- | --- | --- | --- | --- | --- | --- |
| D-001 |  |  | explicit decision / implied decision / rationale / criteria / tradeoff / rejected option / authority-boundary / unresolved / missing context |  |  | strong / partial / weak |

## Decision Context Extracts

Use short excerpts or paraphrases. Preserve enough context to understand the
decision process without absorbing unrelated project substance.

### D-001

Project / entry:

```text

```

Source:

```text

```

Observed decision or decision signal:

```text

```

Observed rationale:

```text

```

Criteria or values visible:

```text

```

Tradeoffs visible:

```text

```

Options rejected:

```text

```

Authority or boundary context:

```text

```

Missing context:

```text

```

Model implication:

```text

```

## Case-Specific Questions

Generate questions only where the observed project, file, decision area, or
missing rationale supports them.

| ID | Project / Entry | Source File | Missing Context | Question | Why It Matters |
| --- | --- | --- | --- | --- | --- |
| Q-001 |  |  |  |  |  |

## Emerging Decision Patterns

Patterns observed:

- 

Possible model refinements:

- 

Patterns not yet supported by enough evidence:

- 

## Coverage Limits

Known limits:

- 

Files or entries not inspected:

- 

Reasons coverage is incomplete:

- 

## Follow-Up

Recommended next action:

```text

```

Decision needed from user:

```text
None / [specific decision]
```

Next scan trigger:

```text
User says scan, update, or look for decisions; or a scheduled registry-scoped
decision discovery cadence is approved.
```

## Closeout

Completed:

- 

Outputs written inside `C:\DECISION_INTELLIGENCE_SYSTEM`:

- 

Source projects modified:

```text
No
```

Registry modified:

```text
No
```
