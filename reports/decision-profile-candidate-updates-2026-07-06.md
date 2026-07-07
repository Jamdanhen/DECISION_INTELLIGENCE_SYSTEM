# Decision Profile Candidate Updates - 2026-07-06

Status: candidate updates, not promoted

Source scan:

```text
C:\DECISION_INTELLIGENCE_SYSTEM\reports\registry-decision-pattern-sweep-2026-07-06.md
```

## Candidate Profile Fields

### 1. Decision Domain

Purpose: prevent procurement from becoming the default frame.

Candidate values:

- procurement
- project authority
- source-of-truth
- workflow continuation
- promotion / adoption
- interface / human decision surface
- data extraction / classification
- cleanup / migration
- public-private separation
- pause / reset / archive
- strategy / priority

### 2. Action Risk Class

Purpose: identify whether the system may continue or must stop for approval.

Candidate ladder:

- read-only observation
- analysis / classification
- draft / plan-only artifact
- reversible local test
- non-canonical preview
- local project record update
- authority adoption / promotion
- source modification
- file operation: copy / move / rename / delete / merge / overwrite
- cleanup / archive
- ecosystem-wide standard

### 3. Authority Confidence

Purpose: separate strong source authority from uncertain registry/project state.

Candidate values:

- confirmed authority
- likely authority
- mirror / copy only
- no authority location established
- stale authority reference
- conflicting authority references
- not owned by this project

### 4. Promotion State

Purpose: prevent useful material from becoming authority by accident.

Candidate ladder:

- source
- reference
- candidate guidance
- local adoption candidate
- locally adopted
- shared standard candidate
- accepted shared standard

### 5. Source Case Relationship

Purpose: allow rich project examples without absorbing them.

Candidate values:

- evidence source
- test case
- reference case
- inspiration / influence
- implementation example
- local adoption source
- authority source
- out of scope except for read-only scan

### 6. Evidence Completeness

Purpose: detect when the answer is premature because evidence coverage is thin.

Candidate values:

- complete enough for decision
- structurally valid but content-thin
- missing source evidence
- missing rationale
- missing tradeoff
- missing authority boundary
- missing human-facing impact
- missing owner-only interpretation
- blocked until absent categories are explicitly marked

### 7. Human Burden / Decision Surface Quality

Purpose: measure whether a decision is easy for the owner to make cleanly.

Candidate checks:

- one clear question
- one answer location
- plain-language options
- visible consequence / impact preview
- nearby context
- no duplicated answer locations
- no manual machine-readable block
- machine-readable output generated after human answer
- next action visible after save/decision

### 8. Missing Context Handling

Purpose: avoid false certainty and avoid unnecessary user decisions.

Candidate values:

- preserve as non-blocking context
- preserve as fragile detail
- ask case-specific question
- block because authority would change
- block because source modification would occur
- block because owner-only interpretation is required
- park as candidate / carry-forward

### 9. Root-Cause Confidence

Purpose: distinguish a durable decision from a surface-level patch.

Candidate values:

- symptom only
- local cause identified
- shared mechanism traced
- durable repair path known
- user-facing verification path known
- verified against actual dependency path

### 10. Outcome Class

Purpose: make stopping and resetting first-class decision outcomes.

Candidate values:

- continue current lane
- continue automatically inside approved boundary
- ask for real decision
- preserve and defer
- pause lane
- reset architecture
- archive / extract lessons
- promote candidate
- reject / abandon

## Candidate Matrix Rows

| Candidate ID | Pattern | Why It Matters | Candidate Addition |
| --- | --- | --- | --- |
| DPM-001 | Real decision boundary detection | Reduces micro-approval loops while preserving safety | Add action risk class plus next real decision boundary |
| DPM-002 | Authority confidence | Prevents mirror/source/reference confusion | Add authority confidence field |
| DPM-003 | Promotion state ladder | Keeps useful material from becoming authority by proximity | Add promotion state field |
| DPM-004 | Completeness before authority | Blocks structurally valid but context-thin decisions | Add evidence completeness gate |
| DPM-005 | Missing context as question | Converts absent rationale into case-specific questions | Add missing-context handling |
| DPM-006 | Fragile detail preservation | Keeps uncertainty visible without forcing needless decisions | Add fragile/non-blocking preservation state |
| DPM-007 | Human burden as criterion | Decision quality includes the surface where the human decides | Add human burden / decision-surface checks |
| DPM-008 | Source case relationship | Allows Grayline and other projects to inform without being absorbed | Add source case relationship |
| DPM-009 | Root-cause confidence | Helps avoid repeated surface patching | Add root-cause confidence field |
| DPM-010 | Candidate-level approval | Prevents all-or-nothing approval when items differ | Add separability check |
| DPM-011 | Stop/reset outcomes | Some lanes should pause or reset rather than continue | Add outcome class |
| DPM-012 | Durable decision record shape | Preserves decision memory across sessions | Add preferred decision record fields |

## Draft Decision Record Shape

Use this shape when a decision case is being recorded or scanned:

```text
decision_id:
decision_domain:
decision_question:
source_case_relationship:
source_authority:
destination_authority:
authority_confidence:
write_boundary:
action_risk_class:
promotion_state:
evidence_completeness:
human_burden_assessment:
observed_rationale:
accepted_tradeoffs:
rejected_options:
missing_context:
fragile_details:
root_cause_confidence:
outcome_class:
next_real_decision_boundary:
model_implication:
```

## Promotion Recommendation

Do not promote all candidate fields immediately.

Recommended next test:

Use these fields in one bounded decision case or next registry-scoped scan, then promote only the fields that improve decision quality without creating extra process drag.
