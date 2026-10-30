# Methods and limitations

Model 7.2.0. Frozen on 2026-10-30. Configuration SHA256: cc19695f4f1a48599f5bccc5995f3d76110c861d4ca54f517ae45911868e9331.

## Decision and scope

Hub & Book first is the report's proposed strategic priority. The catalogue ranking remains a separate conditional economic comparison; this pack does not force booking to rank first.

The named report configuration evaluates Hub & Book through pilot then expansion, with 20% dedicated additional placement as an improvement objective. Reference and stress cases change only that share to 25% and 30%. The Oslo market is estimated at 124,822 active customers; sample segment proportions are assumed portfolio weights. This is not an observed customer cohort.

The commercial catalogue and the report's pilot implementation are different comparisons. The commercial catalogue's preferred candidate is Hub paid booking + coordination + split payment at +NOK 1.72m. The report does not relabel that result to make its preferred initiative win.

## Valuation and cash

Finite-horizon economic contribution = discounted incremental economic contribution against the same no-offer baseline, less resource setup cost. In symbols: value = -resource_setup + sum_m(economic_contribution_m / (1 + annual_discount)^(m/12)). Horizon 36 months; assumed annual discount 10%; no terminal value. Discounted payback refers to economic recovery from project start.

Cash flows and peak funding use incremental cash expenditure. Full internal-office opportunity cost remains in economic value; 100% is treated as extra cash. Change this share only when a staffing and financing explanation supports it. Lower cash funding is not an increase in economic value.

Revenue basis: market. Current blended net revenue is 23.0560 NOK per ride. The market allocation and group benchmark are proxies, not observed Oslo marginal economics. PAYG is reconciled after net Pass revenue. Historical Pass pricing and ordinary ride cost remain planning inputs.

## Product assumptions and limitations

| Assumption | Entered planning value | Argument and required evidence |
| --- | --- | --- |
| Hub concentration | 20% additional placement; 40% eligible reach | Select approved hubs and time windows with existing usable supply. Reduced placement must be achievable without simply losing customers. Measure geocoded requests, failed searches and incremental crew jobs. |
| Service reliability | 95% fulfilment | Verify a usable, sufficiently charged vehicle at the promised location and time. Record failures and remedies; measure reliability jointly with placement and reach. |
| Price and response | NOK 35 fee; 8 bookings per adopter/month | A convenience need does not establish willingness to pay. Test fee conversion and repeat booking among eligible customers; include non-users in the economic evaluation. |
| Demand response | 15% frequent / 30% subscriber adoption at the entered fee | Adoption is price-adjusted from a reference fee; both rates and the response coefficient remain assumptions. Record conversion at tested prices and compare assigned cohorts. |
| Scale and unit economics | 124,822 estimated active customers; 23.06 net NOK/ride | Oslo scale and revenue allocation are constructed estimates. The survey is not representative. Validate city customer counts, segment reach and marginal costs before committing to scale. |
| Internal resource cost | 100% of internal office-hour cost treated as new cash | Keep the full economic opportunity cost. Finance must distinguish hiring, contractor or replacement cash expenditure from existing salaried capacity. |

The behavioural model has occasional, frequent, subscriber and inactive usage states. These do not identify acquaintance, friend or partner relationships. Additional retention, repeat, upgrade and placement-spillover benefits are switched off in this report case. Genuine extra PAYG ride contribution is counted, while extra Pass rides incur operating cost. Discounts on non-additional trips are costs.

Lower additional placement is not an observed efficiency gain. The five-point change is a joint operational hypothesis with unchanged price, reach and fulfilment. It must be tested as a coherent product design, not treated as a free cost reduction.

## Uncertainty, competition and forecasting

The paired analysis uses the pilot implementation path and includes the selected investment and the no-investment comparison. Its assumed ranges and dependencies describe tested combinations, not observed probabilities or calibrated forecasts. A change in ranges changes this scenario experiment; it is not new evidence of product performance. The point result is not a simulated mean.

Competitor imitation and price effects operate through entered demand and relationship mechanisms. The no-offer world is static unless an external stress is applied to both worlds. No proprietary switching barrier or independent protection premium is assumed. Continued operating rights are a condition, not a proven 36-month entitlement.

No compatible historical scooter trip series was obtained in this audit. This is a data-availability finding, not proof that none exists. Explicit seasonality scenarios are used. Availability feeds and city-bike trips are not observed Voi trip demand. No Prophet forecast is fitted or claimed.

## Reproducibility

The accompanying JSON contains all configurations, options, assumptions, source IDs and source-code hashes. monthly_results.csv gives pilot and commercial monthly results for all three report cases; implementation_monthly_results.csv gives the catalogue comparison export. Figures are computed from the same frozen case. The manifest lists every output hash.

The source register records provenance and limits; academic theories justify mechanisms, not numerical treatment effects. Three genuine first-time-reader checks remain a human acceptance task.

## References

Voi Technology AB (2026). Annual Report and Sustainability Statement 2025, Note 2. https://attachment.news.eu.nasdaq.com/a534eaecb2d7c0996d894f06920f9ee27

Ruter (2026). Årsrapport 2025: Slik reiste vi i 2025. https://ruter.no/rapporter/aarsrapport2025/aaret-2025/slik-reiste-vi-i-2025

European Central Bank. EXR.A.NOK.EUR.SP00.A, annual average 2025.

Statistics Norway (SSB). Table 11418: monthly earnings by occupation, 2025. https://www.ssb.no/statbank/table/11418

Our survey dataset VOI_Dataset_Original.sav (n=72, convenience sample), four-cluster solution QCL_4.

Johnson, M. D. & Selnes, F. (2004). Customer portfolio management. Journal of Marketing 68(2), 1–17. https://ecommons.cornell.edu/entities/publication/22d27c0a-b390-418d-a76b-9ebd360bab11

Burnham, T. A., Frels, J. K. & Mahajan, V. (2003). Consumer Switching Costs: A Typology, Antecedents, and Consequences. Journal of the Academy of Marketing Science 31(2), 109–126. Publisher abstract checked; no Voi coefficient transferred. https://doi.org/10.1177/0092070302250897

Osorio, J., Lei, C. & Ouyang, Y. (2021). Optimal rebalancing and on-board charging of shared electric scooters. Transportation Research Part B 147, 197–219. Introduction, p. 197: historical contractor payments for overnight charging and placement. https://par.nsf.gov/servlets/purl/10313347

Selnes, F., & Johnson, M. D. (2022). Manage your customer portfolio for maximum lifetime value. MIT Sloan Management Review, 64(1), 22-27.

Selnes, F., & Lanseng, E. J. (2024). Marketing management: A customer-centric approach. SAGE. Customer Portfolio Management chapter, pp. 141-186.

Gupta, S., Lehmann, D. R., & Stuart, J. A. (2004). Valuing customers. Journal of Marketing Research, 41(1), 7-18.
