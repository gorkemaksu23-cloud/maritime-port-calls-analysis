# maritime-port-calls-analysis
Exploratory analysis of maritime port-call and vessel characteristics across economies using UNCTADstat data (2022–2023) and Tableau.
# Maritime Port Calls Analysis | 2022–2023

## Project Overview

This project analyzes international maritime port-call and vessel characteristics across economies in 2022 and 2023 using data from UNCTADstat.

The analysis was developed around a simulated business scenario in which management of a maritime and logistics consulting company requires an exploratory assessment of operational patterns, differences, and outliers across economies and vessel segments.

The project was developed in Tableau, with the final analysis presented through two interactive dashboards.

## Business Questions

The analysis focuses on the following questions:

- How does median time in port differ across ship categories and economies?
- Is there a visible relationship between vessel size and median time in port?
- How do container vessel carrying capacities differ across economies?
- What changed between 2022 and 2023?
- Which patterns or outliers may warrant further investigation?

## Data

**Source:** UNCTADstat — United Nations Conference on Trade and Development  
**Dataset:** Port Calls  
**Period:** 2022–2023

The dataset contains maritime indicators across economies and ship categories, including median time in port, vessel size, cargo carrying capacity, and container carrying capacity.

## Data Preparation

Before analysis, the data was reviewed and prepared for use in Tableau. The preparation process included:

- reviewing field names and data structure
- checking missing values
- validating numerical fields and data types
- removing fields not required for the analysis
- preparing comparable 2022 and 2023 datasets
- combining both years into a single analytical dataset

## Key Findings

- **Dry bulk carriers recorded comparatively long median port times** across many economies and in both 2022 and 2023.
- **No clear relationship was identified between average vessel size and median time in port.** Larger average vessel size did not consistently correspond to longer port stays.
- **Average container carrying capacity tended to increase from 2022 to 2023 across many comparable economies**, although the pattern was not universal.
- The analysis revealed meaningful differences across both **economies and ship categories**, indicating that maritime characteristics should not be interpreted through a single global pattern.
- The available dataset identifies these patterns but does not provide sufficient operational or contextual information to determine their underlying causes.

## Interactive Tableau Dashboards

Two interactive dashboards were developed:

**1. Port Calls & Vessel Characteristics — 2023**  
Explores median port time, vessel size, and container carrying capacity across economies and ship categories.

**2. Year-over-Year Port Call Comparison — 2022 vs. 2023**  
Allows users to compare median port time and average container carrying capacity between 2022 and 2023 by economy.

➡️ **[View the interactive dashboards on Tableau Public](https://public.tableau.com/app/profile/g.rkem.aksu/viz/MaritimePortCallsAnalysis20222023/Year-over-YearPortCallComparison2022vs_2023)**

## Management Takeaway

Ship category emerged as an important differentiating factor in port-stay duration, with dry bulk carriers representing the clearest area for further investigation. However, determining the operational drivers behind these differences would require additional data beyond the scope of the current dataset.

## Project Report

A complete report covering the business scenario, data preparation, analysis, dashboards, and management findings is available here:

➡️ **[View the full project report](./Maritime_Port_Calls_Analysis_Report.pdf)**

## Tools

**Tableau** — data preparation, exploratory analysis, visualization, and interactive dashboard development
