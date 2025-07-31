# Cyclistic Capstone 2024  
**Fachreza Dewanto** • Creative by Experience, Analytical by Curiosity  

[![HTML Report](https://img.shields.io/badge/report-HTML-blue)](output/report.html)  
[![Tableau Dashboard](https://img.shields.io/badge/dashboard-Tableau-lightblue)](tableau/dashboard_link.txt)  

## Project Overview
This capstone explores 4.2M bike-share rides (Jan–Dec 2024) to:
- Uncover casual vs. member behavior  
- Analyze seasonal and hourly usage patterns  
- Estimate ride-level revenue by user and bike type  
- Recommend marketing and operational tactics  

## Repo Contents
- **data/**: Data schema & sample CSV  
- **code/**:  
  1. `01_data_prep.R` — BigQuery extraction & cleaning  
  2. `02_analysis.Rmd` — Tidy analysis, plots & report  
  3. `03_export_tableau.R` — CSVs for Tableau  
- **output/**: Knit HTML report & figure assets  
- **tableau/**: Public dashboard link  
- **docs/**: (Optional) GitHub Pages site files  

## How to Reproduce
1. Clone this repo  
   ```bash
   git clone https://github.com/fac-dew/cyclistic-capstone.git
   cd cyclistic-capstone
