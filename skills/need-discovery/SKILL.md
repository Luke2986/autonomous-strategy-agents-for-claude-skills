---
name: need-discovery
description: Ladders stated wants down to root motivations to build a prioritized need map, so you stop solving the wrong problem. Use when the real need sits beneath the one being discussed.
---

# Need Discovery Agent

## When to use

Use this agent when you suspect you are solving the wrong problem, and the
feature requests or complaints on the table feel like symptoms rather than
causes. It fits when customers ask for one thing but keep behaving as if
they want another. Reach for it before committing roadmap or positioning to
a need you have not verified.

## What it does

Produces a prioritized need map that separates surface wants from the
underlying drivers beneath them, and ranks the root needs by how strongly
they move the customer. The output tells you which need to actually solve
for, and which requests were only symptoms.

## Method

This agent runs needs laddering to root motivations.

1. Collect the stated wants. List what customers say they want, in their
   words, without editing them into what you wish they meant.

2. Ladder each want down. For each stated want, ask why it matters, then
   ask why that matters, repeating until you reach a motivation that does
   not reduce further. This turns "I want a faster export" into "I need to
   look prepared in front of my boss."

3. Separate functional, emotional, and social drivers at the bottom of
   each ladder, since the deepest need is often not the practical one.

4. Cluster the root motivations. Group ladders that bottom out at the same
   underlying need, so recurring drivers become visible.

5. Rank the root needs. Score each on intensity (how much it hurts),
   frequency (how often it bites), and how poorly it is served today. The
   best needs are intense, frequent, and underserved.

6. Test for a real gap. For each top need, check that current solutions
   genuinely fail to meet it, not just that the customer has not noticed
   the fix.

7. Reframe the problem. Restate what you are solving in terms of the root
   need, and note which stated wants were symptoms you can safely ignore.

## Inputs

- The customers or users whose needs you want to understand

- Their stated wants, requests, and complaints

- Any behavioral or usage evidence that shows what they do, not just say

- The current solution and where it falls short

- The decision this discovery needs to inform

## Output format

Claude returns a Ladders section showing each stated want laddered down to
its root motivation in prose. It then gives a Root Need Map grouping the
recurring underlying needs, a Ranking that scores each root need on
intensity, frequency, and how underserved it is, and a Reframe that
restates the problem worth solving and flags the stated wants that were
only symptoms.

## Example

For a fictional company, Sprout Learning, an online course platform,
teachers keep asking for more quiz templates:

Ladder. More templates leads to faster course setup, which leads to
launching before the term starts, which leads to not losing enrollments to
a competitor.

Root Need Map. The root need is not templates, it is time-to-launch
confidence.

Ranking. Highest, because it is intense, recurs every term, and is poorly
served today.

Reframe. Solve fast course setup end to end, and treat the template request
as a symptom rather than the target.
