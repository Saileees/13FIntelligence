# 13F Intelligence Platform Demo

Standalone SEC 13F fund intelligence dashboard.

This demo turns public SEC 13F filing data into a local/static intelligence product:

- multi-quarter 13F history
- position change detection
- best ideas
- rare consensus
- manager fingerprints
- style drift
- manager/security network scores
- template-based signal narratives
- drill-through views down to raw filing evidence

The deployed dashboard is a single self-contained `index.html` file. It does not require a backend, database, API key, external JavaScript, npm, or Python runtime to view.

## Live Dashboard

After enabling GitHub Pages, the demo will be available at:

```text
https://saileees.github.io/13FIntelligence/
```

## Caveat

13F filings are delayed public disclosures. They do not show short books, cost basis, intraperiod trades, or full derivative context. This project is intended as an exploratory intelligence dashboard, not a trading system.
