# Daikibo Industrials: Operational Efficiency & Workplace Equity Analysis

<img src="./Task%201:%20Data%20Analysis/Daikibo's%20Machine's%20Downtime%20Analysis.png" alt="Tableau Dashboard Screenshot" style="width:70%;"/>

## Project Overview
This repository contains two analytical tasks conducted for Daikibo Industrials:
1. **Factory Telemetry Analysis**: Identified machines with highest downtime across 4 global factories using Tableau
2. **Pay Equity Evaluation**: Classified gender pay equality across job roles using Excel

## Task 1: Machine Downtime Analysis
### Objective
Determine which factory location and machine types had the highest failure rates in May 2021.

### Methodology
- Processed JSON telemetry data from 4 factories (Japan, Germany, China)
- Created Tableau dashboard with:
  - **Down Time per Factory** bar chart
  - **Down Time per Device Type** bar chart (filterable by factory)
- Calculated "Unhealthy" measure (10 mins downtime per unhealthy status)

### Key Findings
- Highest downtime factory: daikibo-factory-seiko
- Most problematic machine type: LaserWelder

## Task 2: Pay Equity Classification
### Objective
Evaluate gender pay equality across job roles and locations.

### Methodology
- Processed compensation data in Excel
- Implemented classification logic:
  - **Fair** (±10)
  - **Unfair** (±11 to ±20)
  - **Highly Discriminative** (±21+)

### Sample Results
| Factory               | Job Role  | Score | Classification          |
|-----------------------|-----------|-------|-------------------------|
| Daikibo Factory Meiyo | C-Level   | -25   | Highly Discriminative   |
| Daikibo Berlin        | Engineer  | 2     | Fair                    |

## Files Included
- `Daikibo's Machine Downtime Analysis.twbx` (Tableau workbook)
- `Task 5 Equality Table.xlsx` (Enhanced pay equity analysis)
- `Daikibo's Machine's Downtime Analysis.png` (Results visualization)

## Tools Used
- Tableau Public (Data visualization)
- Microsoft Excel (Data processing)

## How to Reproduce
1. For Task 1: Open Tableau workbook with JSON data source
2. For Task 2: Review Excel classification formulas in Column D
