# Methods and limitations / Voi Portfolio Lab 7

Frozen configuration: `4fc8f515adf767ee3fb3815588d8df7d47faae9a51b0699f2c47d56900aca49a`. Model 7.0.0; generated 2026-10-28T15:16:57.934Z.

## Research question
Under what customer, operational and competitive conditions do Hub & Book and Voi Together deserve investment, and what evidence changes that decision?

## Scope and computation
The starting portfolio has 10,000 illustrative active customers, sample-derived segment weights and replacement inflow. It is not an observed Voi cohort or a closed attrition-only cohort. Horizon: 36 months; annual discount: 10%; no terminal value.

ΔCPE = sum over months of [(offer operating cash − no-offer operating cash) / (1 + annual discount)^(month/12)] − setup.

This is finite-horizon incremental discounted operating contribution, not full lifetime customer equity. Four usage states (occasional, frequent, subscriber, inactive) must not be equated with acquaintance/friend/partner relationships.

Revenue is net of VAT. The starting blended net revenue benchmark is 178.2m EUR /115.815m rides ×11.7173 NOK/EUR = 18.0290 NOK/ride. It is a group average proxy. PAYG revenue is the residual after net Pass revenue, not an observed PAYG tariff. The 399 kr Pass is a historical planning benchmark, not a verified current Oslo price. Average vehicle cost is not measured Oslo marginal cost.

Retention effects are relative reductions among exposed bookers/hosts, bounded before exposure weighting. They start at zero. Repeat, upgrade and placement spillover start at zero. Acquisition, adoption, additionality, costs and baseline dynamics remain assumptions. Zero placements produce zero placement-driven spillover. Guest acquisition is valued through subsequent states, with no up-front CLV added.

Default fee response 1 and group incentive response 2 are deliberately explicit, unestimated planning hypotheses. Tested ranges include zero response and alternatives; these are not estimated confidence intervals. Do not infer willingness to pay from Q25/Q26. Uncertainty draws use paired triangular scenario ranges and assumed dependency, not observed probabilities of business success.

Launch investment includes scale-up purchased at launch in direct rollout. Peak cash is the deepest cumulative undiscounted deficit. The 750,000 kr launch budget is a design allowance, not specified by Assignment 2. No total funding ceiling is entered, so cash affordability is unconfirmed.

## Frozen finding
All active investments have negative current-case value at the chosen scale and build assumptions. Both offers: −1.78 MNOK, launch 669,104 kr, peak funding 1,953,210 kr. The appropriate current-case result is no investment. This does not establish that either customer proposition is intrinsically unviable; right-sized delivery cost, scale and behaviour require investigation. Fixed costs have not been reduced to make the case positive.

The v6.6 result of +4.18 MNOK uses a different scope, different assumptions and old mechanics. It is retained as an archive, not used as evidence of v7 accuracy.

## Competition and theory
Use course literature critically: Johnson & Selnes (2004) and Selnes & Lanseng (2024) motivate dynamic portfolio allocation; Burnham, Frels & Mahajan (2003) distinguishes procedural, financial and relational switching costs. Satisfaction, retention and switching barriers are different constructs. A group invitation network is not automatically proprietary to Voi. Rival imitation, relative price disadvantage and fading retention advantages are scenario mechanisms, with no separate defence premium.

Mobility studies identify operating mechanisms and cost categories, not treatment effects or exact Oslo costs. In particular Kabra, Belavina & Girotra (2020), Management Science 66(9), 3803–3824, doi:10.1287/mnsc.2019.3407, is a bike-share analogue. The current survey supports segment descriptions, not representative shares or causal coefficients.

## Forecasting
No compatible historical scooter trip series was obtained in this audit. This is a data-availability finding, not proof that none exists. Explicit seasonality scenarios are used. No Prophet model was fitted to invented or analogue-as-Voi data. The optional pipeline requires completed scooter trips, documented comparable regimes and rolling validation. Three forecast origins compare 30/90-day errors against a seasonal baseline. Future demand indices enter both intervention and counterfactual once; no aggregate forecast estimates offer adoption or retention.

## Reproduction
Run generate_pack.cjs, then make_evidence_pack.py. The JSON contains frozen inputs, all four results, monthly cash, analysis, provenance and source identifiers. The CSV contains all monthly cash flows. Preserve the hash and model version when copying any figure into the paper.
