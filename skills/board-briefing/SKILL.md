---
name: board-briefing
description: Structures a decision-ready board pack using SCQA, use it when the board needs a crisp pack built to reach a decision.
---

# Board Briefing Agent

## When to use
Use this agent when the board needs a briefing built to drive a decision, not a data dump. It fits the case where the material is rich but unstructured and the board's time is short. Reach for it when you must open with the situation everyone shares, land the complication, and put a clear question and recommendation in front of directors who will decide in minutes.

## What it does
It produces a board briefing structured for a decision: a pack organized around the SCQA arc that states the situation, sharpens the complication, poses the decision question, and answers it with a recommendation and the evidence a board needs. Everything serves the one decision the board must make, with depth pushed to an appendix rather than the main line.

## Method
The agent runs an SCQA board-pack structure.

1. **Fix the decision.** Name the single decision the board must make and the specific ask, so everything downstream serves that one question.
2. **Write the Situation.** State the shared, uncontested context the board already accepts, kept brief so the pack does not stall in background.
3. **Write the Complication.** State what has changed or gone wrong that forces a decision now, the tension that earns the board's attention.
4. **Write the Question.** Sharpen the decision the complication raises, phrased so it can be answered yes or no or as a clear choice.
5. **Write the Answer.** Lead with the recommendation, then give the two or three reasons that support it, up front rather than buried.
6. **Marshal the evidence.** Place the support behind each reason where it reinforces the argument:
   - The numbers and the value case.
   - The options considered and why they lose.
   - The key risks and how they are managed.
7. **Add the ask and implications.** State the decision ask, what approving sets in motion, and a short appendix for depth the board may probe.

## Inputs
- The decision the board must make
- The underlying analysis, options, and data
- The recommendation, if one is already formed
- The board's context: what they know, care about, and will challenge

## Output format
Claude returns a board briefing in named sections following the SCQA arc:
- **Situation:** the shared context, briefly.
- **Complication:** what forces a decision now.
- **Question:** the sharp decision to be made.
- **Answer:** the recommendation stated first.
- **Reasons:** the two or three supporting arguments.
- **Evidence:** numbers, options, and risks marshaled in prose.
- **Decision Ask and Implications:** the ask and what approving sets in motion, with an appendix note.

Keep it tight and decision-first, evidence in prose rather than raw tables.

## Example
For Riverstone Foods, an illustrative grocery brand, the board pack opens on the Situation that the core brand holds share in a flat category. The Complication: a private-label surge has cut margin two points in three quarters and the trend is accelerating. The Question: should the board approve a 15-million reformulation-and-relaunch investment.

The Answer is yes, for three reasons: the margin trend is structural not cyclical, a tested reformulation lifts preference in trials, and the payback lands inside two years. Evidence marshals the margin bridge, the tested alternatives, and the downside if share keeps slipping. The ask is a funding approval, with sensitivity cases held in the appendix for directors who probe.
