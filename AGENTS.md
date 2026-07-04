# Decision Intelligence System Project Guidance

## Crucible Registry Inheritance

This project is organized by the Crucible Registry.

Before acting, check the applicable project guidance and use the Crucible
Ecosystem Operating Standards as inherited default behavior unless this local
project guidance explicitly overrides or specializes them.

Inherited defaults include:

- work from meaningful decision point to meaningful decision point
- do not create micro-approval loops
- continue through safe implied work inside an approved lane
- stop only at real decision, authority, source-modification, or safety
  boundaries
- provide a concrete next action or real pause boundary in closeouts
- when user approval or direction is needed, provide short, separate,
  copyable `ADD TO CHAT` blocks; each block must contain one action only and
  must include the expected output
- when the user asks for a generated artifact or content output, provide the
  artifact itself in the appropriate readable or copyable format, not an `ADD
  TO CHAT` approval block
- keep project substance inside the owning project
- preserve local project authority and local overrides
- treat the C drive as the default source of truth for durable project files
  until another source of truth is explicitly identified; treat OneDrive,
  sync folders, mirrors, and interface folders as copies only
- when the user says `establish waypoint` or `create a waypoint`, follow the
  Registry Project Waypoint Synchronization Rule, including current Registry
  guidance review, inherited-guidance refresh, local state review, commit, push
  to GitHub when connected, alignment confirmation, and notation of any
  intentionally unfinished work
- protect user files from unapproved move, rename, delete, merge, overwrite,
  cleanup, or restructure operations

Local project guidance controls when it is more specific.

## Ecosystem Standards Inheritance

This project participates in a pilot of the Crucible Ecosystem Operating
Standards.

It inherits the ecosystem standards for:

- working to real decision points
- avoiding micro-approval loops
- providing next-step outputs at real pause points
- preserving durable project authority in project files
- treating C-drive project files as the durable authority
- preserving project autonomy
- using evidence before authority
- marking incompleteness before authority
- classifying before action
- protecting user files and source projects
- preferring root-cause repair
- separating human-facing output from internal mechanics
- parking future work without displacing active work

Local project guidance controls all Decision Intelligence System-specific
behavior, including decision architecture, module boundaries, scoring models,
procurement report format, workstation candidate criteria, monitoring cadence,
final recommendation boundaries, and purchase-related pauses.

This pilot does not make draft ecosystem standards final governance.

## Working Style

Move from meaningful decision point to meaningful decision point.

Do not require the user to ask "what's next" after every completed step.

The purpose of project guidance is to reduce user supervision, not to require
the user to approve every minor working artifact.

Continue through routine project work when the direction is already established.

Do not stop merely to ask approval for creating or updating templates, checklists,
drafts, evidence records, scoring drafts, candidate boards, notes, interim
reports, or other non-destructive working files that clearly support the active
case or module.

When a step is completed, continue to the next useful step unless a real user
decision is needed.

## Project Waypoint Synchronization

This project inherits the Crucible Registry Project Waypoint Synchronization
Rule.

When the user says "establish waypoint" or "create a waypoint":

- Recheck current Registry-provided guidance.
- Refresh the local Registry inheritance block if the approved Registry block
  has changed.
- Review changed files.
- Confirm the waypoint aligns with the active objective, authority boundary, and
  next real decision point.
- Record intentionally unfinished work, open unknowns, and next triggers.
- Commit meaningful completed work.
- Push to GitHub if the repository is connected to a GitHub remote.
- Stop only after the local and remote project state are synchronized, or after
  clearly recording the blocker that prevents synchronization.

## Project Boundary

The Decision Intelligence System owns the reusable decision framework and
domain-specific decision modules.

It supports decisions for other projects, but it does not become the authority
over those projects.

## Registry-Scoped Decision Discovery

The Decision Intelligence System should not begin by inventing a full decision
model from theory alone.

Its first expansion behavior is evidence gathering from the Crucible Registry.

When the user says `scan`, `update`, or `look for decisions` in the context of
this project, interpret that as a registry-scoped decision discovery request.

For that request:

- use `C:\CRUCIBLE_REGISTRY` as the registry authority boundary
- inspect registry entries and registry-approved project authority references
- identify project files updated since the last Decision Intelligence System
  scan, when a prior scan record exists
- look for decisions made inside those projects
- look for context showing how those decisions were made
- extract decision-process evidence, not project substance for its own sake
- record findings only inside `C:\DECISION_INTELLIGENCE_SYSTEM`
- do not modify the Crucible Registry or any source project unless the user
  explicitly approves that separate modification

Decision discovery should classify findings as:

- explicit decision
- implied decision
- decision rationale
- criteria or values used
- tradeoff accepted
- option rejected
- authority or boundary decision
- unresolved decision
- missing decision context

When updated files do not contain enough decision context, generate
case-specific questions that would help refine the Decision Intelligence model.
Questions should be tied to the observed project, file, decision area, or
missing rationale. Do not ask generic questions merely to fill a template.

Registry-scoped decision discovery may produce:

- scan records
- decision evidence extracts
- case-specific question lists
- model-refinement notes
- recommendations for what decision pattern may be emerging

Every Decision Intelligence scan must create a scan-derived note inside
`C:\DECISION_INTELLIGENCE_SYSTEM`.

The scan record preserves what was inspected and what was found. The note
preserves what the scan means for the project.

Scan-derived notes should capture:

- durable implications for the Decision Intelligence model
- candidate fields, patterns, or distinctions suggested by evidence
- case-specific questions raised by missing decision context
- risks of over-generalizing project-local rules
- any recommended next model-refinement action

Scan-derived notes are working notes. They do not update the core model,
project standards, Registry entries, or source projects unless the user later
approves that separate promotion or modification.

These outputs are working evidence, not final governance.

The Decision Intelligence System may use the registry to discover where
decision evidence lives, but it must not absorb authority from the registry or
from the projects described by the registry.

## Architecture Guidance

Preserve the distinction between:

- core decision model
- domain module
- decision case
- evidence record
- scoring model
- recommendation output
- monitoring or re-evaluation plan

Procurement is the first module, not the whole system.

## Pause Points

Pause when:

- budget targets or hard constraints would change
- core requirements would change
- project authority or ownership boundaries are unclear
- a recommendation would become final
- a purchase, order, vendor contact, account action, or external commitment would
  be made
- existing user files would be moved, copied, renamed, deleted, merged,
  overwritten, cleaned up, or restructured
- a source repository or project outside the approved project boundary would be
  modified
- a contradiction, missing input, or blocker prevents responsible continuation

Do not pause merely because:

- a template is needed
- a checklist is needed
- an evidence format is needed
- a scoring draft is needed
- a candidate comparison is needed
- market research needs to be recorded
- an interim report should be produced
- a working folder is needed inside the approved project boundary

## Standing Working Authority

Within `C:\Decision_Intelligence_System`, Codex may create and update
non-destructive working files and folders needed to advance the active Decision
Intelligence System work.

This includes:

- core model drafts
- module notes
- case files
- evidence templates
- evidence records
- scoring drafts
- candidate comparisons
- market snapshots
- interim reports
- monitoring notes

Codex should keep these artifacts clearly labeled as drafts, working records, or
interim outputs until the user approves a final recommendation or reusable
standard.

## Workstation Procurement Report Rule

For the Primary Development Workstation case, user-facing market outputs should
follow the procurement report format from
`Development_Workstation_Advisor_v1.0_Bootstrap.md`.

Do not substitute a loose shortlist, shopping board, or link list when the user
is asking to evaluate workstation candidates.

Every workstation procurement report should contain:

1. Executive Summary
2. Purchase Readiness Score from 0 to 100
3. Current Market Summary
4. Current Price Snapshot
5. Top 10 Overall Recommendations
6. Category Rankings
7. Category Winners
8. Active Promotions
9. Historical Pricing
10. Incremental Value Analysis
11. Procurement Decision

For every candidate in the current price snapshot, include:

- clickable product link built into the candidate name
- current price
- typical price
- historical low
- current promotion
- coupon availability
- ready-to-use status
- required upgrades
- estimated completed cost
- time to productivity

Every procurement decision should end with:

- Buy Now or Wait
- Why
- confidence
- rationale

If evidence is incomplete, produce the report anyway and mark unknowns clearly.
Unknowns are work items, not a reason to abandon the required report format.

## Workstation Report Cadence

During an active workstation procurement case, maintain the following default
cadence unless the user changes it:

- Weekly procurement report refresh.
- Same-day refresh when a major price drop, promotion, stock change, or new
  clearly superior candidate appears.
- Same-day refresh when the user changes requirements, budget, or constraints.
- Final recommendation refresh immediately before any purchase decision.

Weekly reports should update:

- purchase readiness score
- current market summary
- current price snapshot
- top 10 recommendations
- category rankings and winners
- active promotions
- historical pricing notes
- incremental value analysis
- Buy Now or Wait decision

Do not wait for the user to ask "what is next" during active procurement
monitoring.

## Workstation Candidate Evaluation Rules

For workstation procurement, evaluate against the bootstrap criteria:

- preferred completed system cost around $1,000
- normal hard target of $1,500
- exceptional candidate visibility up to $2,000 when a candidate is materially
  better and the added cost is explicitly justified
- Windows 11 Pro
- 64 GB RAM preferred
- 2 TB NVMe preferred, but 1 TB NVMe is acceptable at purchase when the system
  has a clear, low-risk upgrade path to 2 TB or more
- Intel Core Ultra 5, Intel Core i5 or better, AMD Ryzen 5 or better
- Core Ultra 7, Ryzen 7, or Ryzen 9 preferred when value justifies
- Wi-Fi 7 preferred
- Wi-Fi 6E acceptable
- excellent real-world wireless
- easy maintenance
- ready-to-use productivity
- workflow fit for ChatGPT, Codex, VS Code, GitHub, Markdown repositories, and
  Microsoft Office
- reliability target of 4-5 years as a fast, stable primary development
  workstation, with 3 years as the minimum acceptable expected useful life
- total ownership value
- reasonable future flexibility

Upgradeable systems remain eligible, but every upgradeable candidate must state:

- required upgrades
- upgrade cost
- upgrade difficulty
- upgrade time
- whether upgrades are justified
- estimated completed cost
- time to productivity

Do not treat a low base price as a final value score until completed cost and
time to productivity are visible.

Do not reject an otherwise strong candidate solely because it ships with 1 TB
storage if it has an easy, low-risk path to 2 TB or more. Treat 512 GB as too
tight unless explicitly temporary.

Do not overbuy only to chase a 7-10 year lifespan. Prefer a machine that should
remain fast and stable for 4-5 years, with upgrade paths that can extend useful
life if the market and workload justify it.

Do not let the search balloon upward just because higher-priced options exist.
Candidates above $1,500 should be shown only as explicit exceptions, not normal
recommendations. Any candidate above $1,500 must state why it is worth seeing,
what extra value it buys, and what lower-cost candidate it beats. Candidates
above $2,000 are out of scope unless the user explicitly changes the budget.

## Workstation Report Depth

When the user asks to see candidates, prefer a procurement report or report
excerpt over a loose link list.

When the user wants a quick view, show the top candidates from the report, but
retain report fields: price, completed cost, readiness, upgrades, promotion
status, and Buy Now or Wait posture.

Candidate names in user-facing reports should be clickable product links
wherever a product page is known. Do not bury all links in a sources section.

## Required Output At Real Decision Points

When a real decision point is reached, provide:

- what was completed
- what decision is needed
- the recommended next action
- 2-4 concrete options
- the expected output of each option
