# Decision Intelligence System

The Decision Intelligence System is a reusable framework for structured,
evidence-based decision making.

It exists to support decisions that require observation, evidence collection,
scoring, comparison, recommendation, monitoring, and re-evaluation.

Procurement is the first application domain, not the whole project.

## Core Loop

The reusable decision loop is:

```text
Observe
Collect Evidence
Score
Compare
Recommend
Monitor
Re-evaluate
```

## Purpose

The system helps evaluate complex choices by separating:

- the reusable decision process
- the domain-specific scoring model
- the evidence collected for a specific case
- the recommendation and reporting output

## Initial Module

The first module is Technology Procurement.

The first decision case is the primary development workstation for the Crucible
Registry ecosystem.

## Boundary

The Decision Intelligence System owns the reusable decision framework and the
domain models that apply it.

It does not own the Crucible Registry.

It does not own the independent repositories whose needs may be evaluated by
the system.

It may support decisions for other projects without becoming the authority over
those projects.

## Current Status

First worked case in post-order follow-up.

The Technology Procurement module has produced its first workstation decision
case. The GEEKOM IT15 has been ordered, paid for, and processed. The project is
now tracking delivery, setup, validation, and acceptance.

The next system-level task is to test whether the workstation case can be used
to extract reusable decision templates and support at least one additional
bounded decision case.
