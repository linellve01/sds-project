# ZüriWieNeu – Urban Issue Analysis in Zurich

## Project Description

This project analyzes urban issue reports from the ZüriWieNeu platform in the city of Zurich.  
The goal is to explore spatial and temporal patterns of reported infrastructure problems across Zurich’s neighbourhoods (Quartiere) using Python and GeoPandas.

The project focuses on questions such as:

- Which neighbourhoods receive the most reports?
- Which issue categories are most common?
- How do reports vary over time?
- Which categories dominate specific neighbourhoods?

---

## Data Sources

### ZüriWieNeu Reports
https://data.stadt-zuerich.ch/dataset/geo_zueri_wie_neu

### Statistical Neighbourhoods (Quartiere)
https://data.stadt-zuerich.ch/dataset/geo_statistische_quartiere

---

## Repository Structure

my-project/
├── README.md
├── environment.yml
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
└── outputs/

---

## Setup Instructions

Required Software:
- Python 3.11+
- Jupyter Lab
- Git

Required Libraries:
The required libraries are listed in "environment.yml"

Install the environment:
- conda env create -f environment.yml
- conda activate sds-project

---

## Execution Order
1. "data_clean.ipynb"
2. "spatial-analysis.ipynb"
3. "data_visualization.ipynb"
