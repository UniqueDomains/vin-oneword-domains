# Available .VIN One-Word Domains (12,374)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C374%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .vin one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,374 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,374 domains · **Median ask:** $22.41 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
**Canonical page:** `https://unique.domains/domains/tld/vin`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/vin?utm_source=github&utm_medium=referral&utm_campaign=repo_vin_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./vin.csv">CSV</a> / <a href="./vin.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_vin_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_vin_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .VIN search](https://unique.domains/domains/tld/vin?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_vin_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .VIN search](https://unique.domains/domains/tld/vin?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_vin_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_vin_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .VIN one-word domain catalog.

### Files

- `vin.csv` — public CSV extract (1,000 rows)
- `vin.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/vin-oneword-domains/main/vin.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain          | status    | ask_price | renewal_price | attractiveness | demand | length | registrar    |
| --------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------ |
| prompts.vin     | available | $11.99    | —             | 54             | 39     | 7      | name.com     |
| coins.vin       | resell    | —         | —             | 56             | 41     | 5      | DNSPod, Inc. |
| bonappetit.vin  | premium   | $123.75   | —             | 86             | 8      | 11     | name.com     |
| etc.vin         | available | $11.99    | —             | 58             | 34     | 3      | name.com     |
| alcoholfree.vin | premium   | $82.50    | —             | 70             | 6      | 12     | name.com     |
| teams.vin       | available | $11.99    | —             | 62             | 32     | 5      | name.com     |
| trends.vin      | available | $11.99    | —             | 60             | 32     | 6      | name.com     |
| solutions.vin   | available | $11.99    | —             | 56             | 31     | 9      | name.com     |
| rewards.vin     | available | $11.99    | —             | 62             | 30     | 7      | name.com     |
| popup.vin       | available | $11.99    | —             | 84             | 29     | 6      | name.com     |
| SanDiego.vin    | available | $11.99    | —             | 74             | 29     | 9      | name.com     |
| blocks.vin      | available | $11.99    | —             | 53             | 29     | 6      | name.com     |
| cams.vin        | available | $11.99    | —             | 52             | 29     | 4      | name.com     |
| pages.vin       | available | $11.99    | —             | 52             | 28     | 5      | name.com     |
| backyard.vin    | available | $11.99    | —             | 80             | 27     | 9      | name.com     |
| KFC.vin         | available | $75.98    | —             | 74             | 27     | 3      | namecheap    |
| trades.vin      | available | $11.99    | —             | 71             | 26     | 6      | name.com     |
| has.vin         | available | $11.99    | —             | 60             | 26     | 3      | name.com     |
| traders.vin     | available | $11.99    | —             | 60             | 26     | 7      | name.com     |
| sites.vin       | available | $11.99    | —             | 53             | 26     | 5      | name.com     |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,374 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/vin?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_vin_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/vin?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_vin_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_vin_oneword_domains&utm_content=related_pricing)

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

This selection is entirely made up of one-word .vin domains. The set ranges from direct, simple terms such as clean.vin and office.vin to broader words like society.vin and extraordinary.vin. For founders, the best choices are usually the names that are easy to say, easy to spell, and closely aligned with a wine-related brand or product. For investors, the key question is whether the word has enough commercial meaning inside the .vin extension to support resale interest. With a median ask of 22.41, price discipline matters less than choosing words with clear fit, strong recall, and manageable renewal expectations.

- Prefer words that fit wine, hospitality, retail, or tasting
- Short, clear spelling usually improves recall and trust
- Check if the word feels natural with the .vin extension
- Avoid terms with possible trademark or weak commercial fit

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .VIN One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .VIN page](https://unique.domains/domains/tld/vin?utm_source=github&utm_medium=referral&utm_campaign=repo_vin_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_vin_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_vin_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_vin_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
