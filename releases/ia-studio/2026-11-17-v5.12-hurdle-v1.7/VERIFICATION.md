# iA Studio v5.12 / Hurdle v1.7 Production Verification
Date: 2026-11-17
## Production deployment
- READY, target production: dpl_AtBmQpcPiuiw48oh7wvnNcix6hEn
- Live Hurdle: https://www.paulandrewesplana.com/ia-studio/hurdle-calculator/
- Live iA Studio: https://www.paulandrewesplana.com/studio.html
- Domains on deployment: www.paulandrewesplana.com, paulandrewesplana.com, p001-preview.vercel.app
- Review preview previously READY: dpl_AogDnsEDh3UDDf3TLFQoStWitGEy
- Source commit deployed: 1aa3ed9c18eba6a2c207f9ecba0bf0fe3072531f

## Post-deployment checks
- HTTP 200: /studio.html, /ia-studio/hurdle-calculator/, /ia-studio/theo-calculator/, /ia-studio/adt-calculator/.
- Live Hurdle HTML contains "Customer Historical Average Bet ($)" and its explanatory no-discount copy.
- Live Hurdle retains official NGCB source benchmark and link and no advanced-settings panel.
- Prior static QA: JavaScript syntax valid, all JS DOM IDs present and unique.
- Full browser clicks/clipboard/print remain untested.

## Version control / rollback
- Previous production: dpl_7UzJ8aUP131ZJ9bf2STKUakm6bGH (iA Studio v5.6 / Hurdle v1.1)
- Previous full-feature preview source: release/p001-v5-11-hurdle-v1-6-ngcb-slot-benchmark-2026-11-17
- This release source: release/p001-v5-12-hurdle-v1-7-agent-historical-rating-2026-11-17
- Source-only verification note commit is after the deployed source commit; it does not change the deployed website.

## Caveats
- Historical wager comes from independent agent without an automatic discount. It is not guaranteed first-trip play.
- Rating/theo model and 30% reinvestment are illustrative; do not claim actual property-approved promotional thresholds.
- NGCB 7.76% is an observed all-slots Strip market win proxy (Oct 2025–Sep 2026), not verified machine theoretical hold.
- Projected contribution is estimated Theo minus modeled promotional cost, not actual casino accounting profit.
