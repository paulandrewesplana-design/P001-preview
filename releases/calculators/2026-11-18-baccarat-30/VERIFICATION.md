# Theo & ADT Calculator — Baccarat Rate Default Update
Date: 2026-11-18
Status: Deployed to production and verified at both standalone and iA Studio-embedded routes.

## User-requested change
- Baccarat estimated decisions/hour **72 → 30**.
- Mini-Baccarat estimated decisions/hour **72 → 30**.
- Both values remain editable by the agent.
- Every other game's default is unchanged, including Blackjack 70.
- Only Theo & ADT standalone applications and their same-origin iA Studio proxies updated; Hurdle Calculator unchanged.

## Source backups
- Theo v1.3: releases/theo-calculator/2026-11-18-v1.3/index.html
- ADT v1.2: releases/adt-calculator/2026-11-18-v1.2/index.html
- Archived previous Theo v1.2: release/theo-v1-2-audit-2026-11-17/releases/theo-calculator/2026-11-17-v1.2/index.html

## Production and rollback
- Theo: deployment dpl_4TK1x5T5wPjY5NkXH9qNLFyqrTAi, previous production dpl_69eNNFH2FyyKXQ4bjzDGXRjVAdjA
- ADT: deployment dpl_Dgj5Hr2hEb9tHC4shKqosddWG92Y, previous production dpl_RJtGXGnGgMU9AsiVhsRJkC7FMX9n
- Theo URL: https://theo-calculator.vercel.app/
- ADT URL: https://adt-calculator-preview.vercel.app/

## Verification
- Both preview builds and production deployments READY; production targets confirmed.
- Four live routes returned HTTP 200: Theo standalone, ADT standalone, /embedded-theo, /embedded-adt on www.paulandrewesplana.com
- Both Baccarat & Mini-Baccarat source entries show 30 decisions/hour; old 72 entries absent.
- JavaScript syntax successfully parsed in the source files.
- Full visual-browser interaction not executed; new defaults validated at source and HTTP response level.
- Theoretical calculations are estimates, not predictions of actual win or casino-specific policy.

## Illustrative impact
For Baccarat, an unchanged $2,800 bet, 1 hour, 1 day and 1.2% rating advantage:
- Old 72 decisions/hour => $2,419.20 Theo
- New 30 decisions/hour => $1,008.00 Theo
- Difference is purely a change in the default rate assumption, not a change in the formula.
