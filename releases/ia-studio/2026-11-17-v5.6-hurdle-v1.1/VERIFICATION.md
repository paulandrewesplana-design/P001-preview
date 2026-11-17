# iA Studio v5.6 — Hurdle Calculator v1.1 Deployment Verification
Release date: 2026-11-17

## Production
- Public website: https://www.paulandrewesplana.com/studio.html
- Unified Hurdle Calculator: https://www.paulandrewesplana.com/ia-studio/hurdle-calculator/
- Vercel project: p001-preview
- Production deployment: dpl_7UzJ8aUP131ZJ9bf2STKUakm6bGH
- Exact deployed Git commit: a473ec9bd9b4ed4b74b2d34e6598cfc81b6083f5
- GitHub branch: release/p001-v5-6-hurdle-v1-1-unified-2026-11-17
- Previous v5.5 production (rollback): dpl_57FupqCT34wyoKMG1U2wcQUUWYnX
- Previous GitHub backup: release/p001-v5-5-hurdle-2026-11-17

## Verified
- New v1.1 webpage source parses as JavaScript; no duplicate HTML element IDs.
- Offer-first, customer play, shared casino economics, and unified results appear in the correct order.
- 13 table-game rating defaults preserved; slots require provided rate/hold.
- Sample Baccarat/slot models passed independent arithmetic tests; default $2,800 Baccarat, 4 hours, one playing day produces $9,676.80 Theo at 72/hr and 1.2% rating assumption.
- Requested $1,000 upfront plus $1,000 after-hurdle yields $2,000 face value. At illustrative 30% reinvestment and 100% promo economic cost, required Theo is $6,666.67 and modeled playing-hour hurdle is 2.76 hrs/day. The proposed release condition remains separately shown as 4 hrs/day.
- Vercel deployment READY, target production; www.paulandrewesplana.com is among production aliases.
- Public Homepage, iA Studio, Hurdle, Theo, ADT, both embedded calculator engines, Story, and Independent Agents routes all returned HTTP 200.
- The four live iA Studio and calculator-wrapper HTML files exactly match GitHub source at the deployed commit.
- Browser-level click, clipboard and print interaction tests not yet completed.

## Compliance boundaries
- Economic cost and reinvestment defaults are illustrative, not M Resort or PENN policy.
- An offer's release condition is not necessarily an economically sufficient casino hurdle.
- No customer data needs to be submitted; tool is a local planning model.
- All offers require casino authorization.

## Rollback
Restore Vercel deployment dpl_57FupqCT34wyoKMG1U2wcQUUWYnX, which remains in READY status, or redeploy archived source from release/p001-v5-5-hurdle-2026-11-17. Do not overwrite historical versions.
