# Methods and limitations

Model 7.2.1. Frozen on 2026-11-02. Configuration SHA256: cc19695f4f1a48599f5bccc5995f3d76110c861d4ca54f517ae45911868e9331.

Independent student analysis. Not affiliated with, endorsed by or commissioned by Voi.

## Decision and scope

Hub & Book first is the report's proposed strategic priority. Candidates are ranked on the selected pilot-then-expansion plan because that is the proposed investment being appraised; direct rollout is shown alongside on the same baseline. Group confirmation of this ranking-basis decision remains pending. Capital efficiency informs the strategic priority without forcing the economic ranking.

The named report configuration evaluates Hub & Book through pilot then expansion, with 20% dedicated additional placement as an improvement objective. Reference and stress cases change only that share to 25% and 30%. The Oslo market is estimated at 124,822 active customers; sample segment proportions are assumed portfolio weights. This is not an observed customer cohort.

The selected pilot-then-expansion catalogue prefers B1×G3 (Hub paid booking + coordination + split payment) at NOK 1.074860m; the same design gives NOK 1.719723m on direct rollout. Direct rollout is a like-for-like alternative implementation, with one common no-offer baseline. The selected pilot plan is ranked because it is the proposed investment. Group confirmation of that basis remains pending. Capital efficiency does not force the catalogue ranking.

## Capital policy and staging

Require discounted economic value at least 1 times the selected path's maximum cash need and discounted payback by month 24. This is a normative capital-allocation policy, chosen independently of the case result; it is not an observed Voi hurdle or an empirically estimated optimum. The resulting hurdle follows the capital required by the selected configuration. Hub & Book's selected-path hurdle is NOK 623,353 and its value per NOK of cash need is 1.53.

For Hub & Book, direct rollout gives +NOK 1.41m against +NOK 0.95m for pilot then expansion: staging forgoes NOK 0.45m if the improvement assumptions hold. These are conditional full-programme values, not pilot-only outcomes. A failed gate requires stop or redesign, not automatic expansion.

At 30% placement, expanding despite a failed gate gives -NOK 0.85m. Its NOK 905,782 maximum cash need is the month-36 deficit and is still growing at the horizon; it is not an established lifetime peak.

| Placement | Direct rollout value | Pilot + expansion value | Stop after gate value | Stop-path max cash |
| --- | --- | --- | --- | --- |
| 20% | +NOK 1.41m | +NOK 0.95m | -NOK 0.51m | NOK 511,618 |
| 25% | +NOK 0.37m | +NOK 0.11m | -NOK 0.53m | NOK 537,635 |
| 30% | -NOK 0.80m | -NOK 0.85m | -NOK 0.56m | NOK 563,652 |
| 35% | -NOK 2.32m | -NOK 2.08m | -NOK 0.58m | NOK 589,669 |

Stop after the gate includes the remaining wind-down month and excludes later expansion. The pilot protects downside only when its decision rule is followed. The source review evidence is preserved in the JSON with the original v7.2 configuration hash.

## Joint operating and scale sensitivities

| Eligible reach | 20% placement value | 25% placement value |
| --- | --- | --- |
| 40% | +NOK 0.95m | +NOK 0.11m |
| 36% | +NOK 0.72m | -NOK 0.04m |

| Convenience Seeker share | Pilot value | Value / cash | Meets both policy targets |
| --- | --- | --- | --- |
| 25% | +NOK 0.58m | 0.91 | No |
| 20% | +NOK 0.23m | 0.35 | No |

Validate the eligible Convenience Seeker population before launch. Sample weights are applied to the market estimate as a scenario assumption; changing that share also changes the rest of the portfolio composition. One-input thresholds are not a substitute for jointly measured reach, adoption, fulfilment and cost.

Across 3,000 assumed paired combinations, Hub & Book has median +NOK 0.20m, 43.0% below zero and 35.1% meeting both capital-policy targets. These shares describe tested assumptions, not observed probabilities.

## Valuation and cash

Finite-horizon economic contribution = discounted incremental economic contribution against the same no-offer baseline, less resource setup cost. In symbols: value = -resource_setup + sum_m(economic_contribution_m / (1 + annual_discount)^(m/12)). Horizon 36 months; assumed annual discount 10%; no terminal value. Discounted payback refers to economic recovery from project start.

Cash flows and maximum cash need within the horizon use incremental cash expenditure. Where the deficit is still growing at the horizon, this maximum is not a proven lifetime peak. Full internal-office opportunity cost remains in economic value; 100% is treated as extra cash. Maintenance remains cash expenditure. Change the office-hour cash share only when a staffing and financing explanation supports it. Lower cash funding is not an increase in economic value.

Revenue basis: market. Current blended net revenue is 23.0560 NOK per ride. The market allocation and group benchmark are proxies, not observed Oslo marginal economics. PAYG is reconciled after net Pass revenue. Historical Pass pricing and ordinary ride cost remain planning inputs.

## Product assumptions and limitations

| Assumption | Entered planning value | Argument and required evidence |
| --- | --- | --- |
| Hub concentration | 20% additional placement; 40% eligible reach | Select approved hubs and departure windows where usable inventory is already available after the 23:00-05:00 closure. Reduced placement must not simply remove customers. Measure requests, failed searches and extra crew jobs. |
| Service reliability | 95% fulfilment | Verify a usable, sufficiently charged vehicle at the promised location and time. Record failures and remedies; measure reliability jointly with placement and reach. |
| Price and response | NOK 35 fee; 8 bookings per adopter/month | A convenience need does not establish willingness to pay. Test fee conversion and repeat booking among eligible customers; include non-users in the economic evaluation. |
| Demand response | 15% frequent / 30% subscriber adoption at the entered fee | Adoption is price-adjusted from a reference fee; both rates and the response coefficient remain assumptions. Record conversion at tested prices and compare assigned cohorts. |
| Scale and unit economics | 124,822 estimated active customers; 23.06 net NOK/ride | Oslo scale and revenue allocation are constructed estimates. The survey is not representative. Validate city customer counts, segment reach and marginal costs before committing to scale. |
| Internal resource cost | 100% of internal office-hour cost treated as new cash | Keep the full economic opportunity cost. Finance must distinguish hiring, contractor or replacement cash expenditure from existing salaried capacity. |

The behavioural model has occasional, frequent, subscriber and inactive usage states. These do not identify acquaintance, friend or partner relationships. Additional retention, repeat, upgrade and placement-spillover benefits are switched off in this report case. Genuine extra PAYG ride contribution is counted, while extra Pass rides incur operating cost. Discounts on non-additional trips are costs.

Lower additional placement is not an observed efficiency gain. The five-point change is a joint operational hypothesis with unchanged price, reach and fulfilment. It must be tested as a coherent product design, not treated as a free cost reduction.

## Uncertainty, competition and forecasting

The paired analysis uses the pilot implementation path and includes the selected investment and the no-investment comparison. Its assumed ranges and dependencies describe tested combinations, not observed probabilities or calibrated forecasts. A change in ranges changes this scenario experiment; it is not new evidence of product performance. The point result is not a simulated mean.

Competitor imitation and price effects operate through entered demand and relationship mechanisms. The no-offer world is static unless an external stress is applied to both worlds. No proprietary switching barrier or independent protection premium is assumed. The current Oslo permit ends 31 March 2027 (model month 6), before the month-9 gate; renewal is not assumed granted. The 36-month horizon is a conditional medium-term appraisal, extending beyond a hypothetical next 24-month permit term. Booking reserves vehicles inside a capped fleet; the reliability promise could support a later tender but has no separate value premium.

No compatible historical scooter trip series was obtained in this audit. This is a data-availability finding, not proof that none exists. Explicit seasonality scenarios are used. Availability feeds and city-bike trips are not observed Voi trip demand. No Prophet forecast is fitted or claimed.

## Reproducibility

The accompanying JSON contains all configurations, options, assumptions, source IDs and source-code hashes. monthly_results.csv gives pilot and direct-rollout monthly results for all three report cases; implementation_monthly_results.csv gives the selected-pilot-basis catalogue export, with the selected investment identified and direct-rollout values alongside. Figures are computed from the same frozen case. The manifest lists every output hash. The unchanged v7.2 archive retains its original configuration hash and historical evidence pack; it is distinct from this version.

The source register records provenance and limits; academic theories justify mechanisms, not numerical treatment effects. Three genuine first-time-reader checks remain a human acceptance task.

## References

Voi Technology AB (2026). Annual Report and Sustainability Statement 2025, Note 2. https://attachment.news.eu.nasdaq.com/a534eaecb2d7c0996d894f06920f9ee27

Ruter (2026). Årsrapport 2025: Slik reiste vi i 2025. https://ruter.no/rapporter/aarsrapport2025/aaret-2025/slik-reiste-vi-i-2025

European Central Bank. EXR.A.NOK.EUR.SP00.A, annual average 2025.

Statistics Norway (SSB). Table 11418: monthly earnings by occupation, 2025. https://www.ssb.no/statbank/table/11418

Oslo kommune. Leie av elsparkesykler og elsykler: fleet cap, authorised operators and 23:00-05:00 closure. Accessed 2 November 2026. https://www.oslo.kommune.no/gate-transport-og-parkering/sykkel/leie-av-elsparkesykler-og-elsykler/

Oslo kommune. Annual report 2024: awarded operating period 1 April 2025-31 March 2027. Accessed 2 November 2026. https://www.oslo.kommune.no/get-file/461813/087587e9f9ecaedba72c9f43819edaad095c7eaafe4347019ff75bbd36cb2db1/

Our survey dataset VOI_Dataset_Original.sav (n=72, convenience sample), four-cluster solution QCL_4.

Johnson, M. D. & Selnes, F. (2004). Customer portfolio management. Journal of Marketing 68(2), 1–17. https://ecommons.cornell.edu/entities/publication/22d27c0a-b390-418d-a76b-9ebd360bab11

Burnham, T. A., Frels, J. K. & Mahajan, V. (2003). Consumer Switching Costs: A Typology, Antecedents, and Consequences. Journal of the Academy of Marketing Science 31(2), 109–126. Publisher abstract checked; no Voi coefficient transferred. https://doi.org/10.1177/0092070302250897

Osorio, J., Lei, C. & Ouyang, Y. (2021). Optimal rebalancing and on-board charging of shared electric scooters. Transportation Research Part B 147, 197–219. Introduction, p. 197: historical contractor payments for overnight charging and placement. https://par.nsf.gov/servlets/purl/10313347

Selnes, F., & Johnson, M. D. (2022). Manage your customer portfolio for maximum lifetime value. MIT Sloan Management Review, 64(1), 22-27.

Selnes, F., & Lanseng, E. J. (2024). Marketing management: A customer-centric approach. SAGE. Customer Portfolio Management chapter, pp. 141-186.

Gupta, S., Lehmann, D. R., & Stuart, J. A. (2004). Valuing customers. Journal of Marketing Research, 41(1), 7-18.
