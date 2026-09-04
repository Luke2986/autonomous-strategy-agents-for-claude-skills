---
name: growth-options
description: Maps growth options across existing and new products and markets using the Ansoff matrix so leadership can debate where growth should come from with the risk of each path made explicit.
---

# Growth Options Agent

## When to use
Use this agent when leadership is debating where growth should come from and the options are being compared apples to oranges.
It fits the moment when penetration, new products, new markets, and diversification are all on the table and no one has laid out the risk of each.
Reach for it during growth planning, or when the ambition number needs a credible set of paths behind it.

## What it does
It produces growth options mapped across products and markets.
The full set of growth paths is sorted into the four Ansoff quadrants, each option carrying its risk profile and its key assumption.
The output ends in a recommended sequence, so growth becomes a staged plan rather than a menu.

## Method
The agent applies the Ansoff growth matrix across the product and market axes.

1. Anchor the two axes.
   - Products, existing versus new, against markets, existing versus new.
   - The cross gives four growth modes.
2. Populate Market Penetration.
   - Existing products into existing markets.
   - List moves to sell more to current customers: share gain, usage, retention, pricing.
3. Populate Product Development.
   - New products into existing markets.
   - List new offers, extensions, or bundles for customers you already serve.
4. Populate Market Development.
   - Existing products into new markets.
   - List new geographies, segments, or channels for offers you already have.
5. Populate Diversification.
   - New products into new markets.
   - List the bolder bets, marking each as related (adjacent capability) or unrelated.
6. Assess risk per option.
   - Penetration is lowest risk, diversification highest.
   - Note the key assumption and the capability each option demands.
7. Recommend a sequence.
   - Propose which quadrants to lean on first given ambition, risk appetite, and capability.
   - Balance near-term certainty against longer-term upside.

## Inputs
- The business and its current products and markets
- The growth ambition or target
- Risk appetite and any constraints: capital, capability, timeline
- Known adjacent markets or product ideas already under discussion
- Current share position in the core market, if known
- The time horizon the ambition must be hit within

## Output format
Claude returns the analysis in this shape:
- Four Ansoff quadrant sections: Market Penetration, Product Development, Market Development, Diversification.
- Each holds a bulleted list of concrete growth options. Every option names its key assumption, the capability it needs, and a risk rating.
- A recommendation describing the proposed sequence in prose: which quadrants to prioritize first and which bolder bets to stage for later.

## Example
Take Verdant Kitchens, a fictional maker of plant-based ready meals.
Market Penetration lists winning more freezer facings in current grocery accounts, low risk.
Product Development adds a chilled ready-meal line for the same retailers, moderate risk, dependent on a chilled supply chain the company lacks.
Market Development proposes entering foodservice for existing frozen lines, moderate risk.
Diversification flags a branded meal-kit subscription as a related but higher-risk bet.
The recommended sequence: press penetration now for near-term volume, build the chilled capability in parallel for product development next year, and hold the subscription bet until the core retail base is secured and cash-generative.
