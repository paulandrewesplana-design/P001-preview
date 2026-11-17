# iA Studio v5.13 / Hurdle v1.8 Production Verification
Date: 2026-11-17

## Deployment
- READY production: dpl_EUKMDh58biRqsBpKiciAVQFudEYD
- Main portfolio: https://www.paulandrewesplana.com/studio.html
- Live Hurdle Calculator: https://www.paulandrewesplana.com/ia-studio/hurdle-calculator/
- Deployed source commit: 168d07e85c0218a4e343b0a9aef7562c155e2f12
- Preview passed: dpl_BhMj7gnSeCWdmH1fsXJoGztJhBpp

## Post-deployment route and content checks
- HTTP 200: iA Studio, Hurdle Calculator, Theo Calculator, ADT Calculator.
- Hurdle page does not contain the Profitability Check section, actual casino win/loss field, projected contribution, Copy Proposal or Print Proposal controls.
- Hurdle page retains Customer Historical Average Bet ($) and NGCB market benchmark disclosure.
- JavaScript syntax valid; no duplicate DOM IDs; all JS-referenced IDs exist.
- Full graphical browser interaction testing not performed.

## Rollback and transparency
- Prior production deployment: dpl_AtBmQpcPiuiw48oh7wvnNcix6hEn (Hurdle v1.7).
- Prior source branch: release/p001-v5-12-hurdle-v1-7-agent-historical-rating-2026-11-17.
- Current release branch: release/p001-v5-13-hurdle-v1-8-agent-offers-only-2026-11-17.
- Numeric assumptions remain hypothetical (30% Theo reinvestment, 100% promo cost). Not property-approved offer policy.
