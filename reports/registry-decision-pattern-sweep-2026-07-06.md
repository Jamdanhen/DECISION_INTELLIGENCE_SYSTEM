# Registry Decision Pattern Sweep - 2026-07-06

Status: baseline sweep record

## Objective

Sweep Registry-oriented project records and the explicitly allowed Shadowrun Grayline data-extraction area for decision-making patterns that could improve the Decision Intelligence System's decision matrix and profile.

This scan is not limited to technology procurement. It treats procurement as one decision class among many.

## Authority Boundary

Write boundary:

```text
C:\DECISION_INTELLIGENCE_SYSTEM
```

Read-only source boundary:

```text
C:\CRUCIBLE_REGISTRY
registry-identified C-drive project authorities
C:\ROLE_PLAYING GAMES\Shadowrun\_GRAYLINE
```

No Registry files, source project files, Grayline files, campaign files, repository files, or OneDrive mirror files were changed by this sweep.

## Sources Sampled

- `C:\DECISION_INTELLIGENCE_SYSTEM\AGENTS.md`
- `C:\DECISION_INTELLIGENCE_SYSTEM\DECISION_CONTEXT_LAYER_DRAFT.md`
- `C:\CRUCIBLE_REGISTRY\CROSS_PROJECT_PROMOTION_MODEL.MD`
- `C:\CRUCIBLE_REGISTRY\REFLECTION_INFLUENCE_SAFETY_MODEL.MD`
- `C:\CRUCIBLE_REGISTRY\LENS_MOTU_BOUNDARY_CLARIFICATION.MD`
- `C:\Campaign_Archive_System\AGENTS.md`
- `C:\Campaign_Archive_System\docs\V2_SOURCE_OF_TRUTH_OWNERSHIP_RULES.md`
- `C:\Campaign_Archive_System\docs\COMPLETENESS_BEFORE_AUTHORITY_GUIDANCE.md`
- `C:\Campaign_Archive_System\docs\AUTHORITY_REVIEW_DECISION_PERSISTENCE.md`
- `C:\Campaign_Interface_Preservation\Interface development\CAMPAIGN_UI_APPROVAL_PROTOTYPE_DECISION_START.md`
- `C:\Campaign_Interface_Preservation\Interface development\INTERFACE_BRIDGE_CHANGE_REPORT.md`
- `C:\CAMPAIGN_PROJECT_DEVELOPMENT\Project_Architect\04_DECISION_LOG.md`
- `C:\CAMPAIGN_PROJECT_DEVELOPMENT\Project_Architect\17_FRAGILE_DETAIL_HANDLING_REVIEW_PACKET.md`
- `C:\CAMPAIGN_PROJECT_DEVELOPMENT\Project_Architect\project_logs\476_PROJECT_PAUSED_AFTER_V1_DEATH_SPIRAL.md`
- `C:\file_organization_project\DECISIONS.md`
- `C:\file_organization_project\RECONCILIATION_DECISION_POINTS.md`
- `C:\file_organization_project\ORGANIZATION_VALUE_MODEL.md`
- `C:\LENS-SYSTEM\AGENTS.md`
- `C:\MOTURPG\AGENTS.md`
- `C:\MOTURPG\docs\publication\project-separation-plan-moturpg-lens-fracture-v0.1.md`
- `C:\REflections\AGENTS.md`
- `C:\ROLE_PLAYING GAMES\Shadowrun\_GRAYLINE\CODEX_PLACEMENT_RULE.md`
- `C:\ROLE_PLAYING GAMES\Shadowrun\_GRAYLINE\Index\README.md`
- `C:\ROLE_PLAYING GAMES\Shadowrun\_GRAYLINE\Index\FOLDER_ROLE_GUIDE.md`
- `C:\ROLE_PLAYING GAMES\Shadowrun\_GRAYLINE\Index\COPIED_SOURCE_REGISTER.md`
- `C:\ROLE_PLAYING GAMES\Shadowrun\_GRAYLINE\Repository Staging\WORKFLOW_INTAKE_ROUTER.md`
- `C:\ROLE_PLAYING GAMES\Shadowrun\_GRAYLINE\Repository Staging\WORKSHEET_DESIGN_DEFECT_USER_ENTRY_NOTE.md`
- `C:\ROLE_PLAYING GAMES\Shadowrun\_GRAYLINE\Repository Staging\SESSION_000_USER_INPUT_REQUIRED_WORKSHEET.md`
- `C:\ROLE_PLAYING GAMES\Shadowrun\_GRAYLINE\Repository Staging\HUMAN_GATED_AUTOMATION_SKELETON.md`

## Observed Decision Patterns

### 1. Decision Boundary Before Decision Content

Across the projects, strong decision records first establish whether a decision is actually needed. File Organization, Campaign Archive, REflections, LENS, and Grayline all distinguish safe continuation from real approval boundaries.

Candidate model implication:

Decision Intelligence should classify the next action before asking for judgment:

- read-only / analysis
- plan-only / draft-only
- reversible local test
- non-canonical candidate
- authority or promotion action
- source/project modification
- cleanup / deletion / merge / overwrite

### 2. Authority Confidence Is Part Of The Decision

Registry and cross-project records repeatedly separate source, reference, candidate guidance, local adoption, shared standard candidate, and accepted standard. LENS/MOTU separation adds origin/reference/extraction as a reusable distinction.

Candidate model implication:

Every decision case should track:

- source authority
- destination authority
- authority confidence
- source/destination relationship
- promotion state
- whether usefulness is being mistaken for authority

### 3. Completeness Before Authority

Campaign Archive shows a repeated lesson: structural validity, clean schema, successful UI rendering, or a neat packet does not prove that enough context has been preserved to support authority.

Candidate model implication:

The decision matrix needs a content completeness gate. A decision may be blocked not because the recommendation is wrong, but because evidence coverage is too thin.

### 4. Missing Context Should Become Questions, Not Fake Certainty

Decision records repeatedly preserve unresolved details as missing, deferred, fragile, candidate, carry-forward, or owner-added instead of forcing them into final authority.

Candidate model implication:

When evidence is incomplete, the system should generate case-specific questions and preserve the uncertainty class.

### 5. Human Burden Is A Decision Criterion

Interface Preservation and Grayline show repeated failures where the human-facing decision surface became too technical, duplicated answer locations, or forced manual machine-readable work. The correction pattern is one decision card, direct answer location, plain-language action, and machine-readable output generated afterward.

Candidate model implication:

Decision quality should include human-completion cost and interface clarity, not only correctness of the underlying recommendation.

### 6. Use The Lightest Relationship That Solves The Problem

Cross-project promotion, REflections influence, and LENS/MOTU separation all point to a recurring rule: source material can inform, reference, test, or inspire without being absorbed.

Candidate model implication:

The profile should prefer reference, candidate guidance, or local notes when adoption would overstate authority.

### 7. Source Case Does Not Transfer Ownership

Grayline can be a rich test case for extraction and decision modeling without becoming owned by the Decision Intelligence System. MOTU can be an origin for LENS without making LENS depend on MOTU. REflections can inform other projects without becoming their canon.

Candidate model implication:

Add a source-case relationship field:

- evidence source
- test case
- reference
- local adoption candidate
- authority source
- not owned / not adopted

### 8. Fragile Details Need A Non-Blocking Preservation State

Campaign Project Development's fragile detail handling separates preservation from canon creation, repository update approval, and owner decision requirement.

Candidate model implication:

The decision system should not turn every uncertain detail into a user decision. It should preserve fragile details non-blockingly unless the uncertainty blocks identity extraction, canon classification, repository update, contradiction resolution, phase acceptance, or owner-only interpretation.

### 9. Root-Cause Fixes Beat Surface Patches

Campaign Archive and Campaign Project Development repeatedly distinguish fixing the visible symptom from tracing the shared path that produced the problem.

Candidate model implication:

Add a root-cause confidence field:

- symptom patched
- local cause identified
- shared mechanism traced
- durable repair path known
- verification path matches user-facing dependency

### 10. Stop Or Reset Can Be A Valid Decision

The V1 death spiral record is important: continuing to patch a failing lane can be worse than pausing, preserving lessons, and resuming from a clearer architecture.

Candidate model implication:

The system should identify "continue", "pause", "reset", "archive", and "extract lessons" as decision outcomes, not treat continuation as the default good.

### 11. Durable Decision Records Matter

Several projects preserve owner-selected commands, effect, boundary, result, and next valid resume point. This creates continuity and avoids forcing the user to re-explain settled context.

Candidate model implication:

The decision profile should prefer records that capture:

- decision
- source/user direction
- rationale or observed context
- effect
- boundary
- promotion state
- next real decision

### 12. Candidate-Level Approval Beats All-Or-Nothing Approval

Campaign Project Development shows a specific pattern where reward/karma/loot review needed candidate-level decisions rather than a single bulk approval.

Candidate model implication:

The system should detect when a decision bundle contains separable candidates and recommend item-level approval instead of all-or-nothing approval.

## Candidate Matrix / Profile Updates

The strongest candidates are recorded separately in:

```text
C:\DECISION_INTELLIGENCE_SYSTEM\reports\decision-profile-candidate-updates-2026-07-06.md
```

## Scan-Derived Note

The required project note from this scan is recorded in:

```text
C:\DECISION_INTELLIGENCE_SYSTEM\reports\registry-decision-pattern-sweep-note-2026-07-06.md
```

## Promotion Status

This sweep creates candidate guidance only.

It does not modify `DECISION_MODEL.md`.

It does not promote the Decision Context Layer Draft into final standard.

It does not adopt any other project's guidance as Decision Intelligence authority.
