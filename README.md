# Regional Creator Sponsorship Rate Benchmarking Worksheet

> Stop overpaying for influencer sponsorships. Calculate fair market rates for GCC and Egyptian creators based on real median views and ad usage rights.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Format: STATIC_INTERACTIVE_TOOL](https://img.shields.io/badge/Format-STATIC--INTERACTIVE--TOOL-green.svg)](#)
[![Tier: 2](https://img.shields.io/badge/Tier-2-orange.svg)](#)
[![Region: MENA](https://img.shields.io/badge/Region-Egypt%20%7C%20GCC%20%7C%20Saudi-purple.svg)](#)
[![Tests: Passing](https://img.shields.io/badge/Tests-Passing-brightgreen.svg)](#)
[![Owner: mahmoudabdelnaby1](https://img.shields.io/badge/Owner-mahmoudabdelnaby1-blue.svg)](https://github.com/mahmoudabdelnaby1)

---

## 📌 Problem Statement & Target Persona

### Target Persona
**BOTH** operating in high-growth e-commerce, digital publishing, and direct-response marketing across Saudi Arabia, UAE, and Egypt.

### Core Problem
Develop a regional creator pricing valuation toolkit: 1) Dynamic pricing formula factoring Median Views (not vanity followers), Engagement Rate, Audience Geography (KSA/UAE vs Egypt), Content Production Complexity, and Paid Ad Usage Rights duration, 2) Single-file responsive HTML/JS calculator (`calculator.html`), 3) Negotiation counter-offer email/WhatsApp scripts.

---

## 🛠️ Repository Architecture & Deliverables

This repository provides self-contained, documented implementations and specifications:

- `data/regional_rate_cards.json`
- `docs/pricing-factors-guide.md`
- `docs/pricing-formula-methodology.md`
- `index.html`
- `LICENSE`
- `models/creator-rate-benchmark-model.xlsx`
- `README.md`
- `scripts/negotiation-scripts-bilingual.md`
- `tests/test_data_integrity.py`
- `tools/calculator.html`


---

## 🚀 Quick Start & How to Run Locally

### Run Test Suite Locally
```bash
# Ensure no bytecode generation
export PYTHONDONTWRITEBYTECODE=1  # Linux / macOS
$env:PYTHONDONTWRITEBYTECODE="1"  # Windows PowerShell

# Run Python unittest discovery
python -m unittest discover -s tests
```

### Interactive Browser Tool
Open `index.html` directly in your web browser (Chrome, Edge, Safari) to use the local interactive calculator or dashboard. Operates 100% client-side with zero external network calls.

---

## 📊 Sample Input & Output Fixtures

> **Data Disclosure:** Any included sample data is illustrative and may be synthetic; it is not a measured customer result or market benchmark unless a source and collection method are stated alongside it. These files run offline with standard libraries and require no paid third-party API credentials.

```json
{
  "domain": "social",
  "repository": "creator-sponsorship-rate-benchmarking-tool",
  "status": "READY_FOR_LOCAL_REVIEW",
  "license": "MIT"
}
```

---

## ⚠️ Known Technical & Domain Constraints

- **Median Views Valuation:** Base pricing formula calculates cost-per-view strictly from median views of recent 10 posts, ignoring vanity follower counts.
- **Usage Rights Licensing Surcharges:** Mandates explicit percentage markups (e.g. +30-50% for 30-day paid ad whitelist usage).
- **Mawthooq License Verification:** Ensures all sponsored creators in Saudi Arabia possess active regulatory advertising permits.

---

## 📚 Primary Documentation & Verifiable References

- [IAB Influencer Marketing Guide & Measurement Standards](https://www.iab.com/) - Industry standards for evaluating influencer sponsorship ROI and viewability.
- [Saudi General Authority for Media Regulation (GAMR): Mawthooq Platform](https://gcam.gov.sa/) - Mandatory regulatory licensing rules for commercial social media influencers.
- [HypeAuditor: Influencer Marketing Benchmarks for GCC](https://hypeauditor.com/) - Regional market pricing ranges and engagement rate standards.

---


## 👤 Maintainer & License

- **Author & Maintainer:** [Mahmoud Abdelnaby](https://github.com/mahmoudabdelnaby1) (`@mahmoudabdelnaby1`)
- **License:** [MIT License](LICENSE) - Open-source, auditable, and freely adaptable for internal enterprise or commercial use.
