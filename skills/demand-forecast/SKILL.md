---
name: demand-forecast
description: Builds a driver-based demand forecast with scenarios, so planning rests on the real levers rather than a trend line. Use when planning needs a forecast grounded in drivers.
---

# Demand Forecast Agent

## When to use

Use this agent when planning needs a forecast built on real drivers rather
than a line extended off last year. It fits when demand depends on levers
you can name, price, distribution, seasonality, or a macro factor, and you
need to see how each moves the number. Reach for it before capacity,
budget, or inventory decisions that a bad forecast would wreck.

## What it does

Produces a driver-based demand forecast that ties projected volume to the
underlying drivers, expressed as low, base, and high scenarios rather than
a single line. The output shows not just what demand will be but why, and
which lever to pull if it drifts.

## Method

This agent runs driver-based forecasting.

1. Define the forecast unit and horizon. State what is being forecast, in
   what units, at what granularity, over what period.

2. Decompose demand into drivers. Break volume into the factors that
   produce it, for example addressable base times penetration times
   purchase frequency times units per purchase, or traffic times
   conversion times basket.

3. Source each driver. For every driver, establish its current level and
   its historical movement, separating structural trend from noise and
   seasonality.

4. Model each driver forward. Project each driver using the mechanism that
   governs it: a growth rate, a saturation curve, a seasonal pattern, or a
   link to an external variable like price or a macro index.

5. Combine into a base case. Multiply the projected drivers through the
   decomposition to build the base forecast, keeping the arithmetic
   transparent so any driver can be flexed.

6. Build scenarios. Flex the two or three most uncertain and most
   impactful drivers to produce a low and a high case, and describe the
   world each scenario assumes.

7. Attach sensitivities and signals. Rank drivers by how much they swing
   the forecast, and name the leading indicator that would show demand
   tracking toward low or high early.

## Inputs

- What to forecast, in what units, over what horizon

- The drivers you believe produce demand

- Historical data or estimates for each driver

- Any planned changes: price moves, launches, distribution shifts

- External factors that materially affect demand

## Output format

Claude returns a Definition of the forecast unit and horizon, a Driver
Decomposition showing how demand is built up in prose, and a Driver
Projections section modeling each lever forward. It then gives a Base Case
number with the arithmetic visible, Scenarios describing the low and high
cases and the world each assumes, and a Sensitivities note ranking drivers
by impact with the early signal to watch for each.

## Example

For a fictional company, Brightwave Beverages, forecasting a sparkling
drink over the next year:

Driver Decomposition. Demand decomposes into stores stocking times average
units per store per week times 52.

Base Case. Distribution grows from 2,000 to 3,200 stores, at 40 units per
store weekly, giving about 6.7 million units.

Scenarios. Low case assumes distribution stalls at 2,400 stores; high case
assumes a chain win pushes 4,000.

Sensitivities. Distribution is the dominant driver, so the leading signal
is monthly new-store count; if it lags plan by month three, demand is
tracking toward the low case.
