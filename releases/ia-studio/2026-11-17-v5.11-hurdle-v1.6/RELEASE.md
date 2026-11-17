# iA Studio v5.11 / Hurdle Calculator v1.6 — NGCB Slot Benchmark
Date: 2026-11-17
Status: Preview-only, not published on the public portfolio.

## Source and exact data
Nevada Gaming Control Board (NGCB), Gaming Revenue Report, September 2026.
Official report: https://www.gaming.nv.gov/siteassets/content/about/gaming-revenue/monthly-revenue-report----september-2026.pdf
GRI archive: https://www.gaming.nv.gov/about-us/gaming-revenue-information-gri/
Market: Clark County Las Vegas Strip Area — All Nonrestricted Locations
Category: Slot Machines, Total
Measure: 12-month **actual win percent** through 9/30/2026, October 2025–September 2026
Value: **7.76%**
This is NOT the theoretical hold of a specific slot machine, not a verified player-rating factor, and not an NGCB recommendation for player promotional reinvestment.

## Code changes
- Slot rate-source selector defaults to NGCB historical market benchmark (7.76%) as an example for modeling.
- An alternative option accepts a verified machine theoretical hold entered manually.
- Direct official report and GRI archive links next to benchmark and detailed disclosure.
- Category-wide benchmark is explicitly the same aggregate for reel, video, progressive, and video poker categories; not category-specific theoretical hold.
- Player must still enter spins/hour; no invented slot speed.
- When NGCB benchmark selected, label calculation a modeled value using historical market proxy, not exact Theo.
- Existing 13 table-game historical rating assumptions remain unchanged.
- Fixed 30% reinvestment, 100% face-value cost, zero additional trip expenses/agent fees remain purely illustrative. All offers require casino approval.

## Rollback
Previous preview source: release/p001-v5-10-hurdle-v1-5-single-tile-2026-11-17
Latest confirmed public production: dpl_7UzJ8aUP131ZJ9bf2STKUakm6bGH (Hurdle v1.1).
No production deployment intended without separate approval.

## Validation status
Static JavaScript syntax passes; elements referenced by code exist uniquely. Browser interactive and print checks are outstanding.
