# AI-Powered Credit Portfolio Analytics & GCM Optimization Engine

## 📌 Project Overview
This repository contains a cloud-engineered data pipeline built to process complex, multi-layered relational banking schemas. The core objective is tracking and optimizing Gross Contribution Margin (GCM) across credit card cohorts.

By shifting away from traditional static SQL reporting, this framework leverages programmatic data manipulation (Python/Pandas) to lay the groundwork for automated risk detection and predictive portfolio management.

## 🧮 GCM Calculation Methodology
The execution matrix computes GCM dynamically using transactional variables rather than pre-calculated data layers:

$$GCM = (\text{Spend} \times \text{Revenue Rate}) - (\text{Spend} \times \text{Cost Rate})$$

- **Revenue Capture:** Modeled at a flat interchange fee structure ($2.5\%$).
- **Variable Cost Multipliers:** Adjusted dynamically based on merchant categorization risks (e.g., higher reward liabilities for Restaurants ($1.0\%$) vs standard categories ($0.3\%$)).

## 🚀 Phase 2 Roadmap (Coming June 20-26)
- Integrating OpenAI/Gemini programmatic APIs to ingest these data tables.
- Engineering automated system prompts to generate executive risk diagnostics for underperforming card products.
