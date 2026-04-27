# Wärtsilä Field Service Analytics

**Course:** Data Analytics II — Lagos Business School MBA (MMBA-8)
**Author:** Eugene Ozor
**Date:** April 2026

## Overview
This repository contains the Quarto source code and dataset for a
capstone case study applying five exploratory and inferential analytics
techniques to 101 Wärtsilä engine field service records.

## Techniques Applied
1. Exploratory Data Analysis (EDA)
2. Data Visualisation
3. Hypothesis Testing (Kruskal-Wallis)
4. Correlation Analysis
5. Multiple Linear Regression

## Key Finding
Problem category is the dominant driver of repair time
(Kruskal-Wallis H = 33.251, p < 0.001, η² = 0.332).
Maintenance jobs take a median of 300 hours versus 48 hours
for Troubleshooting events — a sixfold difference with direct
implications for Wärtsilä field service SLA planning.

## Files
| File | Description |
|---|---|
| `wartsilä_analysis.qmd` | Quarto source document |
| `wartsilä_service_data.xlsx` | Anonymised field service dataset |

## Live Report
Published on RPubs: [insert your RPubs URL here]

## Tools
R · Quarto · tidyverse · ggplot2 · corrplot · rstatix · car · effectsize
