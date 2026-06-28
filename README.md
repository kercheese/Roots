# Roots

**What your family keeps and builds, city by city.**

Roots is an iOS-style web app that compares the real cost of raising a family across 12 cities — not just rent and salaries, but what's actually left after taxes, childcare, healthcare, and housing, and how that compounds into wealth over time.

## Why it exists

"City A pays more" is rarely the real answer. A higher salary can vanish into taxes, childcare, and rent — while a lower-paying city with free healthcare and subsidized daycare quietly leaves you better off. Roots models the whole picture so the comparison is honest.

## What it does

- **12 cities, 8 tax systems** — New York, Chicago, Austin, Miami, Paris, Berlin, Toronto, Vancouver, London, Tokyo, Sydney, Singapore.
- **Effective tax, not headline rates** — real brackets plus the deductions and credits families actually take.
- **Childcare that ages out** — under-3 daycare costs disappear as kids reach free school, modeled over the time horizon.
- **Healthcare as expected value** — a probability-weighted typical year plus a rare costly one, which is where the US vs. Europe gap really lives.
- **Rent vs. buy** — mortgage, property tax, and home-equity accumulation.
- **Total compensation** — optional employer-side costs (French social charges, US employer health premiums, pension match).
- **Purchasing-power view** — what the money actually buys locally, not just nominal dollars.
- **Multi-year projection** — cumulative wealth built, where the lines cross is the real answer.

## Add it to your home screen

1. Open the live app URL in **Safari** (iPhone) or **Chrome** (Android).
2. iPhone: **Share → Add to Home Screen**. Android: **⋮ → Add to Home screen**.
3. It launches full-screen, like a native app.

## Sources & confidence

Every figure is confidence-tagged: verified (primary/official source), triangulated (several sources), or estimate (representative average). Rent comes from official observatories and major platforms (OLAP, TRREB, ONS, StreetEasy, RentCafe). Taxes from IRS, DGFiP, CRA, HMRC, OECD, and PwC. Salaries from levels.fyi, BLS, and Canada Job Bank. Full methodology is in the app's **Sources** tab.

## Disclaimer

Roots produces rounded, illustrative estimates for comparison — not financial, tax, or relocation advice, and not a personal quote. Always verify against your own situation.

---

Built as a single self-contained HTML file. No build step, no dependencies beyond Chart.js (loaded from a CDN).
