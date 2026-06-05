# Analysis of Temperature Trends in Wisconsin Counties (2000–2024)
 
## Overview
 
This project analyzes long-term temperature trends in Wisconsin counties using historical weather data from 2000 to 2024. The goal is to identify changes in average temperatures over time and compare patterns across different regions of the state.
 
---
 
## Objectives
 
- Clean and prepare county-level weather data
- Explore annual and seasonal temperature trends
- Compare temperature patterns across counties
- Visualize long-term changes using statistical graphics
- Interpret evidence of warming or cooling trends
---
 
## Tools Used
 
| Tool | Purpose |
|------|---------|
| R | Primary analysis language |
| R Markdown | Reproducible reporting |
| tidyverse | Data wrangling and pipeline |
| ggplot2 | Data visualization |
| dplyr | Data manipulation |
| readr | CSV data ingestion |
 
---
 
## Project Structure
 
```
.
├── data/
│   ├── dane_weather.csv
│   └── milwaukee_weather.csv
├── Analysis of Temperature Trends in Wisconsin Counties (2000-2024).Rmd
├── Analysis-of-Temperature-Trends-in-Wisconsin-Counties--2000-2024-.html
└── README.md
```
 
---
 
## Key Questions
 
1. How have average temperatures changed between 2000 and 2024?
2. Do different Wisconsin counties show similar trends?
3. Are temperature increases statistically meaningful?
4. What insights can be drawn from the observed patterns?
---
 
## Results
 
The analysis uses data visualization and summary statistics to identify trends in county-level temperatures and highlight regional differences throughout Wisconsin.
 
Key outputs include:
 
- **Annual trend lines** for Dane and Milwaukee counties across the 24-year period
- **Seasonal breakdowns** revealing which seasons show the strongest warming signals
- **County comparisons** highlighting regional variation in temperature change
- **Statistical summaries** assessing the significance of observed trends
---
 
## Getting Started
 
### Prerequisites
 
Install required R packages before running the analysis:
 
```r
install.packages(c("tidyverse", "ggplot2", "dplyr", "readr"))
```
 
### Running the Analysis
 
Open the R Markdown file in RStudio and knit to HTML:
 
```r
rmarkdown::render("Analysis of Temperature Trends in Wisconsin Counties (2000-2024).Rmd")
```
 
Or open the pre-rendered output directly:
 
```
Analysis-of-Temperature-Trends-in-Wisconsin-Counties--2000-2024-.html
```
 
---
 
## Data Sources
 
| File | County | Description |
|------|--------|-------------|
| `dane_weather.csv` | Dane | Daily/monthly weather records, 2000–2024 |
| `milwaukee_weather.csv` | Milwaukee | Daily/monthly weather records, 2000–2024 |
 
---
