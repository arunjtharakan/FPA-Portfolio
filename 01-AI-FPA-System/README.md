# 01 — AI-Assisted FP&A System (Capstone)

## Overview

End-to-end AI-assisted FP&A system designed for a mid-size industrial distributor ($240M revenue). Reduces simulated month-end close from 25 hours to approximately 2 hours — a 91% reduction.

## Architecture

5 components:

1. **Data Input** — Scheduled CSV exports from NetSuite ERP (4 hrs → 30 min)
2. **Variance Calculation** — Python script with dual materiality thresholds: ≥5% AND ≥$25K (6 hrs → 5 min)
3. **AI Commentary** — R-S-F-L prompt framework with anti-hallucination guardrails (4 hrs → 30 min)
4. **Dashboard Output** — Power BI with KPI tiles and narrative panel (3 hrs → instant)
5. **Board Pack Assembly** — Python-generated Word/PDF deliverable (8 hrs → 1 hr)

## Governance

Built on AICPA/CIMA's January 2026 AI governance framework. All AI output is treated as a junior analyst's first draft — never as final.

## Tools

Python (pandas) · Power BI · AI Prompt Engineering · AICPA/CIMA Governance Framework
