# Available .VIN One-Word Domains (12,390)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C390%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .vin one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,390 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,390 domains · **Median ask:** $17.92 · **High-demand under $2,500:** 2

**Last updated:** 2026-08-06
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

- `vin.csv`, public CSV extract (1,000 rows)
- `vin.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/vin-oneword-domains/main/vin.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain    | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                    |
| --------- | --------- | --------- | ------------- | -------------- | ------ | ------ | -------------------------------------------- |
| yes.vin   | premium   | $118.80   | $118.80       | high           | medium | 3      | namesilo                                     |
| axe.vin   | available | $11.99    | —             | medium         | low    | 3      | name.com                                     |
| air.vin   | resell    | $11.99    | —             | high           | medium | 3      | Xiamen ChinaSource Internet Service Co., Ltd |
| Ava.vin   | premium   | $500      | —             | high           | medium | 3      | name.com                                     |
| cap.vin   | available | $11.99    | —             | high           | low    | 3      | name.com                                     |
| drone.vin | resell    | $11.99    | —             | high           | medium | 5      | Dynadot Inc                                  |
| moi.vin   | premium   | $118.80   | $118.80       | high           | low    | 3      | namesilo                                     |
| end.vin   | available | $11.99    | —             | high           | low    | 3      | name.com                                     |
| for.vin   | resell    | —         | —             | high           | medium | 3      | DNSPod, Inc.                                 |
| usa.vin   | premium   | $242      | $242          | high           | medium | 3      | namesilo                                     |
| hum.vin   | available | $11.99    | —             | high           | low    | 3      | name.com                                     |
| fun.vin   | resell    | —         | —             | high           | medium | 3      | Xiamen ChinaSource Internet Service Co., Ltd |
| web.vin   | premium   | $500      | —             | high           | medium | 3      | name.com                                     |
| ive.vin   | available | $11.99    | —             | medium         | low    | 3      | name.com                                     |
| hit.vin   | resell    | —         | —             | high           | low    | 3      | NameCheap, Inc.                              |
| wow.vin   | premium   | $242      | $242          | high           | medium | 3      | namesilo                                     |
| lip.vin   | available | $11.99    | —             | high           | low    | 3      | name.com                                     |
| free.vin  | resell    | —         | —             | high           | medium | 4      | NameSilo, LLC                                |
| odd.vin   | available | $11.99    | $77.99        | high           | low    | 3      | name.com                                     |
| block.vin | resell    | —         | —             | medium         | low    | 5      | Xiamen ChinaSource Internet Service Co., Ltd |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,390 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 2 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/vin?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_vin_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/vin?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_vin_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_vin_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This list covers one-word .vin domain names — compact, single-token names without hyphens or numbers, spanning everyday words, short phrases, and brandable terms like flaxseed.vin or makesense.vin. With 12,382 domains and a median ask near $19, most of this selection remains inexpensive to acquire outright, giving investors scanning for volume and founders searching for a memorable name plenty to evaluate. Updated daily, the list reflects current asking prices across the .vin extension.

- 12,382 one-word .vin domain names in this set
- Median asking price near $19 across the list
- Single-token names — no hyphens or numbers
- Updated daily to reflect current asking prices

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .VIN One-Word Domains*. Version 2026-08-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .VIN page](https://unique.domains/domains/tld/vin?utm_source=github&utm_medium=referral&utm_campaign=repo_vin_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_vin_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_vin_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_vin_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
