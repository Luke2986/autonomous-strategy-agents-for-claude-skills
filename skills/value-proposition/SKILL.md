---
name: value-proposition
description: Maps an offer to what customers actually value using the Value Proposition Canvas, so you can find and close the fit gap. Use when the offer does not clearly connect to customer needs.
---

# Value Proposition Agent

## When to use

Use this agent when the offer does not clearly connect to what customers
value, and messaging keeps falling flat despite a solid product. It is the
right call when sales, marketing, and product each describe the value
differently and cannot agree on what the customer is really buying. Reach
for it before a launch, a repositioning, or a pricing change that depends
on a crisp value story holding up under scrutiny.

## What it does

Produces a value proposition mapped to customer gains, pains, and jobs,
with an explicit fit assessment between what the offer provides and what
the customer is trying to achieve. The output names where fit is strong,
where it is weak, and exactly what to change to close the gap.

## Method

This agent runs the Value Proposition Canvas end to end.

1. Fix the customer segment. Name one specific buyer or user. A canvas
   built for everyone fits no one, so resist the urge to generalize.

2. Map the customer profile in three parts. List the customer jobs
   (functional, social, emotional), then the pains (obstacles, risks,
   undesired outcomes), then the gains (required, expected, desired,
   unexpected).

3. Rank each list by importance to the customer, not by how easy it is
   for you to serve. Mark the top jobs, the severe pains, and the
   essential gains.

4. Map the value map in three parts. List your products and services,
   then your pain relievers (how the offer removes each severe pain),
   then your gain creators (how the offer produces each essential gain).

5. Draw the fit lines. Connect each pain reliever and gain creator back
   to a ranked pain, gain, or job. Anything that connects to nothing is
   a feature without a buyer.

6. Score fit at three levels: problem-solution fit (do relievers and
   creators address the important items), product-market fit signal
   (evidence customers care), and business-model fit (can you deliver it
   profitably).

7. Write the gap list. Name the top-ranked pains and gains with no
   matching reliever or creator, and the offer elements that serve
   nothing important.

## Inputs

- The specific customer segment to canvas

- What the customer is trying to get done, in their words if available

- The current offer: features, services, and how you describe the benefit
  today

- Any evidence of what customers complain about or ask for

- Known constraints on cost, delivery, or capability

## Output format

Claude returns four named sections. First, Customer Profile, as a ranked
prose list of jobs, pains, and gains. Second, Value Map, as prose linking
each offer element to a pain reliever or gain creator. Third, Fit
Assessment, a short paragraph scoring problem-solution, market, and
business-model fit. Fourth, Gap List, a ranked set of the highest-value
unmet items and the offer elements to cut or reframe.

## Example

For a fictional company, Cadence Payroll, serving small clinic owners:

Customer Profile. Top job: close payroll in under an hour without an
accountant. Severe pains: fear of tax filing errors, and hours lost
reconciling hours worked. Essential gain: confidence the filing is correct.

Value Map. Automated tax filing relieves the filing-error pain, a strong
fit. The mobile app connects to no ranked job, a weak fit.

Fit Assessment. Problem-solution fit is partial: the worst pain is
unaddressed. Market signal is positive. Business-model fit is sound.

Gap List. The top pain, reconciling hours, has no pain reliever.
Recommendation: build timesheet import before promoting the app, and lead
messaging with filing confidence rather than mobility.
