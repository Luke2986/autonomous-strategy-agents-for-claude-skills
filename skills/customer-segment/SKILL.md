---
name: customer-segment
description: Builds needs-based, MECE customer segments with priorities and fit, so you can stop sending one message to everyone. Use when one-size messaging is failing across different buyers.
---

# Customer Segment Agent

## When to use

Use this agent when one-size messaging is failing across different buyers
and conversion varies wildly by audience without a clear reason. It fits
when the team argues about who the customer is, or when a broad market
needs to be cut into groups you can actually serve differently. Reach for
it before building targeting, packaging, or a go-to-market plan that
assumes a single audience.

## What it does

Produces needs-based segments that are mutually exclusive and collectively
exhaustive, each with its priority need, its size and value signal, and a
fit read against what the business can deliver. The output tells you which
segments to pursue, which to ignore, and why.

## Method

This agent runs needs-based, MECE segmentation.

1. Set the segmentation basis. Choose needs and behaviors as the primary
   axis, not demographics or firmographics alone. Demographics describe
   who; needs explain why they buy.

2. Gather the raw variation. List the distinct needs, buying triggers, use
   contexts, and decision criteria you observe across the market.

3. Cluster into candidate segments. Group buyers whose priority need and
   buying behavior are alike, so that members of a segment look more like
   each other than like outsiders.

4. Enforce MECE. Check that every target buyer lands in exactly one
   segment (mutually exclusive) and that the segments together cover the
   whole addressable market (collectively exhaustive). Merge overlaps and
   add a residual segment if coverage has a hole.

5. Profile each segment on a fixed template: priority need, buying
   trigger, decision criteria, rough size, value or willingness-to-pay
   signal, and how they buy.

6. Score attractiveness and fit. Rate each segment on attractiveness
   (size, growth, value, intensity of need) and on right-to-win (how well
   the current offer and capabilities match the need).

7. Make the call. Sort segments into pursue, watch, and deprioritize, and
   name the one or two priority segments the strategy should be built
   around.

## Inputs

- The market or customer base to segment

- What you know about customer needs, triggers, and buying behavior

- Any usage, sales, or survey data available

- The current offer and the capabilities behind it

- Constraints on which segments you can realistically serve

## Output format

Claude returns a Segmentation Basis note, then a set of Segment Cards
written as prose, one per segment, each covering priority need, trigger,
decision criteria, size, value signal, and buying behavior. It closes with
an Attractiveness and Fit read describing where each segment sits, and a
Priority Call naming the one or two segments to build around and the
rationale.

## Example

For a fictional company, Northwind Tools, selling cordless drills, a
needs-based cut beats a demographic one:

Segment A, jobsite pros. Priority need is battery life under heavy load;
buys through trade distributors; high value; strong fit.

Segment B, weekend renovators. Priority need is low price and simplicity;
buys through retail; medium value; medium fit.

Segment C, industrial buyers. Priority need is fleet management and service
contracts; low current fit.

Priority Call. Build around jobsite pros, serve renovators with a stripped
model, and deprioritize industrial until service capability exists.
