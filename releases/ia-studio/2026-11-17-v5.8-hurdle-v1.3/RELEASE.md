# iA Studio v5.8 / Hurdle Calculator v1.3 — Simplified Proposal
Date: 2026-11-17
Status: Preview-only, awaiting user review.

## Changes
- Remove the large "05 / Shared Proposal Results" side panel.
- Add an always-visible compact "Current proposal at a glance" summary directly underneath the target average bet recommendation tile.
- Summary displays editable proposal's upfront promo, after-hurdle promo, average wager, qualifying hours, estimated Theo, total modeled investment, and simple illustrative ceiling status.
- Move Copy Proposal Summary and Print Proposal into the compact summary.
- Keep the complete calculations (Theo, allowance, required Theo, required hourly and bet hurdles, costs and commissions) inside the model and copyable report. The compact summary includes a short explanatory distinction between the proposed qualifying condition and modeled economic hurdle.
- Preserve Table Games and Slots, 13 table-game defaults, slot custom assumptions, single target-average-bet input without suggested wager buttons, and the $2,800 default in customer play inputs.
- All inputs recompute both the target suggestion and the compact proposal summary; applying a suggestion updates the proposal.
- Ensure agent and casino contact can see cost assumptions in Shared Casino Economics.
- No updates to public production, Theo, or ADT tools in this preview.

## Version and rollback
Current public production: v5.6 / Hurdle v1.1 (Vercel deployment dpl_7UzJ8aUP131ZJ9bf2STKUakm6bGH).
Prior Hurdle v1.2 source backup: release/p001-v5-7-hurdle-v1-2-target-bet-2026-11-17.
This source: release/p001-v5-8-hurdle-v1-3-simplified-2026-11-17.
Full browser click / clipboard / print interaction testing must be completed before describing those functions as end-to-end verified.
