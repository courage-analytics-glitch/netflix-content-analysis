# Netflix Content Analysis Dashboard

## Project Overview
A 4-page interactive Power BI dashboard analysing 8,809 Netflix titles 
(Movies and TV Shows) spanning 1925–2021 across 749 countries. Built 
from raw CSV data through full Power Query transformation, DAX measure 
creation, and professional dashboard design.

## Tools & Technologies
- **Power BI Desktop** — Dashboard design and visualisation
- **Power Query** — Data cleaning and transformation
- **DAX** — Calculated measures and columns
- **Microsoft Bing Maps** — Geographic visualisation

## Dataset
- **Source:** Netflix Titles Dataset (Kaggle)
- **Size:** 8,809 rows × 12 columns
- **Period:** 1925–2021

## Dashboard Pages
| Page | Description |
|------|-------------|
| 1. Content Overview | KPI cards, content type split, library growth trend, top countries |
| 2. Genre & Ratings | Genre distribution, rating breakdown, content type by rating |
| 3. Trends & Catalogue | Release year trends, interactive searchable catalogue, slicers |
| 4. Global Demographics | World map, regional content distribution, key metrics |

## Key Insights Uncovered
- 68% of Netflix content originates outside the United States
- Netflix library peaked in 2019 — COVID reduced additions by 25% by 2021
- 67% of TV shows have only 1 season — revealing Netflix's content lottery strategy
- 46% of all content is rated TV-MA or R — Netflix is structurally an adult platform
- North America dominates with 34% of content vs Africa's 3.42%
- Average movie runtime: 99.59 minutes across 6,131 films

## Data Cleaning Steps
- Removed erroneous date values (1944 in date_added column)
- Split duration column into numeric value and unit (min/seasons)
- Replaced nulls in director, cast, and country with "Unknown"
- Converted date_added to proper Date type
- Removed show_id as redundant identifier

## DAX Measures Created
- Total Titles, Total Movies, Total TV Shows
- % Movies, % TV Shows
- Avg Movie Runtime
- Total Countries

## Calculated Columns
- Year Added, Month Added, Content Age, Region

## Author
**Richard Courage Cobbinah**
Target Role: Business/Data Analyst | Oil & Gas | Business Intelligence

[LinkedIn](https://www.linkedin.com/in/courage-cobbinah-56531255/) | [GitHub](https://github.com/courage-analytics-glitch)
