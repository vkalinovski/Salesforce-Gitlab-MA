# Salesforce → GitLab: Hypothetical M&A

**Recommendation: do not acquire at the modeled $62.29 offer; pursue a commercial partnership.**

An investment-banking recruiting case linking strategic rationale, valuation, transaction financing, purchase accounting, cost synergies and pro forma EPS. Information as of **4 September 2026**; assumed closing **1 February 2027**. Independent hypothetical analysis, with provisional analyst assumptions for owner review.

[Download Excel model](models/Salesforce_GitLab_Merger_Model.xlsx) · [Read pitchbook PDF](presentation/Salesforce_GitLab_MA_Pitchbook.pdf) · [Editable PPTX](presentation/Salesforce_GitLab_MA_Pitchbook.pptx)

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

![EPS dilution by year](assets/accretion_dilution.png)

Recurring EPS includes new PPA and SBC. All-in EPS also includes transaction fees and integration costs. The workbook shows a separate supplemental view excluding new PPA while retaining SBC; this is not company-reported non-GAAP EPS.

## Valuation

![Valuation football field](assets/valuation_football_field.png)

Gordon DCF: **$20.31** per share. Exit DCF: **$33.24** at 20× GAAP EBIT. Trading comps imply **$53.26–$108.63**, using limited peers and explicit share / forward-revenue proxies. The disagreement is not resolved by averaging methods. The HashiCorp observation is a single marker, not a precedent range; a dated 52-week range is unavailable.

## Strategic rationale

GitLab could extend Salesforce's enterprise workflow ecosystem into software delivery and DevSecOps. Slack integrations, co-selling and customer pilots can test those benefits before paying a control premium. The base case assigns **zero revenue synergy** and excludes R&D cuts. [Strategic rationale](analysis/strategic_rationale.md) · [Risks](analysis/risks.md)

## Explore the model

The Excel workbook has 20 visible tabs: source facts, both standalone forecasts, comps, two DCF methods, transaction bridge, Sources & Uses, PPA, synergies, pro forma earnings, A/D, sensitivities, live valuation chart, precedents, opening balance and checks.

- Begin at `15_Output`, then `13_Accretion_Dilution` and `14_Sensitivities`.
- Edit central blue inputs in `01_Assumptions`. Green formulas link tabs; black formulas calculate within a tab. Historical / market hardcodes are blue too, with sources identifying their type.
- Test premiums, synergy multiplier, debt rate and funding mix. Six funding structures, 25 premium / savings cases and 25 WACC / growth cases recalculate the transaction mechanics.
- `18_Checks` has **14 arithmetic controls, all passing**. Dynamic tests and an independent audit are in `analysis/`.

## Read before presenting

Key assumptions are provisional, as requested in the brief. Review [the decision sheet](analysis/assumptions_for_review.md) before adopting the recommendation. The model is a recruiting case, not a claim of completed transaction diligence.

Material limitations: full original 10-K / 10-Q documents are **not archived**; factual extracts and a dated source register are supplied. Peer shares / forward revenues, deal awards, WACC, tax realization, PPA and closing balances use disclosed proxies or assumptions. Only one precedent has a verified EV / revenue calculation. PDF pages preserve slide appearance as images with searchable headings; PPTX content remains editable.

[Methodology](analysis/methodology.md) · [Source register](sources/sources.md) · [Valuation detail](analysis/valuation_summary.md) · [Interview guide](analysis/interview_guide.md) · [Rebuild instructions](scripts/README.md)

## Repository layout

| Folder | Contents |
|---|---|
| `models/` | Dynamic Excel merger model |
| `presentation/` | 17-slide editable PPTX and matching PDF |
| `data/raw/` | Source inventory and preserved factual extraction; archive limitations |
| `data/processed/` | Historical CSVs, assumptions, formula inventory and calculated snapshot |
| `analysis/` | Methodology, strategy, risks, valuation, review sheet and validation |
| `sources/` | Linked source register |
| `assets/` | README charts generated from the model |
| `scripts/` | Rebuild / refresh scripts and environment requirements |


