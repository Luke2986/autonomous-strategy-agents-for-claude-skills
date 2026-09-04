---
name: esg-strategy
description: Frames an ESG strategy using double materiality so commitments cohere, use it when ESG pledges exist but lack a strategy and metrics.
---

# ESG Strategy Agent

## When to use
Use this agent when ESG commitments have piled up without a coherent strategy behind them, or when the business must show both how ESG issues affect it and how it affects the world. It fits the run-up to a reporting cycle, a rating review, or an investor conversation where scattered pledges need to become a defensible framework. Reach for it when you need priorities, targets, and metrics that hold together.

## What it does
It produces an ESG framework: the priority topics seen through both directions of materiality, the commitments and time-bound targets attached to each, and the metrics that make progress measurable. It separates the topics that affect the business from the topics the business affects, then unites them into one set of priorities with clear ownership.

## Method
The agent runs a double-materiality ESG framing.

1. **List candidate topics by pillar.** Assemble ESG topics across environmental, social, and governance pillars for the sector and value chain.
2. **Assess financial materiality (outside-in).** Rate how each topic affects the company's own value:
   - Revenue and market access.
   - Cost, operational risk, and asset exposure.
   - Cost of capital and financing conditions.
3. **Assess impact materiality (inside-out).** Rate how the company's activities affect people and the environment, from emissions and resource use to labor and community effects.
4. **Combine the two views.** Let a topic material on either axis earn a place, and let topics material on both rise to the top of the priority set.
5. **Set commitments and targets.** For each priority topic, define a specific, time-bound, owned target rather than a vague aspiration.
6. **Define metrics.** For each target, name the measures and their data source, separating:
   - Outcome metrics that prove real progress.
   - Activity metrics that show effort is under way.
7. **Add governance.** Assign an owner to each pillar and set the cadence at which progress is reviewed and reported.

## Inputs
- The business, sector, and value chain
- Existing ESG commitments, ratings, or disclosures
- Applicable reporting frameworks or regulatory requirements
- Any investor or stakeholder expectations already voiced

## Output format
Claude returns an ESG framework in named sections:
- **Topics by Pillar:** the candidate set organized across E, S, and G.
- **Double-Materiality Assessment:** each topic with its financial-materiality and impact-materiality reads, in prose.
- **Priorities:** topics material on one or both axes.
- **Commitments and Targets:** each priority paired with a time-bound goal and owner.
- **Metrics:** the outcome and activity measures with data sources.
- **Governance:** pillar ownership and review cadence.

Keep all scoring in prose.

## Example
For Harbor Logistics, an illustrative regional freight operator, the agent finds fleet emissions material on both axes: financially through fuel cost and tightening low-emission-zone rules, and by impact through air quality in the cities it serves. Driver safety scores high on impact materiality; data privacy scores high on financial materiality through contract risk.

Emissions becomes the anchor priority with a target to cut fleet carbon intensity 25 percent over five years, owned by the operations lead. The outcome metric is grams of carbon per ton-kilometer drawn from telematics data, backed by an activity metric of electric-vehicle share of new purchases. Governance puts the operations lead over the environmental pillar with a quarterly review feeding the board.
