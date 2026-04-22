# United Airlines Departure Delay Analysis
**Course:** DATA 5300 - Applied Statistical Inference & Experimental Design  
**Institution:** Seattle University, MS in Data Science  
**Term:** Fall 2025  
**Type:** Group Project (Individual Contribution)

---

## Overview

This project investigates what factors are associated with United Airlines departure delays using the `nycflights13` dataset in R. The analysis was conducted as part of a group project; this repository contains **my individual code contribution**.

The goal was to prepare a report for a general audience that uses exploratory data analysis and permutation tests to study departure delays across six key variables.

---

## Research Questions

1. Does the **time of day** affect departure delays?
2. Does the **time of year / season** affect departure delays?
3. Is **temperature** associated with departure delays?
4. Is **wind speed** associated with departure delays?
5. Is **precipitation** associated with departure delays?
6. Is **visibility** associated with departure delays?

---

## Dataset

- **Source:** `nycflights13` R package
- **Subset:** United Airlines (carrier code: UA) flights
- **Joined with:** Weather data from the same package
- **Key variables used:** `dep_delay`, `temp`, `wind_speed`, `precip`, `visib`, `month`, `hour`

---

## Methods

- Exploratory data analysis with visualizations (ggplot2)
- Feature engineering: binary delay variables (`late`, `very_late`)
- Seasonal and categorical groupings for time-based analysis
- Permutation tests to assess statistical significance across all six factors
- Data merging, cleaning, and transformation using `dplyr` and `tidyr`

---

## Tools & Technologies

- **Language:** R
- **Libraries:** `nycflights13`, `dplyr`, `ggplot2`, `tidyr`
- **Output:** R Markdown rendered as HTML

---

## Key Findings

- Departure delays varied meaningfully by time of day and season
- Weather factors including precipitation and visibility showed statistically significant relationships with delay likelihood
- Permutation tests confirmed that several of these associations were unlikely to be due to chance

---

## Files

| File | Description |
|------|-------------|
| `Project1_ruman.html` | Rendered R Markdown output with full analysis and visualizations |

> **Note:** This was a collaborative course project. The code and analysis in this repo represent my individual contribution to the group's work.

---

## About

Part of the MS in Data Science program at Seattle University. This course covered statistical inference, experimental design, and applied hypothesis testing using real-world datasets.
