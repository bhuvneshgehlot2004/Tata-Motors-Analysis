# Tata Power EV Charging Network Expansion Analysis

This project evaluates Bengaluru’s electric vehicle (EV) charging ecosystem and identifies the most viable locations for expanding Tata Power’s charging network. The analysis combines operational charging session data, station-level network information, customer demographics, district demand forecasts, and investment feasibility metrics for proposed charging stations.

## Project Objective

The goal is to support data-driven planning for EV infrastructure by answering key business questions such as:

- Which districts and locations have the highest charging demand?
- Where are the strongest opportunities for new station expansion?
- Which charging projects deliver the best return on investment?
- How do station type, charger power, tariff, and demand affect revenue and profitability?
- Which investments are most suitable for subsidy eligibility and priority ranking?

## Business Context

Bengaluru is experiencing rapid growth in EV adoption, but charging infrastructure remains uneven across districts. This project helps map both current network coverage and future investment opportunities by combining:

- real charging session usage data,
- station-level infrastructure information,
- district demand projections,
- customer and vehicle profile patterns,
- financial ROI and payback analysis for proposed investment projects.

## Data Sets Included

The workspace contains the following datasets under the Raw Files folder:

1. charging_sessions.csv
   - 114,000 charging sessions
   - Includes session timing, customer identifiers, station IDs, energy consumed, and cost per kWh

2. charging_stations.csv
   - Station locations, district details, operator names, plug counts, and coordinates

3. customers.csv
   - Customer income tiers and EV model profile data

4. districts.csv
   - District-level projected EV demand, projected plugs, and regular customer estimates

5. roi_bengaluru_districts.csv
   - 98 proposed station projects across Bengaluru
   - Includes CAPEX, OPEX, annual revenue, EBITDA, payback, subsidy eligibility, ROI, and priority tier

## Key Performance Metrics Analyzed

The project focuses on several investment and operating metrics:

- Total CAPEX and capitalized land lease
- Annual revenue and annual OPEX
- EBITDA and payback period
- Five-year ROI
- Government subsidy eligibility and amount
- Priority tier for project ranking
- District-wise EV demand and projected charging need
- Session consumption patterns and tariff analysis

## Data Quality and Methodology Notes

The project includes data quality improvements and financial consistency checks:

- 23 projects with negative 5-year ROI were reclassified from Medium to Low priority
- A new capitalized land lease field was added to improve transparency in CAPEX calculations
- Financial metrics were aligned with project feasibility and investment-priority logic

## Deliverables

This project supports a planning dashboard and investment review framework built around Bengaluru’s EV charging network. The work includes:

- identifying underserved areas,
- evaluating station economics,
- prioritizing expansion opportunities,
- understanding customer demand and charging behavior,
- comparing viability of different charger types and deployment sites.

## Project Files

- README.md — project overview and documentation
- Raw Files/ — source datasets used for analysis
- Tata Power Project.xlsx — Excel-based project workbook / analysis file

## Recommended Use

This repository is intended for:

- EV infrastructure planning
- investment screening and prioritization
- market demand analysis
- charging network performance evaluation
- business case analysis for expansion decisions

## Summary

This project reflects a real-world EV infrastructure planning exercise that combines operational charging data with financial and strategic decision-making. It is designed to help Tata Power prioritize high-impact charging station investments and identify where Bengaluru’s charging network should expand next.

---

Prepared for the Tata Power EV Infrastructure Planning and Expansion Analysis project.
