# Tableau-Dashboard-Chicago-crime-analysis

# 🏙️ Chicago Crime & Public Sentiment Analysis

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data-Crime%20%26%20Sentiment-3b82f6?style=for-the-badge)
![City](https://img.shields.io/badge/City-Chicago%2C%20IL-10b981?style=for-the-badge)

### 🔗 [View Live Dashboard on Tableau Public](https://public.tableau.com/app/profile/viignesh.manikanta.reddy.velagala/viz/Chicagocrimeanalysis_17755873521720/DashboardStory)

---

## Overview

This Tableau workbook provides an end-to-end visual analysis combining **Chicago crime incident data** with **public sentiment signals** to uncover patterns in criminal activity, community perception, and how citizen sentiment correlates with crime trends across the city's neighborhoods and districts.

The dashboard is designed for public safety analysts, policymakers, journalists, and researchers looking to understand crime dynamics in Chicago through both hard data and the voice of its communities.

---

## What's Inside

### 🔴 Crime Analysis
- **Crime Trends Over Time** — Temporal breakdown of incidents by year, month, and day of week to identify recurring patterns and spikes
- **Crime Type Distribution** — Ranked breakdown of offense categories (theft, assault, battery, robbery, narcotics, etc.)
- **Geographic Heatmap** — Spatial density mapping of crime incidents across Chicago's 77 community areas and 25 police districts
- **Arrest Rate Analysis** — Comparison of crime volume vs. arrest outcomes by category and district
- **Domestic vs. Non-Domestic Incidents** — Classification and trend analysis of domestic violence-related crimes
- **Top Crime Hotspots** — Ranked neighborhoods and blocks by incident frequency

### 💬 Public Sentiment Analysis
- **Sentiment Score Trends** — Positive, neutral, and negative public sentiment plotted over time
- **Sentiment by Neighborhood** — Community-level sentiment mapping overlaid with crime density
- **Sentiment vs. Crime Correlation** — Cross-analysis of how crime rates influence (and lag) public sentiment shifts
- **Topic Modeling** — Key themes emerging from public discourse (safety, policing, community, fear)
- **Sentiment Source Breakdown** — Distribution across social media, survey responses, or public records

### 📊 Combined Insights
- **Safety Perception Gap** — Areas where perceived safety diverges significantly from actual crime statistics
- **High-Crime / High-Sentiment Areas** — Identifying communities experiencing crime but showing community resilience
- **Policy Impact Tracking** — Measuring sentiment shifts before and after public safety interventions

---

## File

| File | Description |
|------|-------------|
| `Chicago Crime and Public Sentiment Analysis.twbx` | Packaged Tableau workbook with all dashboards, data sources, and visualizations |
| [Live on Tableau Public](https://public.tableau.com/app/profile/viignesh.manikanta.reddy.velagala/viz/Chicagocrimeanalysis_17755873521720/DashboardStory) | Interactive version hosted online — no software required |

---

## Data Sources

The analysis draws from publicly available datasets including:

- **Chicago Data Portal** — City of Chicago's official crime incident reports (`crimes.csv`), updated regularly
- **CPD District Boundaries** — Chicago Police Department district and beat shapefiles for geographic mapping
- **Public Sentiment Data** — Social media posts, citizen surveys, or 311 service request data reflecting community sentiment
- **Census / ACS Data** — Demographic overlays for socioeconomic context by community area

> All data is packaged within the `.twbx` file — no external connections required to view the workbook.

---

## Requirements

To open and interact with this workbook:

- [Tableau Desktop](https://www.tableau.com/products/desktop) (version 2020.1 or later recommended)
- **OR** [Tableau Public](https://public.tableau.com/) (free) for basic viewing

---

## Getting Started

1. Clone or download this repository
2. Open **Tableau Desktop** or **Tableau Public**
3. Go to **File → Open** and select `Chicago Crime and Public Sentiment Analysis.twbx`
4. Use the dashboard tabs to navigate between Crime Analysis, Sentiment Analysis, and Combined views
5. Apply filters (year, district, crime type) to explore specific slices of the data

---

## Key Findings

> *(These are representative insights typical of Chicago crime + sentiment analyses — update with your actual findings)*

- **Theft and battery** consistently rank as the most reported crime types citywide
- Crime incidents peak during **summer months (June–August)** and on **Friday/Saturday nights**
- The **South and West sides** show disproportionately high crime density relative to their population share
- Public sentiment scores show a measurable **negative lag of 2–4 weeks** following high-crime periods
- Several high-crime neighborhoods demonstrate **strong community sentiment resilience**, suggesting active civic engagement despite elevated risk

---

## Use Cases

| Audience | Application |
|----------|-------------|
| **City Planners** | Allocate resources and interventions based on hotspot mapping |
| **Law Enforcement** | Identify patrol prioritization areas and arrest rate gaps |
| **Journalists / Researchers** | Data-driven crime reporting and academic research |
| **Community Organizations** | Understand neighborhood sentiment and advocate for policy change |
| **Students / Analysts** | Reference project for geospatial + sentiment analysis techniques |

---

## Tableau Features Used

- **Geospatial mapping** with filled maps and density heatmaps
- **Dual-axis charts** for crime vs. sentiment overlays
- **Dashboard actions** for interactive cross-filtering
- **Parameter controls** for dynamic time range and district selection
- **Calculated fields** for sentiment scoring, arrest rates, and YoY comparisons
- **Story points** for guided narrative walkthrough (if applicable)

---

## Contributing

1. Fork this repository
2. Create a new branch: `git checkout -b feature/your-update`
3. Commit your changes: `git commit -m "Add update"`
4. Push to the branch: `git push origin feature/your-update`
5. Open a Pull Request

---

## Disclaimer

This project uses publicly available data for analytical and educational purposes. Crime data reflects reported incidents and may not capture unreported crimes. Sentiment data is derived from public sources and does not represent the views of any government agency.

---

## License

This project is open source and available under the [MIT License](LICENSE).

---

*Visualizing the intersection of public safety data and community voice in Chicago.*
