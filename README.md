# UK Electricity Carbon Intensity (Time-Series Analysis)

Undergraduate empirical project analysing the relationship between renewable electricity generation and the carbon intensity of electricity generation in the United Kingdom using annual time-series data (2000–2024).

---

## Project overview

This project examines how changes in the UK electricity generation mix relate to observed changes in carbon intensity. The research question is deliberately tightly scoped, allowing for a focus on careful data construction and disciplined time-series modelling rather than complexity for its own sake.

---

## Methods and approach

- Construction of renewable electricity share from disaggregated generation data (wind, solar, hydropower, and other renewables)
- Time-series regression analysis using:
  - Levels and trend-controlled specifications  
  - First-difference models to examine short-run dynamics  
  - Mechanism-based checks focusing on coal displacement  
  - Interaction and non-linear specifications
- Graphical analysis and residual diagnostics
- Results interpreted as descriptive associations rather than causal estimates

---

## Tools

- R (tidyverse, ggplot2, broom)
- R Markdown for reproducible analysis

---

## Repository contents

- `report.pdf` – Final knitted report
- `analysis.Rmd` – Reproducible R Markdown file used to generate the report

---

## Notes

This project was completed as part of an undergraduate Programming & Statistics module.

The project received a **First Class mark (82% overall)**, assessed 50/50 through a research report and a technical exam.
