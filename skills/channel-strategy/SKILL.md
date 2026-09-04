---
name: channel-strategy
description: Designs the right route-to-market and channel mix to reach and serve buyers, with the economics that prove each route pays. Use when you are choosing how to sell and deliver, not what to sell.
---

# Channel Strategy Agent

## When to use
Use this when you need the right route to reach and serve buyers and the current mix feels accidental rather than chosen. It fits moments when direct, partner, and marketplace routes all look plausible and leadership wants the economics before committing coverage or headcount. Reach for it before you hire a sales team or sign a distributor.

## What it does
It produces a channel mix with the economics and coverage logic behind each route, so you can see which channels reach which segments at what cost, and where the mix leaks margin or leaves demand unserved.

## Method
This agent runs a route-to-market and channel-economics analysis.

1. Map the buying journey for each priority segment.
   - Trace how they discover, evaluate, buy, and get served.
   - Mark where a human, a partner, or self-serve is genuinely required versus merely traditional.
2. List every candidate route and match it to segments.
   - Cover direct field sales, inside sales, self-serve, resellers, distributors, marketplaces, and embedded or OEM.
   - Assign each route to the segments whose journey it actually fits.
3. Build channel economics per route.
   - Estimate cost to acquire and cost to serve for each route.
   - Compare against average deal size and gross margin after channel margin or commission.
   - Compute a rough contribution per route so weak routes surface.
4. Assess coverage.
   - Estimate what share of each target segment a route can realistically reach.
   - Flag where routes overlap and where they leave white space.
5. Check for channel conflict.
   - Flag where two routes chase the same buyer.
   - Note where partner margin cannibalizes direct and where pricing must differ by route.
6. Recommend the mix.
   - Name the primary route per segment, the secondary routes, and the routes to retire.
   - State the coverage gained and the contribution trade-off behind each call.
7. Name the enablement each chosen route needs.
   - Specify incentives, tooling, and terms.
   - Attach the one metric that proves the route is working.

## Inputs
- Priority customer segments and their rough size
- Average deal size, sales cycle, and gross margin per segment
- Current channels in use and any known cost or performance data
- Partner or distributor terms already in place, if any
- Constraints on budget, headcount, or geography

## Output format
Claude returns a memo in four named sections:
- Segment Journeys: one short paragraph per segment naming the route each stage requires.
- Channel Economics: ranked route cards written as prose, each naming the route, the segments it serves, cost to acquire, cost to serve, contribution, and reachable coverage.
- Conflict and Overlap: the flagged clashes and how to price or fence around them.
- Recommended Mix: the primary and secondary route per segment, routes to retire, and the enablement and metric for each.

## Example
For Northwind Freight Tools, a fictional maker of fleet-maintenance software, the agent maps three segments. Owner-operators buy self-serve after a free trial, so cost to acquire is low and self-serve wins. Regional fleets of ten to fifty trucks evaluate with a human and buy on a demo, so inside sales carries the best contribution once cost to serve is netted out. National fleets need field sales and a proof of concept, expensive but justified by deal size.

The agent flags that a proposed reseller route would undercut inside sales on regional fleets, and recommends fencing resellers to markets with no Northwind coverage. Recommended mix: self-serve for owner-operators, inside sales for regional, field sales for national, resellers only in uncovered territories, tracked by contribution per route per quarter.

A sample channel economics card reads:
- Route: Inside sales.
- Serves: Regional fleets, ten to fifty trucks.
- Cost to acquire: moderate, one rep touch over a two-week cycle.
- Cost to serve: low after onboarding.
- Contribution: highest of the three routes once channel margin is netted out.
- Coverage: roughly two-thirds of the regional segment reachable with current headcount.
