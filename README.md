# africa-procurement-risk-analysis
# Africa Procurement Risk Analysis — Kenya & Uganda

## Project Overview

This project explores public procurement data from Kenya and Uganda to identify patterns related to procurement practices, competition, risk indicators, and procurement activity over time.

The analysis represents the exploratory data analysis stage of a broader BI lifecycle project.


## Data Source

This project uses a **synthetic public procurement dataset** generated programmatically to reproduce the structure and analytical characteristics of real-world government procurement data from Kenya and Uganda.

The dataset was designed using procurement **corruption-risk indicators (red flags)** documented in the research project *Curbing Corruption in Government Contracting*, supported by the UK Department for International Development (DFID).

The synthetic dataset includes variables such as:

* `single_bidding` — contracts involving a single bidder
* `short_bidding_period` — unusually short bidding periods
* `direct_adjudication` — direct contract awards
* `tax_haven` — transactions involving a tax-haven indicator
* `tender_value` — contract value
* `tender_currency` — local currency
* `tender_date` — procurement date
* `buyer_name` — contracting entity
* `bidder_name` — awarded supplier

The dataset was intentionally generated to provide a realistic analytical structure while avoiding the use of personally identifiable, confidential, or restricted procurement information.

**Dataset:** `contratos_africanos_redflags.csv`
**Type:** Synthetic dataset
**Countries represented:** Kenya and Uganda
**Period:** 2023–2025
**Records:** 56 contracts

> **Important:** This dataset is synthetic and does not represent actual government procurement transactions. The results of this analysis should therefore not be interpreted as evidence of corruption, misconduct, or procurement risk in Kenya or Uganda.

## Project Purpose

The purpose of this project is to demonstrate an end-to-end approach to **exploratory data analysis of public procurement information**, using procurement risk indicators to identify patterns in competition, contracting practices, and potential risk signals.

The analysis focuses on:

* Comparing procurement activity between Kenya and Uganda.
* Examining competition through single-bidding contracts.
* Analyzing direct adjudication practices.
* Identifying short bidding periods.
* Exploring tax-haven indicators.
* Developing a composite procurement risk score.
* Analyzing procurement activity over time.

The project demonstrates how structured data can be transformed into **clear analytical insights and visualizations that support transparency and evidence-based decision-making in public procurement.**

## Objectives

* Compare procurement activity between Kenya and Uganda.
* Analyze direct adjudication practices.
* Examine single-bidding contracts as a competition indicator.
* Identify contracts with short bidding periods.
* Analyze tax-haven indicators.
* Create a combined procurement risk score.
* Explore procurement activity over time.

## Data Preparation

The analysis includes:

* Data inspection and validation
* Country identification
* Handling of categorical and binary variables
* Creation of derived variables
* Calculation of procurement indicators
* Creation of a composite risk score

## Key Findings

* Kenya had a higher proportion of direct adjudication contracts than Uganda.
* Kenya also showed a higher proportion of single-bidding contracts.
* Kenya had a higher average number of selected procurement risk indicators per contract.
* Procurement activity changed over time, with Kenya leading in 2023 and Uganda surpassing Kenya in 2024 and 2025.

## Visualizations

The project includes visualizations covering:

1. Contracts by Country
2. Direct Adjudication by Country
3. Single Bidding by Country
4. Short Bidding Period by Country
5. Tax Haven by Country
6. Combined Procurement Risk Indicators
7. Procurement Activity Over Time

## Tools

* Python
* Pandas
* Matplotlib
* Jupyter Notebook

## Next Steps

This exploratory analysis can be extended into the next stages of the BI lifecycle, including deeper analysis, dashboard development, and communication of actionable insights.

## Disclaimer

The risk score used in this project is an analytical construct based on four binary indicators: single bidding, short bidding period, direct adjudication, and tax-haven indicator. It should not be interpreted as an official measure of corruption or misconduct.

