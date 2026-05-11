# Available .HELP One-Word Domains (11,120)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C120%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .help one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,120 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,120 domains · **Median ask:** $32.02 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-11  
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

- `help.csv` — public CSV extract (1,000 rows)
- `help.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/help-oneword-domains/main/help.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain            | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                  |
| ----------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | -------------------------- |
| CocaCola.help     | available | $43.98    | —             | 92             | 82     | 9      | namecheap                  |
| banana.help       | resell    | —         | —             | 86             | 41     | 6      | Dynadot LLC                |
| RedSox.help       | premium   | $98       | $140          | 72             | 60     | 7      | namecheap                  |
| deeplearning.help | available | $1.99     | —             | 74             | 23     | 13     | name.com                   |
| motorsport.help   | resell    | —         | —             | 74             | 23     | 10     | Key-Systems LLC            |
| regions.help      | premium   | $87.50    | —             | 64             | 59     | 7      | name.com                   |
| Places.help       | available | $43.98    | —             | 74             | 22     | 6      | namecheap                  |
| registration.help | resell    | —         | —             | 75             | 19     | 12     | Porkbun, LLC               |
| events.help       | premium   | $87.50    | —             | 68             | 37     | 6      | name.com                   |
| machines.help     | available | $1.99     | —             | 56             | 22     | 8      | name.com                   |
| godmode.help      | resell    | —         | —             | 74             | 19     | 8      | 1API GmbH                  |
| yellowpages.help  | premium   | $87.50    | —             | 78             | 32     | 12     | name.com                   |
| Allie.help        | available | $43.98    | —             | 72             | 21     | 5      | namecheap                  |
| leasing.help      | resell    | —         | —             | 70             | 19     | 7      | Name.com, Inc              |
| SanDiego.help     | premium   | $83.30    | $116          | 74             | 29     | 9      | namesilo                   |
| designs.help      | available | $1.99     | —             | 72             | 21     | 7      | name.com                   |
| rehabs.help       | resell    | —         | —             | 51             | 8      | 6      | Instra Corporation Pty Ltd |
| blocks.help       | premium   | $87.50    | —             | 53             | 29     | 6      | name.com                   |
| studios.help      | available | $1.99     | —             | 54             | 21     | 7      | name.com                   |
| keepfaith.help    | resell    | —         | —             | 82             | 3      | 10     | Key-Systems LLC            |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 11,120 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/help?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_help_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/help?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_help_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_help_oneword_domains&utm_content=related_pricing)

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

These domains are one-word names in the .help extension. The set includes direct action terms like act.help and install.help, broad nouns like someone.help, and more difficult terms such as corrupt.help or jail.help. For founders, the strongest picks usually read clearly, match a support or assistance use case, and are easy to remember when spoken aloud. For investors, quality depends on practical end-user fit, clean semantics, and disciplined entry price. The median ask in this selection is 32.02, but pricing alone is not enough. When comparing these domains, focus on relevance, clarity, potential trademark conflict, and whether the word makes sense with .help.

- Prefer words that naturally fit support, service, or guidance
- Check for trademark issues, especially names like Sony.help
- Clear verbs and nouns often beat abstract or negative terms
- Use pricing with context; cheap names can still be weak fits

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .HELP One-Word Domains*. Version 2026-05-11. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .HELP page](https://unique.domains/domains/tld/help?utm_source=github&utm_medium=referral&utm_campaign=repo_help_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_help_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_help_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_help_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
