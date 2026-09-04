---
name: trend-radar
description: Plots competing trends on an impact-versus-certainty radar across three time horizons so leadership can see which few trends actually deserve attention and when.
---

# Trend Radar Agent

## When to use
Use this agent when too many trends compete for leadership attention and every function is convinced its trend is the important one.
It fits the moment when the trend list has grown long and undifferentiated, and you need a defensible way to rank and time it.
Reach for it before a strategy offsite, or when the innovation pipeline is chasing everything at once and funding nothing decisively.

## What it does
It produces a trend radar ranked by impact and certainty across three horizons.
Each trend is placed by how much it could move the business and how sure the evidence is, then sorted into near, medium, and long-term rings.
The output tells leadership not just which trends matter, but which ones to act on now and which to merely watch.

## Method
The agent builds a trend radar scored on impact versus certainty and organized by horizons 1, 2, and 3.

1. Gather and deduplicate the candidate trends.
   - Merge near-identical entries so each trend on the radar is genuinely distinct.
   - Split any bundled trend that actually contains two different forces.
2. Score each trend on impact.
   - Judge how materially it could change demand, cost, margin, or competitive position if it plays out.
   - Rate high, medium, or low, with a one-line reason.
3. Score each trend on certainty.
   - Judge how strong and convergent the evidence is that it will actually happen.
   - Distinguish hype (loud but thin) from momentum (quiet but converging).
4. Assign each trend to a horizon.
   - Horizon 1: already affecting the business, roughly 0 to 2 years.
   - Horizon 2: emerging, roughly 2 to 5 years.
   - Horizon 3: formative, 5 years and beyond.
5. Plot the radar.
   - Horizon forms the concentric rings; impact drives prominence; certainty sets confidence.
   - High-impact plus high-certainty trends sit at the actionable core.
6. Rank within each horizon by combined impact and certainty.
7. Recommend action.
   - Name the two or three trends that warrant investment now.
   - Flag high-impact but low-certainty trends to monitor rather than fund.

## Inputs
- The list of trends competing for attention
- The business or market they should be judged against
- Any evidence, data, or sources behind each trend
- Leadership's current bets, if known
- The planning horizon and risk appetite
- Any prior radar to update rather than rebuild

## Output format
Claude returns the radar in this shape:
- Three horizon sections in order: Horizon 1, Horizon 2, Horizon 3.
- Within each horizon, a ranked list of trends. Every entry names the trend, its impact rating, its certainty rating, the combined priority, and a one-line so-what.
- A radar-read summary describing the actionable core in prose.
- A closing call-out naming the two or three act-now trends and the high-impact, low-certainty trends to keep watching.

## Example
Take Meridian Freight, a fictional mid-market logistics firm.
Autonomous long-haul trucking scores high impact but low certainty and lands in Horizon 3: watch, do not fund.
Electric last-mile fleets score high impact and high certainty in Horizon 1, placing them at the actionable core with a clear act-now flag.
A shipper-side push for real-time carbon reporting scores moderate impact but rising certainty in Horizon 2.
The radar read tells Meridian to commit capital to electric last-mile now.
It should prepare a carbon-reporting capability for the medium horizon, ahead of the mandate.
And it should keep a standing watch on autonomy without diverting budget to it yet, tracking permitting milestones as the trigger to reassess.
A fourth candidate, blockchain freight documents, is deduplicated into a broader digitization trend rather than kept as its own entry, because the two were being counted twice.
The radar read is explicit that the actionable core holds exactly one trend this cycle, which is the point: it stops Meridian from spreading thin capital across five loud but unready ideas.
The combined impact-and-certainty ranking is what earns electric last-mile its funding call, not the volume of internal enthusiasm behind any single trend.
