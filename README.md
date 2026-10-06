VaultTrack
A personal savings dashboard built for Nigerians who save across multiple platforms and want to know one thing: are my returns beating inflation?
What it does

Track savings across multiple platforms (PiggyVest, Cowrywise, CPCompass, etc.)
Automatically calculates your balance, monthly yield, and annualized APY per platform
Compares your overall APY (total interest over total principal) against Nigeria's current annual (year-on-year) inflation rate
Carries your balance forward month to month automatically
Works across January to December in one place
Trends view charts your balance and net deposits, and your weighted APY against inflation, month by month

Why I built it
I save across multiple platforms for diversification but couldn't find a single tool that tracked everything in one place and told me whether my money was actually growing in real terms. So I built one.
Tech

Vanilla HTML, CSS, JavaScript — no frameworks
Google Fonts (Space Grotesk, IBM Plex Mono), hand-written CSS, inline SVG icons and hand-drawn inline SVG charts, no CSS framework, icon library or charting library
localStorage for data persistence — no login, no backend, no data leaves your device

Usage
No installation needed. Open index.html in any browser and start adding your platforms.
Update the Annual inflation (YoY) field each month using the latest headline figure from the National Bureau of Statistics.
Status
## v1.0.2 
- Functional and in active personal use. UI improvements and multi-currency support planned.
## v1.0.3 — 2026-07-03
- Added CSV export grouped by month with monthly totals and carry-over
## v1.1.0 - 2026-10-04
- Visual redesign with dark and light themes. Headline APY is now weighted. See the CHANGELOG
## v1.2.0 - 2026-10-06
- Trends view with balance, net deposits and weighted APY charts. Wider page on desktop. See the CHANGELOG