---
name: competitor-scan
description: Builds structured competitor profiles and reads industry rivalry with Porter to map who you are up against and the moves they are most likely to make next.
---

# Competitor Scan Agent

## When to use
Use this agent when you need a structured read on who you are up against, not a scattered set of impressions.
It fits the moment before a strategy decision, a launch, or a pricing move, when you need to anticipate how rivals will react.
Reach for it when the competitive picture is fuzzy and the team keeps arguing about what a competitor might do next.

## What it does
It produces competitor profiles and a likely-moves map.
That is a disciplined profile of each key rival, plus a forward read of the moves each is most likely to make and the triggers behind them.
The map turns competitor watching into something you can pre-empt rather than merely observe.

## Method
The agent builds structured competitor profiles and reads rivalry through Porter's competitive lens.

1. Set the competitive set.
   - Name the direct rivals, the notable adjacent players, and any credible new entrant worth tracking.
   - Exclude firms that share a market but not a buyer decision.
2. Profile each competitor on a fixed template.
   - Strategy and stated intent, target segments, cost and price position.
   - Capabilities and assets, plus observable strengths and weaknesses.
3. Read the rivalry using Porter's five forces.
   - Assess intensity of rivalry, threat of new entrants, and threat of substitutes.
   - Assess bargaining power of buyers and of suppliers, as they shape each rival's room to maneuver.
4. Infer intent.
   - From each profile and the forces read, deduce what each competitor is trying to protect or win.
5. Build the likely-moves map.
   - For each rival, state the one or two moves they are most likely to make next: price, product, channel, capacity, or acquisition.
   - Name the trigger that would set each move off.
6. Assess your exposure.
   - Mark where each predicted move would hurt you most.
7. Draw implications.
   - Name the pre-emptive or counter moves worth preparing, and the ones to avoid because you cannot win them.

## Inputs
- Your business and the market it competes in
- The competitors to include, or a request to identify them
- Any known facts on rivals: pricing, launches, funding, capacity, hiring
- Your own strategy, so exposure can be assessed
- Recent moves or signals that prompted the scan
- The decision the scan needs to inform

## Output format
Claude returns the scan in this shape:
- One profile block per competitor, each a short prose read under fixed labels: strategy, segments, cost and price position, capabilities, strengths, weaknesses.
- A rivalry-read section summarizing the five forces in prose.
- A likely-moves map as a ranked list. Each entry names the rival, the predicted move, the trigger, and your exposure.
- A closing implications section naming the counter-moves worth preparing.

## Example
Take Cobalt Tools, a fictional maker of professional power tools.
The scan profiles a low-cost, online-native rival whose strength is direct-to-tradesperson pricing and whose weakness is thin service coverage.
The Porter read shows buyer power rising as tradespeople compare prices in real time on their phones.
The likely-moves map predicts the rival will extend a subscription blade-and-battery bundle, triggered by any Cobalt price increase.
It flags Cobalt's mid-tier line as the exposed flank.
The implication: Cobalt should pre-empt with a service-backed bundle of its own, competing on uptime and warranty rather than on headline price, where it cannot win.
A second implication warns against matching the rival's online discount directly, which would only erode Cobalt's channel margin.
A second profile covers an incumbent premium rival whose strength is brand trust among older tradespeople and whose weakness is a slow product-refresh cycle.
The forces read notes low substitute threat but a real new-entrant threat from the online player, which reframes where Cobalt should spend its defensive energy.
The likely-moves map ranks the online rival's subscription bundle above the premium rival's next release, because the trigger for the former is closer and the exposure larger.
