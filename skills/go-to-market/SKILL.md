---
name: go-to-market
description: Designs a coherent launch motion across acquisition, conversion, and expansion using GTM motion design and the bowtie funnel, with the metrics that prove it works. Use when a product needs a launch plan.
---

# Go-to-Market Agent

## When to use
Use this when a product needs a coherent launch motion and the pieces exist but do not add up to a plan. It fits the moment before launch when sales, marketing, and product each have a view and no one owns the whole funnel. Reach for it when you need one motion, one funnel, and one scoreboard rather than three disconnected plans.

## What it does
It produces a GTM plan spanning the sales motion, the full acquisition-to-expansion funnel, and the metrics for each stage, so the launch has a defined engine and a way to tell whether that engine is turning.

## Method
This agent designs a GTM motion and models it against the bowtie funnel.

1. Fix the fundamentals.
   - Name the target segment, the core value promise, and the primary buyer and user.
2. Choose the GTM motion that fits the price and complexity.
   - Options: product-led self-serve, inside sales, field sales, or channel-led.
   - State why the motion fits the deal size and buying process.
3. Build the bowtie funnel across both halves.
   - Left half is acquisition: awareness, education, and commitment through to closed deal.
   - Right half is post-sale: onboarding, adoption, retention, and expansion.
   - The bowtie makes revenue after the sale as visible as revenue before it.
4. Define each stage.
   - Name the buyer action that moves them forward.
   - Name the owner and the play or asset that triggers the move.
5. Attach a metric and a conversion target to every stage.
   - Make drop-off visible from first touch to expansion.
6. Model the economics.
   - Cost to acquire against the value a retained, expanding customer returns over time.
   - The payback period that results.
7. Set the launch sequence.
   - Name the first bottleneck to watch and the leading indicator that the motion is working.

## Inputs
- The product, its price point, and the target segment
- The core value promise and the primary buyer and user
- Current sales and marketing capabilities and channels
- Any funnel or conversion data you already hold
- The launch date and any capacity constraints

## Output format
Claude returns a GTM plan:
- Fundamentals: segment, promise, and buyer in brief.
- Motion: the chosen motion and why.
- Bowtie Funnel: described stage by stage across both halves, each stage naming the buyer action, the owner, the play, the metric, and the conversion target.
- Economics: acquisition cost against retained and expansion value with payback.
- Launch Sequence: the first bottleneck to watch and the leading indicator of success.

## Example
For Ledgerly, a fictional invoicing app for freelancers at a low monthly price, the agent picks a product-led self-serve motion, since the deal is too small for sales. The bowtie left half runs from content-driven awareness to a free trial to activation on first invoice sent. The right half runs from onboarding to habitual weekly use to expansion into paid payment collection.

Each stage gets a metric: trial-start rate, first-invoice activation, week-four retention, and expansion-to-paid rate. Economics show a low acquisition cost paid back inside four months once expansion revenue is counted. The launch sequence leads with a template library to drive activation, flagging first-invoice activation as the bottleneck and week-four retention as the leading indicator that the motion holds.

A sample funnel-stage entry reads:
- Stage: Activation, left half of the bowtie.
- Buyer action: sends a first invoice.
- Owner: product and lifecycle marketing.
- Play: guided template and a one-click send.
- Metric: first-invoice activation rate.
- Target: half of trials send within seven days.
