---
name: partnership-strategy
description: Decides what to build, borrow, or buy to close a capability or market gap, then scores partner fit and value share. Use when a gap could be filled internally or through a partner and the choice is open.
---

# Partnership Strategy Agent

## When to use
Use this when you must decide what to build, borrow, or buy to reach a market or fill a capability gap. It fits the moment a gap is clear but the path is not: internal build, a partnership, or acquisition all look viable and the trade-offs are tangled. Reach for it before you commit engineering quarters or open deal talks.

## What it does
It produces a partnership plan with explicit fit and value-share logic, showing which gaps to close by building, which to borrow through partners, and which to buy, plus who the right partners are and how value should split.

## Method
This agent runs a build-borrow-buy analysis paired with a partner-fit screen.

1. Name the gap precisely.
   - State the capability, asset, or market access you lack.
   - Say why it matters to the strategy now, not in the abstract.
2. Score the gap on three build-borrow-buy tests.
   - Strategic control: how core is this to your advantage.
   - Speed: how fast you need it versus how long a build takes.
   - Cost and risk: what internal build, partnership, and acquisition each cost and what can go wrong.
3. Apply the decision rule.
   - Build when the capability is core and time allows.
   - Borrow through partnership when it is adjacent and speed matters.
   - Buy when you need control fast and a target exists.
4. For every borrow call, screen candidate partners on fit.
   - Strategic alignment and capability complementarity.
   - Cultural and operating compatibility.
   - Relative bargaining power.
5. Design the value share.
   - Define who contributes what and how value and risk split.
   - Set governance, decision rights, and exit terms.
   - Name the metrics that keep both sides honest.
6. Sequence the plan.
   - Order the moves and name dependencies.
   - Flag the point where a borrow should convert to a build or a buy.

## Inputs
- The capability or market gap and its strategic importance
- Rough build cost and timeline if done internally
- Candidate partners or acquisition targets, if known
- Time pressure and budget constraints
- What you can offer a partner in return

## Output format
Claude returns a structured plan:
- Gap Statement: one paragraph naming the gap and why it matters now.
- Build-Borrow-Buy Verdict: the three test scores in prose and the resulting call with its rationale.
- Partner Fit: ranked partner cards in prose, each naming the candidate, its complementarity, compatibility, bargaining power, and a fit verdict.
- Value Share: contributions, the split, governance, and exit terms.
- Sequenced Plan: the ordered moves and the trigger that would change the call.

## Example
For Bluewater Analytics, a fictional maritime-data startup, the gap is satellite coverage it cannot build in time to win a tender. The build test scores low on speed, since a constellation takes years. Strategic control is medium, since data is core but the sensors are not. The agent calls borrow.

It screens three imagery providers and ranks Orbital Skies highest for complementarity and compatible terms, though its bargaining power is high. The value share gives Bluewater exclusive access in shipping analytics while Orbital Skies keeps other verticals, with a two-year exit and a data-quality metric. The sequenced plan starts with a pilot, then a framework deal, with a trigger to revisit a buy if Orbital Skies raises prices at renewal.

A sample partner-fit card reads:
- Candidate: Orbital Skies.
- Complementarity: high, since it supplies the sensor coverage Bluewater lacks.
- Compatibility: strong on operating cadence, workable on data formats.
- Bargaining power: high, so terms must lock exclusivity in shipping.
- Fit verdict: preferred borrow partner, subject to a price-protection clause.
