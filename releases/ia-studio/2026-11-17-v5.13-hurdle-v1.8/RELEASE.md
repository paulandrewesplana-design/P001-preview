# iA Studio v5.13 / Hurdle v1.8 — Independent Agent Offer-Only Experience
Date: 2026-11-17

## Changes
- Completely remove the "02 / PROFITABILITY CHECK" card, projected contribution, optional actual win/loss input and all related actual-contribution calculations and UI.
- Remove Copy Proposal and Print Proposal buttons, along with exported proposal text and clipboard/print event handlers.
- Preserve historical average bet input (without a speculative haircut), table and slot game choices, proposed qualifying hours/days, estimated Theo, suggested promotional total/upfront/earned values, modeled cost/Theo ratio, and the illustrative $50-rounding promotion model.
- Preserve the NGCB published 7.76% Las Vegas Strip 12-month observed slot win benchmark through Sep 2026, its official citation, alternate verified machine-hold choice, and prominent disclaimer that observed market win is not machine-specific theoretical hold.
- Preserve transparent modeling disclaimer: 30% hypothetical Theo reinvestment, 100% promo economic cost, and zero additional expenses/agent fees, none of which is casino policy.
- Do not modify Theo, ADT, or other portfolio pages.

## Production/rollback
- Previously verified production: dpl_AtBmQpcPiuiw48oh7wvnNcix6hEn (Hurdle v1.7).
- Previous source branch: release/p001-v5-12-hurdle-v1-7-agent-historical-rating-2026-11-17.
- Current branch: release/p001-v5-13-hurdle-v1-8-agent-offers-only-2026-11-17.

## QA scope
Static JavaScript syntax and DOM references checked; preview page routes/production alias to be verified. Full interactive browser testing remains outstanding.
