# 04 — Apple Board Pack (Q1 FY26)

## Overview

AI-assisted board pack generation using Apple's Q1 FY26 results ($143.8B revenue). Created the R-S-F-L prompt framework to produce CFO-grade variance commentary, reducing production time from approximately 4 hours to 30 minutes.

## R-S-F-L Framework

A structured prompting approach developed during this project:

- **Role** — Define AI's persona (e.g., Senior FP&A Analyst)
- **Style** — Set tone and audience (e.g., CFO-facing, concise)
- **Format** — Specify output structure (e.g., bullet commentary by line item)
- **Length** — Constrain output (e.g., 2-3 sentences per variance)

## Anti-Hallucination Guardrails

- AI must use preliminary-indication language (not definitive claims)
- Source-data citation required for any numbers
- No fabricated specifics — if the data doesn't support it, don't say it
- Human review mandatory before any output goes downstream

## Tools

AI Prompt Engineering (R-S-F-L Framework) · Anti-Hallucination Guardrails
