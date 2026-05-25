# Castle Doctrine and Violent Crime: Replication and Extension
**Course:** Causal Inference, Hertie School of Governance
**Author:** Yenus Ibrahim Ayalew (Student ID: 25173530)
**Due Date:** May 27, 2025

## Paper
Cheng, Cheng, and Mark Hoekstra. 2013.
"Does Strengthening Self-Defense Law Deter Crime or Escalate Violence?
Evidence from Expansions to Castle Doctrine."
Journal of Human Resources 48(3): 821-854.

## Replication Data
Data source: causaldata R package (castle dataset)
Install with: install.packages("causaldata")
No external data download required.

## How to Reproduce
1. Clone this repository
2. Open report/replication_report.Rmd in RStudio
3. Install packages:
   install.packages(c("causaldata", "fixest", "bacondecomp", "did", "ggplot2", "dplyr", "modelsummary"))
4. Knit the report to HTML

## Structure
- report/replication_report.Rmd   -- Full report: Part 1, Part 2, Part 3
- output/figures/                  -- Generated figures
- output/tables/                   -- Generated tables
