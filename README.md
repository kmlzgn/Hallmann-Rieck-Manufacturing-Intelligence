# Hallmann & Rieck — Manufacturing Intelligence

**A Power BI portfolio project connecting manufacturing performance, reliability, quality and delivery outcomes.**

## Overview

This project demonstrates how operational data can be transformed into an interactive manufacturing performance reporting solution for a fictional CNC machining company.

The report combines plant-level KPIs with machine-level and machine–product investigations. Its objective is to make performance gaps visible and provide measurable evidence for further investigation—not to automate management decisions.

**All company names, operational records and business figures are synthetic and intended for demonstration purposes. This is not a real customer engagement.**

## Report Pages

1. **Executive Overview** — Plant-level performance and business impact.
2. **OEE & Machine Performance** — OEE components, machine comparisons, product mix and shift performance.
3. **Downtime & Reliability** — Downtime analysis, Pareto views, MTBF, MTTR and maintenance cost.
4. **Quality** — Defect distribution, scrap and rework performance, and machine–product quality analysis.
5. **Delivery & Business Impact** — OTIF, On-Time, In-Full, customer performance and estimated losses.
6. **Machine Investigation** — Drill-through analysis of machine-specific performance and reliability evidence.
7. **Quality Investigation** — Drill-through analysis of machine–product quality issues.
8. **Improvement Opportunities** — An evidence-based worklist for further investigation, without an automated priority score.

## Analytical Approach

- OEE calculated from Availability × Performance × Quality.
- DAX measures designed around appropriate aggregation grain.
- KPI thresholds maintained in a configuration table.
- Interactive slicers and native drill-through navigation.
- Downtime, quality, delivery and business-impact measures connected through a dimensional data model.
- Improvement opportunities presented as evidence, not as automated recommendations or rankings.

## Tools & Techniques

- Microsoft Power BI Desktop
- DAX
- Dimensional data modelling
- KPI design and conditional formatting
- Drill-through and interactive reporting
- Lean Manufacturing and Operational Excellence concepts

## How to View

1. Download the `.pbix` file from this repository.
2. Open it with Microsoft Power BI Desktop.
3. Navigate through the report pages and interact with the available filters and drill-through views.

The report can be viewed using its saved data snapshot. Refreshing the data may require access to the original source files or a compatible source path.

## Project Scope

This is a portfolio demonstration of manufacturing analytics and operational-performance reporting. Its figures and thresholds are illustrative; they should not be treated as industry benchmarks or used for real operational decisions without validation.

## Author

Developed as a portfolio project at the intersection of manufacturing operations, Lean, Operational Excellence and Business Intelligence.
