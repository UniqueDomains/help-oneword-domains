# Available .HELP One-Word Domains (15,959)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-15%2C959%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .help one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **15,959 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 15,959 domains · **Median ask:** $35.66 · **High-demand under $2,500:** 34

**Last updated:** 2026-08-20
**Canonical page:** `https://unique.domains/domains/tld/help`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/help?utm_source=github&utm_medium=referral&utm_campaign=repo_help_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./help.csv">CSV</a> / <a href="./help.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_help_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_help_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .HELP search](https://unique.domains/domains/tld/help?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_help_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .HELP search](https://unique.domains/domains/tld/help?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_help_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_help_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .HELP one-word domain catalog.

### Files

- `help.csv`, public CSV extract (1,000 rows)
- `help.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/help-oneword-domains/main/help.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain      | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                     |
| ----------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------------------------- |
| out.help    | premium   | $437.50   | —             | high           | low    | 3      | name.com                      |
| bad.help    | premium   | $218.75   | —             | high           | medium | 3      | name.com                      |
| off.help    | premium   | $437.50   | —             | high           | low    | 3      | name.com                      |
| bang.help   | premium   | $83.30    | $116          | high           | low    | 4      | namesilo                      |
| xcvi.help   | available | $1.99     | $50.99        | low            | low    | 4      | name.com                      |
| live.help   | resell    | —         | —             | high           | medium | 4      | West263 International Limited |
| act.help    | premium   | $218.75   | —             | high           | low    | 3      | name.com                      |
| askew.help  | available | $1.99     | $50.99        | low            | low    | 5      | name.com                      |
| pizza.help  | resell    | —         | —             | high           | low    | 5      | Porkbun, LLC                  |
| ain.help    | premium   | $83.30    | $116          | low            | low    | 3      | namesilo                      |
| fanny.help  | available | $1.99     | $50.99        | low            | low    | 5      | name.com                      |
| young.help  | resell    | —         | —             | high           | low    | 5      | Dynadot LLC                   |
| all.help    | premium   | $91       | $130          | high           | medium | 3      | namecheap                     |
| irons.help  | available | $1.99     | —             | medium         | low    | 5      | name.com                      |
| income.help | resell    | —         | —             | high           | low    | 6      | Porkbun, LLC                  |
| AOL.help    | premium   | $437.50   | —             | high           | high   | 3      | name.com                      |
| jolly.help  | available | $1.99     | —             | medium         | low    | 5      | name.com                      |
| policy.help | resell    | —         | —             | high           | low    | 6      | Porkbun, LLC                  |
| are.help    | premium   | $83.30    | $116          | high           | low    | 3      | namesilo                      |
| kinda.help  | available | $43.98    | —             | high           | low    | 5      | namecheap                     |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 15,959 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 34 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/help?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_help_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/help?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_help_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_help_oneword_domains&utm_content=related_pricing)

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

This selection covers one-word .help domain names across 11,117 entries, with a median asking price of $51.52. Many combine everyday verbs and nouns—getmoving.help, herbbutter.help, coffeecupful.help—while a few carry established brand terms like Chanel.help. The .help extension signals support, guidance, or service-oriented positioning, making these names suitable for helpdesks, customer service tools, and community resources. Pricing varies by word length, dictionary-word status, and brand recognition, so comparing individual listings is essential before choosing one.

- 11,117 one-word .help domain names in this selection
- Median asking price: $51.52 across the set
- Mix of everyday phrases and brand-adjacent names
- Well suited for support, service, and helpdesk branding

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .HELP One-Word Domains*. Version 2026-08-20. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .HELP page](https://unique.domains/domains/tld/help?utm_source=github&utm_medium=referral&utm_campaign=repo_help_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_help_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_help_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_help_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
