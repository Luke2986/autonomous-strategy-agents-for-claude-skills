---
name: tam-estimation
description: Estimates total market two ways, top-down and bottom-up, then reconciles them into one credible number. Use when you need a total-market figure that will survive challenge.
---

# TAM Estimation Agent

## When to use

Use this agent when you need a credible total-market number and a
single-method estimate will not survive challenge. It fits when a top-down
figure from a report and a bottom-up build from your own economics
disagree, and you need to know which to trust. Reach for it when a market
number will anchor a strategy, a raise, or a board decision.

## What it does

Produces a total addressable market estimated two independent ways,
top-down and bottom-up, plus a reconciliation that explains any gap and
lands on one defensible figure with a confidence read. The output is a
number that holds up because it was triangulated, not asserted.

## Method

This agent runs top-down and bottom-up TAM triangulation.

1. Fix the definition. State the product, buyer, geography, and time frame
   precisely, since top-down and bottom-up can only be reconciled if they
   size the same thing.

2. Build the top-down estimate. Start from a published market or
   population figure and narrow by the fraction that is genuinely
   addressable, documenting each filter and its source.

3. Build the bottom-up estimate. Start from the unit economics: number of
   potential buyers times adoption times price, or capacity times
   utilization, built from your own data.

4. Keep them independent. Do not let one method borrow the other's
   assumptions, or the check is worthless; the value is in two separate
   roads to the same place.

5. Compare and diagnose the gap. Put the two numbers side by side. A gap
   under roughly 20 percent is reassuring; a large gap points to a wrong
   filter, a double count, or an unrealistic price or adoption input.

6. Reconcile to one figure. Adjust the weaker assumptions on either side
   until the methods converge, and choose the figure the corrected
   evidence best supports.

7. State confidence and drivers. Report the reconciled TAM with a
   confidence level and name the two or three inputs that move it most.

## Inputs

- The precise market definition: product, buyer, geography, time frame

- A top-down source: a published market size or buyer population

- Bottom-up inputs: buyer counts, adoption rates, and price or capacity

- Any known benchmarks or comparators

- The decision the TAM will anchor

## Output format

Claude returns a Definition statement, a Top-Down build showing each filter
and source in prose, and a Bottom-Up build showing the unit-economics
chain. It then gives a Reconciliation that compares the two, diagnoses the
gap, and adjusts the weaker assumptions, closing with a Reconciled TAM
figure, a confidence level, and the drivers that move it most.

## Example

For a fictional company, Solara Panels, sizing residential solar installs
in one country over five years:

Top-Down. Start from 12 million owner-occupied homes, narrow to the 30
percent with suitable roofs and income, at an 18,000 dollar average
install, giving about 65 billion.

Bottom-Up. Build from an installer base and realistic annual capacity,
landing near 48 billion.

Reconciliation. The gap traces to an over-optimistic top-down suitability
filter; corrected, the methods converge.

Reconciled TAM. Roughly 52 billion at medium confidence, with
roof-suitability rate and install price as the swing drivers.
