# Available .TEL One-Word Domains (10,950)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-10%2C950%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .tel one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **10,950 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 10,950 domains · **Median ask:** $31.25 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-08  
**Canonical page:** `https://unique.domains/domains/tld/tel`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/tel?utm_source=github&utm_medium=referral&utm_campaign=repo_tel_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./tel.csv">CSV</a> / <a href="./tel.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_tel_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_tel_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .TEL search](https://unique.domains/domains/tld/tel?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_tel_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .TEL search](https://unique.domains/domains/tld/tel?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_tel_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_tel_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .TEL one-word domain catalog.

### Files

- `tel.csv` — public CSV extract (1,000 rows)
- `tel.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/tel-oneword-domains/main/tel.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain            | status    | ask_price | renewal_price | attractiveness | demand | length | registrar        |
| ----------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------- |
| insight.tel       | available | $10.99    | —             | 76             | 69     | 8      | name.com         |
| guitar.tel        | resell    | —         | —             | 80             | 29     | 6      | NameCheap, Inc.  |
| Cats.tel          | premium   | $350      | $12.60        | 59             | 33     | 4      | namecheap        |
| letsgo.tel        | available | $10.99    | —             | 57             | 31     | 7      | name.com         |
| toys.tel          | resell    | —         | —             | 60             | 24     | 4      | Name.com, Inc.   |
| slots.tel         | premium   | $610.50   | —             | 49             | 31     | 5      | name.com         |
| inspiration.tel   | available | $10.99    | —             | 88             | 30     | 11     | name.com         |
| Places.tel        | resell    | —         | —             | 74             | 22     | 6      | Dynadot Inc      |
| quotes.tel        | premium   | $1,221    | —             | 58             | 29     | 6      | name.com         |
| blocks.tel        | available | $10.99    | —             | 53             | 29     | 6      | name.com         |
| studios.tel       | resell    | —         | —             | 54             | 21     | 7      | EuroDNS SA       |
| chem.tel          | premium   | $24.42    | —             | 74             | 24     | 4      | name.com         |
| pages.tel         | available | $10.99    | —             | 52             | 28     | 5      | name.com         |
| ladies.tel        | resell    | —         | —             | 80             | 17     | 6      | EuroDNS SA       |
| CapeCod.tel       | premium   | $350      | $12.60        | 78             | 22     | 8      | namecheap        |
| backyard.tel      | available | $10.99    | —             | 80             | 27     | 9      | name.com         |
| updates.tel       | resell    | —         | —             | 54             | 15     | 7      | Dynadot Inc      |
| Alexis.tel        | premium   | $24.42    | —             | 72             | 21     | 6      | name.com         |
| systems.tel       | available | $10.99    | —             | 46             | 27     | 7      | name.com         |
| neighbourhood.tel | resell    | —         | —             | 70             | 14     | 13     | Webnames.ca Inc. |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 10,950 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/tel?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_tel_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/tel?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_tel_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_tel_oneword_domains&utm_content=related_pricing)

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

This selection is focused entirely on .tel domains. The mix includes concise dictionary words, common terms, and a few longer phrase-style names such as appetizing.tel, adolescent.tel, tuesday.tel, and coffeebreak.tel. For founders, the strongest candidates are usually the shortest, easiest-to-pronounce names with broad meaning and low ambiguity. For investors, the key is price discipline: .tel is a narrow extension, so entry price matters more than stretch assumptions. When comparing these domains, weigh memorability, spelling clarity, commercial relevance, and whether the ask leaves room for realistic resale or long holding periods.

- Prioritize short, clear words like see.tel or soil.tel
- Treat longer .tel names as narrower, lower-liquidity bets
- Use the 31.25 median ask as a basic price reality check
- Check for trademark overlap before valuing brandability

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .TEL One-Word Domains*. Version 2026-05-08. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .TEL page](https://unique.domains/domains/tld/tel?utm_source=github&utm_medium=referral&utm_campaign=repo_tel_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_tel_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_tel_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_tel_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
