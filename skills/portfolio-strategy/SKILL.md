---
name: portfolio-strategy
description: Plots bets on a two-factor matrix of market attractiveness versus competitive strength and issues allocation calls. Use when resources are spread thin across too many bets.
---

# Portfolio Strategy Agent

## When to use

Use this agent when resources are spread thin across too many bets and
everything is funded a little while nothing is funded to win. It fits when
a product, business-unit, or investment portfolio needs a clear-eyed sort
into grow, hold, and exit. Reach for it before a budget cycle or a strategy
review where allocation is on the table.

## What it does

Produces a portfolio view that places each bet by market attractiveness and
competitive strength, then converts position into an allocation call:
invest to grow, hold and optimize, or divest and reallocate. The output
tells you where to concentrate and where to stop.

## Method

This agent runs a two-factor portfolio matrix on attractiveness versus
strength.

1. Define the units. List the products, segments, or business units to be
   placed, at a level where each has its own economics and can be funded
   separately.

2. Build the attractiveness axis. Choose weighted factors for market
   attractiveness: size, growth, margin potential, and competitive
   intensity. Score each unit and combine into one attractiveness score.

3. Build the strength axis. Choose weighted factors for competitive
   strength: share, cost position, capability fit, and customer loyalty.
   Score each unit and combine into one strength score.

4. Plot the grid. Place each unit on the two-by-two or three-by-three
   grid, sizing each bubble by revenue or capital employed so scale is
   visible.

5. Read the quadrants. High attractiveness and high strength is grow; high
   attractiveness and low strength is build selectively or partner; low
   attractiveness and high strength is harvest for cash; low on both is
   exit.

6. Set allocation calls. Direct incremental resources toward grow units,
   hold spend flat on harvest units, and free capital from exit units for
   reallocation.

7. Stress the balance. Check the portfolio has enough growth engines to
   fund, and flag over-concentration or a pipeline gap.

## Inputs

- The list of products, segments, or units to assess

- Market data on size, growth, and margin for each

- Your competitive position for each: share, cost, capability, loyalty

- Revenue or capital employed per unit for sizing

- The pool of resources available to reallocate

## Output format

Claude returns an Axis Definition naming the weighted attractiveness and
strength factors, a Placement section describing where each unit sits and
why, written as prose rather than a grid picture, and a Quadrant Read
grouping units into grow, build, harvest, and exit. It closes with
Allocation Calls that direct resources unit by unit and a Balance Check on
portfolio health.

## Example

For a fictional company, Vireo Foods, four lines are placed:

Chilled ready-meals. High on both axes, the grow engine; give incremental
spend.

Frozen desserts. High attractiveness but low strength; build selectively
via a co-manufacturing partner.

Canned soups. Low attractiveness but high strength; harvest for cash.

Bottled juices. Low on both; exit and redeploy the capital.

Balance Check. One strong growth engine funds the build, but the pipeline
is thin, so seed one new bet from the juice proceeds.
