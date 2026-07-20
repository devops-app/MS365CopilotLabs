---
title: Sample Excel Workbook Specification
---

# Sample Excel Workbook Specification

[← Back to Home](../index.md)

## Workbook name

Microsoft 365 Copilot Sample - BP Operational Performance Trends.xlsx

## Purpose

Provide a safe, fictional, Copilot-ready Excel dataset that learners can use to summarize operational performance, identify trends and anomalies, compare regional metrics, and generate management-ready insights during the Excel and Analyst agent labs.

## Sheets

| Sheet | Purpose |
|---|---|
| Operational_Data | Main structured table for learner analysis using Copilot in Excel. |
| Data_Dictionary | Explains each field, unit, expected data type, and training purpose. |
| Scenario_Guide | Provides the learner scenario, business context, and recommended starting prompts. |
| Expected_Insights | Trainer reference showing intended trends, anomalies, risks, and discussion points. |
| Prompt_Practice | Optional prompt examples for learners to copy, refine, and compare. |

## Required fields

| Required field | Example value or guidance |
|---|---|
| Month | January 2026 through December 2026, using consistent date formatting. |
| Site | Fictional names such as North Terminal A, South Retail Cluster, or East Refinery Unit. |
| Region | Use broad fictional regions such as Europe, Asia Pacific, Americas, and Middle East. |
| Product | Diesel, gasoline, jet fuel, lubricants, or EV charging service. |
| Throughput_Litres | Numeric monthly volume, for example 1,250,000. |
| Maintenance_Hours | Numeric maintenance hours, with at least one intentional high-maintenance month. |
| Safety_Observations | Numeric count of fictional observations, near misses, or safety improvement notes. |
| Energy_Consumption_MWh | Numeric monthly energy consumption value. |
| Emissions_Estimate_tCO2e | Estimated emissions value for training analysis only. |
| Customer_Satisfaction_Score | Score from 0 to 100, with one site intentionally below target. |
| Notes | Short operational context, such as planned shutdown, supply disruption, weather impact, or staffing constraint. |

## Workbook design requirements

- Create at least 12 months of data across multiple fictional sites and regions.
- Format the main dataset as an Excel table or a supported range with one header row, unique column headers, no blank headers, no empty rows or columns, no merged cells, and consistent data formatting.
- Include intentional training patterns: one region with rising emissions estimates, one site with lower customer satisfaction, one high-maintenance month, and one case where throughput increases while emissions also increase.
- Use fictional, rounded, non-sensitive values only; do not use real BP production, safety, customer, or commercially sensitive data.
- Turn on AutoSave and store the workbook in OneDrive or SharePoint before the lab so Copilot in Excel can access the file during training.
