# Stripe vs Polar vs Dodo Payments vs Creem vs Paddle (2026): Indie SaaS Payment & Merchant of Record Benchmark

[![CERN Zenodo DOI](https://img.shields.io/badge/Zenodo%20DOI-10.5281%2Fzenodo.24386243-blue)](https://doi.org/10.5281/zenodo.24386243)
[![$20 Fee Benchmark DOI](https://img.shields.io/badge/Fee%20Benchmark%20DOI-10.5281%2Fzenodo.24387072-blue)](https://doi.org/10.5281/zenodo.24387072)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

Open empirical benchmark by **Jason Zhu ([jasonzhu.ai](https://jasonzhu.ai/en))** comparing **Stripe, Polar, Dodo Payments, Creem, Waffo Pancake, Paddle, Lemon Squeezy, and Gumroad** across **~200,000 live checkout links** (2023–2026) and real-world **$20 AI SaaS subscription fees**.

- **Full Adoption Report**: [What 200,000 Checkout Links Say: The 2026 Indie Payments Report](https://jasonzhu.ai/en/blog/indie-payments-report-2026)
- **8-Platform Comparison Guide**: [How to Choose a Payment Platform as an Indie Developer (2026)](https://jasonzhu.ai/en/blog/choose-payment-platform-2026)
- **Dual-Gateway $20 Fee Teardown**: [Waffo + Dodo Payments vs Stripe HK & Lemon Squeezy](https://jasonzhu.ai/en/blog/dodo-payments-waffo-ai-saas-fee-comparison)
- **Interactive Selector Tool**: [Go-Global Payment Platform Picker](https://jasonzhu.ai/en/go-global/payments)

---

## Key Empirical Findings (Data through October 15, 2026)

1. **Rapid indie seller growth:** 21,000 new sellers in 2023 → 29,000 in 2024 → 56,000 in 2025 → **82,000 in 2026 (Jan–Oct 15)**.
2. **Software & AI surge:** Software share among new sellers rose from **5% (2023)** to **20% (Sept 2026)**; AI products climbed from **2% to 12%**.
3. **AI founders pick Merchant of Record (MoR) platforms over Stripe:** Since 2025, **29%** of new Dodo Payments sellers, **27%** of Polar sellers, and **24%** of Creem sellers ship AI products — versus **7%** on Stripe and **8%** on Gumroad.
4. **Lemon Squeezy migration window:** Lemon Squeezy announced in November 2026 that it will stop processing payments on **March 31, 2027**, pushing SaaS founders toward Stripe Managed Payments, Polar, Dodo Payments, Creem, Paddle, or Waffo.

---

## 1. 2026 Pricing, Merchant of Record Fees & $20 SaaS Net Take-Home

Fees verified against official pricing pages (Oct–Nov 2026). Full machine-readable table in [`data/mor-20usd-subscription-fees-2026.csv`](data/mor-20usd-subscription-fees-2026.csv).

| Platform | MoR (Global VAT/Sales Tax) | Published Base Fee | Extra Surcharges | Est. Taken on $20 Sub | Net Kept on $20 | Mainland China Payouts |
|---|---|---|---|---|---|---|
| **Dodo Payments** (Partner Rate) | Yes | `3.8%–3.9% + $0.40` | None (`$0` payout at `$1,000+`) | `$1.16–$1.18` | **`$18.82–$18.84`** | Yes (Bank / ID) |
| **Waffo Pancake** | Yes | `3.9% + $0.50` | None (`1%` payout, `$10` min) | `$1.28` | **`$18.72`** | Yes (Alipay / Bank) |
| **Creem** | Yes | `3.9% + $0.40` | None (`1%` or `$7` payout) | `$1.37` | **`$18.63`** | Yes (Alipay / Bank) |
| **Paddle** | Yes | `5.0% + $0.50` | All-in | `$1.50` | **`$18.50`** | Yes |
| **Dodo Payments** (Default Rate) | Yes | `4.0% + $0.40` | `+1.5%` intl, `+0.5%` sub | `$1.60` | **`$18.40`** | Yes (Bank / ID) |
| **Stripe HK** (Billing+Tax+FX) | No (+3.5% Managed) | `3.4% + $0.30` | `+0.5%` intl, `+0.7%` Billing, `+2.5%` FX/Tax | `$1.79` | **`$18.21`** | Requires HK/US entity |
| **Polar** (Post May 27, 2026) | Yes | `5.0% + $0.50` (or `3.4%–3.8%` plans) | `+1.5%` international | `$1.80` | **`$18.20`** | No |
| **Lemon Squeezy** *(sunsetting Mar 2027)* | Yes | `5.0% + $0.50` | `+1.5%` non-US, `+0.5%` sub, `+1%` payout | `$2.08` | **`$17.92`** | PayPal only |
| **Stripe US** (Base card only) | No (+3.5% Managed) | `2.9% + $0.30` | `+1.5%` intl, `+1%` FX | `$0.88` (US dom.) | `$19.12` (pre-tax) | Requires US entity |
| **Gumroad** | Yes (since 2025) | `10% + $0.50` + `2.9% + $0.30` | `30%` on Discover | `$3.38+` | `~$16.62` | PayPal only |

---

## 2. Empirical Adoption Across ~200,000 Checkout Links (2025–2026)

Full CSV in [`data/platform-adoption-200k-2026.csv`](data/platform-adoption-200k-2026.csv). Methodology: DataForSEO link graph (Oct 14–15, 2026) tracking unique domains linking to platform checkout URLs, excluding shared multi-site spam/repost links (17,000 sites excluded).

| Platform | New Sellers Since 2025 | Software Share | AI Product Share | 2024 → 2025 → 2026 (to Oct 15) |
|---|---:|---:|---:|---|
| **Stripe** | 102,590 | 9% | 7% | Largest total base (mostly services/local/general) |
| **Gumroad** | 28,860 | 11% | 8% | Dominated by ebooks, templates & courses |
| **Lemon Squeezy** | 4,637 | 36% | 15% | Sunsetting payments on March 31, 2027 |
| **Polar** | 1,664 | 58% | 27% | `55` → `305` → `1,364` |
| **Dodo Payments** | 441 | 71% | 29% | `0` → `68` → `373` |
| **Creem** | 249 | 65% | 24% | `1` → `38` → `211` |
| **Paddle** *(classic links)* | 84 | 56% | 5% | Primarily JS overlay checkout (under-represented in link graph) |

---

## 3. Quick Decision Matrix by Founder Profile

- **AI SaaS / indie tool founder wanting Merchant of Record (global VAT/GST handled):** **Polar** (GitHub-native, US/EU/HK entities), **Dodo Payments**, **Creem**, **Waffo Pancake**, or **Paddle**.
- **Mainland China individual founder without an overseas entity:** **Dodo Payments**, **Creem**, or **Waffo Pancake** (all act as MoR and support mainland payouts; Stripe and Polar do not support mainland China payouts).
- **US LLC or HK company optimizing for high-volume domestic US card rates:** **Stripe** (add Stripe Managed Payments at `+3.5%` if you want MoR tax compliance).
- **Migrating off Lemon Squeezy before March 31, 2027:** Compare **Dodo Payments**, **Polar**, **Creem**, **Paddle**, and **Stripe Managed Payments** using the `$20` effective take-home table above.

---

## Data Files

- [`data/platform-adoption-200k-2026.csv`](data/platform-adoption-200k-2026.csv) — Platform-level seller counts, software/AI shares, and YoY trajectories (2024–2026).
- [`data/mor-20usd-subscription-fees-2026.csv`](data/mor-20usd-subscription-fees-2026.csv) — Line-by-line `$20` international AI SaaS subscription fee breakdown.

## Citation

If you use these tables in an article, documentation, or benchmark, please cite the CERN Zenodo archives:

```bibtex
@dataset{zhu_2026_indie_payments_200k,
  author       = {Zhu, Jason},
  title        = {200,000 Indie Developer Checkout Links and Payment Platform Adoption Benchmark (2023-2026)},
  year         = 2026,
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.24386243},
  url          = {https://jasonzhu.ai/en/blog/indie-payments-report-2026}
}

@dataset{zhu_2026_mor_20usd_fees,
  author       = {Zhu, Jason},
  title        = {$20 Cross-Border AI SaaS Subscription Fee Benchmark Across Payment Gateways and MoRs (2026)},
  year         = 2026,
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.24387072},
  url          = {https://jasonzhu.ai/en/blog/choose-payment-platform-2026}
}
```

## License

Data and documentation are released under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Attribution: Jason Zhu ([jasonzhu.ai](https://jasonzhu.ai/en)).
