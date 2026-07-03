# Core Decision Model

Status:

```text
Reusable project standard
```

The Decision Intelligence System uses a reusable decision loop across modules.

```text
Observe
Collect Evidence
Score
Compare
Recommend
Monitor
Re-evaluate
```

## 1. Observe

Define the decision question, context, authority boundary, known constraints,
and the real work the decision must support.

Observation should clarify:

- what is being decided
- who or what the decision affects
- what authority the system has
- what authority remains outside the system
- what constraints are already known
- what would make the decision successful

## 2. Collect Evidence

Collect evidence before making recommendations.

Evidence should be structured enough to be reviewed later.

Evidence may include:

- requirements
- candidate options
- specifications
- prices
- promotions
- historical pricing
- availability
- external reviews
- benchmarks
- warranty and return terms
- risks
- unknowns

Every evidence record should include source and collection date when possible.

## 3. Score

Score options using the domain-specific scoring model.

The core model does not impose one universal scoring schema.

Scoring should separate:

- mandatory gates
- weighted preferences
- evidence strength
- risk flags
- unknowns
- total score or readiness score

Unknowns should be visible and should not be silently treated as neutral.

## 4. Compare

Compare options side by side before recommending.

Comparison should show:

- strengths
- weaknesses
- completed cost or full impact
- accepted tradeoffs
- rejected tradeoffs
- category winners where relevant

## 5. Recommend

Produce a recommendation that is reviewable.

A recommendation should include:

- selected option or deferral
- rationale
- confidence
- accepted tradeoffs
- rejection rationale for alternatives
- conditions that would change the recommendation

## 6. Monitor

Some decisions remain live after recommendation.

Monitor when the evidence can change materially after the initial decision.

Monitoring may track:

- price
- availability
- risk
- requirements
- lifecycle
- vendor or product changes
- new alternatives

## 7. Re-evaluate

Re-evaluate when monitoring triggers fire or when the scheduled review cadence
arrives.

Re-evaluation should preserve prior reports so changes are visible over time.

## Required Decision Record Parts

Every decision case should eventually have:

- decision question
- authority boundary
- requirements
- evidence records
- scoring or comparison method
- recommendation output
- monitoring or re-evaluation plan

