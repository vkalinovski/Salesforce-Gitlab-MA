# Salesforce → GitLab: Hypothetical M&A

**Recommendation: do not acquire at the modeled $62.29 offer; pursue a commercial partnership.**

## Executive summary

The proposed purchase combines a plausible workflow adjacency with an unattractive base financial case. At a 25% premium, recurring EPS dilution is **-9.7% in Year 1** and **-5.9% in Year 3**, including SBC and incremental purchase amortization. Run-rate savings of **$99.6m** are insufficient: Year 3 EPS neutrality requires **$878.5m**. The SBC-explicit Gordon DCF and net synergies imply an economic break-even price of **$24.03**, below both market and offer.

## Key deal metrics

| Metric | Base case |
|---|---:|
| Reference GitLab close | $49.83 |
| Illustrative offer / premium | $62.29 / 25.0% |
| Equity consideration | $10.73bn |
| Transaction enterprise value | $9.57bn |
| EV / FY2027E revenue | 8.5× |
| Cash / debt / stock | 25% / 25% / 50% |
| Incremental debt cost | 6.5% |
| Run-rate cost synergies | $99.6m |
| Year 3 recurring EPS impact | -5.9% |
| Buyer NPV before financing frictions | ($6.37)bn |
| Economic break-even offer / share | $24.03 |
| Year 3 EPS-neutral offer / share | $19.84 |

## Accretion / dilution

Recurring EPS includes new PPA and SBC. All-in EPS also includes transaction fees and integration costs. The workbook shows a separate supplemental view excluding new PPA while retaining SBC; this is not company-reported non-GAAP EPS.

## Valuation

Gordon DCF: **$20.31** per share. Exit DCF: **$33.24** at 20× GAAP EBIT. Trading comps imply **$53.26–$108.63**, using limited peers and explicit share / forward-revenue proxies. The disagreement is not resolved by averaging methods. The HashiCorp observation is a single marker, not a precedent range; a dated 52-week range is unavailable.

## Strategic rationale

GitLab could extend Salesforce's enterprise workflow ecosystem into software delivery and DevSecOps. Slack integrations, co-selling and customer pilots can test those benefits before paying a control premium. The base case assigns **zero revenue synergy** and excludes R&D cuts

## Explore the model

The Excel workbook has 20 visible tabs: source facts, both standalone forecasts, comps, two DCF methods, transaction bridge, Sources & Uses, PPA, synergies, pro forma earnings, A/D, sensitivities, live valuation chart, precedents, opening balance and checks.

- Begin at `15_Output`, then `13_Accretion_Dilution` and `14_Sensitivities`.
- Edit central blue inputs in `01_Assumptions`. Green formulas link tabs; black formulas calculate within a tab. Historical / market hardcodes are blue too, with sources identifying their type.
- Test premiums, synergy multiplier, debt rate and funding mix. Six funding structures, 25 premium / savings cases and 25 WACC / growth cases recalculate the transaction mechanics.
- `18_Checks` has **14 arithmetic controls, all passing**. Dynamic tests and an independent audit are in `analysis/`.




