# iA Studio v5.7 — Hurdle Calculator v1.2 Preview Verification
Date: 2026-11-17
Source branch: release/p001-v5-7-hurdle-v1-2-target-bet-2026-11-17
Source commit deployed: aeda7f03486fd7f85cab76777b61ae0aec11f080

## Vercel
Preview ID: dpl_EGvFNXyvNacMgqxJ4mYRHmKtJh91
Preview URL: https://p001-preview-p7qoeaa38-paul-e-s-projects.vercel.app/ia-studio/hurdle-calculator/
Deployment state: READY; target: preview (not production)
Prior production rollback: dpl_7UzJ8aUP131ZJ9bf2STKUakm6bGH

## Checks
- JavaScript syntax compiled successfully during source validation.
- Target average wager is a single editable field, initially blank. No $800, $1,500, or $2,800 preset-selection buttons.
- Existing customer-play field retains editable $2,800 default.
- Target suggestions use game assumptions, hours, days, cost factor, other trip expenses, commissions and illustrative Theo reinvestment percentage.
- Suggested face promo never exceeds modeled allowance under tested cases; suggestions round down to $50 increments.
- Baccarat sample: $800 wager × 72 decisions/hour × 4 hours × 1 day × 1.2% -> $2,764.80 Theo; 30% allowance $829.44 -> $800 face value, $500 upfront and $300 earned, 4-hour proposed qualification.
- $1,500 Baccarat sample -> $5,184 Theo; $1,550 modeled face promo at 30%, split $950/$600.
- Slot sample requires manually entered speed and theoretical hold; no slot-rating defaults invented.
- Target recommendation applies its bet and promo amounts to the shared proposal model on user click.
- Portfolio landing, iA Studio, Hurdle, Theo wrapper, ADT wrapper, and embedded calculator engine routes returned HTTP 200.
- Confirmed public production Hurdle remains v1.1; no promotion executed.
- Full visual browser testing and download/print interaction testing remain outstanding.

## Production gate
Only promote after user reviews and approves the preview.
