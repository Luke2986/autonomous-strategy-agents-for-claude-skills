---
name: pricing-strategy
description: Sets price from customer value and willingness to pay using value-based pricing and Van Westendorp sensitivity. Use when pricing power, discounting, or packaging is unclear.
---

# Pricing Strategy Agent

## When to use

Use this agent when pricing power, discounting, or packaging is unclear,
and price is set by cost-plus or gut rather than value. It fits when
discounts are creeping, when a new offer needs a launch price, or when you
suspect you are leaving money on the table or scaring buyers off. Reach for
it before a pricing change or a packaging redesign.

## What it does

Produces a pricing recommendation grounded in the value the offer creates
and the customer's willingness to pay, with a defensible price point or
range, a packaging logic, and the sensitivity boundaries around it. The
output says what to charge and why it holds.

## Method

This agent runs value-based pricing with Van Westendorp sensitivity.

1. Quantify the value created. Estimate the economic value to the
   customer: money saved, time saved, revenue gained, or risk avoided
   versus their next best alternative. This sets the ceiling.

2. Anchor to the reference. Identify the competitive or substitute price
   the customer compares against, since willingness to pay is relative,
   not absolute.

3. Set the value-based band. Place a candidate price between the cost
   floor and the value ceiling, capturing a fair share of the value you
   create rather than all of it.

4. Run the Van Westendorp four questions. For the target buyer, establish
   at what price the offer feels too cheap (quality doubted), a bargain,
   getting expensive, and too expensive to consider.

5. Read the intersections. Find the range of acceptable pricing between
   the too-cheap and too-expensive curves, and the optimal point where
   too-cheap and too-expensive resistance balance.

6. Reconcile value and sensitivity. Where the value band and the
   acceptable Van Westendorp range overlap is the defensible zone; where
   they diverge, decide whether to educate on value or adjust the offer.

7. Design the packaging and fences. Set tiers or metrics that let
   different segments self-select, and define discount discipline so
   concessions map to something you get back.

## Inputs

- The offer and the customer segment being priced

- The customer's next best alternative and its price

- The value the offer creates, or the inputs to estimate it

- Any price-sensitivity signals or survey responses available

- The cost floor and any margin or positioning constraints

## Output format

Claude returns a Value Estimate quantifying the economic value versus the
alternative, an Anchor note on the reference price, and a Sensitivity Read
describing the Van Westendorp acceptable range and optimal point in prose.
It then gives a Recommendation with a price point or band and the
defensible zone, a Packaging design of tiers and fences, and a Discount
Discipline note.

## Example

For a fictional company, ClearRoute, a delivery-routing tool:

Value Estimate. Fuel and driver time saved worth about 900 dollars per
vehicle each month, so the ceiling is high.

Anchor. The reference is a spreadsheet plus manual dispatch, effectively
free but painful.

Sensitivity Read. Van Westendorp on fleet managers puts the acceptable
range at 60 to 140 dollars per vehicle monthly, optimal near 95.

Recommendation. Price at 99 per vehicle, a fraction of value yet well clear
of the free workaround.

Packaging. A per-vehicle metric with a small-fleet tier, and discounts only
in exchange for an annual commitment.
