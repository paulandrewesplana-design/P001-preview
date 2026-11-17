# v1.4 Hurdle Preview Verification — 2026-11-17

## Deploy
- Vercel preview: dpl_5RyepmUqjmapjJk3dgGTqpi6zQrk
- URL: https://p001-preview-2nap0lhvb-paul-e-s-projects.vercel.app/ia-studio/hurdle-calculator/
- State: READY; target is preview, NOT production.
- Live production (unchanged): dpl_7UzJ8aUP131ZJ9bf2STKUakm6bGH (Hurdle v1.1).
- Source branch: release/p001-v5-9-hurdle-v1-4-profitability-2026-11-17

## Verified
- New source JavaScript syntax and element references validated, no duplicate IDs.
- Single target-average-wager tile, no preset wager shortcuts.
- Casino economics in a hidden-by-default details element.
- Target wager $800, default 4 hours/day, Baccarat 72 decisions/hour, 1.2% rating advantage, 30% illustrative ceiling, 100% face-value cost, no other costs => Theo $2,764.80, suggested $500 upfront / $300 after hurdle, projected contribution $1,964.80.
- Target wager $1,500 under the same assumptions => Theo $5,184, suggested $950 upfront / $600 after hurdle, projected contribution $3,634.
- Actual casino win $1,200 on the $800 example => actual contribution after modeled costs +$400. Casino loss $2,000 => actual contribution −$2,800. Positive theoretical contribution does not guarantee actual casino profit.
- Expenses and commissions deducted before promo budget; tested $100 other costs plus $50 agent fees reduces suggested promo to $650, preserving budget under the chosen assumption.
- Casino actual win/loss is optional; no actual contribution is shown until a figure is entered.
- Preview iA Studio, Hurdle, Theo, ADT, embedded Theo and embedded ADT URLs all return HTTP 200.
- Public Hurdle remains v1.1, with no v1.4 profitability section.

## Limitations
- Projected contribution = Theo minus modeled promo economic cost, expenses and commissions; this is NOT accounting profit or actual casino revenue.
- Actual contribution = actual casino gaming win/loss minus modeled trip costs; excludes unmodeled casino operating expenses.
- Game ratings, promo costs and reinvestment ceiling are illustrative, not property rules. Confirm offer approval and parameters with casino contacts.
- Full rendered-browser, clipboard and print interaction testing still outstanding.

## Rollback
Previous v1.3 GitHub version: release/p001-v5-8-hurdle-v1-3-simplified-2026-11-17
Previous public v1.1 Vercel deployment: dpl_7UzJ8aUP131ZJ9bf2STKUakm6bGH

Do not promote to production until user approves the preview.
