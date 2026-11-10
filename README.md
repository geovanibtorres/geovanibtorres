# Geovani Torres

## Summary
Data & Analytics professional with an Economics background and MBA, specialized in business intelligence, KPI frameworks and decision-oriented reporting. Transform financial and operational data into clear Power BI, Tableau and HTML dashboards. Use GitHub Copilot to accelerate analysis, drafting and documentation, with Claude Code adoption underway. Open to full-time, contractor and project work, and to international opportunities.

## Projects
### Pipeline Health Monitor · Jun 2026 – Jul 2026
Sanitized portfolio version of an execution-centric observability layer for BigQuery pipelines, with an SLA catalog, dependency-based status rollup and de-duplicated alerts.
- Read BigQuery job metadata and checked each pipeline run against a per-table SLA catalog, recording a PASS, WARN, FAIL or NO_DATA status with a severity and a root-cause hint.
- Covered Tableau Prep flows, which do not appear in BigQuery job metadata, with a daily pending row that a separate feeder completes.
- Flagged a warning when a table's row count dropped against its previous run, as a lightweight data-quality check.
### Unified Sales View · May 2026
Sanitized portfolio repository with a layered BigQuery SQL model that unifies multi-source billings, with conformed dimensions, currency conversion and subscription revenue recognition.
### Higher-Ed Evasion Modeling · May 2026
Public portfolio repository that models student evasion in Brazilian higher education with public census data.
- Fitted fixed-effects and random-effects panel regressions with robust covariance (linearmodels) to model evasion rates by institution and year.
- Benchmarked the panel regressions against a random forest regressor (scikit-learn) on a hold-out split, evaluated with mean squared error and R-squared.
- Built SQL feature engineering that aggregates course-level census data to institution-year level, with support tables for lagged entrants and data-quality checks.
- Wrote a Python consolidator (pandas) that turns public education census files into partitioned Parquet datasets with source manifests.
### Sales Performance & Quota Analytics · Started Jan 2023
Anonymized portfolio repository with a layered SQL model that attributes billings to sales reps across ERP sources and combines them with monthly quota plans.
- Built per-source customer masters that resolve the sales rep from a source field, a geography rule or a customer-type rule, unified into one canonical contract.
- Loaded the monthly quota plan, kept in a spreadsheet by sales operations, through a Tableau Prep workflow into a quota table by month, rep and sub-region.
- Combined actuals and quota at one grain in a single view and a performance mart with attainment by month, sub-region and rep.

## Experience
### Pearson — Data Analytics & Automation Specialist · May 2024 – Present
### Pearson — Business Intelligence Analyst · Feb 2023 – May 2024
### Pearson — Performance Analyst · Jan 2022 – Feb 2023

## Skills
Power BI · Tableau · SQL · ETL · Data Pipelines · Data Modeling · KPI · Forecasting · Data Quality · Business Intelligence · Python · Google Cloud Platform · Tableau Prep · AI-assisted development

## Languages
Portuguese: native · English: fluent · Spanish: fluent
