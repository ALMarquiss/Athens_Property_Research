# Property Value Analysis – Attica, Greece

## Overview
This project explores residential property listings in the Attica region of Greece, 
aiming to identify which factors most influence property value — location, size, 
construction year, and property type. The analysis was completed as part of the 
Big Blue Data Academy Data Science bootcamp.

## Team
- Alexandros Papalexandris
- Michalis Fessas

## Dataset
- **Source:** [Greece Property Listings (Kaggle)](https://www.kaggle.com/datasets/argyrisanastopoulos/greece-property-listings)
- ~20,000 property sale listings scraped from a Greek real estate platform
- Filtered to the Attica region for this analysis

## Repository Structure
├── data/            # Raw dataset (CSV)

├── cleaning/         # Data cleaning notebook + cleaned output CSV

├── analysis/         # Exploratory data analysis & visualizations

├── presentation/     # Final business presentation (PowerPoint)

└── README.md
## Methodology
- **Why:** Understanding what drives property value in Attica helps buyers, sellers, 
  and investors make more informed decisions.
- **How:** Cleaned and filtered ~20k listings (removed invalid entries, handled 
  missing values, standardized categorical fields), then explored price, size, 
  construction year, and property type relationships using pandas and matplotlib.
- **What:** See Key Findings below.

## Key Findings
- Price per m² varies significantly by neighborhood within Attica, more than it 
  varies by property size alone.
- Construction activity shows distinct historical waves: a 1965-1984 building boom, 
  a sharp slowdown during 2015-2019 (Greek economic crisis era), and a new surge 
  in 2020-2024 listings.
- Property type (apartment, maisonette, detached house, etc.) has a measurable 
  effect on price per m², independent of location.

## Tools
- Python, pandas, matplotlib
- Jupyter Notebook

## Authors
Alexandros Papalexandris & Michalis Fessas
