# Theo and ADT Baccarat Initialization Correction — 2026-11-18

## Root cause
The first deployment updated the Baccarat/Mini-Baccarat game table from 72 to 30 decisions/hour, but each app's `add()` constructor still hardcoded `speed:"72"`, so newly created games initially showed 72 in the UI. This affected both Theo and ADT standalone and iA Studio embedded views. User-reported screenshot confirmed.

## Corrective change
- Replaced initial new-game hardcode with `speed:String(games[0][1])` in BOTH calculators.
- Both Baccarat and Mini-Baccarat records remain default 30 decisions/hour, with editable user inputs; game-changing handler follows selected game rate. Other games unaffected.
- No recalculation or business-policy formula change.

## Immutable source
- Theo v1.3.1: releases/theo-calculator/2026-11-18-v1.3.1/index.html
- ADT v1.2.1: releases/adt-calculator/2026-11-18-v1.2.1/index.html
- Branch: release/theo-adt-baccarat-30-init-fix-2026-11-18

## Deploy and rollback
- Theo READY production: dpl_4ZJK1oNsXT5UrLQ7bNZsExqhrxnX
- ADT READY production: dpl_7D7ZVYUea2j6YyDYTy1cUBg4Pnrc
- Previous Theo production: dpl_4TK1x5T5wPjY5NkXH9qNLFyqrTAi
- Previous ADT production: dpl_Dgj5Hr2hEb9tHC4shKqosddWG92Y

## Verification
HTTP 200 and source checks passed for https://theo-calculator.vercel.app/ , https://adt-calculator-preview.vercel.app/ , https://www.paulandrewesplana.com/embedded-theo , and https://www.paulandrewesplana.com/embedded-adt .
All four now show game Baccarat default 30 and derived first-game init from game table. The hardcoded initial 72 is absent.
Javascript syntax checked. Not run through full mobile graphical browser click testing. A user might need a hard refresh to discard a previously loaded open page.
