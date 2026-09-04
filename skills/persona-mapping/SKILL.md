---
name: persona-mapping
description: Builds decision-oriented personas with goals, blockers, and the triggers that move them, so teams stop designing for an average user who does not exist. Use when product or messaging targets a fictional average.
---

# Persona Mapping Agent

## When to use

Use this agent when teams design for an average user who does not exist,
blending real buyers into a bland composite that fits none of them. It fits
when product, marketing, and sales each picture a different person, or when
you need to know who actually decides and what moves them. Reach for it
before a redesign, a campaign, or a sales-play build.

## What it does

Produces a small set of decision-oriented personas, each with goals,
blockers, and the concrete decision triggers that move them from interest
to action. Personas are built to drive choices about product, message, and
channel, not to decorate a slide.

## Method

This agent runs persona modeling with decision triggers.

1. Bound the set. Decide which segment or buying unit the personas belong
   to, and keep the count small, usually three to five, so each is
   distinct and usable.

2. Separate roles in the decision. Distinguish the economic buyer, the
   user, and the influencer or blocker, since one human rarely plays all
   three.

3. Build each persona on a fixed spine: goal (what success looks like for
   them), context (their situation and constraints), blockers (what stops
   them from acting), and decision criteria (what they judge options on).

4. Name the triggers. For each persona, list the specific events or
   realizations that move them from passive to active: a pain crossing a
   threshold, a deadline, a competitor move, a budget cycle.

5. Map the objections. For each persona, capture the reasons they hesitate
   or say no, and the proof that would answer each.

6. Trace the journey moments. Note where each persona enters, what they
   need at consideration, and what closes the decision.

7. Pressure-test against reality. Check each persona against real behavior
   or evidence, and cut any that is an assumption dressed as a person.

## Inputs

- The segment or buying unit the personas serve

- What you know about the people who buy, use, and block the purchase

- Their goals, constraints, and stated objections

- Any interview, sales-call, or support evidence

- The decision or campaign the personas need to inform

## Output format

Claude returns one Persona Card per persona, written as prose, each
covering role in the decision, goal, context, blockers, decision criteria,
triggers, and objections with the proof that answers them. It closes with a
Journey Note describing where each persona enters and what closes the
decision, and a short Use Note on which persona to design and message for
first.

## Example

For a fictional company, Ledgerly, selling accounting software to mid-size
firms, three personas emerge:

Finance Director, the economic buyer. Goal is audit-ready books; blocker is
switching risk; trigger is a failed audit finding; proof needed is a clean
migration track record.

Staff Accountant, the user. Goal is fewer manual entries; trigger is
month-end overtime.

IT Lead, the blocker. Goal is no new security exposure; objection answered
by a security attestation.

Use Note. Win the Finance Director on audit safety, and disarm IT early
with the attestation.
