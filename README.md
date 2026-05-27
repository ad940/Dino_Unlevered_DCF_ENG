# Dino_Unlevered_DCF

This repository contains my Excel-based DCF valuation model for Dino Polska.

---

## Project Overview

The project is an unlevered discounted cash flow valuation of Dino Polska, a Polish grocery retailer. The model forecasts the company’s financial performance, calculates free cash flow to firm, estimates WACC, and derives an implied equity value per share.

The main purpose of the project was not only to calculate a valuation, but also to build a clean and understandable model that can be reviewed by someone else. I tried to keep the structure practical: historical data, assumptions, forecast statements, WACC, DCF output, scenario analysis, and sensitivity tables are separated into clear sections.

---

## Files Included

| File | Description |
|---|---|
| `Dino_Unlevered_DCF_EN.xlsx` | English version of the Excel valuation model |
| `screenshots/` | Screenshots of the model dashboard, assumptions, output and sensitivity analysis |

---

## Model Features

The model includes:

- historical financial data analysis
- revenue and margin forecasting
- depreciation, CapEx, and working capital assumptions
- unlevered free cash flow calculation
- WACC calculation
- terminal value calculation
- implied enterprise value and equity value
- implied value per share
- scenario analysis
- sensitivity analysis
- basic model sanity checks

---

## Valuation Methodology

The valuation is based on an unlevered free cash flow to firm approach.

Free cash flow to firm is calculated as:

```text
FCFF = EBIT × (1 - Tax Rate) + D&A - CapEx - Change in Net Working Capital
