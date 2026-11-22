# New Sellers on Seven Checkout Platforms and Fees on a $20 Subscription (2026)

[![DOI: seller counts](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.24386242-blue)](https://doi.org/10.5281/zenodo.24386242)
[![DOI: $20 fees](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.24387071-blue)](https://doi.org/10.5281/zenodo.24387071)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0000--2894--6285-A6CE39)](https://orcid.org/0009-0000-2894-6285)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

A mirror of two summary tables that Jason Zhu ([jasonzhu.ai](https://jasonzhu.ai/en), ORCID [0009-0000-2894-6285](https://orcid.org/0009-0000-2894-6285)) archived on Zenodo. The Zenodo records are the reference; these DOIs always point to their newest version:

- New sellers on seven checkout platforms, 2023 to 15 October 2026: [10.5281/zenodo.24386242](https://doi.org/10.5281/zenodo.24386242)
- Fees taken from a $20 cross-border subscription, eight payment setups (November 2026): [10.5281/zenodo.24387071](https://doi.org/10.5281/zenodo.24387071)

**Corrected on 22 November 2026.** The first versions of both tables (20–21 November 2026) did not match the reports they came from. The seller counts per platform were wrong (Polar was given 2,400 new sellers in 2026; the report says 1,364), there was a Waffo Pancake row with no data behind it, and the fee table put a total without a payout fee beside totals with one. The files here are the corrected ones.

## Files

- `data/platform-adoption-200k-2026.csv`: one row per platform (Stripe, Gumroad, Lemon Squeezy, Polar, Dodo Payments, Creem, Paddle): new sellers since 2025, the share selling software, the share selling AI products, and new sellers per year for Polar, Creem and Dodo Payments (the only per-year figures published).
- `data/new-sellers-by-year.csv`: new sellers across the seven platforms in each year (21,000 in 2023, 29,000 in 2024, 56,000 in 2025, 82,000 in 2026 up to 15 October), rounded as published.
- `data/mor-20usd-subscription-fees-2026.csv`: what one $20 monthly subscription paid with an international card costs under eight payment setups, itemized, with a column saying whether a payout fee is in the total.

## Reading the tables

- A website that links to a platform's checkout page counts as a seller on that platform, dated by the day it first linked. Only sites that still linked in October 2026 are counted, so earlier years are undercounted. The link data comes from DataForSEO's link graph (queried through AIsa on 14–15 October 2026); DataForSEO's terms do not allow redistributing it, so only summary tables are published.
- Shares are within each platform. AI products are 24–29% of new sellers on Dodo Payments, Polar and Creem and 7% on Stripe, but Stripe is so much larger that it has more AI sellers in absolute numbers: about 7,200, against 2,354 new sellers of any kind on the three platforms combined.
- Six fee rows are from Liu Xiaopai's post of 15 November 2026 ([WeChat, in Chinese](https://mp.weixin.qq.com/s/uTtP5zv_exiHa52qSa07BA)); the Paddle and Polar rows are Jason Zhu's arithmetic from published rates. Waffo Pancake's $1.28 leaves out its 1% payout fee. Fees change, so check each platform's current pricing.
- Write-ups: [What 200,000 Checkout Links Say](https://jasonzhu.ai/en/blog/indie-payments-report-2026) · [How to choose a payment platform](https://jasonzhu.ai/en/blog/choose-payment-platform-2026) · [the $20 fee breakdown](https://jasonzhu.ai/en/blog/dodo-payments-waffo-ai-saas-fee-comparison) · [working paper](https://doi.org/10.5281/zenodo.24420870)

## Citation

```bibtex
@dataset{zhu_2026_new_sellers_checkout_platforms,
  author    = {Zhu, Jason},
  title     = {New Sellers on Seven Checkout Platforms, 2023 to 15 October 2026: Summary Tables},
  year      = 2026,
  publisher = {Zenodo},
  doi       = {10.5281/zenodo.24386242}
}

@dataset{zhu_2026_fees_20usd_subscription,
  author    = {Zhu, Jason},
  title     = {Fees Taken from a \$20 Cross-Border Subscription, Itemized for Eight Payment Setups (November 2026)},
  year      = 2026,
  publisher = {Zenodo},
  doi       = {10.5281/zenodo.24387071}
}
```

## License

CC BY 4.0. When you use the fee rows from Liu Xiaopai's post, credit him and link it.
