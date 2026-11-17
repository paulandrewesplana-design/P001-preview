# Theo Calculator v1.2 — Deployment Verification
Date: 2026-11-17
Deployment status: READY (production)
Production URL: https://theo-calculator.vercel.app
Deployed ID: dpl_69eNNFH2FyyKXQ4bjzDGXRjVAdjA
Previously active deployment (rollback): dpl_7eTabhJCPaFG3NtSk8nwgc7zdvGs
Preview QA deployment: dpl_CLQfsSaduCsLe7z1yAmUdxUWdPiU
Source branch: release/theo-v1-2-audit-2026-11-17
Source file: releases/theo-calculator/2026-11-17-v1.2/index.html
Prior source file: releases/theo-calculator/2026-11-14-v1.1/index.html

Validation performed:
- Source JavaScript syntax passed.
- All 13 catalog games and their numerical defaults unchanged from v1.1.
- Core Theo formula unchanged.
- Baccarat 1-hour ($2,419.20), 3-day ($7,257.60) and 45-minute ($1,814.40) arithmetic passed.
- Blackjack $100, 2h/day, 2 days ($210.00) arithmetic passed.
- Preview HTTP 200; updated labels, CSV total and disclosures present.
- Production alias HTTP 200; public iA Studio embedded-Theo route HTTP 200 serves new version.
- ADT app and iA Studio layout preserved.
- Full browser interaction and download-file verification still outstanding.
Rollback instructions: promote or redeploy dpl_7eTabhJCPaFG3NtSk8nwgc7zdvGs through Vercel.
