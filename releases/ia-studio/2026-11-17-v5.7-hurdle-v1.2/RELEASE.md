# iA Studio v5.7 / Hurdle Calculator v1.2 — Target Average Bet
Date: 2026-11-17
Status: Review preview pending approval, not live

## Changes
- Adds Target Bet → Suggested Promo as the first card, above the existing four-step transparent proposal workflow.
- One editable customer target-average-bet input. No $800, $1,500 or $2,800 preset selector buttons.
- Retains $2,800 default for the separately editable existing customer-play wager field.
- Suggestions read the game type, hourly decision rate, rating advantage / slot theoretical hold, proposed four-hour requirement, playing days, promo cost percentage, other trip expenses, commission, and illustrative reinvestment percentage.
- Budget for promo face value: max(0, (estimated Theo × reinvestment %) − other expenses − commissions) / (promo cost %), rounded down to $50 increments.
- Upfront split target: 62.5%, rounded down to $50; remaining amount is after-hurdle.
- Can apply the suggestion to the existing proposal; the reverse mode and requested-promotion evaluation use the same inputs and formulas.
- Zero promo economic cost cannot produce a meaningful recommended face amount: prompts the user to enter a nonzero verified basis.
- No game speed / hold defaults for slot categories, to avoid invented assumptions.
- Clearly indicates estimates are not approved property offers or reinvestment policies.

## Existing production / rollback
Public portfolio currently v5.6: dpl_7UzJ8aUP131ZJ9bf2STKUakm6bGH
Previous GitHub release: release/p001-v5-6-hurdle-v1-1-unified-2026-11-17
v1.2 source: ia-studio/hurdle-calculator/index.html on this branch
Do not promote without review approval.

## Example test cases
- Baccarat $800 average bet, 4 hours/day, 1 day, 72 decisions/hour, 1.2%: estimated Theo $2,764.80; 30% cap $829.44; rounded face value $800, with $500 upfront and $300 conditional.
- Baccarat $1,500 under the same assumptions: Theo $5,184; cap $1,555.20; rounded face value $1,550, with $950 upfront and $600 conditional.
- Other costs and commissions are deducted before suggested promo.
- Slot games remain unmodeled until spin rate and theoretical hold are entered.

Note: Illustrative calculations and conditional award eligibility do not constitute an approved casino promotional offer.
