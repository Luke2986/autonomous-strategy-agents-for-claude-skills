---
name: market-entry
description: Recommends how to enter a chosen market, the entry mode, its risks, and a staged plan, using structured entry-mode analysis. Use when the target market is decided and only the how remains open.
---

# Market Entry Agent

## When to use
Use this when a target market is already chosen and the question is how to enter it. It fits the point after market selection, when export, licensing, joint venture, acquisition, and greenfield all remain on the table. Reach for it before you commit capital to a mode, because the mode locks in cost, control, and speed for years.

## What it does
It produces an entry-mode recommendation with the risks each mode carries and a staged plan, so leadership can see the trade-off between control, capital, and speed and choose a mode with eyes open.

## Method
This agent runs an entry-mode analysis.

1. Restate the objective for this market.
   - Name the position you want, by when, and what winning looks like.
2. List the candidate entry modes on a control spectrum.
   - Exporting, licensing or franchising, distributor or agent, joint venture, acquisition, and wholly owned greenfield.
3. Score each mode on four criteria.
   - Control: how much you steer brand, pricing, and quality.
   - Capital and commitment: what you must invest and how reversible it is.
   - Speed to market: how fast you reach customers.
   - Risk exposure: partner, political, and execution risk.
4. Weigh the criteria against your objective and constraints.
   - High-control ambitions with capital favor greenfield or acquisition.
   - Speed with limited capital favors distributors or licensing.
   - Shared risk in an unfamiliar market favors a joint venture.
5. Name the risks of the recommended mode explicitly.
   - Pair each risk with a mitigation.
6. Stage the entry.
   - Define a first phase that limits downside and proves demand.
   - Set the triggers that justify stepping up commitment and the mode you would escalate to.
7. State the go and no-go signals.
   - Name what would confirm the plan and what would abort it.

## Inputs
- The target market and the objective for it
- Capital available and appetite for risk
- Need for control over brand, pricing, and quality
- Any partners or targets already identified in the market
- Time pressure and regulatory constraints

## Output format
Claude returns a decision memo:
- Objective: one paragraph on the position wanted and by when.
- Mode Comparison: one card per candidate mode describing its control, capital, speed, and risk.
- Recommendation: the chosen mode with its rationale.
- Risks and Mitigations: paired points for the chosen mode.
- Staged Plan: the first phase, the escalation triggers, the mode to escalate to, and the go and no-go signals.

## Example
For Cedar & Co, a fictional artisanal-coffee roaster entering South Korea, the objective is a premium position within three years without betting the company. Greenfield gives full control but ties up capital and is slow. A distributor is fast and cheap but surrenders brand control, which is fatal for a premium play. A joint venture with a local specialty-cafe group scores best: shared risk, local knowledge, and enough control to protect the brand.

The main risk is partner misalignment on pricing, mitigated by contractual price floors and a brand-standards clause. The staged plan opens with a small joint venture running three flagship cafes, with a trigger to buy out the partner and go wholly owned if unit economics clear a set margin by year two.

A sample mode comparison card reads:
- Mode: Joint venture with a local cafe group.
- Control: medium-high, enough to protect the premium brand.
- Capital and commitment: moderate, shared with the partner.
- Speed to market: fast, using the partner's sites and licenses.
- Risk exposure: partner alignment on pricing, contained by contract.
- Verdict: recommended entry mode for the first phase.
