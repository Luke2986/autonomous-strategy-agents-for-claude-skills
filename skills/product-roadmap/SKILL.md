---
name: product-roadmap
description: Turns a wish list into a now-next-later roadmap tied to strategic themes and outcomes. Use when the roadmap is a pile of features without sequence or rationale.
---

# Product Roadmap Agent

## When to use

Use this agent when the roadmap is a wish list without sequence, and every
request looks urgent because nothing is anchored to a strategic theme. It
fits when stakeholders each push their own feature, or when leadership
cannot see what is coming and why. Reach for it before a planning cycle or
a commitment to customers.

## What it does

Produces a now-next-later roadmap organized by strategic theme, where each
item is justified by the outcome it drives rather than the feature it
ships. The output gives a defensible sequence and a story leadership and
customers can follow without fake precision on dates.

## Method

This agent runs now-next-later roadmapping.

1. Anchor to themes. Restate the two to four strategic themes or outcomes
   the roadmap must advance, so every item can be traced to one.

2. Collect and normalize candidates. Gather the requests, ideas, and
   commitments, and rewrite each as the outcome it aims for, not the
   feature that implements it.

3. Map each candidate to a theme. Drop or park anything that serves no
   theme, since a roadmap is a filter, not a container.

4. Assess each candidate on value and confidence. Estimate the outcome
   value and how sure you are of both the problem and the solution; low
   confidence means it belongs later, not now.

5. Place into horizons. Now holds committed, high-confidence work in
   delivery. Next holds validated bets being shaped. Later holds
   directional intentions still being explored. Horizons express
   confidence and sequence, not calendar dates.

6. Balance the mix. Check each horizon carries a healthy blend across
   themes and across run, grow, and transform work, so one theme does not
   starve the rest.

7. Attach signals. For each item, name the outcome metric that will show
   it worked and the trigger that promotes a Later item to Next.

## Inputs

- The strategic themes or outcomes the roadmap must serve

- The candidate features, requests, and commitments

- Any evidence of customer value or demand per candidate

- Delivery capacity and known dependencies

- Constraints or hard commitments already made

## Output format

Claude returns a Themes anchor, then three horizon sections, Now, Next, and
Later, each listing items as the outcome they drive with the theme and
rationale in prose. It adds a Balance Check on the spread across themes and
horizons, and a Signals note pairing each key item with its outcome metric
and the trigger that would promote it forward.

## Example

For a fictional company, Trailhead Fitness, a workout app, themes are
retention and premium conversion:

Now. Cut onboarding drop-off with a guided first session; high confidence;
serves retention.

Next. A validated bet on adaptive workout plans, shaped but not committed;
serves premium conversion.

Later. A directional wearable integration, still exploratory; serves both.

Balance Check. Retention is well covered but premium conversion leans on
one Next item, so promote a second.

Signals. The onboarding item is watched via day-seven return rate, and the
wearable moves to Next once integration cost is scoped.
