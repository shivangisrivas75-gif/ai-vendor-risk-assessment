# ai-vendor-risk-assessment# AI Vendor Risk & Governance Assessment (Prototype)

A learning project that scores AI vendors on five risk areas and produces a risk register with recommendations.

**Data:** Fully synthetic (made-up). No real vendors or companies.

## What it does
- Generates 20 synthetic AI vendors, scored 1-5 on: data privacy, AI bias, security, regulatory compliance, third-party risk
- Calculates a weighted risk score (0-100) and classifies vendors as High / Medium / Low
- Builds a risk register with a top risk area, recommendation and action priority for each vendor
- Creates a dashboard (dashboard.png)

## Tools
Python (pandas, numpy, matplotlib), SQLite (SQL)

## Frameworks
Risk areas are inspired by NIST AI RMF and ISO/IEC 42001. This is not an official assessment against either standard.

## Assumptions and limitations
- Weights and thresholds are my own assumptions, not an official standard
- Scores are random synthetic values, so results show the method, not real vendor risk
- Recommendations are general examples and need expert review in real use
