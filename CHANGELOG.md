# Changelog

## v1.2.0 - 2026-10-06
New
- Trends view: a Ledger | Trends tab row under the banner. Trends shows balance with net deposits and withdrawals in one chart, and weighted APY against the current inflation rate in another, plotted from the first to the last month with an entry
- Hover or drag across a chart to preview a month, and click or release to select it. The selected month stays in sync with the banner
- Net deposits include a new platform's starting deposit, so they can differ from the CSV "Deposits/Withdrawals" column in the month a platform is added
Changes
- Page content widened to 1120px on desktop, matching the old layout. Phones are unchanged
- Removed the DeepSite badge script
Fixes
- The APY chart axis no longer piles up labels when one month's APY is very large
Unchanged: data model, storage key, CSV layout and saved data

## v1.1.0 - 2026-10-04
Visual redesign
- Rose gold design with dark (default) and light themes, toggle in the footer, remembered on this device
- Tailwind and Lucide replaced by hand-written CSS and inline icons
- Platform names are now escaped, so names containing HTML characters show as plain text
Behavior changes
- Headline APY is now weighted (total interest over total principal), matching the CSV TOTAL row. It was a simple average of platform APYs
- Inflation field relabelled "Annual inflation (YoY)", since the NBS headline figure is year on year
- Keyboard focus is kept after editing a ledger field
Fixes
- Balances now carry forward through December on every edit and when a platform is added. Edits are committed before switching months or exporting. Exports for a platform added mid-year now include months through December.
Unchanged: data model, storage key and CSV layout. Saved data loads as before

## v1.0.2 - 2026-06-05
Platforms start in the month added, not January

## v1.0.1 — 2026-06-05
- Limited savings type options to Locked, Semi-locked, and Flexible

## v1.0.0
- Initial release: multi-platform savings dashboard with inflation comparison