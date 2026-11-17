# iA Studio v5.9 — Hurdle Calculator v1.4 (Review Preview)
Date: 2026-11-17
Status: Source saved in GitHub; preview-only, pending user approval for production.

## Experience
- One primary card: Target Bet → Suggested Promo, no fixed wager shortcut buttons.
- Default playing assumption: Baccarat, 72 decisions/hour, historical 1.2% estimated rating advantage, four qualifying hours per day, one playing day.
- Automatically suggests face value rounded down to $50 and roughly 62.5% upfront / 37.5% conditional earned portion.
- One hidden-by-default Advanced Settings accordion contains gaming category (Table Games or Slots), specific game, hours, days, decisions/spins per hour, rating advantage/slot theoretical hold, promo economic cost, reinvestment assumption, other expenses and agent fees.
- A profitability panel beneath the suggestion explicitly distinguishes **projected contribution** (Theo minus modeled promo cost, other expenses and fees) from **actual gaming contribution** (casino actual gaming win/loss minus those costs). A field for actual casino win/loss is optional, and actual contribution is not displayed without it.
- Actual contribution is not complete property profit: full operating costs are excluded. Never describe estimated Theo as realized casino revenue.
- Calculations run in-browser; do not input player-identifying or confidential casino information.

## Assumptions
- Current 30% reinvestment percentage is hypothetical and not PENN/M Resort policy. Actual approved offers require casino authorization.
- Slot and video poker speed/hold are blank until entered, with no invented defaults.

## Rollback
- v1.3 GitHub source: release/p001-v5-8-hurdle-v1-3-simplified-2026-11-17
- v1.2 GitHub source: release/p001-v5-7-hurdle-v1-2-target-bet-2026-11-17
- Last confirmed public production before this work: iA Studio v5.6 Hurdle v1.1, deployment dpl_7UzJ8aUP131ZJ9bf2STKUakm6bGH.

## QA requirements before production
Verify preview HTTP routes, source syntax, DOM references, representative numerical cases, slot no-assumptions behavior, conditional actual profit display, mobile layout and copy/print interactions. Do not promote before approval.
