---
name: ecosystem-mapping
description: Maps the value network around your firm, its roles, flows, and control points, so you can see where value is created and captured across players. Use when value depends on many players, not one company.
---

# Ecosystem Mapping Agent

## When to use
Use this when value is created across players rather than by one firm, and you cannot see the whole board. It fits platforms, marketplaces, and multi-sided models where suppliers, complementors, channels, and customers all shape outcomes. Reach for it when you suspect the real leverage sits at a control point you do not yet hold.

## What it does
It produces an ecosystem map of roles, value flows, and control points, showing who does what, how value and money move between them, and where the choke points and bottlenecks that decide power actually sit.

## Method
This agent runs a value-network and ecosystem-mapping analysis.

1. Name the participant roles.
   - Cover your firm, customers, suppliers, complementors, channels, platforms, standard-setters, and any orchestrator.
   - Keep roles distinct from named companies so the structure stays legible.
2. Trace the flows between roles.
   - Product and service flows.
   - Money flows.
   - Information or data flows, with direction and rough magnitude for each.
3. Identify where value is created.
   - Mark the activities and combinations that make the whole worth more than the parts.
4. Identify where value is captured.
   - Locate the margin pools.
   - Name the roles that hold pricing power.
5. Find the control points.
   - Spot the assets, standards, data, or relationships that let a role tax, gate, or steer the network.
   - Note who holds each control point and how contested it is.
6. Assess your position.
   - State the roles you play and the control points you hold or could reach.
   - Name the dependencies that expose you.
7. Recommend moves.
   - Control points to build toward.
   - Roles to add or shed, and complementors to court or defend.

## Inputs
- Your firm's current role and activities
- Known suppliers, complementors, channels, and customer types
- How money flows today and where you see the biggest margins
- Any platform, standard, or data asset in play
- Where you feel dependent or blocked

## Output format
Claude returns a mapped analysis in prose:
- Roles: a labeled list of participant roles with a one-line function each.
- Flows: product, money, and information flows between roles with direction and rough size.
- Value Creation and Capture: where worth is made and where it is captured, naming the margin-holding roles.
- Control Points: each choke point, who holds it, and how contested it is.
- Your Position and Moves: your current roles, exposures, and a short ranked set of moves toward stronger control points.

## Example
For Harvest Ledger, a fictional farm-to-restaurant produce platform, the agent names roles: growers, the platform, logistics carriers, restaurants, and a payments provider. Product flows from growers through carriers to restaurants; money flows back through the platform, which takes a fee; data on demand and quality flows to the platform and nowhere else.

Value is created by matching surplus produce to demand; value is captured mostly by the platform fee and, quietly, by the payments provider. The key control point is the demand data, which the platform holds but has not exploited. The recommended moves: turn demand data into grower forecasting to lock in supply, and bring payments in-house to stop margin leaking to the provider.

A sample control-point entry reads:
- Control point: aggregated restaurant demand data.
- Held by: the platform, exclusively.
- Contested: low today, but a large distributor could replicate it at scale.
- Leverage: it can steer growers, price dynamically, and lock supply if productized.
- Move: build grower forecasting on it before a rival closes the gap.
