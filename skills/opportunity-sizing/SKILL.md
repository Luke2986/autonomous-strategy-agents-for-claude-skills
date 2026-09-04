---
name: opportunity-sizing
description: Sizes a bet with TAM/SAM/SOM, making assumptions and ranges explicit before capital is committed. Use when a bet needs a defensible size before it gets funded.
---

# Opportunity Sizing Agent

## When to use

Use this agent when a bet needs a defensible size before it gets funded,
and the number floating around is a guess no one can trace. It fits when a
business case, a board ask, or an investment memo rests on how big the
prize is. Reach for it before capital is committed, so the size survives
scrutiny.

## What it does

Produces a sized opportunity broken into total, serviceable, and obtainable
market, with every assumption named and a range rather than a single
false-precise number. The output gives a fundable figure and the levers
that move it.

## Method

This agent runs TAM/SAM/SOM sizing.

1. Define the unit and the boundary. State exactly what is being sized:
   which product, which customer, which geography, and over what time
   frame. A number without a boundary is meaningless.

2. Size the TAM. Estimate the total addressable market, the full demand if
   everyone who could buy did, using population of buyers times value per
   buyer.

3. Narrow to the SAM. Apply the constraints that make demand actually
   serviceable: the segments, geographies, and use cases the offer fits
   and the business can reach.

4. Narrow to the SOM. Estimate the obtainable share within a realistic
   horizon, grounded in capacity, channel reach, and likely competitive
   share, not aspiration.

5. Name every assumption. For each step, write down the driver used, buyer
   count, penetration, price, share, and where it came from, so a reviewer
   can challenge one input at a time.

6. Build a range. Run a low, base, and high case by flexing the two or
   three assumptions with the widest uncertainty, and report the band, not
   a point.

7. Sanity-check against reality. Cross-check the result against a known
   comparator, an existing player's revenue, or a bottom-up build, and
   reconcile any large gap.

## Inputs

- The specific offer, customer, and geography to size

- The time frame the size should cover

- Data on buyer counts, penetration, and price, or proxies for them

- Any comparator revenue or benchmark to check against

- Capacity and channel limits that bound obtainable share

## Output format

Claude returns a Boundary statement of what is being sized, then TAM, SAM,
and SOM sections, each with the figure and the drivers behind it in prose.
It adds an Assumptions Register listing each input and its source, a Range
showing low, base, and high with the swing factors, and a Sanity Check
reconciling the number against a comparator.

## Example

For a fictional company, Grafton Robotics, selling warehouse pick-robots in
one region:

Boundary. Mid-size warehouses over a three-year horizon.

TAM. 4,000 eligible warehouses times an estimated 500,000 dollars average
deployment gives 2 billion.

SAM. Only the 1,600 with compatible layouts and adequate volume, roughly
800 million.

SOM. A realistic 12 percent share given two rivals and a limited install
team, about 96 million.

Range. 60 to 140 million as penetration and share flex.

Sanity Check. The incumbent's regional revenue implies the SAM is credible,
not inflated.
