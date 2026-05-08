# Available .MENU One-Word Domains (12,457)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C457%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .menu one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,457 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,457 domains · **Median ask:** $36.98 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-08  
**Canonical page:** `https://unique.domains/domains/tld/menu`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/menu?utm_source=github&utm_medium=referral&utm_campaign=repo_menu_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./menu.csv">CSV</a> / <a href="./menu.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_menu_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_menu_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .MENU search](https://unique.domains/domains/tld/menu?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_menu_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .MENU search](https://unique.domains/domains/tld/menu?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_menu_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_menu_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .MENU one-word domain catalog.

### Files

- `menu.csv` — public CSV extract (1,000 rows)
- `menu.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/menu-oneword-domains/main/menu.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain             | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| ------------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| regions.menu       | available | $38.98    | —             | 64             | 59     | 7      | namecheap |
| pops.menu          | premium   | $41.30    | $41.30        | 74             | 24     | 4      | namesilo  |
| keepthechange.menu | available | $38.98    | —             | 46             | 59     | 15     | namecheap |
| tracks.menu        | premium   | $44.99    | —             | 60             | 18     | 6      | name.com  |
| tokens.menu        | available | $27.99    | $27.99        | 51             | 36     | 6      | namesilo  |
| skies.menu         | premium   | $44.99    | —             | 63             | 11     | 5      | name.com  |
| aliens.menu        | available | $27.99    | $27.99        | 56             | 35     | 6      | namesilo  |
| wraps.menu         | premium   | $41.30    | $41.30        | 53             | 11     | 5      | namesilo  |
| payments.menu      | available | $38.98    | —             | 58             | 33     | 8      | namecheap |
| HoChiMinhCity.menu | premium   | $41.30    | $41.30        | 64             | 7      | 16     | namesilo  |
| spaces.menu        | available | $38.98    | —             | 54             | 30     | 6      | namecheap |
| YouTube.menu       | premium   | —         | —             | 94             | 96     | 7      | —         |
| heroes.menu        | available | $38.98    | —             | 68             | 29     | 6      | namecheap |
| Walmart.menu       | premium   | —         | —             | 92             | 94     | 7      | —         |
| trades.menu        | available | $27.99    | $27.99        | 71             | 26     | 6      | namesilo  |
| IsleofMan.menu     | premium   | —         | —             | 62             | 91     | 11     | —         |
| sites.menu         | available | $38.98    | —             | 53             | 26     | 5      | namecheap |
| CocaCola.menu      | premium   | —         | —             | 92             | 82     | 9      | —         |
| destination.menu   | available | $38.98    | —             | 90             | 25     | 11     | namecheap |
| RedSox.menu        | premium   | —         | —             | 72             | 60     | 7      | —         |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,457 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/menu?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_menu_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/menu?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_menu_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_menu_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This selection is entirely made up of one-word .menu domains. The words range from direct food and service cues like breakfast.menu to broader dictionary terms like raise.menu, phrase.menu, and positive.menu. For founders, the main question is whether the word makes the .menu ending feel natural, memorable, and easy to trust. For investors, the focus is tighter: whether the term has clear commercial relevance, realistic resale appeal, and a low enough entry point relative to the median ask of 36.98. In this set, stronger names usually read cleanly, avoid ambiguity, and pair naturally with restaurant, dining, ordering, or hospitality use cases.

- Prefer words that make natural sense with .menu
- Use price discipline around the 36.98 median ask
- Check ambiguity in broad terms like phrase or positive
- Favor memorable, commercial words like breakfast or raise

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .MENU One-Word Domains*. Version 2026-05-08. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .MENU page](https://unique.domains/domains/tld/menu?utm_source=github&utm_medium=referral&utm_campaign=repo_menu_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_menu_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_menu_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_menu_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
