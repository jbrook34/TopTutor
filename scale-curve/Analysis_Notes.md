# Wireless Scale Curve: Data & Analysis Notes (Verizon vs. T-Mobile)

These are working notes with numbers and talking points. Your instructor asked that the written answers be in your team's own words, so use these to shape your thinking and write the final answers yourselves.

Workbook: `Wireless_Scale_Curve.xlsx`
- **Slope Summary** tab: SLOPE/RSQ regressions and the per-doubling ratio, all live formulas.
- **Verizon** and **T-Mobile** tabs: yearly data, cost per subscriber, and a scale-curve chart with a power trendline.
- **Sources** tab: the filing and URL for each number.

## Method
- **Total costs.** Total operating revenues minus operating income. That equals total operating expenses: cost of service, equipment, SG&A, D&A and impairments. It is not just cost of service.
- **Cost per subscriber.** Total costs ÷ subscribers, in dollars per subscriber per year.
- **Slope.** Fit ln(cost/sub) = a + b·ln(subs). Each doubling multiplies cost per sub by 2^b, so the drop per doubling is 1 − 2^b. This matches Excel's power trendline exponent.
- **Subscriber estimates.** Verizon 2019–2022 come from rounded "approximately X million" segment figures in the 10-Ks (Consumer + Business). They are highlighted yellow in the workbook.

## Results (2014–2025, 12 years each)

| | b | R² | Cost/sub per doubling | Subscriber growth |
|---|---|---|---|---|
| Verizon, all years | −0.77 | 0.89 | **−41%** (59% curve) | +36% |
| Verizon 2014–2020 (pre-TracFone) | −0.78 | 0.42 | −42% | +12% |
| Verizon 2021–2025 | +0.28 | 0.02 | n/m | +4% |
| T-Mobile, all years | +0.17 | 0.15 | **+13%** (costs rose) | +159% |
| T-Mobile 2014–2019 (pre-Sprint) | −0.19 | 0.59 | **−13%** (87% curve) | +56% |
| T-Mobile 2020–2025 (post-Sprint) | −0.95 | 0.70 | **−48%** (52% curve) | +39% |

Cost per subscriber in 2025:
- Verizon: about **$721**, down from $924 in 2014.
- T-Mobile: about **$492**, down from a post-merger peak of $674 in 2021 and back near its 2014 level of $512.
- **T-Mobile has the lowest cost per subscriber every year**. The gap ranges from about 5% below Verizon (2021, right after the Sprint merger) to about 46% below (2019).

## Things worth thinking about for (a)
- **Verizon's steep slope is suspect.** Verizon grew only 36%, so "per doubling" extrapolates well beyond the data. Most of the drop comes from one step: TracFone added about 20M low-cost prepaid lines in late 2021. That is a mix shift, not learning or scale. Without TracFone the fit is weak (R² 0.42).
- **T-Mobile's full-period slope is distorted.** The Sprint merger in 2020 brought integration and merger costs plus Sprint's high-cost network. Cost per sub jumped from $457 to $674 before falling back. The two sub-periods tell the real story: a modest ~87% curve standalone, then a steep ~52% curve while it took out duplicate Sprint costs.
- **The Verizon figures are understated by design.** Verizon's costs include Fios/wireline, which is about 20% of revenue. Verizon stopped reporting a separate wireless P&L after 2018. So Verizon's wireless-only cost per sub is somewhat lower than shown. Even so, it would likely stay above T-Mobile's.
- **Scale alone doesn't explain cost per sub.** Verizon has had more subscribers than T-Mobile in every year (147M vs. 142M in 2025), yet it is the higher-cost firm at every scale. Customer mix (Verizon's premium postpaid and business base), network strategy and spending choices matter at least as much as size.
- **The data is not a clean doubling experiment.** Mergers, accounting recasts (Verizon's 2017 pension change; T-Mobile's 2017 recasts and ASC 606 in 2018), 5G spectrum spending (C-band, 2021–22) and impairments all move the points.

## Things worth thinking about for (b)
**Verizon**
- It is the high-cost incumbent with slow subscriber growth (about 1–2% a year organically). It can't count on growth to push costs down.
- Cost discipline has to come from other levers: cost programs, wireline/Fios efficiency, the Frontier acquisition (fiber) and convergence bundles.
- It needs to keep a price premium (network quality, business customers) to justify higher cost per sub. If price competition from T-Mobile intensifies, margins get squeezed.
- The TracFone-style approach of buying low-cost subscribers lowers average cost per sub but doesn't necessarily raise profit per sub.

**T-Mobile**
- It is the low-cost producer and the fastest grower, adding about 8M customers in 2025. It is still moving down its curve.
- Merger synergies are largely realized now, so future declines will likely look more like the gentler pre-Sprint slope.
- Low cost gives room to undercut on price (the "Un-carrier" playbook) or keep margin. Operating income went from $6.5B in 2022 to $18.3B in 2025.
- Risks: the market is saturated, so growth increasingly has to come from taking share or from fixed wireless and fiber, and that could slow scale gains.

**Industry**
- Wireless is a high-fixed-cost network business, so scale matters. But with three national players at 100M+ subscribers each, the remaining scale economies are smaller than the mix, merger and strategy effects.

## Caveats to state in the submission
- Verizon subscribers for 2019–2022 are estimates from rounded 10-K figures, flagged in the workbook.
- T-Mobile 2015–2017 use figures as recast in the 2017 10-K. 2014 is as originally reported.
- Some figures were confirmed through secondary summaries of the filings, because SEC EDGAR couldn't be reached directly while this was compiled. Spot-check the key numbers against the 10-Ks linked in the Sources tab before submitting.
