---
name: geographic-expansion
description: Ranks candidate markets by attractiveness and distance from home using a market attractiveness index and CAGE distance, so you enter in the right order. Use when choosing which geographies to enter first.
---

# Geographic Expansion Agent

## When to use
Use this when you are choosing which markets to enter first and a long list of countries or regions needs a disciplined ranking. It fits the moment ambition outruns capacity and you must sequence, not scatter. Reach for it before committing to a market on gut feel or on where a founder happens to have contacts.

## What it does
It produces a ranked market shortlist scored on both attractiveness and distance from your home base, so the order of entry reflects real opportunity net of the friction each market imposes.

## Method
This agent runs a market attractiveness index paired with a CAGE distance analysis.

1. Define the candidate set.
   - Fix the countries or regions in scope.
   - Fix the home base you will measure distance from.
2. Build the market attractiveness index.
   - Choose weighted factors that fit your business: market size, growth, willingness to pay, competitive intensity, ease of doing business, and regulatory openness.
   - Score each market and weight to a single attractiveness figure.
3. Score CAGE distance from home for each market.
   - Cultural: language, values, and trust norms.
   - Administrative: shared history, trade agreements, legal and political ties.
   - Geographic: physical distance, logistics, and time zones.
   - Economic: income levels, cost structures, and infrastructure.
4. Convert distance into friction.
   - Treat high distance as a discount on raw attractiveness, since it raises cost to serve and slows traction.
5. Plot attractiveness against distance.
   - Attractive and close markets are first movers.
   - Attractive but distant markets need a heavier entry model.
   - Close but unattractive markets are parked.
6. Rank and sequence the shortlist.
   - Order markets and name, for each, the one distance dimension that most shapes how to enter.
7. Flag the fragile assumptions.
   - Name the inputs most likely to reorder the ranking so leadership knows what to watch.

## Inputs
- The list of candidate markets and your home base
- What matters most to your economics (size, growth, margin, or speed)
- Any market data you already hold on size, growth, or competition
- Product or operational constraints that travel badly across borders
- Appetite for risk and investment horizon

## Output format
Claude returns a ranked analysis:
- Index Design: the chosen factors and weights in prose.
- Market Scorecards: one card per market describing its attractiveness score, its CAGE distance across the four dimensions, and the friction-adjusted verdict.
- Ranked Shortlist: markets ordered first to last with a one-line reason each.
- Entry Sequence: the order, the dominant distance dimension per market, and the assumptions to monitor.

## Example
For Solaria Kettles, a fictional premium-appliance brand based in Germany, the agent scores six markets. Austria and the Netherlands rank first: attractive enough and low on every CAGE dimension, so a light distributor entry works. The United States scores highest on attractiveness but carries large economic and administrative distance, so it needs a heavier, later entry with local support and certification.

Japan is attractive but culturally distant, flagging that product presentation and retail relationships, not price, will decide traction. The sequence is Austria and the Netherlands now, the United States in year two with a dedicated team, Japan piloted through a local partner, with the euro-dollar rate flagged as the assumption most likely to reorder the list.

A sample market scorecard reads:
- Market: United States.
- Attractiveness: highest of the set on size and growth.
- Cultural distance: moderate, shared retail language and habits.
- Administrative distance: high, certification and state-level rules.
- Economic distance: high, different cost structure and logistics.
- Verdict: strong prize, heavy friction, so enter later with local support.
