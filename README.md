# Direction

Independent market research and writing. A static, manually curated website with four sections:

1. About Me — public profile (awaiting author approval)
2. Write-ups — original articles (awaiting first approved article)
3. Macro Indicators — Federal Reserve transcript archive and future macro readings
4. Financial Indicators — indicators and dashboards to be added later

## Website

- `index.html`: the entire first-version homepage and four navigable sections.
- `macro/fomc/index.html`: searchable 2026 press-conference transcript library, manually curated and machine-extracted from primary-source PDFs.
- The library links to Federal Reserve PDFs for source verification. The author keeps the original PDF archive offline.
- No automatic collection, scheduling, API integrations, or automated writing. Future publication requires deliberate manual changes.

## Local preview

Double-click `index.html` to see the site in your browser. Use the top navigation and select **FOMC Press Conference Transcripts** under Macro.

## Free deployment

Create a Cloudflare Pages project connected to this repository, using a **static HTML** configuration: framework preset **None**, build command blank, build output directory **/**. Changes manually committed to `main` are then deployed. No paid hosting plan is required for ordinary static usage within Cloudflare's free-plan limits.

## Content and data integrity

Publication is independent, not affiliated with the Federal Reserve. Transcript text is extracted from official PDFs; extraction can alter layout and spacing. The official PDF should be treated as authoritative when citing exact language.

## Proposed next steps

Approve the biography, supply the first article, then add selected economic and financial series with original sources, units and observation dates.
