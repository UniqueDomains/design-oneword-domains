# Available .DESIGN One-Word Domains (7,273)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-7%2C274%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-7%2C273%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated dataset of available and resale .design one-word domains from Unique Domains.

> **Note:** this repository currently mirrors the full live catalog for this exact search.
> Unique Domains counts can still change as the search refreshes.

**Public extract:** 7,274 rows · **Live catalog:** 7,273 domains

**Last updated:** 2026-04-12  
**Canonical page:** `https://unique.domains/domains/tld/design`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/design?utm_source=github&utm_medium=referral&utm_campaign=repo_design_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./design.csv">CSV</a> / <a href="./design.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_design_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_design_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .DESIGN search](https://unique.domains/domains/tld/design?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_design_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .DESIGN search](https://unique.domains/domains/tld/design?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_design_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_design_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .DESIGN one-word domain catalog.

### Files

- `design.csv` — public CSV extract (7,274 rows)
- `design.json` — public JSON extract (7,274 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/design-oneword-domains/main/design.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain            | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                    |
| ----------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | -------------------------------------------- |
| prayer.design     | available | $59.98    | —             | 78             | 22     | 6      | namecheap                                    |
| risk.design       | resell    | $59.98    | —             | 62             | 38     | 4      | Dynadot Inc                                  |
| easy.design       | premium   | $2,500    | $2,500        | 128            | 62     | 4      | name.com                                     |
| wealthy.design    | available | $59.98    | —             | 78             | 22     | 7      | namecheap                                    |
| release.design    | resell    | $59.98    | —             | 98             | 25     | 7      | Dynadot Inc                                  |
| ace.design        | premium   | $812.50   | $812.50       | 88             | 57     | 3      | name.com                                     |
| television.design | available | $59.98    | —             | 104            | 21     | 10     | namecheap                                    |
| checkout.design   | resell    | —         | —             | 68             | 79     | 9      | Dynadot Inc                                  |
| zero.design       | premium   | $125      | $125          | 112            | 53     | 4      | name.com                                     |
| shorts.design     | available | $59.98    | —             | 74             | 21     | 6      | namecheap                                    |
| loop.design       | resell    | —         | —             | 72             | 77     | 4      | Porkbun                                      |
| true.design       | premium   | $812.50   | $812.50       | 86             | 52     | 4      | name.com                                     |
| diligent.design   | available | $59.98    | —             | 68             | 20     | 8      | namecheap                                    |
| get.design        | resell    | —         | —             | 88             | 69     | 3      | Spaceship, Inc.                              |
| game.design       | premium   | $2,500    | $2,500        | 120            | 50     | 4      | name.com                                     |
| mingle.design     | available | $59.98    | —             | 62             | 20     | 6      | namecheap                                    |
| solo.design       | resell    | —         | —             | 116            | 68     | 4      | Xiamen ChinaSource Internet Service Co., Ltd |
| air.design        | premium   | $845      | $845          | 84             | 49     | 3      | namecheap                                    |
| strip.design      | available | $59.98    | —             | 84             | 19     | 5      | namecheap                                    |
| fleet.design      | resell    | —         | —             | 62             | 68     | 5      | Dynadot Inc                                  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 7,274-row public sample | 7,273 live domains                               |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/design?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_design_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/design?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_design_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_design_oneword_domains&utm_content=related_pricing)

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

This repository follows the exact public search represented by the canonical page above.

- This repository is a public extract, not the full live catalog.
- Counts, prices, and statuses can change over time.
- Scores are decision-support signals, not guarantees of resale value.
- Trademark, SEO, and risk signals should be treated as screening inputs, not legal or specialist advice.
- Unique Domains contains deeper filters, monitoring, and decision workflows than this public extract.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .DESIGN One-Word Domains*. Version 2026-04-12. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .DESIGN page](https://unique.domains/domains/tld/design?utm_source=github&utm_medium=referral&utm_campaign=repo_design_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_design_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_design_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_design_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
