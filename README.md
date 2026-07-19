# HR Employee Attrition Analysis

Identifying which employee factors are most associated with attrition, using verified
statistics benchmarked against a baseline rate — not assumption-driven conclusions.

## Dataset
IBM HR Analytics Employee Attrition dataset (Kaggle), 1,470 employee records, 35 columns.
Pre-cleaned synthetic dataset — no missing values, no cleaning required.

## Method
- Established baseline attrition rate (16.1%)
- Tested 8 candidate drivers via crosstab (attrition rate by category, normalized)
- Flagged findings only where rate deviated meaningfully from baseline
- Visualized top drivers against the baseline

## Key Findings
Associations found in the data — not proven causes (see Limitations):
- **Overtime** is the strongest association: 30.5% attrition vs 10.4% for non-overtime employees (~3x)
- **Early-career employees (18-25)** attrite at 35.8%, more than double baseline
- **Sales Representatives** are the highest-risk role at 39.8% attrition
- **Single, frequently-traveling employees** are a compounding risk segment worth monitoring

## Limitations
- Synthetic IBM sample data, not a real company - findings are directional, not prescriptive
- Correlational only — no causal claims; e.g. overtime may reflect an already-stressful role rather than cause attrition itself
- No significance testing on subgroup differences; some job-role subgroups are small
- Single time snapshot — no trend or seasonality analysis possible

## Tools
Python (Pandas, Seaborn, Matplotlib), Jupyter Notebook