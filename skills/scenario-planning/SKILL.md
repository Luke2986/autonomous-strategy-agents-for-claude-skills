---
name: scenario-planning
description: Builds four named futures on a two-axis scenario matrix with early-warning signposts so strategy can be stress-tested against uncertainty instead of a single forecast.
---

# Scenario Planning Agent

## When to use
Use this agent when the future is uncertain and one forecast is not enough to plan on.
It fits high-stakes, long-horizon decisions where the key uncertainties are structural, not just noisy.
Reach for it when leadership is betting the plan on a single view of how the world unfolds and wants to know how the strategy holds up if that view is wrong.

## What it does
It produces four named scenarios on a two-axis matrix with signposts.
These are four distinct, plausible futures built from the two most important uncertainties, each with early indicators that tell you which world is arriving.
The point is not to predict, but to build a strategy that survives across all four.

## Method
The agent builds a two-by-two scenario matrix with early indicators.

1. Frame the focal decision.
   - State the specific choice or plan the scenarios must inform, so the exercise stays decision-driven.
2. List the critical uncertainties.
   - Surface the forces that are both highly impactful and genuinely uncertain.
   - Set aside the impactful-but-predictable trends as givens that hold in every scenario.
3. Choose the two axes.
   - Pick the two uncertainties that are most important and most independent of each other.
   - Define each as a spectrum with two clear poles.
4. Build the four quadrants.
   - Cross the axes to create four futures.
   - Give each a vivid, memorable name that captures its internal logic.
5. Write each scenario as a coherent narrative.
   - Describe how the world got there and what it means for demand, competition, and the focal decision.
6. Define signposts.
   - For each scenario, name the early indicators and leading metrics that would signal this world is materializing.
7. Stress-test the strategy.
   - Identify no-regret moves that work across all four scenarios.
   - Identify contingent bets that only pay off in one, and the trigger to commit to each.

## Inputs
- The focal decision or plan the scenarios must inform
- The time horizon
- Known uncertainties, trends, or forces at play
- The current strategy, to test for robustness
- Any constraints that hold regardless of scenario
- The decisions that cannot wait for certainty

## Output format
Claude returns the scenarios in this shape:
- The two chosen axes, each defined by its two poles.
- Four named scenario sections. Each gives a short narrative, its implications for the focal decision, and a bulleted list of signposts to monitor.
- A robustness section naming the no-regret moves that hold across all four futures.
- A contingent-bets section listing bets tied to a single scenario, each with the signpost that would trigger it, written as prose.

## Example
Take Solstice Energy, a fictional regional utility.
The two axes are pace of electrification (slow to fast) and regulatory posture (restrictive to enabling).
Crossing them yields four futures, including "Grid Rush" (fast electrification, enabling regulation) where demand for capacity surges, and "Held Back" (fast electrification, restrictive regulation) where demand exists but build-out stalls.
Signposts for Grid Rush include EV registration curves steepening and permitting timelines shortening.
The no-regret move across all four futures: invest in grid-flexibility software, which pays off whether build-out is fast or blocked.
A contingent bet on large new generation is reserved for the enabling-regulation worlds only, triggered when permitting timelines drop below a set threshold.
The other two futures are "Slow Grind" (slow electrification, restrictive regulation), where legacy demand persists and cost discipline wins, and "Managed Shift" (slow electrification, enabling regulation), where the utility has time to modernize deliberately.
Naming all four forces leadership to plan for the worlds it would rather ignore, not just the one it hopes for.
Solstice leaves the exercise with one no-regret investment funded now and a clear set of signposts that will tell it, within a year, which of the four worlds it is actually entering.
