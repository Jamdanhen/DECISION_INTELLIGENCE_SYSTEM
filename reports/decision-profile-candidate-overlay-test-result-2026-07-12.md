# Decision Profile Candidate Overlay Test Result - 2026-07-12

Status: test result note

Test source:

```text
C:\DECISION_INTELLIGENCE_SYSTEM\reports\decision-profile-candidate-use-approval-2026-07-06.md
```

Scan used for test:

```text
C:\DECISION_INTELLIGENCE_SYSTEM\reports\registry-decision-scan-2026-07-12.md
```

## Test Result

The 2026-07-06 candidate profile fields were useful in the July 12 registry-scoped decision scan.

They helped distinguish:

- cleanup candidates from executable cleanup decisions
- mirrors/access surfaces from authority
- candidate guidance from promoted guidance
- broad impact summaries from field-level decision evidence
- safe no-action outcomes from unresolved indecision

## Fields That Improved The Scan

| Field | Result |
| --- | --- |
| `decision_domain` | Useful for separating cleanup, source-truth, visual canon, advisory-thread, and learning-continuity decisions. |
| `action_risk_class` | Strongly useful; cleanup/archive and source-truth apply paths require risk classification before recommendation. |
| `authority_confidence` | Strongly useful; repeated mirror/source/export distinctions depend on it. |
| `promotion_state` | Useful; especially for REflections learning notes and Comics canon/register movement. |
| `source_case_relationship` | Useful but still candidate; helps prevent Grayline/Comics/REflections evidence from becoming Decision Intelligence authority. |
| `evidence_completeness` | Strongly useful; cleanup and apply-path decisions hinge on completeness proof. |
| `human_burden_assessment` | Strongly useful; field-level before/after review is about making decisions human-possible. |
| `missing_context` | Useful; generated case-specific questions without forcing generic templates. |
| `root_cause_confidence` | Useful but less central in this scan than in prior Campaign Archive evidence. |
| `outcome_class` | Strongly useful; "no executable cleanup retained" is a decision outcome. |

## Fields That Created Process Drag

None were harmful, but three should stay lightweight:

- `source_case_relationship`
- `root_cause_confidence`
- `promotion_state`

These are most valuable when authority transfer, repair confidence, or candidate/adoption movement is actually at issue.

## Redundant With Existing Decision Context Layer Draft

The following overlap with existing draft context fields and should probably merge rather than remain separate:

- `authority_confidence` with `source_authority` / `authority_boundary`
- `promotion_state` with current `promotion_state`
- `missing_context` with `missing_context_questions`
- `source_case_relationship` with `source_authority` plus project relationship context

## Strong Enough To Propose For Promotion

Recommended for a draft model update:

- `decision_domain`
- `action_risk_class`
- `authority_confidence`
- `evidence_completeness`
- `human_burden_assessment`
- `outcome_class`

## Keep Candidate-Only For Now

Keep testing:

- `source_case_relationship`
- `promotion_state`
- `missing_context`
- `root_cause_confidence`

Add or refine as candidates:

- `owner_correction_state`
- `rejected_option_memory`

## Promotion Boundary

No promotion has occurred.

`DECISION_MODEL.md` remains unchanged.

`DECISION_CONTEXT_LAYER_DRAFT.md` remains unchanged.
