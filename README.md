# SURVMETH 727 Final Project  
## Understanding Increased Voter Turnout in the Context of Growing Distrust

This project examines a central question:  
**If public trust in politicians continues to decline, why are voters still turning out at increasingly high rates?**

To explore this puzzle, the analysis draws on multiple data sources that together provide insight into what might motivate voter participation beyond simple trust in political leaders:

- **U.S. Census Bureau ACS data** to measure county-level demographic and economic characteristics that correlate with turnout.
- **COVID-19 case data** to assess whether public health crises influenced participation.
- **New York Times Article Search API** to capture patterns in political media coverage of Florida figures, as a way to understand information exposure and agenda-setting effects.

By combining these datasets, the project evaluates whether voter engagement may be driven by broader demographic forces, pandemic-related behavior shifts, or media context rather than by confidence in elected officials. The goal is to identify structural and informational factors that help explain turnout increases even when political trust remains low.

## HTML Report (RPubs)
View the full interactive HTML version of the project here:  
**[file:///Users/zacharywinograd/R%20Studios%20Folders/SURVMETH-727-Final-Project/Final_Project.html](https://rpubs.com/ZWin1234/1379033)**
- `Final_Project.html`

## PDF Report
The full PDF version is included in this repository:  
- `Final_Project_pdf.pdf`

## Data Files saved or created and then used( All data execpt for Pew_PD and Florida_COVID_CASES_0 were gathered from scraping, API, made for text analysis tasks)
- `Pew_PD.csv ` 
- `Florida_COVID_CASES_0.csv`
- `tunrout_2016.csv`
- `tunrout_2020.csv`
- `tunrout_2024.csv`
- `sent_2016_scores.rds`
- `sent_2020_scores.rds`
- `articles_2016.rds`
- `articles_2020.rds`

## R Markdown Source
- `Final_Project.Rmd` (main analysis)
- `Final_Project_pdf.Rmd` (Rmd used to convert project into pdf friendly output)

## Overview
This project analyzes county-level voter turnout across Florida using data from:
- ACS 5-year estimates
- FL Department of State turnout files
- COVID case counts
- NYT Article Search API

The HTML version includes:
- Interactive plots (Plotly)
- Maps
- Tables and summaries

